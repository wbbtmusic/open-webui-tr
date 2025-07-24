# UI ve Modelleri Ayrı Ayrı Barındırma
Bazen Ollama'yı UI'den ayrı olarak barındırmak, ancak kullanıcılar arasında paylaşılan RAG ve RBAC destek özelliklerini korumak faydalı olabilir:
Türkçeye çeviren: Burak Can Öğüt

# Open WebUI Yapılandırması
## UI Yapılandırması
UI yapılandırması için Apache VirtualHost'u aşağıdaki gibi ayarlayabilirsiniz:
```
# Assuming you have a website hosting this UI at "server.com"
<VirtualHost 192.168.1.100:80>
    ServerName server.com
    DocumentRoot /home/server/public_html
    ProxyPass / http://server.com:3000/ nocanon
    ProxyPassReverse / http://server.com:3000/
    # Needed after 0.5
    ProxyPass / ws://server.com:3000/ nocanon
    ProxyPassReverse / ws://server.com:3000/
</VirtualHost>
```
SSL talep etmeden önce siteyi etkinleştirin:
`a2ensite server.com.conf` # bu siteyi etkinleştirir. a2ensite, "Apache 2 Enable Site" kısaltmasıdır
```
# For SSL
<VirtualHost 192.168.1.100:443>
    ServerName server.com
    DocumentRoot /home/server/public_html
    ProxyPass / http://server.com:3000/ nocanon
    ProxyPassReverse / http://server.com:3000/
    # Needed after 0.5
    ProxyPass / ws://server.com:3000/ nocanon
    ProxyPassReverse / ws://server.com:3000/
    SSLEngine on
    SSLCertificateFile /etc/ssl/virtualmin/170514456861234/ssl.cert
    SSLCertificateKeyFile /etc/ssl/virtualmin/170514456861234/ssl.key
    SSLProtocol all -SSLv2 -SSLv3 -TLSv1 -TLSv1.1
    SSLProxyEngine on
    SSLCACertificateFile /etc/ssl/virtualmin/170514456865864/ssl.ca
</VirtualHost>
```
SSL cluster'larım için burada virtualmin kullanıyorum, ancak doğrudan certbot'u veya tercih ettiğiniz SSL yöntemini de kullanabilirsiniz. SSL kullanmak için:

### Önkoşullar.
Aşağıdaki komutları çalıştırın:
`snap install certbot --classic`
`snap apt install python3-certbot-apache` (bu, apache eklentisini kuracaktır).
Apache sites-available dizinine gidin:
`cd /etc/apache2/sites-available/`
Henüz oluşturulmadıysa, yukarıdaki `<virtualhost>` yapılandırmasını (durumunuza uygun olmalı, gerektiği gibi değiştirin) içeren server.com.conf dosyasını oluşturun. SSL olmayanını kullanın:
Oluşturulduktan sonra `certbot --apache -d server.com` komutunu çalıştırın, bu sizin için bir SSL anahtarları isteyecek ve ekleyecek/oluşturacak, ayrıca server.com.le-ssl.conf dosyasını oluşturacaktır.
Türkçeye çeviren: Burak Can Öğüt

