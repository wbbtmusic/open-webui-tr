# Güvenlik Politikası
Birincil hedefimiz, kullanıcılar tarafından Open WebUI üzerinde depolanan hassas verilerin korunmasını ve gizliliğini sağlamaktır.

## Desteklenen Sürümler
| Sürüm | Destekleniyor          |
| ------- | ------------------ |
| main    | :white_check_mark: |
| others  | :x:                |

## Harici Platformlara Sıfır Tolerans
Üçüncü taraf platformlardan gelen kabul edilemez düzeydeki spam ve istenmeyen iletişim emsallerine dayanarak, duruşumuzu kesin olarak yeniden teyit ediyoruz. **Güvenlik açığı bildirimleri için GitHub dışındaki hiçbir platformla etkileşim kurmayı, katılmayı veya izlemeyi reddediyoruz.** Nedenlerimiz sadece prosedürel değil, aynı zamanda projemizin açık kaynak kültüründe var olan şeffaflık ve doğrudan topluluk etkileşimini savunan etik anlayışına derinden bağlıdır. Süreçlerimizi harici platformlara yönlendirme girişimleri kesinlikle reddedilecektir. Bu politika müzakere edilemez ve hiçbir istisnası yoktur.

Belirlenen GitHub depomuz dışındaki kaynaklardan gelen her türlü rapor veya talep, değerlendirilmeye alınmaksızın reddedilecektir. Harici etkileşimlerin, topluluk odaklı projelerin bütünlüğünü nasıl zayıflatıp tehlikeye atabileceğini gördük ve kullanıcı topluluğumuzun güvenliği ve gizliliği konusunda kumar oynamaya burada değiliz.

## Güvenlik Açığı Bildirme
Potansiyel güvenlik açıklarını tespit etme konusundaki topluluğun ilgisini takdir ediyoruz. Ancak, derhal geçerli olmak üzere, düşük çabalı güvenlik açığı raporlarını **kabul etmeyeceğiz**. Gönderimlerin yapıcı ve uygulanabilir olmasını sağlamak için lütfen aşağıdaki yönergeleri izleyin:

Belirlenen GitHub depomuz aracılığıyla gönderilmeyen raporlar dikkate alınmayacak ve harici platformlarda işbirliği yapma davetlerini kesinlikle reddedeceğiz. Bu konudaki agresif duruşumuz, tüm operasyonların görünür olduğu ve katkıda bulunanların sorumlu olduğu güvenli, şeffaf ve açık bir topluluk oluşturma taahhüdümüzü vurgulamaktadır.

1.  **Muallak Rapor Yok**: Detay içermeyen "Bir güvenlik açığı buldum" gibi gönderimler spam olarak kabul edilecek ve kabul edilmeyecektir.
2.  **Derinlemesine Anlayış Gerekli**: Raporlar, kod tabanı hakkında net bir anlayış yansıtmalı ve etkilenen bileşenler ile potansiyel etkiler dahil olmak üzere güvenlik açığı hakkında spesifik detaylar sağlamalıdır.
3.  **Proof of Concept (PoC) Zorunludur**: Her gönderim, güvenlik açığını gösteren iyi belgelenmiş bir Proof of Concept (PoC) içermelidir. Gizlilik endişesi varsa, raporlayanların depoda özel bir fork oluşturmaları ve erişimi sürdürücülerle paylaşmaları teşvik edilir. Raporlar geçerli kanıt içermeyenler dikkate alınmayacaktır.
4.  **Gerekli Yama Gönderimi**: PoC ile birlikte, raporlayanlar tespit edilen güvenlik açığını gidermek için bir yama veya uygulanabilir adımlar sağlamalıdır. Bu, düzeltmeleri hızla değerlendirmemize ve uygulamamıza yardımcı olur.
5.  **Kolaylaştırılmış Birleştirme Süreci**: Güvenlik açığı raporları yukarıdaki kriterleri karşıladığında, tıpkı normal pull request'ler gibi derhal birleştirmek için değerlendirebiliriz. İyi yapılandırılmış ve kapsamlı gönderimler, güvenliğimizi artırma sürecini hızlandıracaktır.

**Yönetmeliklere uymayan gönderimler kapatılacak ve tekrarlayan ihlalciler yasaklanabilir.** Amacımız, kaliteli gönderimlerin tüm kullanıcılar için daha iyi güvenliği teşvik ettiği yapıcı bir raporlama ortamı oluşturmaktır.

## Ürün Güvenliği
Otomatik ve manuel test tekniklerinin bir kombinasyonunu kullanarak dahili süreçlerimizi ve sistem mimarimizi güvenlik açıkları açısından düzenli olarak denetliyoruz. Yakın zamanda projemizde SAST ve SCA taramalarını da uygulamayı planlıyoruz.

Acil endişeleriniz veya yönergelerimize uyan detaylı raporlar için, lütfen [sorun takip sistemimizde](/open-webui/open-webui/issues) bir sorun oluşturun veya [Discord](https://discord.gg/5rJgQTnV4s) üzerinden bizimle iletişime geçin.

---
_Son güncellenme tarihi:_ **_2024-08-19_**_._

Türkçeye çeviren: Burak Can Öğüt
