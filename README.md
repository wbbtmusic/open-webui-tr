# Open WebUI 👋
![GitHub stars](https://img.shields.io/github/stars/open-webui/open-webui?style=social)
![GitHub forks](https://img.shields.io/github/forks/open-webui/open-webui?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/open-webui/open-webui?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/open-webui/open-webui)
![GitHub language count](https://img.shields.io/github/languages/count/open-webui/open-webui)
![GitHub top language](https://img.shields.io/github/languages/top/open-webui/open-webui)
![GitHub last commit](https://img.shields.io/github/last-commit/open-webui/open-webui?color=red)
[![Discord](https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)
**Open WebUI, tamamen çevrimdışı çalışmak üzere tasarlanmış, [genişletilebilir](https://docs.openwebui.com/features/plugin/), zengin özelliklere sahip ve kullanıcı dostu, kendi kendine barındırılan bir AI platformudur.** **Ollama** ve **OpenAI-uyumlu API'ler** gibi çeşitli LLM çalıştırma ortamlarını destekler ve RAG için **yerleşik çıkarım motoru** ile **güçlü bir AI dağıtım çözümü** sunar.
Açık kaynak AI konusunda tutkulu musunuz? [Ekibimize katılın →](https://careers.openwebui.com/)
![Open WebUI Demo](./demo.gif)
> **İPUCU:**  
> **Bir [Kurumsal Plan (Enterprise Plan)](https://docs.openwebui.com/enterprise) mı arıyorsunuz?** – **[Satış Ekibimizle Bugün Konuşun!](mailto:sales@openwebui.com)**
>
> **Özelleştirilmiş tema ve markalama**, **Hizmet Seviyesi Anlaşması (SLA) desteği**, **Uzun Süreli Destek (LTS) sürümleri** ve **daha fazlası** dahil olmak üzere **gelişmiş yetenekler** edinin!
Daha fazla bilgi için [Open WebUI Dokümantasyonumuzu](https://docs.openwebui.com/) incelediğinizden emin olun.
## Open WebUI'nin Temel Özellikleri ⭐
- 🚀 **Zahmetsiz Kurulum**: Hem `:ollama` hem de `:cuda` etiketli imajlar için destekle, sorunsuz bir deneyim için Docker veya Kubernetes (kubectl, kustomize veya helm) kullanarak sorunsuz bir şekilde kurun.
- 🤝 **Ollama/OpenAI API Entegrasyonu**: Ollama modellerinin yanı sıra OpenAI-uyumlu API'leri de çok yönlü konuşmalar için zahmetsizce entegre edin. **LMStudio, GroqCloud, Mistral, OpenRouter ve daha fazlasıyla** bağlantı kurmak için OpenAI API URL'sini özelleştirin.
- 🛡️ **Detaylı İzinler ve Kullanıcı Grupları**: Yöneticilerin detaylı kullanıcı rolleri ve izinleri oluşturmasına izin vererek güvenli bir kullanıcı ortamı sağlıyoruz. Bu detaylandırma sadece güvenliği artırmakla kalmaz, aynı zamanda özelleştirilmiş kullanıcı deneyimleri sunarak kullanıcılar arasında sahiplenme ve sorumluluk duygusunu teşvik eder.
- 📱 **Duyarlı Tasarım**: Masaüstü Bilgisayar, Dizüstü Bilgisayar ve Mobil cihazlarda kesintisiz bir deneyimin keyfini çıkarın.
- 📱 **Mobil için Progresif Web Uygulaması (PWA)**: PWA'mızla mobil cihazınızda yerel uygulama benzeri bir deneyimin keyfini çıkarın; localhost üzerinde çevrimdışı erişim ve sorunsuz bir kullanıcı arayüzü sağlar.
- ✒️🔢 **Tam Markdown ve LaTeX Desteği**: Zenginleştirilmiş etkileşim için kapsamlı Markdown ve LaTeX yetenekleriyle LLM deneyiminizi yükseltin.
- 🎤📹 **Eller Serbest Sesli/Görüntülü Arama**: Entegre eller serbest sesli ve görüntülü arama özellikleriyle kesintisiz iletişimi deneyimleyin, daha dinamik ve etkileşimli bir sohbet ortamı sağlar.
- 🛠️ **Model Oluşturucu**: Web UI üzerinden kolayca Ollama modelleri oluşturun. Özel karakterler/ajanlar oluşturup ekleyin, sohbet öğelerini özelleştirin ve [Open WebUI Topluluğu](https://openwebui.com/) entegrasyonu aracılığıyla modelleri zahmetsizce içe aktarın.
- 🐍 **Yerel Python Fonksiyon Çağırma Aracı (Native Python Function Calling Tool)**: Araçlar çalışma alanında yerleşik kod düzenleyici desteğiyle LLM'lerinizi geliştirin. Yalnızca saf Python fonksiyonlarınızı ekleyerek Kendi Fonksiyonunuzu Getirin (BYOF), LLM'lerle kesintisiz entegrasyon sağlayın.
- 📚 **Yerel RAG Entegrasyonu**: Çığır açan Retrieval Augmented Generation (RAG) desteğiyle sohbet etkileşimlerinin geleceğine dalın. Bu özellik, belge etkileşimlerini sohbet deneyiminize sorunsuz bir şekilde entegre eder. Belgeleri doğrudan sohbete yükleyebilir veya belge kütüphanenize dosya ekleyebilir, bir sorgudan önce `#` komutunu kullanarak bunlara zahmetsizce erişebilirsiniz.
- 🔍 **RAG için Web Araması**: `SearXNG`, `Google PSE`, `Brave Search`, `serpstack`, `serper`, `Serply`, `DuckDuckGo`, `TavilySearch`, `SearchApi` ve `Bing` gibi sağlayıcıları kullanarak web aramaları yapın ve sonuçları doğrudan sohbet deneyiminize dahil edin.
- 🌐 **Web Tarama Yeteneği**: URL'nin önüne `#` komutunu ekleyerek web sitelerini sohbet deneyiminize sorunsuz bir şekilde entegre edin. Bu özellik, web içeriğini doğrudan konuşmalarınıza dahil etmenizi sağlayarak etkileşimlerinizin zenginliğini ve derinliğini artırır.
- 🎨 **Görsel Üretimi Entegrasyonu**: AUTOMATIC1111 API veya ComfyUI (yerel) ve OpenAI'nin DALL-E (harici) gibi seçenekleri kullanarak görsel üretim yeteneklerini sorunsuz bir şekilde birleştirin, sohbet deneyiminizi dinamik görsel içerikle zenginleştirin.
- ⚙️ **Çoklu Model Konuşmaları**: Optimum yanıtlar için modellerin benzersiz güçlü yönlerinden yararlanarak çeşitli modellerle zahmetsizce aynı anda etkileşim kurun. Deneyiminizi, paralel olarak çeşitli modelleri kullanarak geliştirin.
- 🔐 **Rol Tabanlı Erişim Kontrolü (RBAC)**: Kısıtlı izinlerle güvenli erişim sağlayın; yalnızca yetkili kişiler Ollama'nıza erişebilir ve özel model oluşturma/çekme hakları yöneticilere ayrılmıştır.
- 🌐🌍 **Çok Dilli Destek**: Uluslararasılaşma (i18n) desteğimizle Open WebUI'yi tercih ettiğiniz dilde deneyimleyin. Desteklenen dillerimizi genişletmek için bize katılın! Aktif olarak katkıda bulunanlar arıyoruz!
- 🧩 **Pipelines, Open WebUI Plugin Desteği**: [Pipelines Plugin Framework](https://github.com/open-webui/pipelines) kullanarak özel mantığı ve Python kütüphanelerini Open WebUI'ye sorunsuz bir şekilde entegre edin. Pipelines örneğinizi başlatın, OpenAI URL'sini Pipelines URL'sine ayarlayın ve sonsuz olasılıkları keşfedin. [Örnekler](https://github.com/open-webui/pipelines/tree/main/examples) arasında **Fonksiyon Çağırma (Function Calling)**, erişimi kontrol etmek için Kullanıcı **Hız Sınırlandırması (Rate Limiting)**, Langfuse gibi araçlarla **Kullanım Takibi (Usage Monitoring)**, çok dilli destek için LibreTranslate ile **Canlı Çeviri (Live Translation)**, **Toksik Mesaj Filtreleme (Toxic Message Filtering)** ve çok daha fazlası bulunmaktadır.
- 🌟 **Sürekli Güncel İçerik**: Open WebUI'yi düzenli güncellemeler, düzeltmeler ve yeni özelliklerle geliştirmeye kararlıyız.
Open WebUI'nin özellikleri hakkında daha fazla bilgi edinmek ister misiniz? Kapsamlı bir genel bakış için [Open WebUI dokümantasyonumuza](https://docs.openwebui.com/features) göz atın!
## Sponsorlar 🙌
#### Emerald
<table>
  <tr>
    <td>
      <a href="https://n8n.io/" target="_blank">
        <img src="https://docs.openwebui.com/sponsors/logos/n8n.png" alt="n8n" style="width: 8rem; height: 8rem; border-radius: .75rem;" />
      </a>
    </td>
    <td>
      <a href="https://n8n.io/">n8n</a> • Arayüzünüzün henüz bir backend'i var mı?<br><a href="https://n8n.io/">n8n</a>'i deneyin
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://tailscale.com/blog/self-host-a-local-ai-stack/?utm_source=OpenWebUI&utm_medium=paid-ad-placement&utm_campaign=OpenWebUI-Docs" target="_blank">
        <img src="https://docs.openwebui.com/sponsors/logos/tailscale.png" alt="Tailscale" style="width: 8rem; height: 8rem; border-radius: .75rem;" />
      </a>
    </td>
    <td>
      <a href="https://tailscale.com/blog/self-host-a-local-ai-stack/?utm_source=OpenWebUI&utm_medium=paid-ad-placement&utm_campaign=OpenWebUI-Docs">Tailscale</a> • Kendi kendine barındırılan AI'yı Tailscale ile herhangi bir cihaza bağlayın
    </td>
  </tr>
</table>

---

Sponsorlarımızın cömert desteği için inanılmaz minnettarız. Katkıları, projemizi sürdürmemize ve geliştirmemize yardımcı olarak topluluğumuza kaliteli iş sunmaya devam etmemizi sağlıyor. Teşekkür ederiz!

## Nasıl Kurulur 🚀

### Python pip ile Kurulum 🐍

Open WebUI, Python paket yöneticisi pip kullanılarak kurulabilir. Devam etmeden önce, uyumluluk sorunlarından kaçınmak için **Python 3.11** kullandığınızdan emin olun.

1.  **Open WebUI Kurulumu**:
    Terminalinizi açın ve Open WebUI'yi kurmak için aşağıdaki komutu çalıştırın:
    ```bash
    pip install open-webui
    ```

2.  **Open WebUI'yi Çalıştırma**:
    Kurulumdan sonra, Open WebUI'yi şu komutu çalıştırarak başlatabilirsiniz:
    ```bash
    open-webui serve
    ```
Bu, Open WebUI sunucusunu başlatacak ve [http://localhost:8080](http://localhost:8080) adresinden erişebilirsiniz.

### Docker ile Hızlı Başlangıç 🐳

> **Not:**  
> Lütfen belirli Docker ortamları için ek yapılandırmaların gerekebileceğini unutmayın. Herhangi bir bağlantı sorunuyla karşılaşırsanız, [Open WebUI Dokümantasyonumuzdaki](https://docs.openwebui.com/) detaylı rehberimiz size yardımcı olmaya hazırdır.
> **UYARI:**
> Open WebUI'yi Docker kullanarak kurarken, Docker komutunuza `-v open-webui:/app/backend/data` eklediğinizden emin olun. Bu adım, veritabanınızın doğru şekilde bağlanmasını ve veri kaybını önlemesini sağladığı için çok önemlidir.
> **İPUCU:**  
> Open WebUI'yi Ollama dahil veya CUDA hızlandırmasıyla kullanmak isterseniz, resmi `:cuda` veya `:ollama` etiketli imajlarımızı kullanmanızı öneririz. CUDA'yı etkinleştirmek için Linux/WSL sisteminize [Nvidia CUDA container toolkit](https://docs.nvidia.com/dgx/nvidia-container-runtime-upgrade/) kurmanız gerekmektedir.
### Varsayılan Yapılandırma ile Kurulum
- **Ollama bilgisayarınızdaysa**, şu komutu kullanın:
  ```bash
  docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```
- **Ollama Farklı Bir Sunucudaysa**, şu komutu kullanın:
  Ollama'ya başka bir sunucudan bağlanmak için `OLLAMA_BASE_URL`'yi sunucunun URL'sine değiştirin:
  ```bash
  docker run -d -p 3000:8080 -e OLLAMA_BASE_URL=https://example.com -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```
- **Open WebUI'yi Nvidia GPU desteğiyle çalıştırmak için**, şu komutu kullanın:
  ```bash
  docker run -d -p 3000:8080 --gpus all --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:cuda
  ```
### Sadece OpenAI API Kullanımı için Kurulum
- **Sadece OpenAI API kullanıyorsanız**, şu komutu kullanın:
  ```bash
  docker run -d -p 3000:8080 -e OPENAI_API_KEY=your_secret_key -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main
  ```
### Ollama Desteğiyle Birlikte Open WebUI Kurulumu
Bu kurulum yöntemi, Open WebUI'yi Ollama ile bir araya getiren tek bir container imajı kullanır ve tek bir komutla kolay kurulum sağlar. Donanım kurulumunuza göre uygun komutu seçin:
- **GPU Desteğiyle**:
  Aşağıdaki komutu çalıştırarak GPU kaynaklarını kullanın:
  ```bash
  docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```
- **Sadece CPU için**:
  GPU kullanmıyorsanız, bunun yerine şu komutu kullanın:
  ```bash
  docker run -d -p 3000:8080 -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:ollama
  ```
Her iki komut da Open WebUI ve Ollama'nın yerleşik, sorunsuz kurulumunu kolaylaştırarak her şeyi hızlı bir şekilde çalışır hale getirmenizi sağlar.
Kurulumdan sonra, Open WebUI'ye [http://localhost:3000](http://localhost:3000) adresinden erişebilirsiniz. Keyfini çıkarın! 😄
### Diğer Kurulum Yöntemleri
Docker dışı yerel kurulum yöntemleri, Docker Compose, Kustomize ve Helm dahil olmak üzere çeşitli kurulum alternatifleri sunuyoruz. Kapsamlı rehberlik için [Open WebUI Dokümantasyonumuzu](https://docs.openwebui.com/getting-started/) ziyaret edin veya [Discord topluluğumuza](https://discord.gg/5rJgQTnV4s) katılın.
Yerel bir geliştirme ortamı kurma talimatları için [Yerel Geliştirme Rehberi'ne](https://docs.openwebui.com/getting-started/advanced-topics/development) bakın.
### Sorun Giderme
Bağlantı sorunları mı yaşıyorsunuz? [Open WebUI Dokümantasyonumuz](https://docs.openwebui.com/troubleshooting/) size yardımcı olacaktır. Daha fazla yardım ve canlı topluluğumuza katılmak için [Open WebUI Discord](https://discord.gg/5rJgQTnV4s)'u ziyaret edin.
#### Open WebUI: Sunucu Bağlantı Hatası
Bağlantı sorunları yaşıyorsanız, genellikle WebUI Docker container'ının 127.0.0.1:11434 (host.docker.internal:11434) adresindeki Ollama sunucusuna container içinde ulaşamamasından kaynaklanır. Bu sorunu çözmek için Docker komutunuzda `--network=host` bayrağını kullanın. Portun 3000'den 8080'e değiştiğini ve bağlantının `http://localhost:8080` olacağını unutmayın.
**Örnek Docker Komutu**:
```bash
docker run -d --network=host -v open-webui:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name open-webui --restart always ghcr.io/open-webui/open-webui:main
```
### Docker Kurulumunuzu Güncel Tutma
Yerel Docker kurulumunuzu en son sürüme güncellemek isterseniz, bunu [Watchtower](https://containrrr.dev/watchtower/) ile yapabilirsiniz:
```bash
docker run --rm --volume /var/run/docker.sock:/var/run/docker.sock containrrr/watchtower --run-once open-webui
```
Komutun son kısmında, container adınız farklıysa `open-webui` yerine kendi container adınızı yazın.
Güncelleme Rehberimizi [Open WebUI Dokümantasyonumuzda](https://docs.openwebui.com/getting-started/updating) bulabilirsiniz.
### Dev Branch Kullanımı 🌙
> **UYARI:**
> `:dev` branch'i en son kararsız özellikleri ve değişiklikleri içerir. Hatalar veya eksik özellikler içerebileceği için risk size ait olmak üzere kullanın.
En son geliştirme özelliklerini denemek ve ara sıra oluşabilecek kararsızlıklara razıysanız, `:dev` etiketini şu şekilde kullanabilirsiniz:
```bash
docker run -d -p 3000:8080 -v open-webui:/app/backend/data --name open-webui --add-host=host.docker.internal:host-gateway --restart always ghcr.io/open-webui/open-webui:dev
```
### Çevrimdışı Mod
Open WebUI'yi çevrimdışı bir ortamda çalıştırıyorsanız, modelleri internetten indirme girişimlerini engellemek için `HF_HUB_OFFLINE` ortam değişkenini `1` olarak ayarlayabilirsiniz.
```bash
export HF_HUB_OFFLINE=1
```
## Sırada Ne Var? 🌟
Yol haritamızdaki gelecek özellikleri [Open WebUI Dokümantasyonumuzda](https://docs.openwebui.com/roadmap/) keşfedin.
## Lisans 📜
Bu proje, yeniden düzenlenmiş bir BSD-3-Clause lisansı olan [Open WebUI Lisansı](LICENSE) altında lisanslanmıştır. Klasik BSD-3 lisansıyla aynı haklara sahipsiniz: yazılımı tescilli ve ticari ürünler de dahil olmak üzere minimum kısıtlamalarla kullanabilir, değiştirebilir ve dağıtabilirsiniz. Tek ek gereksinim, LİSANS dosyasında detaylandırıldığı gibi "Open WebUI" markasını korumaktır. Tüm koşullar için [LİSANS](LICENSE) belgesine bakın. 📄
## Destek 💬
Herhangi bir sorunuz, öneriniz varsa veya yardıma ihtiyacınız olursa, lütfen bir sorun (issue) açın veya bizimle bağlantı kurmak için [Open WebUI Discord topluluğumuza](https://discord.gg/5rJgQTnV4s) katılın! 🤝
## Yıldız Geçmişi
<a href="https://star-history.com/#open-webui/open-webui&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
    <img alt="Yıldız Geçmişi Grafiği" src="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
  </picture>
</a>
---
[Timothy Jaeryang Baek](https://github.com/tjbck) tarafından oluşturuldu - Birlikte Open WebUI'yi daha da harika yapalım! 💪
Türkçeye çeviren: Burak Can Öğüt