# Ollama Sunucu Yapılandırması
En son Ollama kurulumunuzda, API sunucunuzu resmi Ollama referansından kurduğunuzdan emin olun:
[Ollama FAQ](https://github.com/jmorganca/ollama/blob/main/docs/faq.md)
Türkçeye çeviren: Burak Can Öğüt

### TL;DR
Rehber, Linux'taki mevcut güncellenmiş servis dosyasıyla eşleşmiyor gibi görünüyor. Bu yüzden burada ele alacağız:
Ollama'yı kaynaktan derlemediğiniz sürece, standart yükleme `curl https://ollama.com/install.sh | sh` ile yüklemek /etc/systemd/system içinde `ollama.service` adında bir dosya oluşturur. Dosyayı düzenlemek için nano kullanabilirsiniz:
```
sudo nano /etc/systemd/system/ollama.service
```
Aşağıdaki satırları ekleyin:
```
Environment="OLLAMA_HOST=0.0.0.0:11434" # this line is mandatory. You can also specify
```
Örneğin:
```
[Unit]
Description=Ollama Service
After=network-online.target
[Service]
ExecStart=/usr/local/bin/ollama serve
Environment="OLLAMA_HOST=0.0.0.0:11434" # this line is mandatory. You can also specify 192.168.254.109:DIFFERENT_PORT, format
Environment="OLLAMA_ORIGINS=http://192.168.254.106:11434,https://models.server.city" # this line is optional
User=ollama
Group=ollama
Restart=always
RestartSec=3
Environment="PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/s>
[Install]
WantedBy=default.target
```
CTRL+S tuşlarına basarak dosyayı kaydedin, ardından CTRL+X tuşlarına basın.
Bilgisayarınız yeniden başlatıldığında, Ollama sunucusu artık belirttiğiniz IP:PORT üzerinden, bu durumda 0.0.0.0:11434 veya 192.168.254.106:11434 (yerel IP adresiniz ne olursa olsun) dinlemeye başlayacaktır. Yönlendiricinizin 11434 portunu yerel IP sunucunuza yönlendirerek sayfaları bu yerel IP'den doğru şekilde sunacak şekilde yapılandırıldığından emin olun.
Türkçeye çeviren: Burak Can Öğüt

# Ollama Model Yapılandırması
## Ollama model yapılandırması için aşağıdaki Apache VirtualHost kurulumunu kullanın:
Apache sites-available dizinine gidin:
`cd /etc/apache2/sites-available/`
`nano models.server.city.conf` # bunu ollama sunucu alan adınızla eşleştirin
Aşağıdaki virtualhost'u içeren örneği ekleyin (gerektiği gibi değiştirin):
```
# Assuming you have a website hosting this UI at "models.server.city"
<IfModule mod_ssl.c>
    <VirtualHost 192.168.254.109:443>
        DocumentRoot "/var/www/html/"
        ServerName models.server.city
        <Directory "/var/www/html/">
            Options None
            Require all granted
        </Directory>
        ProxyRequests Off
        ProxyPreserveHost On
        ProxyAddHeaders On
        SSLProxyEngine on
        ProxyPass / http://server.city:1000/ nocanon # or port 11434
        ProxyPassReverse / http://server.city:1000/ # or port 11434
        SSLCertificateFile /etc/letsencrypt/live/models.server.city/fullchain.pem
        SSLCertificateKeyFile /etc/letsencrypt/live/models.server.city/privkey.pem
        Include /etc/letsencrypt/options-ssl-apache.conf
    </VirtualHost>
</IfModule>
```
SSL talep etmeden önce siteyi etkinleştirmeniz gerekebilir (henüz yapmadıysanız):
`a2ensite models.server.city.conf`
#### Ollama sunucusunun SSL kısmı için
Aşağıdaki komutları çalıştırın:
Apache sites-available dizinine gidin:
`cd /etc/apache2/sites-available/`
`certbot --apache -d server.com`
```
<VirtualHost 192.168.254.109:80>
    DocumentRoot "/var/www/html/"
    ServerName models.server.city
    <Directory "/var/www/html/">
        Options None
        Require all granted
    </Directory>
    ProxyRequests Off
    ProxyPreserveHost On
    ProxyAddHeaders On
    SSLProxyEngine on
    ProxyPass / http://server.city:1000/ nocanon # or port 11434
    ProxyPassReverse / http://server.city:1000/ # or port 11434
    RewriteEngine on
    RewriteCond %{SERVER_NAME} =models.server.city
    RewriteRule ^ https://%{SERVER_NAME}%{REQUEST_URI} [END,NE,R=permanent]
</VirtualHost>
```
Apache'yi `systemctl reload apache2` ile yeniden başlatmayı/yeniden yüklemeyi unutmayın.
Sitenizi https://server.com adresinde açın!
**Tebrikler**, **_Open-AI-benzeri Chat-GPT tarzı kullanıcı arayüzünüz_** artık RAG, RBAC ve multimodal özelliklerle AI sunuyor! Henüz yapmadıysanız Ollama modellerini indirin!
Herhangi bir yanlış yapılandırma veya hatayla karşılaşırsanız, lütfen bir sorun (issue) bildirin veya tartışmamıza katılın. Size yardımcı olmak için burada birçok dost canlısı geliştirici bulunmaktadır.
Bu UI'yi herkes için çok daha kullanıcı dostu hale getirelim!
AI için UI tercihiniz Open-WebUI olduğu için teşekkürler!
Türkçeye çeviren: Burak Can Öğüt

Bu belge, Filipinler'den sizin Open-WebUI hayranınız olan **Bob Reyes** tarafından hazırlanmıştır.
Çeviri: Burak Can Öğüt
```
