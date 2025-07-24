# Open WebUI'ye Katkıda Bulunma
🚀 **Hoş Geldiniz, Katkıda Bulunanlar!** 🚀
Open WebUI'ye katkıda bulunma ilginizden dolayı minnettarız. Bu belge, katkılarınızın projeyi etkili bir şekilde geliştirmesini sağlamak için size yol göstermek amacıyla hazırlanmıştır. Gelin, Open WebUI'yi birlikte daha iyi hale getirelim!

## 📌 Temel Noktalar
### 🦙 Ollama vs. Open WebUI
Ollama ve Open WebUI arasında ayrım yapmak çok önemlidir:
- **Open WebUI**, sohbet etkileşimleri için sezgisel ve duyarlı bir web arayüzü sağlamaya odaklanır.
- **Ollama**, bu etkileşimleri destekleyen temel teknolojidir.
Eğer sorununuz veya katkınız doğrudan Ollama'nın temel teknolojisiyle ilgiliyse, lütfen bunu ilgili [Ollama proje deposuna](https://ollama.com/) yönlendirin. Open WebUI'nin deposu yalnızca web arayüzü yönüne adanmıştır.

### 🚨 Sorun Bildirme
Yanlış giden bir şey mi fark ettiniz? Bir fikriniz mi var? Daha önce bildirilip bildirilmediğini veya önerilip önerilmediğini görmek için [Sorunlar (Issues) sekmemizi](https://github.com/open-webui/open-webui/issues) kontrol edin. Eğer yoksa, yeni bir sorun açmaktan çekinmeyin. Sorun bildirirken, lütfen sorun şablonlarımızı takip edin. Bu şablonlar, gerekli tüm detayların baştan itibaren sağlanmasını sağlamak ve endişelerinizi daha verimli bir şekilde ele almamıza olanak tanımak için tasarlanmıştır.
> **ÖNEMLİ:**
>
> - **Şablon Uyumluluğu:** Sağlanan sorun şablonuna uyulmaması veya istenen bilgilerin hiç sağlanmaması durumunda, sorununuzun daha fazla değerlendirilmeden kapatılabileceğini lütfen unutmayın. Bu yaklaşım, sorun takibinin yönetilebilirliğini ve bütünlüğünü korumak için kritik öneme sahiptir.
> - **Detay Önemlidir:** Sorununuzun anlaşılmasını ve etkili bir şekilde ele alınmasını sağlamak için kapsamlı detaylar eklemek zorunludur. Açıklamalar açık olmalı, yeniden üretme adımları, beklenen sonuçlar ve gerçek sonuçlar dahil edilmelidir. Yeterli detayın olmaması, sorununuzu çözme yeteneğimizi engelleyebilir.

### 🧭 Destek Kapsamı
Open WebUI ile doğrudan ilgili olmayan, özellikle Docker kurulumları gibi çalıştığı ortamla ilgili sorunlarda bir artış fark ettik. Docker dağıtımını desteklemeye çalışsak da, sorunsuz bir deneyim için Docker temellerini anlamak çok önemlidir.
- **Docker Dağıtım Desteği**: Open WebUI, Docker dağıtımını destekler. Docker bilgisi olduğu varsayılır. Docker temelleri için lütfen [resmi Docker dokümantasyonuna](https://docs.docker.com/get-started/overview/) başvurun.
- **Gelişmiş Yapılandırmalar**: HTTPS için reverse proxy kurmak ve Docker dağıtımlarını yönetmek temel bilgi gerektirir. Bu becerileri öğrenmek için çok sayıda çevrimiçi kaynak mevcuttur. Bu bilgiye sahip olmanız, Open WebUI ve benzeri projelerle deneyiminizi büyük ölçüde artıracaktır.

## 💡 Katkıda Bulunma
Katkıda bulunmak mı istiyorsunuz? Harika! İşte nasıl yardımcı olabileceğiniz:
### 🛠 Pull Request'ler
Pull request'leri memnuniyetle karşılıyoruz. Bir tane göndermeden önce lütfen:
1. Fikirlerinizle ilgili bir tartışma başlatın [burada](https://github.com/open-webui/open-webui/discussions/new/choose).
2. Projenin kodlama standartlarına uyun ve yeni özellikler için testler ekleyin.
3. Gerektiğinde dokümantasyonu güncelleyin.
4. Açık, açıklayıcı commit mesajları yazın.
5. Pull request'inizi zamanında tamamlamanız çok önemlidir. Hızlı hareket ediyoruz ve PR'ların çok uzun süre bekletilmesi mümkün değildir. Eğer makul bir süre içinde tamamlayamazsanız, projenin ilerlemesini sağlamak için kapatmak zorunda kalabiliriz.

### 📚 Dokümantasyon ve Eğitimler
Dokümantasyonu geliştirerek, eğitimler yazarak veya web UI'yi kurma ve optimize etme konusunda rehberler oluşturarak Open WebUI'yi daha erişilebilir hale getirmemize yardımcı olun.

### 🌐 Çeviriler ve Uluslararasılaşma
Open WebUI'yi daha geniş bir kitleye ulaştırmamıza yardımcı olun. Bu bölümde, projeye yeni çeviriler ekleme sürecinde size rehberlik edeceğiz.
Çevirileri depolamak için JSON dosyalarını kullanıyoruz. Mevcut çeviri dosyalarını `src/lib/i18n/locales` dizininde bulabilirsiniz. Her dizin belirli bir dile karşılık gelir; örneğin, İngilizce (ABD) için `en-US`, Fransızca (Fransa) için `fr-FR` ve bu böyle devam eder. Belirli bir dil için uygun kodu bulmak üzere [ISO 639 Dil Kodları'na](http://www.lingoes.net/en/translator/langcode.htm) başvurabilirsiniz.
Yeni bir dil eklemek için:
- `src/lib/i18n/locales` yolunda, uygun dil kodunu ad olarak kullanarak yeni bir dizin oluşturun. Örneğin, İspanyolca (İspanya) çevirileri ekliyorsanız, `es-ES` adında yeni bir dizin oluşturun.
- Amerikan İngilizcesi çeviri dosyasını/dosyalarını (`src/lib/i18n/locale` dizinindeki `en-US` dizininden) bu yeni dizine kopyalayın ve JSON formatındaki string değerlerini kendi dilinize göre güncelleyin. JSON nesnesinin yapısını koruduğunuzdan emin olun.
- Dil kodunu ve ilgili başlığını `src/lib/i18n/locales/languages.json` adresindeki diller dosyasına ekleyin.

### 🤔 Sorular ve Geri Bildirim
Sorularınız veya geri bildiriminiz mi var? [Discord topluluğumuza](https://discord.gg/5rJgQTnV4s) katılın veya bir sorun açın. Yardımcı olmak için buradayız!

## 🙏 Teşekkür Ederiz!
Katkılarınız, büyük veya küçük olsun, Open WebUI üzerinde önemli bir etki yaratıyor. Projeye ne katacağınızı görmek için sabırsızlanıyoruz!
Birlikte, topluluk için daha da güçlü bir araç yaratalım. 🌟

Türkçeye çeviren: Burak Can Öğüt
