# Değişiklik Günlüğü

Bu projeye yapılan tüm önemli değişiklikler bu dosyada belgelenecektir.

Format, [Keep a Changelog](https://keepachielog.com/en/1.1.0/) standardını temel alır
ve bu proje [Semantic Versioning](https://semver.org/spec/v2.0.0.html) standardına uyar.

## [0.6.18] - 2025-07-19

### Düzeltildi

- 🚑 **Gruplarda Yüklenmeyen Kullanıcılar**: Kullanıcı grupları içinde kullanıcı listesinin görüntülenmemesi sorunu çözüldü. Bu düzeltme ile ekipler ve admin'ler için grup üyeliklerinin tam görünürlüğü ve yönetimi geri getirildi.

## [0.6.17] - 2025-07-19

### Eklendi

- 📂 **Sohbet Listesi İçeren Özel Klasör Görünümü**: Artık bir klasöre tıklandığında, o klasördeki tüm sohbetlerin bir listesini gösteren yepyeni bir başlangıç sayfası açılıyor. Bu, gezinmeyi basitleştiriyor ve ekiplere projeye özgü konuşmalara anında görünürlük sağlıyor.
- 🆕 **Modernleştirilmiş Klasör Oluşturma Modalı**: Yeni bir klasör oluşturmak artık, klasör düzenleme akışıyla görsel ve işlevsel olarak eşleşen özel bir modal ile kusursuz ve birleşik bir deneyim sunuyor. Bu, tüm kullanıcılar için çalışma alanı organizasyonunu daha sezgisel ve hatasız hale getiriyor.
- 🗃️ **Doğrudan Klasör Bilgi Tabanına Dosya Yükleme**: Artık dosyaları doğrudan bir klasörün bilgi tabanına yükleyebilirsiniz. Bu sayede, önceden bilgi tabanı oluşturmaya gerek kalmadan, kaynak ve belgeleri doğrudan ekleyerek proje alanlarınızı zenginleştirebilirsiniz.
- 🔎 **Aramada Sohbet Önizlemesi**: Sohbetleri ararken, sonuçları açmak zorunda kalmadan anında bağlam içinde önizleyebilirsiniz. Bu, özellikle büyük ve aktif ekiplerde keşfi, denetimi ve geri çağırmayı önemli ölçüde hızlandırır.
- 🖼️ **Notlara Resim Yükleme ve Satır İçi Ekleme**: Notlar artık metinlerinizin arasına doğrudan resim eklemeyi destekliyor. Bu sayede, resimleri sadece ek olarak değil, zengin, görsel olarak yapılandırılmış belgeler, beyin fırtınaları veya raporlar oluşturmanıza olanak tanır.
- 📱 **Gelişmiş Not Seçimi Düzenleme ve Soru-Cevap**: Notlarınızın herhangi bir bölümünü seçerek sadece vurgulanan kısmı düzenleyebilir veya o içerik hakkında odaklanmış sorular sorabilirsiniz. Bu, iş akışlarını kolaylaştırır, üretkenliği artırır ve incelemeleri veya yapay zeka destekli geliştirmeleri daha hedefli hale getirir.
- 📝 **Notları Zengin Metin Olarak Kopyalama**: Tüm notları—biçimlendirme, resimler ve yapı dahil—doğrudan zengin metin olarak kopyalayıp e-postalara, raporlara veya diğer araçlara sorunsuzca yapıştırabilirsiniz. Böylece WebUI dışındaki tutarlılığı ve netliği korursunuz.
- ⚡ **Akıcı Metin için Fade-In Deneyimi**: Canlı olarak oluşturulan yanıtlar artık yapay zeka tarafından akıtılırken zarif bir şekilde belirginleşerek daha doğal ve görsel olarak çekici bir okuma deneyimi yaratır. Eğer statik gösterimleri tercih ederseniz, bu özellik Arayüz ayarlarından kolayca kapatılabilir.
- 🔄 **Takip Eden Prompt'lar için Ayarlar**: Takip eden prompt deneyiminizi hassas bir şekilde ayarlayın. Yeni kontrollerle, bu prompt'ları görünür tutmayı veya otomatik olarak gönderilmek yerine doğrudan mesaj giriş kutusuna eklenmesini seçebilirsiniz. Bu, iş akışınız üzerinde size daha fazla esneklik ve kontrol sağlar.
- 🔗 **Prompt Değişkenleri için Dokümantasyon Hızlı Bağlantısı**: Prompt düzenleyici modalından tek bir tıklama ile prompt değişkenleri dokümantasyonuna erişin. Bu, öğrenme sürecini kısaltır ve gelişmiş prompt oluşturmayı daha erişilebilir hale getirir.
- 📈 **Telemetri için Aktif ve Toplam Kullanıcı Metrikleri**: Aktif ve toplam kullanıcıları izleyen yeni metriklerle kullanım alışkanlıkları ve platform etkileşimi hakkında değerli bilgiler edinin. Bu, büyük kuruluşlar için denetlenebilirliği ve planlamayı geliştirir.
- 🏷️ **Log Trace ve Span ID'leri ile İzlenebilirlik**: Her log kaydı artık ayrıntılı trace ve span ID'leri taşıyor. Bu, admin'lerin dağıtık sistemlerdeki veya karmaşık sorun giderme senaryolarındaki sorunları tespit etmesini ve çözmesini çok daha kolay hale getirir.
- 👥 **Kullanıcı Grubu Ekleme/Kaldırma Endpoint'leri**: Yeni ve geliştirilmiş endpoint'ler ile kullanıcıları gruplara zahmetsizce ekleyin veya çıkarın. Bu, admin'lere ve ekip liderlerine işbirliği ve izinler üzerinde daha hızlı ve net bir kontrol sağlar.
- ⚙️ **Not Ayarları ve Kontrolleri Sadeleştirildi**: Notlar için ana "Ayarlar" artık sadece "Kontroller" olarak adlandırılıyor ve not dosyaları artık özel bir kontroller bölümünde yer alıyor. Bu, gezinmeyi sadeleştirir ve notla ilgili seçenekleri bulmayı ve yapılandırmayı kolaylaştırır.
- 🚀 **Daha Hızlı Admin Kullanıcı Sayfası Yüklemeleri**: Admin'ler için kullanıcı listesi endpoint'i, ağır profil resimlerini hariç tutacak şekilde optimize edildi. Bu, büyük ekipler için yükleme sürelerini hızlandırır ve yönetimsel görevler sırasında beklemeyi azaltır.
- 📡 **Sohbet ID'si Header Yönlendirme**: Ollama ve OpenAI router istekleri artık istek başlıklarında sohbet ID'sini içeriyor. Bu, AI model entegrasyonları arasında daha iyi istek korelasyonu ve hata ayıklama yetenekleri sağlar.
- 🧠 **Gelişmiş Mantık Yürütme Etiketi İşleme**: Standart XML tarzı etiketler ve özel sınırlayıcılar da dahil olmak üzere çeşitli etiket formatlarını daha sağlam bir şekilde işlemek için mantık yürütme etiketi (reasoning tag) ayrıştırması iyileştirildi ve genişletildi. Bu, daha iyi AI mantık yürütme şeffaflığı ve hata ayıklama yetenekleri sağlar.
- 🔐 **OAuth Token Endpoint Kimlik Doğrulama Yöntemi**: Yapılandırılabilir OAuth token endpoint kimlik doğrulama yöntemi desteği eklendi. Bu, kurumsal OAuth entegrasyonları ve kimlik sağlayıcı uyumluluğu için gelişmiş esneklik ve güvenlik seçenekleri sunar.
- 🛡️ **Redis Sentinel Yüksek Erişilebilirlik Desteği**: Otomatik master keşfi, bağlantı hataları için akıllı yeniden deneme mantığı ve master node kesintileri sırasında sorunsuz çalışma özellikleriyle kapsamlı Redis Sentinel failover uygulaması. Bu, tek hata noktalarını ortadan kaldırır ve üretim ortamlarında sürekli hizmet kullanılabilirliği sağlar.
- 🌐 **Yerelleştirme ve Uluslararasılaştırma İyileştirmeleri**: Basitleştirilmiş Çince, Geleneksel Çince, Fransızca, Almanca, Korece ve Lehçe için çeviriler iyileştirildi ve genişletildi. Bu, tüm desteklenen dillerde küresel kullanıcılar için daha akıcı ve doğal bir deneyim sağlar.

### Düzeltildi

- 🏷️ **Hybrid Search İşlevselliği Geri Getirildi**: Hybrid search artık tekrar sorunsuz bir şekilde çalışıyor. Bu, tüm RAG destekli iş akışlarında daha doğru, ilgili ve kapsamlı bilgi keşfi sağlar.
- 🚦 **Not Sohbeti - AI Yanıtı Sırasında Düzenle Butonu Devre Dışı**: Bir notla sohbet ederken, AI yanıt verirken düzenle butonu artık devre dışı bırakılıyor. Bu, sohbet oturumları sırasında kazara yapılan düzenlemeleri önler ve iş akışı netliğini sağlar.
- 🧹 **Daha Temiz Veritabanı Kimlik Bilgileri**: Veritabanı bağlantısı artık kimlik bilgilerinde '@' karakterini kopyalamıyor. Bu, olası bağlantı sorunlarını önler ve daha sorunsuz, daha güvenilir entegrasyonlar sağlar.
- 🧑‍💻 **Dosya Silme Artık İlgili Vektör Verilerini de Kaldırıyor**: Dosyalar depolama alanından silindiğinde, artık vektör veritabanından da temizleniyor. Bu, temiz veri yönetimi sağlar ve dağınıklığı veya eski arama sonuçlarını önler.
- 📁 **Dosyalar Modal Çeviri Sorunları Giderildi**: "Tüm Belgeyi Kullanarak" ve "Odaklanmış Alım Kullanarak" dahil olmak üzere tüm modal iletişim kutusu metinleri artık daha tutarlı ve yerelleştirilmiş bir UI deneyimi için tamamen çevrildi.
- 🚫 **Desteklenmeyen Modeller için Sürükle-Bırak Dosya Yükleme Devre Dışı**: Eklentileri desteklemeyen modeller kullanılırken sürükle-bırak ile dosya yükleme devre dışı bırakıldı. Bu, kafa karışıklığını ortadan kaldırır ve iş akışı kesintilerini önler.
- 🔑 **Ollama Araç Çağrıları Artık Güvenilir**: Ollama tabanlı araç çağrılarındaki sorunlar giderildi. Bu, her sohbet için kesintisiz AI artırması ve araç kullanımı sağlar.
- 📄 **MIME Type Yardım Metni Düzeltmesi**: Dosya yükleme yapılandırmaları için daha net rehberlik sağlamak amacıyla gereksiz karakterler kaldırılarak mimetype yardım metni temizlendi.
- 📝 **Not Düzenleyici İzin Düzeltmesi**: Not sohbeti işlevselliğinden gereksiz admin-only kısıtlaması kaldırıldı. Bu, tüm yetkili kullanıcıların amaçlandığı gibi not düzenleme özelliklerine erişmesine olanak tanır.
- 📋 **Sohbet Kaynakları İşleme İyileştirildi**: Sohbet mesajlarında yinelenen kaynak atamalarını önlemek için kaynak işleme mantığı düzeltildi. Bu, konuşmalar sırasında daha temiz ve daha doğru kaynak atfı sağlar.
- 😀 **Emoji Oluşturma Hata Yönetimi**: Audio router'da hata yönetimi iyileştirildi ve emoji oluşturma görevleri için metadata yapısı düzeltildi. Bu, çökmeleri önler ve daha güvenilir emoji oluşturma işlevselliği sağlar.
- 🔒 **Klasör Sistem Prompt'u İzin Uygulaması**: Klasör düzenleme modalındaki sistem prompt'u alanları, sistem prompt'u izinlerine sahip olmayan kullanıcılar için artık düzgün bir şekilde gizleniyor. Bu, tüm klasör yönetimi arayüzlerinde tutarlı güvenlik politikası uygulanmasını sağlar.
- 🌐 **WebSocket Redis Kilit Zaman Aşımı Tip Dönüşümü**: WebSocket Redis kilit zaman aşımı yapılandırması için sağlam hata yönetimi ile uygun tamsayı tip dönüşümü düzeltildi. Bu, olası yapılandırma hatalarını önler ve kararlı WebSocket bağlantıları sağlar.
- 📦 **PostHog Bağımlılığı Eklendi**: ChromaDB uyumluluk sorunlarını çözmek için PostHog 5.4.0 kütüphanesi eklendi. Bu, kararlı vektör veritabanı işlemlerini sağlar ve dağıtım sırasında kütüphane sürüm çakışmalarını önler.

### Değiştirildi

- 👀 **Tiptap Editor v3'e Yükseltildi**: Altta yatan zengin metin düzenleyici, geleceğe dönük olarak güncellendi, ancak bazı destekleyici kütüphaneler uyumluluk için v2'de kaldı. Şimdilik, kurulum hatalarından kaçınmak için lütfen bağımlılıkları 'npm install --force' komutuyla yükleyin.
- 🚫 **Gereksiz veya Kullanılmayan Metinler ve Öğeler Kaldırıldı**: Sade ve yüksek performanslı bir deneyim sağlamak için çeşitli kullanılmayan, yinelenen veya eski kod ve çeviriler temizlendi.

## [0.6.16] - 2025-07-14

### Eklendi

- 🗂️ **Klasörler Proje Olarak**: İş akışınızı klasör tabanlı projelerle organize edin—klasör düzeyinde sistem prompt'ları ayarlayın ve özel bilgi tabanları ilişkilendirin. Bu, birden fazla girişimi veya müşteriyi yöneten ekipler ve kullanıcılar için sorunsuz, bağlam açısından zengin bir yönetim sağlar.
- 📁 **Anında Klasör Tabanlı Sohbet Oluşturma**: Herhangi bir klasörden doğrudan yeni bir sohbet başlatın; sadece tıklayın ve yeni konuşmanız otomatik olarak doğru proje bağlamına yerleştirilsin—artık manuel sürükleme veya kurulum yok, zamandan tasarruf edin ve hataları ortadan kaldırın.
- 🧩 **Otomatik Giriş Modallı Prompt Değişkenleri**: Değişkenler içeren prompt'lar artık, anında değer girişi için **ilk alana otomatik olarak odaklanan** temiz, otomatik oluşturulmuş bir giriş modalı görüntüler—sadece prompt'u seçin ve tam olarak neyin gerekli olduğunu doldurun, sürtünmeyi ve tahmini azaltın.
- 🔡 **Prompt'larda Değişken Giriş Tipi Belirleme**: Prompt değişkenleri için giriş türleri tanımlayın (örneğin, metin, metin alanı, sayı, seç, renk, tarih, harita ve daha fazlası). Bu, herkese gelişmiş otomasyon veya iş akışları için daha net ve daha kesin bir prompt oluşturma deneyimi sunar.
- 🚀 **Temel Model Listesi Önbellekleme**: Model seçimini hızlandırmak ve tekrarlanan API çağrılarını azaltmak için temel model listenizi önbelleğe alın; büyük veya çok sağlayıcılı kurulumlarda bile duyarlı model yönetimi için bunu Admin Ayarları > Bağlantılar'dan açıp kapatın.
- ⏱️ **Yapılandırılabilir Model Listesi Önbellek TTL'i**: Yeni MODEL_LIST_CACHE_TTL ortam değişkeniyle model listesi önbellekleme üzerinde kontrol sahibi olun. Performans ve güncelliği dengelemek için saniyeler içinde özel bir önbellek süresi ayarlayın, kararlı ortamlarda API isteklerini azaltın veya modeller sık değiştiğinde hızlı güncellemeler sağlayın.
- 🔖 **Notları Bilgi Tabanı Olarak veya Sohbetlerde Referans Verme**: Herhangi bir notu bir model veya klasör için bilgi tabanı olarak kullanın veya doğrudan sohbetten referans verin—canlı belgeleri Retrieval Augmented Generation (RAG) iş akışlarınıza veya tartışmalarınıza entegre ederek bilgi ve eylem arasında köprü kurun.
- 📝 **Notlarla Doğrudan Sohbet (Deneysel)**: Herhangi bir not hakkında sorular sorun ve notları doğrudan bir sohbet içinden düzenleyin veya güncelleyin—doğrudan yapay zeka destekli beyin fırtınası, özetleme ve temizleme kilidini açın, sanki kendi işbirlikçi yapay zeka tuvaliniz varmış gibi.
- 🤝 **Çok Kullanıcılı Düzenleme ile İşbirlikçi Notlar**: Notları başkalarıyla paylaşın ve canlı olarak işbirliği yapın—birden çok kullanıcı bir notu gerçek zamanlı olarak düzenleyebilir, işbirlikçi bilgi oluşturmayı ve iş akışı belgelerini artırabilir.
- 🛡️ **İşbirlikçi Not İzinleri**: Kuruluşunuzun ihtiyaçlarına göre gizliliği veya işbirliğini sağlamak için her notu kimin görüntüleyebileceğini veya düzenleyebileceğini sağlam paylaşım izinleriyle kontrol edin.
- 🔗 **Notlara Bağlantı Kopyala**: Ekibinizdeki veya harici işbirlikçilerinizle daha kolay bilgi aktarımı için notlara doğrudan bağlantıları hızla kopyalayın ve paylaşın.
- 📋 **Notlarda Görev Listesi Desteği**: Notlarınızın içinde kontrol listeleri veya görevler ekleyin, düzenleyin ve yönetin—projeleri planlayın, yapılacakları izleyin ve her şeyi tek bir alanda eyleme dönüştürülebilir tutun.
- 🧠 **AI Tarafından Oluşturulan Not Başlıkları**: Yapay zeka kullanarak notlarınız için anında ilgili ve özlü başlıklar oluşturun—bilgi kütüphanenizi sıkıcı manuel düzenleme olmadan düzenli tutun.
- 🔄 **Notlarda Tam Geri Alma/Yineleme Desteği**: En son not değişikliklerinizi zahmetsizce geri alın veya yineleyin—işbirliği yaparken veya yazarken hatalardan veya kazara yapılan düzenlemelerden asla korkmayın.
- 📝 **Gelişmiş Not Kelime/Karakter Sayacı**: Paylaşılan veya yayınlanan içerik için uzunluk yönergelerine uymayı kolaylaştıran yerleşik sayaçlarla notlarınızın boyutunu her zaman bilin.
- 🖊️ **Not Düzenleyicide Kayan ve Balon Biçimlendirme Menüleri**: Zengin metin düzenlemesini daha hızlı, daha keşfedilebilir ve her zamankinden daha kolay hale getiren hem kayan bir menü hem de not düzenleyicide doğrudan sezgisel bir balon menüsü aracılığıyla metin biçimlendirme araçlarına erişin.
- ✍️ **Zengin Metin Prompt Ekleme**: Yeni bir ayar, prompt'ların başlıklar, listeler ve kalın metin gibi Markdown öğelerini koruyarak sohbet kutusuna tam biçimlendirilmiş zengin metin olarak doğrudan eklenmesine olanak tanır, bu da daha sezgisel ve görsel olarak tutarlı bir düzenleme deneyimi sağlar.
- 🌐 **Yapılandırılabilir Veritabanı URL'si**: WebUI artık yeni ortam değişkenleri aracılığıyla daha esnek veritabanı yapılandırmasını destekliyor—dağıtımı ve çeşitli altyapı kurulumlarında ölçeklendirmeyi basitleştiriyor.
- 🎛️ **Geçici Sohbetlerde Tamamen Frontend Tarafından Yönetilen Dosya Yükleme**: Geçici sohbetleri kullanırken, dosya çıkarma artık tamamen tarayıcınızda gerçekleşir ve backend'e sıfır dosya gönderilir, bu da gizliliği daha da güçlendirir ve size anında geri bildirim verir.
- 🔄 **Gelişmiş Banner ve Sohbet Komutu Görünürlüğü**: Sohbetteki banner yönetimi ve komut geri bildirimi artık daha net ve bağlamsal olarak daha görünür, bu da uyarıları, önerileri ve otomasyonu tüm kullanıcılar için fark etmeyi ve etkileşimde bulunmayı kolaylaştırır.
- 📱 **Mobil Deneyim İyileştirildi**: "Yeni sohbet" butonu mobilde geri döndü, ayrıca temel gezinme ve giriş kontrolleri telefonlarda ve tabletlerde daha iyi kullanılabilirlik için düzeltildi.
- 📄 **OpenDocument Text (.odt) Desteği**: LibreOffice ve OpenOffice gibi açık kaynaklı ofis paketlerinden .odt dosyalarını sorunsuzca yükleyin ve işleyin, daha geniş bir belge formatı yelpazesinden bilgi oluşturma yeteneğinizi genişletin.
- 📑 **Gelişmiş Markdown Belge Bölme**: Yeni bir başlık duyarlı bölme stratejisiyle Markdown dosyalarından bilgi alımını iyileştirin. Bu yöntem, belgeleri başlık yapılarına göre akıllıca parçalara ayırır, orijinal bağlamı ve hiyerarşiyi daha doğru ve ilgili RAG sonuçları için korur.
- 📚 **Bilgi Tabanları için Tam Bağlam Modu**: Bir klasöre veya özel bir modele bilgi tabanı eklerken, artık tüm bilgi tabanı için tam bağlam modunu açabilirsiniz. Bu, normal parçalama ve alım sürecini atlar, bu da daha yalın bilgi tabanları için mükemmel hale getirir.
- 🕰️ **Yapılandırılabilir OAuth Zaman Aşımı**: Yavaş veya kısıtlı ağlarda kimlik doğrulama hatalarını önleyerek tüm OAuth sağlayıcıları (Google, Microsoft, GitHub, OIDC) için özel bir zaman aşımı (OAUTH_TIMEOUT) ayarlayarak giriş güvenilirliğini artırın.
- 🎨 **Erişilebilirlik ve Yüksek Kontrastlı Tema Geliştirmeleri**: Yüksek kontrastlı temada önemli güncellemelerle büyük bir erişilebilirlik revizyonu. İyileştirilmiş odak görünürlüğü, ARIA etiketleri ve anlamsal HTML, sohbet arayüzü ve model seçici gibi temel bileşenlerin görme engelli kullanıcılar için tamamen uyumlu ve okunabilir olmasını sağlar.
- ↕️ **Yeniden Boyutlandırılabilir Sistem Prompt Alanları**: Uzun veya karmaşık talimatları rahatça görüntülemek ve düzenlemek için sistem prompt giriş alanlarını yeniden boyutlandırın, bu da gelişmiş model yapılandırması için kullanıcı deneyimini iyileştirir.
- 🔧 **Ayrıntılı Güncelleme Kontrolü**: Yeni ENABLE_VERSION_UPDATE_CHECK bayrağı ile giden bağlantılar üzerinde daha ince kontrol sahibi olun. Bu, yöneticilerin hala gömme modellerini indirmesi gereken ancak kısıtlı internet erişimi olan ortamlar için sürüm güncelleme kontrollerini tam OFFLINE_MODE'dan bağımsız olarak devre dışı bırakmalarına olanak tanır.
- 🗃️ **Yapılandırılabilir Qdrant Koleksiyon Ön Eki**: Özel bir QDRANT_COLLECTION_PREFIX ayarlayarak ölçeklenebilirliği artırın. Bu, birden çok Open WebUI örneğinin tek bir Qdrant kümesini güvenli bir şekilde paylaşmasına olanak tanır ve ayrı dağıtımlar arasında çakışma olmaksızın tam veri yalıtımı sağlar.
- ⚙️ **İyileştirilmiş Varsayılan Veritabanı Performansı**: Daha akıllı veritabanı bağlantı havuzu varsayılanları ayarlayarak kutudan çıkar çıkmaz performansı artırın, manuel yapılandırma gerektirmeden SQLite dışı veritabanlarındaki kullanıcılar için API yanıt sürelerini azaltın.
- 🔧 **Yapılandırılabilir Redis Anahtar Ön Eki**: REDIS_KEY_PREFIX ortam değişkeni desteği eklendi, bu da birden çok Open WebUI örneğinin bir Redis kümesini yalıtılmış anahtar ad alanlarıyla paylaşmasına olanak tanıyarak çoklu kiracılığı iyileştirir.
- ➡️ **Kullanıcı Bağlamını Reranker'a Yönlendirme**: Gelişmiş RAG entegrasyonları için, kullanıcı bilgileri (ID, ad, e-posta, rol) artık kişiselleştirilmiş sonuçlar veya kullanıcı başına erişim kontrolü sağlamak için harici yeniden sıralama hizmetlerine HTTP başlıkları olarak iletilebilir.
- ⚙️ **PGVector Bağlantı Havuzu**: PGVector tabanlı RAG için performansı ve kararlılığı artırmak için veritabanı bağlantı havuzunu etkinleştirin ve yapılandırın. Yeni ortam değişkenleri, yüksek eşzamanlılık iş yüklerini verimli bir şekilde yönetmek için havuz boyutu, zaman aşımı ve taşma ayarlarını ince ayar yapmanıza olanak tanır.
- ⚙️ **Genel Backend Yeniden Yapılandırması**: Kapsamlı yeniden yapılandırma, daha hızlı, daha güvenilir ve sağlam bir backend deneyimi sunar—sohbet hızını, model yönetimini ve günlük güvenilirliği artırır.
- 🌍 **Genişletilmiş ve İyileştirilmiş Çeviriler**: Arayüz genelinde Çince (Basitleştirilmiş ve Geleneksel), Almanca, Fransızca, Katalanca, İrlandaca ve İspanyolca çeviriler için kapsamlı güncellemeler ve geliştirmeler sayesinde daha erişilebilir ve sezgisel bir deneyimin tadını çıkarın.

### Düzeltildi

- 🛠️ **Zengin Metin Girişi Kararlılığı ve Performansı**: Çok sayıda iyileştirme, daha hızlı, daha temiz metin düzenleme ve oluşturma sağlar ve özellikle notlar ve sohbetlerde bağlantıları, renk seçiciyi, onay kutusu kontrollerini ve kod bloklarını destekler.
- 📷 **Sorunsuz iPhone Resim Yüklemeleri**: HEIC formatını kullanan iPhone'lardan ve diğer cihazlardan zahmetsizce fotoğraf yükleyin—resimler artık doğru bir şekilde tanınır ve işlenir, uyumluluk sorunları ortadan kalkar.
- 🔄 **Ses MIME Türü Kaydı**: Ses dosyası içerik türleriyle ilgili sorunlar çözüldü, bu da transkripsiyon veya not ekleri için daha sorunsuz, hatasız yüklemeler ve oynatma garantisi verir.
- 🖍️ **Giriş Komutları Artık Her Zaman Görünür**: Giriş komutları (prompt'lar veya bilgi tabanları gibi) küçük ekranlarda yüksekliklerini dinamik olarak ayarlar, hiçbir şeyin kesilmemesini ve her aracın kolayca erişilebilir kalmasını sağlar.
- 🛑 **Araç Sonucu Oluşturma**: Araç sonuçlarıyla ilgili görüntüleme sorunları düzeltildi, harici veya dahili araçları kullanırken hızlı, net geri bildirim sağlar.
- 🗂️ **Markdown'da Tablo Hizalaması**: Markdown tabloları artık beklendiği gibi oluşturulur ve hizalanır, raporları ve belgeleri okunabilir tutar.
- 🖼️ **Konu Başlığı Resim Yönetimi**: Konu başlıklarında yalnızca resim içeren mesajların doğru görüntülenmemesi sorunu düzeltildi.
- 🗝️ **Not Erişim Kontrolü Güvenliği**: Paylaşılan veya işbirlikçi notların tüm kullanıcı izinlerine ve gizlilik korumalarına saygı duymasını garanti etmek için notlar için erişim kontrol mantığı sıkılaştırıldı.
- 🧾 **Ollama API Uyumluluğu**: Tüm Ollama endpoint'leri için kesintisiz uyumluluk sağlamak amacıyla API'deki model parametre adlandırması düzeltildi.
- 🛠️ **'text/html' Dosyaları için Algılama**: docling/tika ile yüklenen dosyalar artık doğru tür olarak güvenilir bir şekilde algılanır, bilgi alımını ve belge ayrıştırmasını iyileştirir.
- 🔐 **OAuth Giriş Kararlılığı**: Oturumu kapattıktan sonraki denemelerde giriş hatalarına neden olan kritik bir OAuth hatası çözüldü. Kullanıcı oturumu artık oturum kapatıldığında tamamen temizlenir, bu da tüm desteklenen sağlayıcılarda (Google, Microsoft, GitHub, OIDC) güvenilir ve güvenli kimlik doğrulama sağlar.
- 🚪 **OAuth Oturum Kapatma ve Yönlendirme Güvenilirliği**: OAuth oturum kapatma süreci daha sağlam hale getirildi. Oturum kapatma istekleri artık proxy ortam değişkenlerini doğru bir şekilde kullanır, bu da kurumsal ağlarda başarılı olmalarını sağlar. Ek olarak, özel WEBUI_AUTH_SIGNOUT_REDIRECT_URL artık tüm OAuth/OIDC yapılandırmaları için düzgün bir şekilde dikkate alınır, bu da sorunsuz bir oturum kapatma deneyimi sağlar.
- 📜 **Banner Yeni Satır Oluşturma**: Banner'lar artık yeni satır karakterlerini doğru bir şekilde oluşturur, bu da çok satırlı duyuruların ve mesajların amaçlanan biçimlendirmeleriyle görüntülenmesini sağlar.
- ℹ️ **Tutarlı Model Açıklaması Oluşturma**: Model açıklamaları artık ana sohbet arayüzünde Markdown'ı doğru bir şekilde oluşturur, tutarlı bir kullanıcı deneyimi için model seçim açılır menüsünde görülen biçimlendirmeyle eşleşir.
- 🔄 **Çevrimdışı Mod Güncelleme Kontrolü Gösterimi**: Uygulama çevrimdışı moda ayarlandığında "Güncellemeler kontrol ediliyor..." mesajının süresiz olarak görüntülenmesine neden olan bir UI hatası düzeltildi.
- 🛠️ **Araç Sonucu Kodlaması**: ASCII olmayan karakterler döndüren araç çağrılarının başarısız olmasına neden olan bir hata düzeltildi, bu da araç çıktılarında uluslararası metin ve özel karakterlerin sağlam bir şekilde işlenmesini sağlar.

### Değiştirildi

- 👀 **Tiptap Editor v3'e Yükseltildi**: Altta yatan zengin metin düzenleyici, geleceğe dönük olarak güncellendi, ancak bazı destekleyici kütüphaneler uyumluluk için v2'de kaldı. Şimdilik, kurulum hatalarından kaçınmak için lütfen bağımlılıkları 'npm install --force' komutuyla yükleyin.
- 🚫 **Gereksiz veya Kullanılmayan Metinler ve Öğeler Kaldırıldı**: Sade ve yüksek performanslı bir deneyim sağlamak için çeşitli kullanılmayan, yinelenen veya eski kod ve çeviriler temizlendi.

## [0.6.15] - 2025-06-16

### Eklendi

- 🖼️ **Global Resim Sıkıştırma Seçeneği**: Tüm resim yüklemelerinin ve çıktılarının optimize edilmesi için resim sıkıştırmayı global olarak zahmetsizce ayarlayın. Bu, yükleme sürelerini hızlandırır ve bant genişliğinden tasarruf sağlar—büyük dosyalarla veya sınırlı ağ kaynaklarıyla çalışan ekipler için mükemmeldir.
- 🎤 **Transkripsiyon için Özel Speech-to-Text Content-Type**: Ses transkripsiyonu için özel content type'ları tanımlayın. Bu, çeşitli ses kaynaklarıyla uyumluluk sağlar ve gelişmiş kurulumlarda daha pürüzsüz, daha doğru transkripsiyonların kilidini açar.
- 🗂️ **LDAP Grup Senkronizasyonu (Deneysel)**: Kullanıcı gruplarını LDAP dizininizden doğrudan Open WebUI'ye otomatik olarak senkronize ederek sorunsuz kurumsal erişim yönetimi sağlayın—kuruluşunuz genelinde kimlik entegrasyonunu ve yönetişimi basitleştirir.
- 📈 **OTLP Exporter ile OpenTelemetry Metrikleri (Deneysel)**: Deneysel OpenTelemetry Metrics desteği ile kurumsal düzeyde analitikler elde edin ve AI kullanımınızı gerçek zamanlı olarak izleyin—performans, yük ve kullanıcı etkileşimleri hakkında anında içgörüler için herhangi bir OTLP uyumlu backend'e bağlanın.
- 🕰️ **Kullanıcı Mesajı Zaman Damgalarını Üzerine Gelince Görme (Sohbet Balonu UI)**: Sohbet Balonu modunda herhangi bir kullanıcı mesajının üzerine gelerek ne zaman gönderildiğini zahmetsizce kontrol edin—bağlam için ekran değiştirmeye veya logları karıştırmaya son.
- 🗂️ **Liderlik Tablosu Sıralama Seçenekleri**: En iyi performans gösterenleri, modelleri veya araçları daha net ve eyleme geçirilebilir bir görünüm için liderlik tablosunu doğrudan UI üzerinden sıralayın—ekipler için analiz ve takdiri hızlı ve kolay hale getirir.
- 🏆 **Geri Bildirimler ve Liderlik Tablosunda Değerlendirme Detayları Modalı**: Geri bildirimleri ve liderlik tablosu sıralamalarını incelerken ayrıntılı değerlendirme bilgilerini gösteren yeni modallarla daha derine inin—öğrenmeyi, ilerleme takibini ve kalite iyileştirmesini hızlandırır.
- 🔄 **Harici Belge Yükleyicilerde Birden Fazla Sayfa Desteği**: Harici belgelerde birden fazla sayfaya yayılan içeriği zahmetsizce çıkarın ve üzerinde çalışın, derinlemesine araştırma ve belge iş akışları için size tam esneklik sağlar.
- 🌐 **Arayüz Genelinde Yeni Erişilebilirlik Geliştirmeleri**: Önemli erişilebilirlik iyileştirmelerinden yararlanın—sekme ile gezinme, ARIA rolleri/etiketleri, daha iyi yüksek kontrastlı metin/modlar, erişilebilir modallar ve daha fazlası—Open WebUI'yi yardımcı teknolojiler kullananlar da dahil olmak üzere herkes için daha kullanışlı ve eşit hale getirir.
- ⚡ **Frontend ve Backend Genelinde Performans ve Kararlılık Yükseltmeleri**: Hem frontend hem de backend'de sayısız perde arkası optimizasyon ve yeniden yapılandırma ile daha pürüzsüz, daha güvenilir bir deneyimin tadını çıkarın—daha hızlı yükleme süreleri, daha az hata ve iş akışlarınız boyunca daha da fazla kararlılık sağlar.
- 🌏 **Güncellenmiş ve Genişletilmiş Yerelleştirmeler**: Fince, Almanca (artık model sabitleme özellikleriyle), Korece, Rusça, Basitleştirilmiş Çince, İspanyolca ve daha fazlası için güncel çevirilerin keyfini çıkarın—uluslararası kullanıcılar için her etkileşimi daha pürüzsüz, daha net ve daha sezgisel hale getirir.

### Düzeltildi

- 🦾 **Ollama Hata Mesajları Daha Açıklayıcı**: Ollama modelleriyle ilgili bir şeyler ters gittiğinde daha net, daha eyleme geçirilebilir hata mesajları alın—sorun gidermeyi ve kullanıcı desteğini daha hızlı ve daha etkili hale getirir.
- 🌐 **Webloader'ı Atla Artık Beklendiği Gibi Çalışıyor**: "Webloader'ı atla" özelliğinin doğru çalışmamasını sağlayan bir sorun çözüldü, bu da web arama atlamalarının daha hafif, daha hızlı sorgu sonuçları için sorunsuz ve güvenilir bir şekilde çalışmasını sağlar.
- 🔍 **Alıntı Listesinde Gereksiz Belgeleri Önleme**: Genişletilmiş alıntı listesi artık yinelenen belgeleri göstermiyor, bilgi ve araştırma iş akışlarında kaynakları incelerken daha temiz, daha kolay anlaşılır bir referans deneyimi sunar.
- 🛡️ **Güvenilir Başlık E-posta Eşleştirmesi Artık Büyük/Küçük Harfe Duyarsız**: E-posta büyük/küçük harf duyarlılığının güvenli başlıkların eşleşmemesine neden olabileceği kritik bir kimlik doğrulama sorunu düzeltildi, tüm ortamlarda sağlam, sorunsuz giriş ve oturum yönetimi sağlanır.
- ⚙️ **Doğrudan Araç Sunucusu Girişi Boş Dizeleri Kabul Ediyor**: Artık boş dize değerleri geçerken beklenmedik hatalar olmadan doğrudan araç sunucusu komutları gönderebilirsiniz, bu da entegrasyon ve otomasyon verimliliğini artırır.
- 📄 **Alıntı Sayfa 1 için Sayfa Numarası Artık Görüntüleniyor**: Sayfa 1 belgeleri için referansların sayfa numarasını kaçırdığı bir ihmal düzeltildi; alıntılar artık her zaman doğru ve tam olarak görünür.
- 📒 **Notlara Erişim Geri Getirildi**: Bazı kullanıcıların notlarına erişemediği bir sorun düzeltildi—herkes artık notlarını güvenilir bir şekilde görüntüleyebilir ve yönetebilir, bu da sorunsuz belgelendirme ve iş akışı sürekliliği sağlar.
- 🛑 **OAuth Geri Çağırma Çift Eğik Çizgi Sorunu Çözüldü**: OAuth geri çağırmalarında fazladan bir eğik çizginin başarısız girişlere veya yönlendirmelere neden olduğu nadir durumlar düzeltildi, bu da üçüncü taraf giriş entegrasyonlarını daha güvenilir hale getirir.

### Değiştirildi

- 🔑 **Sistem Prompt'ları için Ayrı İzin**: Sistem prompt erişimi artık genel sohbet kontrolleriyle gruplandırılmak yerine kendi özel izniyle kontrol ediliyor. Bu, admin'lere gelişmiş güvenlik ve iş akışı özelleştirmesi için sistem prompt'larını kimin görüntüleyebileceği veya değiştirebileceği konusunda daha ayrıntılı bir yönetim sağlar.
- 🛠️ **YouTube Transcript API ve python-pptx Güncellendi**: Altta yatan kütüphane yükseltmeleri sayesinde daha iyi performans, güvenilirlik ve daha geniş uyumluluğun keyfini çıkarın—medya açısından zengin ve sunum iş akışlarıyla daha az sürtüşme.

### Kaldırıldı

- 🗑️ **Üretimde Konsol Günlüğü Devre Dışı**: Tüm 'console.log' ve 'console.debug' ifadeleri artık üretimde devre dışı bırakılmıştır. Bu, gereksiz teknik çıktıları kaldırarak son kullanıcılar için daha iyi güvenlik ve daha temiz tarayıcı logları garanti eder.

## [0.6.14] - 2025-06-10

### Eklendi

- 🤖 **Otomatik "Takip" Önerileri**: Open WebUI artık gönderdiğiniz her mesajla akıllıca eyleme geçirilebilir "Takip" önerileri oluşturur, akışınızı kesmeden üretken ve ilham dolu kalmanıza yardımcı olur; dikkatin dağılmadığı bir deneyim tercih ederseniz bunu her zaman Ayarlar'dan devre dışı bırakabilirsiniz.
- 🧩 **OpenAI Uyumlu Embeddings Endpoint'i**: Tamamen OpenAI tarzı bir '/api/embeddings' endpoint'i tanıtıyoruz—artık OpenAI tarzı embeddings iş akışlarını sıfır zahmetle bağlayabilirsiniz, bu da harici araçlar ve platformlarla entegrasyonları sorunsuz ve tanıdık hale getirir.
- ↗️ **Hızlı Erişim için Model Sabitleme**: Favori veya en çok kullandığınız modelleri anında seçim için kenar çubuğuna sabitleyin—artık uzun model listelerinde gezinmek yok; sık kullandığınız modeller her zaman görünür ve hızlı erişime hazırdır.
- 📌 **Seçici Model Öğesi Menüsü**: Seçicideki her model artık kenar çubuğuna kolayca sabitleyip/kaldırabileceğiniz ve doğrudan bir bağlantı kopyalayabileceğiniz bir menüye sahiptir—en yoğun ortamlarda bile işbirliğini basitleştirir ve düzenli kalmayı sağlar.
- 🛑 **Çoklu Kopya Kurulumlarında Devam Eden Sohbetler için Güvenilir Durdurma**: Devam eden bir sohbeti durdurmak veya iptal etmek artık kümelenmiş dağıtımlarda bile güvenilir bir şekilde çalışır—her kullanıcının, ölçeğiniz ne olursa olsun, AI çıktısını herhangi bir zamanda kesintiye uğratabilmesini sağlar.
- 🧠 **Ollama Modelleri için 'Think' Parametresi**: Ollama için yeni 'think' parametre desteğinden yararlanın—AI mantık yürütme süreci üzerinde gelişmiş kontrol sağlar ve benzersiz kullanım durumlarınız için model davranışını daha da ince ayar yapmanızı sağlar.
- 💬 **Docling için Resim Açıklama Modları**: Belge işlem hatlarınızda daha akıllı, daha ayrıntılı ve iş akışına özel görüntü anlama için Docling Loader tarafından görüntülerin nasıl tanımlandığını/çıkarıldığını özelleştirin.
- 🛠 **Ayarlar Modalı Derin Bağlantı**: Ayarlar'daki her sekmenin artık kendi rotası var—doğru ayarlara doğrudan gezinmeyi ve paylaşmayı daha hızlı ve daha sezgisel hale getirir.
- 🎤 **Ses HTML Bileşeni Token'ı**: Sesleri doğrudan sohbetlerinize kolayca yerleştirin ve oynatın, ses tabanlı iş akışlarını iyileştirin ve ses içeriğini herhangi bir konuşmadan anında erişilebilir ve yönetilebilir hale getirin.
- 🔑 **Gizli Anahtar Dosyası Desteği**: Artık daha güvenli ve esnek anahtar yönetimi için 'WEBUI_SECRET_KEY_FILE' belirtebilirsiniz—gelişmiş dağıtımlar ve daha sıkı güvenlik standartları için idealdir.
- 💡 **Prompt'ları Klonlarken Netlik**: Klonlanmış çalışma alanı prompt'ları, prompt kütüphanenizi düzenli tutmak ve kazara üzerine yazmaları önlemek için "(Klon)" ile açıkça etiketlenir ve ID'ler "-klon" içerir.
- 📝 **Özel Kullanıcı Rolü Düzenleme Modalı**: Kullanıcı rollerini güncellemek artık roller arasında geçiş yapmak yerine güvenilir bir şekilde özel bir düzenleme kullanıcı modalı açar—ekip izinlerini yönetmeyi daha güvenli ve daha net hale getirir.
- 🏞️ **Tercüman Tarafından Oluşturulan Görüntülerin Daha İyi İşlenmesi ve Depolanması**: Kod tercümanı tarafından oluşturulan görüntüler artık merkezi olarak depolanır ve veritabanından veya bulut depolamadan güvenilir bir şekilde yüklenir, bu da eserlerinizin her zaman kullanılabilir olmasını sağlar.
- 🚀 **Pinecone ve Vektör Arama Optimizasyonları**: Pinecone'dan en son en iyi uygulamaları, daha akıllı zaman aşımları, akıllı yeniden deneme kontrolü, geliştirilmiş bağlantı havuzu, daha hızlı DNS ve eşzamanlı toplu işlem yönetimi için uygulandı—manuel ayarlamalar olmadan size daha güvenilir, daha hızlı belge arama ve RAG performansı sağlar.
- ⚙️ **Ollama Gelişmiş Parametreleri Birleştirildi**: 'keep_alive' ve 'format' seçenekleri artık gelişmiş parametreler bölümüne entegre edildi—esnek model kontrolü için her şeyi model düzenleyiciden düzenleyin.
- 🛠️ **CUDA 12.6 Docker Image Desteği**: Yeni cuda126 görüntüsü aracılığıyla yetenek 7.0 ve altındaki NVIDIA GPU'larına (örneğin, V100, GTX1080) dağıtım yapın—ölçeklenebilir AI iş yükleri için donanım seçeneklerinizi genişletin.
- 🔒 **Deneysel Tablo Düzeyinde PGVector Veri Şifrelemesi**: Vektör arama tablosu içeriğinizi güvence altına almak için pgvector için pgcrypto şifreleme desteğini etkinleştirin, kuruluşlara gelişmiş uyumluluk ve veri koruması sağlayın—kurumsal veya düzenlenmiş ortamlar için mükemmeldir.
- 👁 **Arayüz Genelinde Erişilebilirlik Yükseltmeleri**: Sohbet düğmeleri ve kapatma kontrolleri artık en iyi erişilebilirlik desteği için etiketlenmiş ve yapılandırılmıştır, yardımcı teknolojilerle daha sorunsuz çalışmayı sağlar.
- 🎨 **Yüksek Kontrast Modu Genişletmeleri**: Yüksek kontrastlı erişilebilirlik modu artık menü öğeleri, sekmeler ve arama giriş alanlarına da uygulanır, tüm kullanıcılar için daha okunabilir bir deneyim sunar.
- 🛠️ **Araç İpucu ve Çeviri Netliği**: Özellikle radyo düğmeleri üzerindeki çeviri ve araç ipucu netliği iyileştirildi, bu da UI'yi tüm kullanıcılar için daha anlaşılır hale getirir.
- 🔠 **Global Yerelleştirme ve Çeviri İyileştirmeleri**: Geleneksel Çince, Basitleştirilmiş Çince, İbranice, Rusça, İrlandaca, Almanca ve Danca çeviri paketlerine yapılan büyük yükseltmeler—platformu dünya çapında daha fazla kullanıcı için yerel ve sezgisel hissettirir.
- ⚡ **Genel Backend Kararlılığı ve Güvenlik Geliştirmeleri**: Bellek kullanımını en aza indirmek, performansı artırmak ve harici API'lerle entegrasyonu kolaylaştırmak için çok sayıda backend rutini iyileştirildi—tüm platformu günlük işler için daha sağlam ve güvenli hale getirir.

### Düzeltildi

- 🏷 **Geri Bildirim Puanı Görüntüsü İyileştirildi**: Daha okunabilir ve erişilebilir değerlendirmeler için geri bildirim puanlarının taşma ve görünürlük sorunları giderildi.
- 🗂 **Admin Ayarları Model Düzenlemeleri Anında Uygulanır**: Admin Ayarları içindeki Model Düzenleyici'de yapılan değişiklikler artık anında yürürlüğe girer, model yönetimi sırasında kafa karışıklığını ortadan kaldırır.
- 🔄 **Atanmış Araçlar Yeni Sohbetlerde Anında Güncellenir**: Belirli araçlarla atanan modeller artık tutarlı bir şekilde güncellenir ve her yeni sohbette kullanılabilir—araç iş akışlarını daha öngörülebilir ve sağlam hale getirir.
- 🛠 **Belge Ayarları Yalnızca Kullanıcı Eyleminde Kaydedilir**: Belge ayarları artık yalnızca Kaydet düğmesine bastığınızda kaydedilir, kazara yapılan değişiklikleri azaltır ve daha fazla kontrol sağlar.
- 🔊 **Eski iOS Cihazlarda Ses Kaydı Geri Getirildi**: Ses girişi artık eski iOS cihazlarda tamamen işlevseldir, ses iş akışlarını tüm kullanıcılar için erişilebilir tutar.
- 🔒 **Güvenilir E-posta Başlığı Oturum Güvenliği**: Kullanıcı oturumları artık güvenilir e-posta başlığının oturum açmış kullanıcının e-postasıyla eşleştiğini kesin olarak doğrular, güvenli kimlik doğrulama sağlar ve kazara oturum geçişini önler.
- 🔒 **E-posta Uyuşmazlığında Tutarlı Kullanıcı Oturum Kapatma**: Başlıktaki güvenilir e-posta değiştiğinde, artık düzgün bir şekilde oturumunuz kapatılır ve yönlendirilirsiniz, oturumunuzun bütünlüğünü korur.
- 🛠 **Genel Hata ve İçerik Doğrulama İyileştirmeleri**: Daha akıllı hata yönetimi, daha net mesajlar ve daha az gereksiz yeniden deneme anlamına gelir—toplu yüklemeleri, belge işlemeyi ve bilgi dizinlemeyi daha dayanıklı hale getirir.
- 🕵️ **Sohbet Başlığı Düzenlemelerinde Daha İyi Geri Bildirim**: Sohbet başlıklarını düzenlerken sorunlar ortaya çıkarsa hata mesajları artık açıkça gösterilir.

### Değiştirildi

- 🔑 **Sistem Prompt'ları için Ayrı İzin**: Sistem prompt erişimi artık genel sohbet kontrolleriyle gruplandırılmak yerine kendi özel izniyle kontrol ediliyor. Bu, admin'lere gelişmiş güvenlik ve iş akışı özelleştirmesi için sistem prompt'larını kimin görüntüleyebileceği veya değiştirebileceği konusunda daha ayrıntılı bir yönetim sağlar.
- 🛠️ **YouTube Transcript API ve python-pptx Güncellendi**: Altta yatan kütüphane yükseltmeleri sayesinde daha iyi performans, güvenilirlik ve daha geniş uyumluluğun keyfini çıkarın—medya açısından zengin ve sunum iş akışlarıyla daha az sürtüşme.

### Kaldırıldı

- 🗑️ **Üretimde Konsol Günlüğü Devre Dışı**: Tüm 'console.log' ve 'console.debug' ifadeleri artık üretimde devre dışı bırakılmıştır. Bu, gereksiz teknik çıktıları kaldırarak son kullanıcılar için daha iyi güvenlik ve daha temiz tarayıcı logları garanti eder.

## [0.6.13] - 2025-05-30

### Eklendi

- 🟦 **Azure OpenAI Embedding Desteği**: Artık metin embedding'leri için Azure OpenAI endpoint'lerini seçebilirsiniz. Bu, güçlü RAG ve bilgi iş akışları için kurumsal ölçekli Azure AI ile sorunsuz entegrasyonu açar—artık geçici çözümlere gerek yok, zahmetsizce bağlanın ve ölçeklendirin.
- 🧩 **Daha Akıllı Özel Parametre İşleme**: Anında daha esnek model kurulumunun keyfini çıkarın—özel parametre alanlarına yapıştırılan herhangi bir JSON artık otomatik olarak ayrıştırılır, böylece sıkıcı manuel ayarlamalara gerek kalmadan zengin, iç içe parametreler tanımlayabilirsiniz. Bu, tüm modeller için gelişmiş yapılandırmayı kolaylaştırır ve denemeleri hızlandırır.
- ⚙️ **Genel Backend Yeniden Yapılandırması**: Önemli backend iyileştirmeleri, daha temiz bir kod tabanı, daha iyi sürdürülebilirlik, daha hızlı performans ve daha da fazla platform güvenilirliği sağlar—tüm iş akışlarınızın daha sorunsuz çalışmasını sağlar.
- 🌏 **Yerelleştirme Yükseltmeleri**: Basitleştirilmiş, Geleneksel Çince, Korece ve Fince dillerinde oldukça geliştirilmiş kullanıcı arayüzü çevirileri ve netliği deneyimleyin. Bu, küresel kullanıcılar için daha doğal, doğru ve erişilebilir bir deneyim sunar.

### Düzeltildi

- 🛡️ **Sohbet Yüklemede Sağlam Mesaj İşleme**: Bir sohbet sayfasının yüklenememesine neden olan bir sorun düzeltildi. Artık sohbetler her zaman sorunsuz yüklenir ve eksik ID'ler iş akışınızı bozmaz.
- 📝 **Doğru Prompt Erişim Kontrolü**: Prompt erişim kontrollerinin doğru bir şekilde kaydedilmesi sağlandı, güvenilir izin yönetimini geri getirdi ve prompt iş akışlarınızı güvence altına aldı.
- 🛠 **Open WebUI'ye Özgü Parametreler Artık Modellere Gönderilmiyor**: Dahili WebUI parametrelerini API'lere gönderen bir hata düzeltildi, yalnızca amaçlanan model seçeneklerinin iletilmesini sağlayarak öngörülebilir, hatasız model çalışmasını geri getirdi.
- 🧠 **Geliştirilmiş Bellek Hata Yönetimi**: Bellekle ilgili işlemler sırasında kararlılık artırıldı, böylece nadir görülen bellek hataları bile oturumunuzu kesintiye uğratmadan sorunsuz bir şekilde yönetilir—daha güvenilir, daha az endişe verici bir deneyim sağlar.

## [0.6.12] - 2025-05-29

### Eklendi

- 🧩 **Özel Gelişmiş Model Parametreleri**: Artık herhangi bir modele kendi özel gelişmiş parametrelerinizi ekleyebilir, böylece davranışı ince ayar yapabilir ve yerleşik seçeneklerin ötesinde daha fazla esneklik elde edebilirsiniz—denemelerinizi hızlandırın.
- 🪧 **Datalab Marker API İçerik Çıkarma Desteği**: Datalab Marker API'sini kullanarak dosyalar ve belgelerden içeriği doğrudan iş akışlarınıza sorunsuzca çıkarın. Bu, UI'de basit bir motor değişikliği ile RAG ve belge işleme için daha sağlam yapılandırılmış veri çıkarmayı sağlar.
- ⚡ **Paralel Temel Model Çekme**: Fark edilir derecede daha hızlı başlangıç ve model yenileme süreleri yaşayın—temel model verileri artık paralel olarak yüklenir, yoğun veya büyük ölçekli dağıtımlarda gecikmeleri önemli ölçüde kısaltır.
- 🧠 **Verimli Fonksiyon Yükleme ve Önbellekleme**: Fonksiyonlar artık yalnızca içerikleri değişirse yeniden yüklenir, gereksiz yinelenen yüklemeleri önler, bant genişliğinden tasarruf sağlar ve performansı artırır.
- 🌍 **Yerelleştirme ve Çeviri Geliştirmeleri**: Basitleştirilmiş, Geleneksel Çince ve Rusça çevirileri iyileştirildi ve genişletildi, küresel kullanıcılar için daha sorunsuz, daha doğru ve bağlama duyarlı deneyimler sunar.

### Düzeltildi

- 💬 **Kararlı Mesaj Giriş Kutusu**: Mesaj giriş kutusunun beklenmedik şekilde kayması sorunu düzeltildi (özellikle mobilde veya ekran okuyucu desteğiyle), her kullanıcı için pürüzsüz ve güvenilir bir yazma deneyimi sağlar.
- 🔊 **Güvenilir Yüksek Sesle Okuma (Text-to-Speech)**: Yüksek sesle okuma artık mesajlar arasında sorunsuz bir şekilde çalışıyor, bu da erişilebilirlik veya çoklu görev için TTS'ye bağımlı kullanıcıların kesintisiz ve net ses çalma deneyimi yaşamasını sağlar.
- 🖼 **Resim Önizleme ve İndirme Geri Getirildi**: Resim önizleme ve indirme sorunları düzeltildi, bu da sohbetlerinizde resimlerin sorunsuz bir şekilde oluşturulmasını, önizlenmesini ve indirilmesini sağlar—yaratıcı veya belgelendirme iş akışlarında artık kesinti yok.
- 📱 **Çalışma Alanı Yetenekleri için Gelişmiş Mobil Stil**: Yetenek yönetimi artık mobil cihazlarda bile okunabilir ve kullanımı kolaydır, bu da admin'lerin ve kullanıcıların hareket halindeyken erişimi hızlı bir şekilde yönetmelerini sağlar.
- 🔁 **/api/v1/retrieval/query/collection Endpoint Güvenilirliği**: Alım koleksiyonlarına yapılan sorgular artık beklenen sonuçları döndürüyor, bilgi iş akışlarınızın ve alıntıya hazır yanıtların güvenilirliğini güçlendiriyor.

### Kaldırıldı

- 🧹 **Yinelenen CSS Öğeleri**: Kullanılmayan CSS'i kaldırarak UI sadeleştirildi, bu da daha sorunsuz bir görsel deneyim için dağınıklığı azaltır ve yükleme sürelerini iyileştirir.

## [0.6.11] - 2025-05-27

### Eklendi

- 🟢 **Model Seçicide Ollama Model Durum Göstergesi**: Ollama model seçicideki açık bir gösterge ile hangi modellerin o anda yüklü olduğunu anında görün, bu da düzenli kalmanıza ve yerel model kullanımını optimize etmenize yardımcı olur.
- 🗑️ **Ollama Modelini Doğrudan Model Seçiciden Kaldırma**: Yüklü Ollama modelini doğrudan model seçicide kaldırarak belleği ve kaynakları kolayca serbest bırakın—sayfalar arasında geçiş yapmadan donanım yönetimini kolaylaştırın.
- 🗣️ **Kullanıcı Tarafından Yapılandırılabilir Speech-to-Text Dil Ayarı**: Bireysel kullanıcıların ayarlarında tercih ettikleri STT dilini açıkça ayarlamalarına izin vererek transkripsiyon doğruluğunu artırın—çok dilli ekipler ve net ses yakalama için idealdir.
- ⚡ **Ayrıntılı Ses Çalma Hızı Kontrolü**: Sadece ön ayarlar yerine, artık sayısal bir giriş kullanarak ayrıntılı ses hızını seçebilir, transkripsiyonlarda ve medya incelemelerinde çalma hızı üzerinde tam kontrol sahibi olabilirsiniz.
- 📦 **GZip, Brotli, ZStd Sıkıştırma Middleware**: Yeni sunucu tarafı sıkıştırma ile önemli ölçüde daha hızlı sayfa yüklemelerinin ve azaltılmış bant genişliği kullanımının keyfini çıkarın—kullanıcılara daha hızlı, daha verimli bir deneyim sunar.
- 🏷️ **Hybrid Search'te BM25 için Yapılandırılabilir Ağırlık**: Hibrit aramada BM25 için ağırlığı UI'dan ayarlayarak arama alaka düzeyini ince ayar yapın, bu da bilgi arama sonuçlarını iş akışınıza göre uyarlamanıza olanak tanır.
- 🧪 **CTRL + SHIFT + V ile Dosya Oluşturmayı Atla**: "Büyük Metni Dosya Olarak Yapıştır" etkinleştirildiğinde, dosya oluşturma iletişim kutusunu atlamak ve metni anında dosya olarak yüklemek için CTRL + SHIFT + V kullanın—hızlı belge hazırlığı için mükemmeldir.
- 🌐 **Web Arama'da Web Yükleyiciyi Atla**: Web içeriği yüklemesini atlamayı ve sayfa yüklemeleri yavaş veya engellendiğinde daha hızlı, daha güvenilir sonuçlar için web aramasında doğrudan snippet'leri kullanmayı seçin.
- 🚀 **Ortam Değişkeni: WEBUI_AUTH_TRUSTED_GROUPS_HEADER**: Artık kullanıcı gruplarını doğrudan güvenilir HTTP başlığı aracılığıyla senkronize edin ve yönetin, kuruluşlar için daha sorunsuz tek oturum açma ve kimlik entegrasyonlarının kilidini açın.
- 🏢 **Çalışma Alanı Modelleri Görünürlük Kontrolleri**: Artık çalışma alanı düzeyindeki modelleri hem model seçiciden hem de paylaşılan ortamlardan gizleyebilirsiniz—ekibinizi odaklanmış tutun ve nadiren kullanılan endpoint'lerin dağınıklığını azaltın.
- 🛡️ **Model Bağlantısını Kopyala**: Artık herhangi bir modele (seçiciden gizlenmiş olanlar dahil) doğrudan bir bağlantı kopyalayabilirsiniz—başkalarıyla paylaşımı ve onboarding'i daha sorunsuz hale getirir.
- 🔗 **Fonksiyonu Doğrudan URL'den Yükle**: Özel fonksiyon yönetimini basitleştirin—herhangi bir GitHub fonksiyon URL'sini Open WebUI'ye yapıştırın ve saniyeler içinde yeni fonksiyonları içe aktarın.
- ⚙️ **Harici Araç Sunucuları için Özel Ad/Açıklama**: Harici araç sunucularını özel adlar ve açıklamalar atayarak kişiselleştirin ve netleştirin, bu da büyük ölçekli çalışma alanlarında entegrasyonları yönetmeyi kolaylaştırır.
- 🌍 **Araç Sunucuları için Özel OpenAPI JSON URL Desteği**: Herhangi bir özel OpenAPI JSON URL'sini belirtmeyi destekler, araç çağrıları için herhangi bir backend ile daha esnek entegrasyonun kilidini açar.
- 📊 **Kaynak Alanı Artık Akışsız Yanıtlarda Eklerle Görüntüleniyor**: Dosyalar veya bilgi tabanları eklendiğinde, "kaynak" alanı artık tüm yanıtlarda, akışsız modda bile görüntülenir—bu da alıntı iş akışını iyileştirir.
- 🎛 **Sabitlenmiş Sohbetler**: Sabitlenmiş sohbet isteklerindeki yük boyutunu azalttı—özellikle yoğun depolarda daha hızlı yükleme süreleri ve daha az veri kullanımı sağlar.
- 🛠 **Varsayılan Prompt Önerilerini İçe/Dışa Aktarma**: Prompt önerilerini tek tıklamayla içe/dışa aktarmanın keyfini çıkarın, bu da ekipler veya dağıtımlar arasında en iyi uygulamaları paylaşmayı, yeniden kullanmayı ve yönetmeyi çok daha kolay hale getirir.
- 🍰 **Banner'lar Artık Yönetici Ayarlarından Sıralanabilir**: Banner'ları hızlıca yeniden sıralayın veya önceliklendirin, bu da ekibiniz için en kritik bilgiyi vurgulamanıza olanak tanır.
- 🛠 **Gelişmiş Sohbet Parametreleri—Daha Net Ollama Destek Etiketleri**: Parametreler ve gelişmiş ayarlar artık Ollama'ya özgü olup olmadıklarını açıkça belirtir, kafa karışıklığını azaltır ve kurulum doğruluğunu artırır.
- 🤏 **Daha İyi Görünürlük için Scroll Bar Başparmağı İyileştirildi**: Kaydırma çubuğu stili geliştirildi, gezinmeyi daha erişilebilir ve görsel olarak sezgisel hale getirdi.
- 🗄️ **Arşivlenmiş ve Kullanıcı Sohbet Listelemeleri için Modal Yeniden Tasarımı**: Arşivlenmiş ve kullanıcıya özgü sohbetlere göz atmak için temiz, modern modal arayüzü, konuşmaları daha hızlı ve daha keyifli bulmanızı sağlar.
- 📝 **Bellek Modalı UX Ekleme/Düzenleme**: Bellek modalları artık daha büyük ve yeniden boyutlandırılabilir giriş alanlarına sahip, uzun veya karmaşık bellek içeriğini daha kolay düzenlemeyi destekler.
- 🏆 **Çeviri ve Yerelleştirme Geliştirmeleri**: Çince (Basitleştirilmiş ve Geleneksel), Korece, Rusça, Almanca, Danca, Fince için büyük yükseltmeler—sadece yazım hatalarını düzeltmekle kalmayıp, daha doğal bir ana dil deneyimi için tutarlılık, ton ve terminolojiyi de kapsar.
- ⚡ **Genel Backend Kararlılığı ve Güvenlik Geliştirmeleri**: Daha sorunsuz çalışma ve gönül rahatlığı için daha dayanıklı, güvenilir ve güvenli bir platform sağlamak amacıyla çeşitli backend iyileştirmeleri.

### Düzeltildi

- 🖼️ **İzin Verilen Dosya Uzantılarıyla Resim Oluşturma Artık Güvenilir Şekilde Çalışıyor**: Katı dosya uzantısı kuralları ayarlanmış olsa bile sorunsuz resim oluşturmayı sağlayın—teknik aksaklıklar nedeniyle yaratıcı iş akışları artık engellenmiyor.
- 🗂 **Dosya Uzantısı Kontrolü için Baştaki Noktayı Kaldır**: Dosya doğrulamasının baştaki bir nokta nedeniyle başarısız olması sorunu düzeltildi, dosya yüklemelerini ve bilgi yönetimini daha sağlam hale getirdi.
- 🏷️ **Doğru Yerel/Harici Model Sınıflandırması**: Platform artık yerel ve harici modeller arasında doğru bir şekilde ayrım yapıyor—yerel modellerin harici olarak (veya tam tersi) görünmesini önlüyor—AI model endpoint'lerinizin sorunsuz kurulumunu, netliğini ve yönetimini sağlıyor.
- 📄 **Harici Belge Yükleyici Artık Amaçlandığı Gibi İşlev Görüyor**: Harici belge yükleyicileri güvenilir bir şekilde çağrılır, harici kaynaklardan daha sorunsuz bilgi alımı sağlar—RAG ve bilgi iş akışlarınızı genişletir.
- 🎯 **Toggle Filtrelerinin Doğru İşlenmesi**: Toggle filtreleri artık sağlam bir şekilde yönetilir, kazara otomatik etkinleştirmeyi önler ve kullanıcı tercihlerinin her zaman dikkate alınmasını sağlar.
- 🗃 **S3 Etiketleme Karakter Kısıtlamaları Düzeltildi**: S3'teki dosyalar için etiketler artık Amazon'un izin verilen karakter kümesini otomatik olarak karşılar, yükleme hatalarını önler ve bulutlar arası uyumluluk sağlar.
- 🛡️ **Kimlik Doğrulama Artık Yinelenen E-postalar Olduğunda Parola Karması Kullanıyor**: Sisteminizde yinelenen e-postalar varsa hesap güvenliğini sağlar ve erişim sorunlarını önler.

### Değiştirildi

- 🧩 **Yönetici Ayarları: OAuth Yönlendirmeleri Artık WEBUI_URL Kullanıyor**: OAuth yönlendirme URL'si artık açıkça ayarlanmış WEBUI_URL'ye dayanıyor, bu da tek oturum açma ve kimlik sağlayıcı entegrasyonlarının kullanıcıları her zaman doğru frontend'e göndermesini sağlar.

### Kaldırıldı

- 💡 **Yinelenen/Yazım Hatası Bileşenlerinin Kaldırılması**: Ekibin genel kod kalitesini iyileştirmek ve kafa karışıklığını azaltmak için eski bileşenler temizlendi.
- 🚫 **Pinecone'daki Akışlı Upsert Kaldırıldı**: En son Pinecone SDK güncellemeleriyle daha iyi uyumluluk ve geleceğe dönüklük için akışlı upsert referansları kaldırıldı.

## [0.6.10] - 2025-05-19

### Eklendi

- 🧩 **Deneysel Azure OpenAI Desteği**: Azure OpenAI URL'nizi yapıştırarak Azure OpenAI endpoint'lerine anında bağlanın—esnek, kurumsal düzeyde AI entegrasyonunu doğrudan iş akışınıza getiriyor.
- 💧 **AI Yanıtlarına Filigran Ekleme**: AI tarafından oluşturulan yanıtlara kolayca görünür bir filigran ekleyerek içeriğin kaynağını ve AB AI düzenlemelerine uyumluluğu net bir şekilde belirtin—düzenlenmiş ortamlar ve şeffaf iletişim için mükemmeldir.
- 🔍 **Özel Modalla Gelişmiş Arama Deneyimi**: Her yerden erişilebilen özel bir modalda (Ctrl/Cmd + K ile açın) modern, güçlü bir arama UI'sinin keyfini çıkarın—sohbetleri, modelleri veya içeriği hızlıca bulun ve üretkenliğinizi artırın.
- 🔲 **Sohbet Girişine "Toggle" Filtre Tipi**: Doğrudan sohbet girişine etkileşimli toggle filtreleri (örneğin Web Search, Image, Code Interpreter) ekleyin—özellikleri tek tıklamayla etkinleştirme kontrolü sağlayarak sohbet yapılandırma sürecini basitleştirir.
- 🧰 **Ayrıntılı Model Yetenekleri Düzenleyici**: Her AI modeli için ayrıntılı yetenekleri ve özellik erişimini doğrudan model düzenleyiciden tanımlayın—her ekip veya kullanım durumu için özelleştirilmiş davranış, modüler kontrol ve daha kişiselleştirilmiş bir AI ortamı sağlar.
- 🌐 **Esnek Yerel ve Harici Bağlantı Desteği**: Artık herhangi bir AI bağlantısını—OpenAI, Ollama veya diğerleri—yerel veya harici olarak belirleyebilirsiniz, bu da yerinde, kendi barındırdığınız veya bulut yapılandırmaları için sorunsuz kurulumu etkinleştirir ve size maksimum kontrol ve esneklik sağlar.
- 🗂️ **RAG için İzin Verilen Dosya Uzantıları**: Retrieval-Augmented Generation (RAG) iş akışlarınız üzerinde tam kontrol sahibi olun. Yüklemeye izin verilen dosya uzantılarını tam olarak belirterek, dizine eklenen belgelerin güvenliğini ve alaka düzeyini iyileştirin.
- 🔊 **Gelişmiş Ses Transkripsiyon Mantığı**: Daha pürüzsüz, daha güvenilir ses transkripsiyonu deneyimi yaşayın—çok uzun ses dosyaları artık otomatik olarak bölünür ve segmentler halinde işlenir, hataları önler ve zorlu dosyaların bile sorunsuz bir şekilde transkript edilmesini sağlar, hepsi sağlam medya iş akışları için daha geniş bir kararlılık yükseltmesinin parçasıdır.
- 🦾 **Harici Belge Yükleyici Desteği**: Geniş bir veri kaynağı yelpazesinden harici yükleyicileri kullanarak belge tabanı oluşturmayı geliştirin, AI'nizin okuyabileceği ve işleyebileceği belge formatlarını genişletin.
- 📝 **Kod Artifact'leri için Önizleme Butonu**: Yeni bir önizleme butonuna tıklayarak bir HTML kod bloğundan ilgili artifact sayfasına anında atlayın—incelemeyi hızlandırır ve analizi kolaylaştırır.
- 🦻 **Yanıt Mesajları için Ekran Okuyucu Desteği**: Tüm sohbet yanıtları artık ekran okuyucularla tamamen uyumludur, platformu herkes için daha kapsayıcı ve erişilebilir hale getirir.
- 🧑‍💼 **Özelleştirilebilir Bekleyen Kullanıcı Katmanı**: Bekleyen kullanıcılara gösterilen katman başlığını ve içeriğini artık özelleştirebilirsiniz, bu da onboarding mesajlarının kuruluşunuzun tonu ve gereksinimleriyle mükemmel bir şekilde uyumlu olmasını sağlar.
- 🔐 **LDAP Sertifika Doğrulamasını Devre Dışı Bırakma Seçeneği**: Çeşitli BT ortamlarında maksimum esneklik için LDAP sertifika doğrulamasını artık devre dışı bırakabilirsiniz—entegrasyonları ve sorun gidermeyi çok daha kolay hale getirir.
- 🎯 **Kullanıcı Adı veya E-posta ile Çalışma Alanı Araması**: Kullanıcı ve kaynak yönetimini kolaylaştırmak için çalışma alanı sayfaları arasında herhangi bir kullanıcı adı veya e-posta adresi kullanarak kolayca arama yapın.
- 🎨 **Yüksek Kontrast ve Koyu Mod Geliştirmeleri**: Daha rahat görüntüleme için yer tutucu, giriş, öneri, toast ve model seçici kontrastları daha da iyileştirildi—özel bir yer tutucu koyu modu dahil.
- 🛡️ **Pipelines ve Model Yüklemeleri için Geliştirilmiş Güvenlik**: Yüklemeler sırasında yol dolaşma güvenlik açıklarına karşı korumalar güçlendirildi—platformunuzun belge ve model yönetiminin güvenli kalmasını sağlar.
- 🌏 **Büyük Yerelleştirme Yükseltmeleri**: Korece, Bulgarca, Katalanca, Japonca, İtalyanca, Geleneksel Çince ve İspanyolca için kapsamlı çeviri güncellemeleri ve iyileştirmeleri—netlik için daha doğru AI terminolojisi dahil; deneyiminiz artık her yerde daha doğal, kapsayıcı ve profesyonel.
- 🦾 **Genel Backend Kararlılığı ve Güvenliği**: Çeşitli backend iyileştirmeleri (dosya yükleme, komut gezintisi ve log refactoring'leri dahil) artırılmış dayanıklılık, daha iyi hata yönetimi ve tüm kullanıcılar için daha sağlam bir platform sağlar.

### Düzeltildi

- ✅ **Değerlendirme Geri Bildirim Endpoint Güvenilirliği**: Model yanıtlarında sorunsuz kullanıcı geri bildirim toplama sağlamak için geri bildirim gönderme endpoint'leriyle ilgili sorunlar giderildi.
- 🫰 **Model Listesi Durum Düzeltmeleri**: Çalışma alanı sayfasındaki model durumu geçişlerinin yanlışlıkla geçiş yapabileceği veya durumu karıştırabileceği sorunlar çözüldü, aktif/pasif modellerin yönetimini daha güvenilir hale getirdi.
- ✍️ **Admin Kayıt Mantığı**: Admin self-signup deneyimi ve doğrulama akışı daha pürüzsüz ve daha sağlam.
- 🔁 **Oturum Kapatma Yönlendirme Akışı İyileştirildi**: Oturum kapatma artık daha güvenilir bir şekilde yönlendirir, kafa karışıklığını azaltır ve oturum yönetimini sorunsuz hale getirir.

## [0.6.9] - 2025-05-10

### Eklendi

- 📝 **Mesajlarda Ekli Resimleri/Dosyaları Düzenleme**: Gönderdiğiniz mesajları ekli dosyaları kaldırarak kolayca düzenleyebilirsiniz—belge yönetimini kolaylaştırır, anında hataları düzeltir ve sohbetlerinizi dağınıklıktan arındırır.
- 🚨 **Özel Görev Modelleri için Açık Uyarılar**: Özel görev modelleriyle etkileşimde bulunurken, UI sizi açıkça uyarır—kaynak kullanılabilirliğini ve erişimini anlamayı kolaylaştırır, iş akışı kurulumu sırasında kafa karışıklığını azaltır.

### Düzeltildi

- 🛡️ **Onay Diyaloğu Odak Tuzağı Güvenilirliği**: Odak artık onay diyaloğunda doğru bir şekilde kalıyor, klavye gezintisi ve erişilebilirliğin sorunsuz olmasını ve kazara işlemleri önlüyor—özellikle kritik veya hızlı iş akışları sırasında yardımcı olur.
- 💬 **Geçici Sohbet Yönetici Kontrolleri ve Oturum Temizliği**: Yöneticiler artık geçici sohbet modunu hatasız bir şekilde etkinleştirebiliyor ve önceki oturum prompt'ları veya araç seçimleri artık taşınmıyor—her seferinde taze, öngörülebilir ve tutarlı bir geçici sohbet deneyimi sunar.
- 🤖 **Harici Reranker Entegrasyon İşlevselliği Geri Getirildi**: Harici reranker entegrasyonları artık doğru çalışıyor, bu da RAG ve bilgi tabanı iş akışlarınızda daha keskin, daha ilgili arama sonuçları için gelişmiş sıralama hizmetlerinden tam olarak yararlanmanızı sağlar.

## [0.6.8] - 2025-05-10

### Eklendi

- 🏆 **Bilgi Tabanı Araması için Harici Reranker Desteği**: Yeni Harici Reranker entegrasyonu ile Retrieval-Augmented Generation (RAG) iş akışlarınızı güçlendirin; daha keskin ve daha ilgili arama sonuçları sunmak için gelişmiş yeniden sıralama hizmetlerini UI aracılığıyla kolayca bağlayın, araştırma ve içgörü keşfini hızlandırın.
- 📤 **Stilize Edilmemiş PDF Dışa Aktarma Seçeneği (Azaltılmış Dosya Boyutu)**: Sohbet dökümlerini veya belgeleri dışa aktarırken, daha hızlı indirmeler, minimum dosya boyutu ve temiz veri arşivlemesi için stilize edilmemiş bir PDF dışa aktarma seçeneği belirleyebilirsiniz—büyük ölçekli depolama veya paylaşım için mükemmeldir.
- 📝 **Farsça ve Arapça için Vazirmatn Fontu**: Arapça ve Farsça kullanıcıları artık metinlerini özel Vazirmatn fontuyla güzel bir şekilde işlenmiş olarak görecekler, bu da yerelleştirilmiş okuma deneyimini iyileştirir.
- 🏷️ **OneDrive için SharePoint Kiracı ID Desteği**: Sorunsuz kimlik doğrulama ve ayrıntılı kurumsal entegrasyon için OneDrive ayarlarında bir SharePoint kiracı ID'si belirleyebilirsiniz.
- 👤 **OAuth Profil Resmi Yenileme**: OAuth profil resminiz artık gerçek zamanlı olarak güncelleniyor, bu da entegre platformlarda varlığınızın ve avatarınızın her zaman en son kimliğinizle eşleşmesini sağlar.
- 🔧 **Milvus Yapılandırma İyileştirmeleri**: Milvus için dizin ve metrik türlerini doğrudan ayarlardan yapılandırın; daha doğru ve sağlam AI arama deneyimleri için vektör veritabanınızın tam kontrolünü ele alın.
- 🛡️ **S3 Etiketleme Uyumluluk için Toggle**: Ortam geçiş anahtarı aracılığıyla isteğe bağlı S3 etiketlemesi, Cloudflare R2 gibi etiketlemeyi desteklemeyenler de dahil olmak üzere tüm depolama backend'leriyle tam uyumluluk sağlar—hatasız ek ve belge yönetimini garanti eder.
- 👨‍🦯 **İkon Buton Erişilebilirlik İyileştirmeleri**: Temel etkileşimli ikon butonları artık aria-label'lar ve ARIA açıklamaları içeriyor, böylece ekran okuyucular her butonun hangi eylemi gerçekleştirdiği hakkında kesin rehberlik sağlar ve erişilebilirliği artırır.
- ♿ **Modal Odak Tuzağı ile Gelişmiş Erişilebilirlik**: Modal diyaloglar ve pop-up'lar artık odak tuzağı ve geliştirilmiş ARIA rolleri içeriyor, sorunsuz gezinme ve ekran okuyucu desteği sağlıyor—klavye ve yardımcı teknoloji kullanıcıları dahil herkes için arayüzü daha kullanıcı dostu hale getiriyor.
- 🏃 **İyileştirilmiş Yönetici Kullanıcı Listesi Yükleme Göstergesi**: Kullanıcı listesi yükleme deneyimi artık yönetici panelinde daha net ve daha duyarlı.
- 🧑‍🤝‍🧑 **Daha Büyük Yönetici Kullanıcı Listesi Sayfa Boyutu**: Yöneticiler artık yönetici arayüzünde sayfa başına 30'a kadar kullanıcıyı yönetebilir, bu da sayfa geçişini önemli ölçüde azaltır ve büyük kullanıcı ekiplerini yönetmeyi kolaylaştırır ve hızlandırır.
- 🌠 **Varsayılan Kod Tercümanı Prompt'u Netleştirildi**: Yerleşik kod tercümanı prompt'u artık daha açık, AI'nin kodu Markdown bloklarına sarmasını engelliyor—doğru biçimlendirilmiş kodun her seferinde amaçlandığı gibi çalışmasını sağlıyor.
- 🧾 **İyileştirilmiş Varsayılan Başlık Oluşturma Prompt Şablonu**: Başlık oluşturma artık güvenilir JSON çıktısı için sağlam bir şablon kullanıyor, sohbet organizasyonunu ve aranabilirliği iyileştiriyor.
- 🔗 **Kök Olmayan Base URL'lerle Jupyter Notebook Desteği**: Notebook tabanlı kod yürütme artık kök olmayan dağıtılmış Jupyter sunucularını destekliyor, hibrit veya çok kullanıcılı kurulumlar için tam esneklik sağlıyor.
- 📰 **UI Kaydırma Çubuğu Taşma Araçları için Her Zaman Görünür**: Mevcut araçlar ekranı aştığında, kaydırma çubuğu artık her zaman görünür ve kullanışlı bir "tümünü göster" geçişi var, bu da büyük araç setlerinde gezinmeyi daha hızlı ve daha sezgisel hale getiriyor.
- 🛠️ **Kararlılık için Genel Backend Yeniden Yapılandırması**: Backend bileşenleri genelinde birden fazla arka plan iyileştirmesi yapıldı, daha sorunsuz performans, daha az hata ve tüm kullanıcılar için daha güvenilir bir genel deneyim sağlıyor.
- 🚀 **Daha Hızlı Sonuçlar için Optimize Edilmiş Web Araması**: Web arama hızı ve performansı önemli ölçüde artırıldı, araştırma yoğun iş akışlarınızı hızlandırmak için rekor sürede yanıtlar ve kaynaklar sunuluyor.
- 💡 **Daha Fazla Desteklenen Dil**: Genişletilmiş dil desteği, daha geniş bir kullanıcı yelpazesinin kendi ana dilinde sezgisel ve doğal bir arayüzden yararlanmasını sağlar.

### Düzeltildi

- 🏃‍♂️ **Websocket Düzeltmesi Nedeniyle Nginx Ters Proxy'de Çalışanları Tüketme**: Websocket oturumları artık Nginx arkasında tamamen uyumlu, çalışanların tükenmesini ortadan kaldırıyor ve karmaşık dağıtımlarda bile gerçek zamanlı sohbetler için 7/24 güvenilirliği geri getiriyor.
- 🎤 **OpenAI ile Ses Transkripsiyonu Sorunu Çözüldü**: OpenAI tabanlı ses transkripsiyonu artık WebM ve daha yeni formatları hatasız işliyor, her seferinde sorunsuz sesli metin iş akışları sağlıyor.
- 👉 **Mesaj Girişi RTL Sorunu Düzeltildi**: Sohbet mesajı girişi artık sağdan sola diller için doğru görüntüleniyor, Arapça, İbranice ve daha fazlası için kusursuz bir yazma ve okuma deneyimi yaratıyor.
- 🀄 **Katex: Matematik Yanındaki Çince Karakterlerin Doğru Oluşturulması**: Matematik formülleri artık doğrudan Çince (CJK) karakterlerin yanında bile mükemmel bir şekilde işleniyor, çok dilli ekipler ve diller arası belgeler için görsel netliği artırıyor.
- 🔂 **Yinelenen Web Arama URL'leri Ortadan Kaldırıldı**: Arama sonuçları artık URL yinelenmelerini güvenilir bir şekilde filtreliyor, böylece bilginiz ve arama alıntılarınız her zaman temiz, kısaltılmış ve incelemesi kolay oluyor.
- 📄 **Bilgi Tabanlarında Markdown Oluşturma Düzeltildi**: Markdown artık bilgi tabanlarında doğru bir şekilde görüntüleniyor, zengin bilgi içeren dosyaların daha iyi biçimlendirilmesini ve netliğini sağlıyor.
- 🗂️ **LDAP İçe Aktarma/Yükleme Sorunu Çözüldü**: LDAP kullanıcı içe aktarmaları doğru bir şekilde işleniyor, sorunsuz onboarding ve kesintisiz erişim sağlanıyor.
- 🌎 **Pinecone Toplu İşlemler ve Asenkron Güvenlik**: Tüm Pinecone işlemleri (toplu ekleme, güncelleme, silme) artık asenkron bir ortamda verimli ve güvenli bir şekilde çalışıyor, performansı artırıyor ve büyük ölçekli RAG işlerinde yavaşlamaları önlüyor.

## [0.6.7] - 2025-05-07

### Eklendi

- 🌐 **Özel Azure TTS API URL Desteği Eklendi**: Artık özel bir Azure Text-to-Speech endpoint'i tanımlayabilirsiniz—kurumsal dağıtımlar ve bölgesel uyumluluk için esneklik sağlıyor.
- ⚙️ **TOOL_SERVER_CONNECTIONS Ortam Değişkeni Desteği**: Araç sunucularını ortam değişkenleri aracılığıyla kolayca yapılandırın ve dağıtın, kurulumu kolaylaştırın ve daha hızlı kurumsal tedarik sağlayın.
- 👥 **Gelişmiş OAuth Grup İşleme (Dize veya Liste Olarak)**: OAuth grup verileri artık bir liste veya virgülle ayrılmış bir dize olarak geçirilebilir, çeşitli kimlik sağlayıcı formatlarıyla uyumluluğu artırır ve onboarding sürtünmesini azaltır.

### Düzeltildi

- 🧠 **Ollama Proxy Endpoint'leri ile Embedding Geri Getirildi**: Proxy'li Ollama modelleri için eksik API config'in embedding'i bozduğu bir sorun düzeltildi—tutarlı performans ve uyumluluk sağlar.
- 🔐 **OIDC OAuth Giriş Sorunu Çözüldü**: Kullanıcılar OpenID Connect tabanlı OAuth kullanarak tekrar sorunsuz bir şekilde oturum açabilir, giriş kesintilerini ortadan kaldırır ve güvenilirliği artırır.
- 📝 **Notlar Özelliği Erişimi Admin Olmayanlar için Düzeltildi**: Admin olmayan kullanıcıların Notlar özelliğine erişmesini engelleyen bir sorun düzeltildi, tam çapraz rol işbirliği yetenekleri geri getirildi.
- 🖼️ **Tika Loader Görüntü Çıkarma Sorunu Çözüldü**: TikaLoader'ın artık 'extract_images' parametresini doğru bir şekilde işlediği, belge iş akışlarında tam dosya çıkarma işlevselliğini geri getirdiği sağlandı.
- 🎨 **Automatic1111 Görüntü Modeli Ayarı Doğru Uygulandı**: UI aracılığıyla belirli bir görüntü modeline geçişin oluşturmada yansıtılmadığı bir sorun düzeltildi, tam görsel yaratıcılık kontrolünü yeniden etkinleştirdi.
- 🏷️ **Mesajlardaki Birden Fazla XML Etiketi Artık Doğru Ayrıştırılıyor**: Mesajlar birden fazla XML tarzı etiket içerdiğinde ayrıştırma sorunları düzeltildi, sohbetlerde zengin içeriğin temiz ve kesintisiz oluşturulmasını sağladı.
- 🖌️ **OpenAI Görüntü Oluşturma Sorunları Çözüldü**: OpenAI'nin görüntü oluşturmasını kullanırken bozuk görüntü çıktısına neden olan sorunlar çözüldü, tamamen işlevsel görsel oluşturma iş akışları sağlandı.
- 🔎 **Araç Sunucusu Ayarları UI Gizliliği Geri Getirildi**: Kısıtlı kullanıcıların arama yoluyla araç sunucusu ayarlarına erişmesi engellendi—sıkı izin kontrolleri geri getirildi ve hassas yapılandırmalar güvence altına alındı.
- 🎧 **WebM Ses Transkripsiyonu Artık Destekleniyor**: Ses transkripsiyonu sırasında WebM dosyalarının başarısız olmasına neden olan bir sorun düzeltildi—bu formatlar artık tamamen destekleniyor, daha sorunsuz sesli not iş akışları ve daha geniş dosya uyumluluğu sağlanıyor.

## [0.6.6] - 2025-05-05

### Eklendi

- 📝 **AI Gelişmiş Notlar (Ses Transkripsiyonu ile)**: Notları zahmetsizce oluşturun, toplantı veya ses kaydı ekleyin ve AI'nın ses transkripsiyonlarını kullanarak notlarınızı anında geliştirmesine, özetlemesine veya iyileştirmesine izin verin—belgelerinizi minimum çabayla daha akıllı, daha temiz ve daha bilgilendirici hale getirin.
- 🔊 **Toplantı Ses Kaydı ve İçe Aktarma**: Toplantılarınızdan sorunsuz bir şekilde ses kaydedin veya ekran sesini yakalayın ve notlarınıza ekleyin—önemli tartışmalardan içgörüleri yeniden ziyaret etmeyi, açıklama eklemeyi ve çıkarmayı kolaylaştırın.
- 📁 **Markdown Notlarını Zahmetsizce İçe Aktarma**: Mevcut bilgi kütüphanenizi Markdown notlarınızı içe aktararak Open WebUI'ye getirin, böylece tüm gelişmiş not yönetimi ve AI özelliklerinden hemen yararlanabilirsiniz.
- 👥 **Kullanıcı Grubuna Göre Not İzinleri**: Notlar için erişimi ve düzenleme haklarını kullanıcı rollerine veya gruplarına göre hassas bir şekilde ayarlayın, böylece gerektiğinde yazmayı delege edebilir veya hassas bilgileri kısıtlayabilirsiniz.
- ☁️ **OneDrive ve SharePoint Entegrasyonu**: İçeriğinizi OneDrive veya SharePoint ile doğrudan notları ve dosyaları bağlayarak senkronize tutun—hızlı kurumsal içe/dışa aktarmayı ve mevcut iş akışlarınızla sorunsuz işbirliğini açın.
- 🗂️ **Yönetici Panelinde Sayfalandırılmış Kullanıcı Listesi**: Yeni sayfalandırılmış kullanıcı listesi aracılığıyla büyük ekipleri zahmetsizce yönetin ve arayın—büyük kuruluşlarda zaman kazanın ve kullanıcı yönetimini kolaylaştırın.
- 🕹️ **Ayrıntılı Sohbet Paylaşımı ve Dışa Aktarma İzinleri**: Sohbetleri kimin paylaşabileceği veya dışa aktarabileceği üzerinde gelişmiş kontrolün keyfini çıkarın, ekip ve kurumsal ayarlarda daha sıkı yönetişim ve gizlilik sağlayın.
- 🛑 **Kullanıcı Rolü Değişikliği Onay Diyaloğu**: Kullanıcı rollerini güncellemeden önce gerekli bir onay adımıyla kazara ayrıcalık değişikliklerini azaltın—güvenliği artırın ve ekip yönetiminde maliyetli hataları önleyin.
- 🚨 **Başarısız Giriş Denemeleri için Denetim Günlüğü**: Denetim izinde başarısız kimlik doğrulamanın ayrıntılı günlükleriyle yetkisiz erişim denemelerini hızla tespit edin veya kullanıcı giriş sorunlarını giderin.
- 💡 **Sohbetler için Özel 'Başlık Oluştur' Düğmesi**: Her konuşmayı hızla düzenleyin—AI'nın tüm sohbetleriniz için ilgili, net başlıklar oluşturmasına izin vermek için yeni düğmeye dokunun, zamandan tasarruf edin ve dağınıklığı azaltın.
- 💬 **Bildirim Sesi Her Zaman Açık Seçeneği**: Sesli uyarıları her zaman çalacak şekilde ayarlayarak bildirimlerinizin kontrolünü ele alın—yoğun ortamlarda önemli güncellemelerin üstesinden gelmenize yardımcı olur.
- 🆔 **S3 Dosya Etiketleme Desteği**: S3'e yüklenen dosyalar, daha iyi organizasyon, arama ve dosya yönetimi politikalarınızla entegrasyon için etiketler içerir.
- 🛡️ **OAuth Engellenen Gruplar Desteği**: Belirli OAuth gruplarını açıkça engelleyerek grup tabanlı erişim üzerinde daha fazla kontrol sahibi olun—karmaşık kimlik veya güvenlik gereksinimleri için idealdir.
- 🚀 **Optimize Edilmiş Daha Hızlı Web Araması ve Çoklu İş Parçacıklı Sorgular**: Yenilenmiş çoklu iş parçacıklı arama ile önemli ölçüde daha hızlı web araması ve RAG (retrieval augmented generation) deneyiminin tadını çıkarın—daha zengin, daha doğru sonuçları daha kısa sürede elde edin.
- 🔍 **Tüm Bilgi Paralel Araması**: Tüm bilgi tabanınızdaki aramalar artık hibrit olmayan modda bile paralel olarak gerçekleşir, yanıtları hızlandırır ve her soru için bilgi doğruluğunu artırır.
- 🌐 **Yeni Firecrawl ve Yacy Web Arama Entegrasyonları**: İki yeni gelişmiş arama motoruyla bilgi dünyanızı genişletin—daha derin web içgörüsü için Firecrawl ve merkezi olmayan, gizlilik dostu arama yetenekleri için Yacy.
- 🧠 **Yapılandırılabilir Docling OCR Motoru ve Dili**: Daha akıllı, daha özel belge çıkarma ve RAG iş akışları için Docling OCR motorunu ve desteklenen dilleri ortam değişkenleriyle ince ayar yapın.
- 🗝️ **Gelişmiş Sentence Transformers Yapılandırması**: Sentence Transformers'ın daha kolay kurulumu ve gelişmiş özelleştirmesi için yeni ortam değişkenleri eklendi—embedding ihtiyaçlarınız için en uygun uyumu sağlar.
- 🌲 **Pinecone Vektör Veritabanı Entegrasyonu**: Kurumsal ölçekte bilgiyi dizine ekleyin, arayın ve yönetin, Pinecone'u vektör veritabanınız olarak tam yerel destekle—en büyük belge kümelerini bile zahmetsizce yönetin.
- 🔄 **Araçlar ve Fonksiyonlar için Otomatik Gereksinim Kurulumu**: Yeniden başlatmada kaybolan bağımlılıklar hakkında asla endişelenmeyin—harici fonksiyon ve araç gereksinimleri artık başlangıçta otomatik olarak kurulur, araçların her zaman "sadece çalışmasını" sağlar.
- 🔒 **Token Süresi Dolduğunda Otomatik Oturum Kapatma**: Güvenlik daha akıllı—kullanıcılar kimlik doğrulama token'ları süresi dolarsa otomatik olarak oturumu kapatılır, hassas içeriği korur ve kesinti olmadan uyumluluğu sağlar.
- 🎬 **Otomatik YouTube Gömme Algılama**: YouTube bağlantılarını yapıştırın ve anında sohbet içi video gömümleri görün—artık manuel gömme yok, bilgi paylaşımını ve medya tüketimini her ekip için daha da kolaylaştırır.
- 🔄 **Genişletilmiş Dil ve Yerel Destek**: Danca, Fransızca, Rusça, Geleneksel Çince, Basitleştirilmiş Çince, Tayca, Katalanca, Almanca ve Korece çevirileri yükseltildi, platform genelinde daha sorunsuz, daha doğal kullanıcı deneyimleri sunar.

### Düzeltildi

- 🔒 **Daha Sıkı HTML Token Güvenliği**: HTML oluşturma artık yalnızca yönetici tarafından yüklenen token'larla kısıtlanmıştır, XSS riskini azaltır ve verilerinizin güvenliğini sağlar.
- 🔐 **Geliştirilmiş HTML Güvenliği ve Token Yönetimi**: HTML token'larının ve içeriğinin nasıl işlendiği daha da güçlendirildi, güvenlik açıklarına ve saldırılara karşı daha da güçlü bir direnç garanti edildi.
- 🔏 **Ollama Proxy Ön Ekleriyle Doğru Model Kullanımı**: Ollama'da proxy'li modellerin her zaman doğru bir şekilde indirilmesini ve çalıştırılmasını sağlayarak geliştirilmiş model referansı işleme—özel ön ekler kullanıldığında bile.
- 📥 **Video Dosya Yükleme İşlemi**: Video dosyalarının yanlışlıkla metin olarak sınıflandırılması önlendi, yüklemelerdeki hatalar düzeltildi ve medya dosyalarının beklendiği gibi çalışması sağlandı.
- 🔄 **Artık Bağımlı WebSocket Sıralı Gecikmeleri Yok**: Özellikle çok kullanıcılı ortamlarda gecikmeleri önlemek ve hızlı gerçek zamanlı işbirliğini sürdürmek için WebSocket işlemi kolaylaştırıldı.
- 🛠️ **Daha Sağlam Eylem Modülü Yürütmesi**: Bir modüldeki birden fazla eylem artık tasarlandığı gibi tetikleniyor, otomasyonu ve betikleme esnekliğini artırıyor.
- 📧 **Bildirim Webhook'ları**: Kullanıcı etkin olmasa bile kullanıcı olayları için bildirim webhook'larının her zaman gönderilmesi sağlandı.
- 🗂️ **Daha Akıllı Bilgi Tabanı Yeniden Dizinleme**: Bilgi yeniden dizinleme, bozuk veya eksik koleksiyonlar karşılaşıldığında bile devam eder, arama özelliklerinizin güvenilir bir şekilde çalışmasını sağlar.
- 🏷️ **Profil Resimli Kullanıcı İçe Aktarma**: Kullanıcılar içe aktarılırken, profil resimleri de beraberinde gelir—ilk günden itibaren onboarding ve işbirliğini görsel olarak daha net hale getirir.
- 💬 **OpenAI o-Serisi Evrensel Desteği**: Tüm OpenAI o-serisi modelleri artık sorunsuz bir şekilde tanınır ve desteklenir, her iş akışı için daha gelişmiş yetenekler ve model seçenekleri sunar.

### Değiştirildi

- 📜 **Özel Lisans Güncellemesi ve Katılımcı Anlaşması**: Open WebUI artık varsayılan olarak Katılımcı Lisans Anlaşması gerektiren özel bir lisans altında çalışmaktadır—ayrıntılar için https://docs.openwebui.com/license/ adresine bakın, topluluk için sürdürülebilir açık inovasyon sağlıyor.
- 🔨 **CUDA Docker Images 12.8'e Güncellendi**: AI altyapınızda daha hızlı, daha uyumlu model çıkarımı ve geleceğe dönük GPU performansı için CUDA görüntü desteği yükseltildi.
- 🧱 **Güvenilirlik için Genel Backend Yeniden Yapılandırması**: Sürekli kararlılık iyileştirmeleri backend mantığını kolaylaştırır, hataları azaltır ve yeni özellik sürümlerinin bir sonraki dalgası için daha güçlü bir temel oluşturur—daha güvenilir bir WebUI için her şey arka planda.

## [0.6.5] - 2025-04-14

### Eklendi

- 🛂 **Kullanıcı Grubuna Göre Ayrıntılı Ses Özelliği İzinleri**: Yöneticiler artık her kullanıcı grubu için Speech-to-Text (ses kaydı), Text-to-Speech (yüksek sesle okuma) ve Tool Calls erişimini ayrı ayrı yönetebilir—ekiplere ses özellikleri üzerinde daha sıkı kontrol ve roller arasında gelişmiş yönetişim sağlar.
- 🗣️ **Whisper STT için Ses Etkinliği Algılama (VAD) Geçiş Anahtarı**: Yeni ortam değişkeni, yerleşik Whisper speech-to-text ile VAD filtrelemesini etkinleştirmenize/devre dışı bırakmanıza olanak tanır, farklı ses kalitesi ve yanıt doğruluğu seviyeleri için optimizasyon esnekliği sağlar.
- 📋 **Biçimlendirilmiş Yanıt Modunu Kopyala**: Artık Ayarlar > Arayüz'den "Biçimlendirilmiş Kopyala"yı etkinleştirebilirsiniz, böylece AI yanıtlarını stilize edildiği gibi (zengin biçimlendirme, bağlantılar ve yapı korunarak) kopyalayabilir, belgelere, e-postalara veya raporlara daha hızlı ve temiz bir şekilde yapıştırabilirsiniz.
- ⚙️ **Backend Kararlılığı ve Performans Geliştirmeleri**: Genel backend yeniden yapılandırması sistemin dayanıklılığını, tutarlılığını ve genel güvenilirliğini artırır—sohbet ederken, medya oluştururken veya harici araçları kullanırken iş akışları genelinde daha sorunsuz performans sunar.
- 🌎 **Birden Fazla Dilde Çeviri İyileştirmeleri**: Güncellenmiş çeviriler, daha sorunsuz dil yerelleştirmesi, daha net etiketler ve UI genelinde geliştirilmiş uluslararası kullanılabilirlik sağlar—İngilizce konuşmayanlar için daha iyi bir deneyim sağlar.

### Düzeltildi

- 🛠️ **LDAP Giriş Güvenilirliği Geri Getirildi**: Bazı LDAP kurulumlarının öznitelik ayrıştırma nedeniyle başarısız olmasına neden olan kritik bir sorun çözüldü—kurumsal dağıtımlar genelinde tutarlı, güvenli ve sorunsuz kullanıcı kimlik doğrulaması sağlanır.
- 🖼️ **Geçici Sohbetlerde Resim Oluşturma Artık Doğru Çalışıyor**: Geçici sohbetler sırasında görüntü çıktılarının oluşturulmaması hatası düzeltildi—görsel içerik artık tüm sohbet modlarında kesintisiz olarak güvenilir bir şekilde kullanılabilir.

## [0.6.4] - 2025-04-12

### Düzeltildi

- 🛠️ **RAG_TEMPLATE Görüntüleme Sorunu Çözüldü**: Özel RAG_TEMPLATE'nin arayüzde doğru bir şekilde oluşturulmamasıyla ilgili bir biçimlendirme sorunu düzeltildi—böylece özel retrieval prompt'ları artık amaçlandığı gibi görünür ve daha güvenilir prompt mühendisliği sağlar.

## [0.6.3] - 2025-04-12

### Eklendi

- 🧪 **Otomatik Artifact Algılama Geçiş Anahtarı**: Sonuçlardaki artifact'leri otomatik olarak algılar—ancak artık tam kontrol için gelişmiş ayarlardan bu davranışı devre dışı bırakabilirsiniz.
- 🖼️ **Paylaşılan Sohbetler için Geniş Ekran Modu**: Paylaşılan bağlantı konuşmaları artık geniş ekran düzenlerini destekliyor—sunumlar veya daha geniş ekranlarda daha kolay inceleme için mükemmel.
- 🔁 **Bilgi Dosyalarını İsteğe Bağlı Olarak Yeniden Dizinleme**: Yöneticiler artık embedding'leri değiştirdikten sonra tüm bilgi dosyalarının yeniden dizinlenmesini tetikleyebilir—optimum RAG performansı için yeni modellerle anında hizalamayı sağlar.
- 📄 **OpenAPI YAML Format Desteği**: Harici araçlar artık YAML formatlı OpenAPI spec'lerini kullanabilir—YAML tabanlı yapılandırmalara aşina olan geliştiriciler için entegrasyonu basitleştirir.
- 💬 **Mesaj İçeriği Kopyalama Davranışı**: Kopyalama eylemi artık 'details' etiketlerini dışarıda bırakır—başka yerlere özetleri paylaşırken veya yapıştırırken pano içeriğini kolaylaştırır.
- 🧭 **Sougou Web Arama Entegrasyonu**: Yeni arama motoru seçeneği eklendi—çok dilli kullanıcılar için küresel alaka düzeyini ve arama kaynaklarının çeşitliliğini artırıyor.
- 🧰 **Frontend Web Loader Engine Yapılandırması**: Yöneticiler artık RAG iş akışları için tercih edilen web loader engine'i doğrudan frontend'den ayarlayabilir—kurulumlar genelinde daha fazla kontrol sağlar.
- 👥 **Çok Modelli Sohbet İzin Kontrolü**: Yöneticiler, kullanıcı grubuna göre çok modelli sohbetlere erişimi yönetebilir—ekip ortamlarında daha sıkı yönetişim sağlar.
- 🧱 **Kalıcı Yapılandırma Devre Dışı Bırakılabilir**: Yeni ortam değişkeni, gelişmiş kullanıcıların ve sunucuların kalıcı yapılandırmaları kapatmasına olanak tanır—değişken veya durumsuz dağıtımlar için idealdir.
- 🧠 **Elixir Kod Vurgulama Desteği**: Elixir sözdizimi artık kod bloklarında güzelce işleniyor—AI veya otomasyon projelerinde bu dili kullanan geliştiriciler için mükemmel.
- 🌐 **PWA Harici Manifest URL Desteği**: Artık harici bir manifest.json tanımlayabilirsiniz—Open WebUI'yi Cloudflare Zero Trust gibi yönetilen veya proxy tabanlı PWA ortamlarında sorunsuz bir şekilde entegre edin.
- 🧪 **Azure AI Speech-to-Text Sağlayıcı Entegrasyonu**: Microsoft'un Azure STT'sini kullanarak büyük ses dosyalarını (200 MB'a kadar) yüksek doğrulukla kolayca transkript edin—Ses Ayarlarında tamamen yapılandırılabilir.
- 🔏 **OIDC için PKCE (Code Challenge Method) Desteği**: Zero-trust ve yerel istemci uygulamaları için ideal olan Proof Key for Code Exchange ile OIDC giriş güvenliğinizi artırın.
- ✨ **Genel UI/UX Geliştirmeleri**: Düzen, stil ve araç etkileşimlerinde sayısız iyileştirme—görsel gürültüyü azaltır ve temel iş akışları genelinde genel kullanılabilirliği artırır.
- 🌍 **Birden Fazla Dilde Çeviri Güncellemeleri**: Katalanca, Rusça, Çince (Basitleştirilmiş ve Geleneksel), Macarca ve İspanyolca çevirileri daha net gezinme ve talimatlar için iyileştirildi.

### Düzeltildi

- 💥 **Eksik Modellerle Sohbet Tamamlama Hatası Çözüldü**: Mevcut olmayan bir modele başvurulduğunda dahili sunucu hatası düzeltildi—zarif bir yedek ve açık hata rehberliği sağlar.
- 🔧 **Doğru Bilgi Tabanı Atıfları Geri Getirildi**: RAG iş akışları tarafından oluşturulan atıflar artık doğru referansları gösteriyor—kaynaklı içerikten çıkan çıktılarda doğrulanabilirliği sağlıyor.
- 🎙️ **Bozuk OGG/WebM Ses Yükleme İşlemi OpenAI için Düzeltildi**: OGG veya WebM dosyalarının yüklenmesi artık transkripsiyondan önce düzgün bir şekilde WAV'ye dönüştürülüyor—doğru AI konuşma tanıma iş akışlarını geri getiriyor.
- 🔐 **Araç Sunucusu 'Oturum' Kimlik Doğrulaması Geri Getirildi**: Daha önce bozuk olan harici araç sunucularındaki oturum kimlik doğrulaması artık tamamen işlevseldir—bağlı araçlara güvenli ve sorunsuz erişim sağlar.
- 🌐 **Klasör Tabanlı Sohbet Yeniden Adlandırma Artık Doğru Güncelleniyor**: Klasörlerdeki sohbetleri yeniden adlandırmak artık her yerde anında yansır—sohbet organizasyonunu ve netliğini iyileştirir.
- 📜 **KaTeX Taşma Görüntüleri Düzeltildi**: Matematik ifadeleri artık mesaj sınırları içinde düzenli bir şekilde kalır—uzun formüllerle bile düzen tutarlılığını korur.
- 🚫 **Devam Eden Sohbet Durdurma Düzeltildi**: Artık aktif (devam eden) bir sohbete geri dönebilir ve üretimi istediğiniz zaman durdurabilirsiniz—oturumlar üzerinde tam kontrol sağlar.
- 🔧 **TOOL_SERVERS / TOOL_SERVER_CONNECTIONS Dizinleme Sorunu Düzeltildi**: Araç listeleri ve erişim yolları arasındaki bir uyuşmazlık düzeltildi—tam işlevselliği geri getirdi ve araç yönetiminde kafa karışıklığını önledi.
- 🔐 **LDAP Girişi Birden Fazla E-postayı İşliyor**: LDAP birden fazla e-posta özniteliği döndürdüğünde, artık ilk geçerli olan kullanılır—giriş başarısı ve hesap tutarlılığı sağlar.
- 🧩 **Model Görünürlüğü Geçiş Anahtarı Düzeltmesi**: Model görünürlüğünü değiştirmek, dokunulmamış modeller için bile çalışır—admin'lerin temel modeller arasında kullanıcı erişimini sorunsuz bir şekilde yönetmesine olanak tanır.
- ⚙️ **Çapraz Kaynak manifest.json Artık Düzgün Yükleniyor**: Cloudflare Zero Trust (ve diğerleri) ile uyumluluk sorunları çözüldü, manifest.json'ın kimliği doğrulanmış proxy'lerin arkasından yüklenmesine izin verir.

### Değiştirildi

- 🔒 **Tüm Kaynaklar için Varsayılan Erişim Kapsamları Özel Olarak Ayarlandı**: Modeller, araçlar ve bilgi tabanları artık varsayılan olarak oluşturulduğunda özeldir—daha iyi temel güvenlik ve görünürlük kontrolleri sağlar.
- 🧱 **Kararlılık için Genel Backend Yeniden Yapılandırması**: Sayısız görünmez iyileştirme, backend ölçeklenebilirliğini, güvenliğini ve sürdürülebilirliğini artırır—daha güçlü bir temel ile gelecek özellikleri güçlendirir.
- 🧩 **Kararlı Bağımlılık Yükseltmeleri**: Temel platform kütüphaneleri—Chromadb (0.6.3), pgvector (0.4.0), Azure Identity (1.21.0) ve Youtube Transcript API (1.0.3)—geliştirilmiş uyumluluk, işlevsellik ve güvenlik için güncellendi.

## [0.6.2] - 2025-04-06

### Eklendi

- 🌍 **Geliştirilmiş Küresel Dil Desteği**: Uluslararası kullanıcılar için netliği ve tutarlılığı artırmak amacıyla birden fazla dilde genişletilmiş ve iyileştirilmiş çeviriler.

### Düzeltildi

- 🛠️ **OpenAPI Sunucularından Doğru Araç Açıklamaları**: Harici araçlar, araç spesifikasyonlarını oluştururken özetler yerine tam endpoint açıklamalarını kullanır—AI modellerinin araç amacını daha hassas bir şekilde anlamasına ve araç iş akışlarında doğru aracı daha doğru bir şekilde seçmesine yardımcı olur.
- 🔧 **Kesin Web Sonuçları Kaynak Atfı**: Tüm web arama sonuçlarının aynı kaynak ID'sini gösterdiği kritik bir sorun düzeltildi—artık her sonuç kendi doğru ve farklı kaynağını alır, doğru atıflar ve izlenebilirlik sağlar.
- 🔍 **Temiz Web Arama Alımı**: Web araması artık yalnızca gerçek içeriğin başarıyla alındığı URL'lerden sonuçları tutar—doğruluğu artırır ve alıntılardan boş veya bozuk bağlantıları kaldırır.
- 🎵 **Ses Dosyası Yükleme Yanıtı Geri Getirildi**: Ses dosyalarını yüklerken geçerli yanıtların dönmemesi sorunu çözüldü, transkripsiyon ve ses tabanlı iş akışları için sorunsuz dosya yönetimini geri getirdi.

### Değiştirildi

- 🧰 **Genel Backend Yeniden Yapılandırması**: Birden fazla perde arkası iyileştirme, backend performansını kolaylaştırır, karmaşıklığı azaltır ve genel olarak daha kararlı, sürdürülebilir bir sistem sağlar—iş akışınızı değiştirmeden her şeyi daha sorunsuz hale getirir.

## [0.6.1] - 2025-04-05

### Eklendi

- 🛠️ **Global Araç Sunucuları Yapılandırması**: Yöneticiler artık Admin Ayarları > Araçlar'dan global harici araç sunucularını merkezi olarak yapılandırabilir, bu da kullanıcı başına manuel kuruluma gerek kalmadan araç entegrasyonlarının tüm kullanıcılar arasında sorunsuz bir şekilde paylaşılmasına olanak tanır.
- 🔐 **Kullanıcılar için Doğrudan Araç Kullanım İzni**: Admin olmayan kullanıcılara doğrudan harici araçlara erişim izni veren yeni bir kullanıcı düzeyinde izin geçiş anahtarı tanıtıldı, daha geniş ekip işbirliğini güçlendirirken kontrolü sürdürür.
- 🧠 **Mistral OCR İçerik Çıkarma Desteği**: Yüksek doğruluklu bir belge yükleyici olarak Mistral OCR için yerel destek eklendi, RAG iş akışlarında taranmış belgelerden metin çıkarmayı önemli ölçüde iyileştirdi.
- 🖼️ **Araçlar Göstergesi UI Yeniden Tasarımı**: Mesaj girişi, hem yerleşik hem de harici araçları birleşik bir açılır menü aracılığıyla akıllıca görüntüler, bu da konuşmalar sırasında araçları etkinleştirmeyi daha basit ve sezgisel hale getirir.
- 📄 **RAG Prompt'u Geliştirildi ve Daha Tutarlı**: Varsayılan RAG sistem prompt'u daha net ve alıntı odaklı olacak şekilde revize edildi—yöneticiler, bu yeni altın standart prompt'u kullanmak için şablon alanını boş bırakabilirler.
- 🧰 **Performans ve Geliştirici İyileştirmeleri**: Stilizasyonu basitleştiren ve harici/dahili işleme mantığını birleştiren, daha iyi sürdürülebilirlik ve performans sağlayan birkaç araçla ilgili bileşenin büyük dahili yeniden yapılandırması.
- 🌍 **Geliştirilmiş Çeviriler**: Tibetçe, Lehçe, Çince (Basitleştirilmiş ve Geleneksel), Arapça, Rusça, Ukraynaca, Felemenkçe, Fince ve Fransızca için güncellenmiş çeviriler, arayüz genelinde netliği ve tutarlılığı artırmak için.

### Düzeltildi

- 🔑 **Harici Araç Sunucusu API Anahtarı Hatası Çözüldü**: Harici OpenAPI araç sunucularından araçları çağırırken kimlik doğrulama başlıklarının gönderilmemesiyle ilgili kritik bir sorun düzeltildi, tam güvenlik ve sorunsuz araç işlemleri sağlandı.
- 🚫 **Koşullu Dışa Aktar Butonu Görünürlüğü**: UI artık modellerde, prompt'larda, araçlarda veya fonksiyonlarda dışa aktarılacak hiçbir şey olmadığında dışa aktar butonlarını zarifçe gizler, görsel netliği iyileştirir ve kafa karışıklığını azaltır.
- 🧪 **Hibrit Arama Hata Kurtarma**: Paralel hibrit aramada boş veya dizine eklenmemiş koleksiyonların backend çökmelerine neden olduğu uç durum düzeltildi—sistem kararlılığını sağlamak için bunlar artık temiz bir şekilde atlanır.
- 📂 **Yönetici Klasörü Silme Düzeltmesi**: Yönetici çalışma alanında oluşturulan klasörlerin silinememesi sorunu giderildi, admin'ler için tam organizasyonel esnekliği geri getirdi.
- 🔐 **Girişte Geliştirilmiş Genel Hata Geri Bildirimi**: Kimlik doğrulama hataları artık gizlilik ve geliştirilmiş UX için basitleştirilmiş, açıklayıcı olmayan mesajlar gösterir, özellikle birleşik girişlerde.
- 📝 **Resimli Araç Mesajı İyileştirildi**: Sohbet içinde araç tarafından oluşturulan mesajların görüntü çıktılarının nasıl gösterildiği iyileştirildi, bunları daha okunabilir ve genel UI tasarımıyla tutarlı hale getirdi.
- ⚙️ **Bozuk RAG Koleksiyonları için Otomatik Dışlama**: Veri getirmede başarısız olan veya "None" döndüren belge koleksiyonlarını otomatik olarak atlar, gizli hataları önler ve retrieval iş akışlarını kolaylaştırır.
- 📝 **Docling Metin Dosyası İşleme Düzeltmesi**: Belirli düz metin dosyaları için docling tabanlı RAG işlevselliğini bozan dosya ayrıştırma tutarsızlığı düzeltildi, daha geniş dosya uyumluluğu sağlandı.

## [0.6.0] - 2025-03-31

### Eklendi

- 🧩 **OpenAPI Aracılığıyla Harici Araç Sunucusu Desteği**: Open WebUI'yi herhangi bir OpenAPI uyumlu REST sunucusuna anında bağlayın—güçlü genişletilebilirlik için binlerce geliştirici aracı, SDK ve SaaS sistemiyle anında entegrasyon sunar. Daha fazla bilgi için: https://github.com/open-webui/openapi-servers
- 🛠️ **MCPO Aracılığıyla MCP Sunucu Desteği**: Artık dahili MCP araçlarınızı Open WebUI içinde birlikte çalışabilir OpenAPI HTTP sunucuları olarak dönüştürebilir ve gösterebilirsiniz, bu da sorunsuz, tak ve çalıştır AI araç zinciri oluşturmayı sağlar. Daha fazla bilgi için: https://github.com/open-webui/mcpo
- 📨 **/messages Sohbet API Endpoint Desteği**: Harici AI sistemleri oluşturan ileri düzey kullanıcılar için, yeni endpoint'ler mesajların asenkron olarak hassas kontrolünü sağlar—uzun süreli harici yanıtları frontend ile bağlamadan Open WebUI sohbetlerine besleyin.
- 📝 **Client-Side PDF Oluşturma**: PDF dışa aktarımları artık tamamen client-side'da oluşturulur ve çıktı kalitesini önemli ölçüde artırır—konuşmaları veya belgeleri kaydetmek için mükemmeldir.
- 💼 **Zorunlu Geçici Sohbet Modu**: Yöneticiler artık katı veri saklama ve uyumluluk gereksinimleriyle uyum sağlamak için varsayılan olarak geçici sohbet oturumlarını zorunlu kılabilir.
- 🌍 **Herkese Açık Kaynak Paylaşım İzin Kontrolleri**: İnce ayarlı kullanıcı grubu izinleri artık modeller, bilgi tabanları, prompt'lar ve araçlar için herkese açık paylaşımı etkinleştirmeye/devre dışı bırakmaya izin verir—gizlilik, ekip kontrolü ve dahili dağıtımlar için idealdir.
- 📦 **Araçlar/Fonksiyonlar için Özel pip Seçenekleri**: Artık "PIP_OPTIONS", "PIP_PACKAGE_INDEX_OPTIONS" ortam değişkenleriyle özel pip kurulum seçenekleri belirleyebilirsiniz—uyumluluğu, özel indeksler için desteği ve Python ortamları üzerinde daha iyi kontrolü iyileştirir.
- 🔢 **Düzenlenebilir Mesaj Sayacı**: Mesaj sayacı numarasını çift tıklayabilir ve doğrudan dizini düzenlemeye geçebilirsiniz—karmaşık sohbetlerde hızlıca gezinin veya belirli mesajları hassas bir şekilde yeniden oluşturun.
- 🧠 **Embedding Ön Ek Desteği Eklendi**: Talimat tarzı token'lar için embedding'lerinize özel ön ekler ekleyin, daha güçlü model hizalaması ve daha tutarlı RAG performansı sağlar.
- 🙈 **Temel Modelleri Gizleme Yeteneği**: İsteğe bağlı olarak temel modelleri UI'den gizleyin, kullanıcıların model görünürlüğünü kolaylaştırmasına ve yalnızca kullanılabilir endpoint'lere erişimi sınırlamasına yardımcı olur.
- 📚 **Docling İçerik Çıkarma Desteği**: Open WebUI artık Docling'i bir içerik çıkarma motoru olarak destekliyor, karmaşık dosya formatlarının daha akıllı ve daha doğru ayrıştırmasını sağlıyor—gelişmiş belge anlama ve Retrieval-Augmented Generation (RAG) iş akışları için idealdir.
- 🗃️ **Redis Sentinel Desteği Eklendi**: Yüksek kullanılabilirlikli, hata toleranslı Redis tabanlı önbellekleme veya pub/sub için Redis Sentinel desteği ile dağıtım yedekliliğini artırın.
- 📚 **Ollama için JSON Schema Formatı**: Ollama uyumlu modellerde formatı JSON schema kullanarak tanımlama desteği eklendi, model çıktılarının esnekliğini ve doğrulanmasını iyileştiriyor.
- 🔍 **Sohbet Kenar Çubuğu Arama "Temizle" Düğmesi**: Yeni ✖️ düğmesini kullanarak sohbet kenar çubuğundaki arama filtrelerini hızlıca temizleyin—tek tıklamayla sohbet gezinmenizi kolaylaştırın.
- 🗂️ **Klasör Adı için Otomatik Odaklanma + Enter Gönderme**: Yeni bir klasör oluştururken, sistem otomatik olarak ad önceden seçilmiş şekilde yeniden adlandırma moduna girer—organizasyon iş akışınızı basitleştirir.
- 🧱 **Markdown Uyarıları Oluşturma**: Sözdizimi ipuçları (örneğin ⚠️, ℹ️, ✅) içeren blok alıntılar, stilize edilmiş Markdown uyarı banner'ları oluşturur, mesajları ve belgeleri görsel olarak daha yapılandırılmış hale getirir.
- 🔁 **Hibrit Arama Artık Paralel Çalışıyor**: Hibrit (BM25 + embedding) arama bileşenleri artık paralel çalışır—yanıt sürelerini önemli ölçüde azaltır ve belge alımını hızlandırır.
- 📋 **Araç Çağrısı Görüntüsü için Daha Temiz UI**: Sohbet mesajları içinde çağrılan araçların görsel düzeni, daha iyi netlik ve azaltılmış görsel dağınıklık için optimize edildi.
- 🧪 **Playwright Zaman Aşımı Artık Yapılandırılabilir**: Playwright süreçleri için varsayılan zaman aşımı artık daha kısa ve ortam değişkenleriyle ayarlanabilir—web kazımayı daha sağlam ve ortamlara göre ayarlanabilir hale getirir.
- 📈 **Gözlemlenebilirlik için OpenTelemetry Desteği**: Open WebUI artık OpenTelemetry ile entegre olur, Grafana, Jaeger veya Prometheus gibi araçlarla bağlantı kurarak ayrıntılı performans içgörüleri ve gerçek zamanlı görünürlük elde etmenizi sağlar—tamamen isteğe bağlıdır ve tamamen kendi barındırdığınızdır. Etkinleştirilse bile, hiçbir veri bize gönderilmez, tüm telemetri verileri üzerindeki gizliliğiniz ve sahipliğiniz sağlanır.
- 🛠 **Genel UI Geliştirmeleri ve UX İyileştirmeleri**: Kenar çubuğu, kod blokları, modal etkileşimleri, düğme hizalaması, kaydırma çubuğu görünürlüğü ve klasör davranışı genelinde sayısız iyileştirme, arayüzün genel akışkanlığını ve kullanılabilirliğini artırır.
- 🧱 **Genel Backend Yeniden Yapılandırması**: Sayısız backend bileşeni, kararlılığı, sürdürülebilirliği ve performansı artırmak için yeniden yapılandırıldı—tüm özellikler genelinde daha tutarlı ve güvenilir bir sistem sağlar.
- 🌍 **Uluslararasılaşma Dil Desteği Güncellemeleri**: Estonca ve Galiçyaca dilleri eklendi, İspanyolca (tamamen revize edildi), Geleneksel Çince, Basitleştirilmiş Çince, Türkçe, Katalanca, Ukraynaca ve Almanca daha yerelleştirilmiş ve kapsayıcı bir arayüz için iyileştirildi.

### Düzeltildi

- 🧑‍💻 **Firefox Giriş Yüksekliği Hatası**: Firefox'taki metin girişi artık uygun yüksekliği korur, mesaj kutularının tutarlı görünmesini ve öngörülebilir şekilde davranmasını sağlar.
- 🧾 **Tika Boş Satır Hatası**: Apache Tika 3.1.0.0 ile işlenen PDF'ler artık aşırı boş satırlar içermez—RAG çıktı kalitesini ve görsel temizliği iyileştirir.
- 🧪 **CSV Yükleyici Kodlama Sorunları**: Bilinmeyen kodlamalara sahip CSV dosyaları artık karakter kümelerini otomatik olarak algılar, UTF-8 olmayan veri kümelerinde içe aktarma hatalarını çözer.
- ✅ **LDAP Kimlik Doğrulama Yapılandırma Düzeltmesi**: Sertifika dosyasına giden yol artık LDAP kurulumları için isteğe bağlıdır, önceden yapılandırılmış sertifika yolları olmayan kullanıcılar için kimlik doğrulama sorunlarını düzeltir.
- 📥 **Bypass Modunda Dosya Silme**: "Bypass embedding" modu etkinleştirildiğinde dosyaların bilgiden silinememesi sorunu çözüldü.
- 🧩 **Hibrit Arama Sonuç Sıralaması ve Tekrarlananları Kaldırma Düzeltildi**: RAG hibrit ve reranker modlarında alıntı ve sıralama sorunları düzeltildi, alınan belgelerin puana göre doğru sırada gösterilmesi sağlandı.
- 📫 **Kimlik Doğrulama Yönlendirme Düzeltmesi**: Oturum açmış kullanıcılar artık zaten kimliği doğrulanmışken gereksiz oturum açma istemleri olmadan düzgün bir şekilde yönlendirilir.

### Değiştirildi

- 🧠 **Prompt Otomatik Tamamlama Varsayılan Olarak Devre Dışı Bırakıldı**: Yazarken otomatik tamamlama önerileri artık kullanıcı tercihlerinde açıkça yeniden etkinleştirilmedikçe devre dışı bırakılmıştır—gelişmiş kullanıcılar için prompt oluştururken dikkat dağıtıcı unsurları azaltır.
- 🧾 **Alıntı Numaralandırmasını Normalleştir**: Kaynak alıntıları artık düzgün bir şekilde "0" yerine "1"den başlar—AI çıktılarında tutarlılığı ve profesyonel sunumu iyileştirir.
- 📚 **Pipelines'dan Geliştirilmiş Hata Yönetimi**: Pipelines artık başarısız görevlerden genel "Bağlantı kapatıldı" yerine gerçek dönen hata mesajını gösterir—hata ayıklamayı çok daha kullanıcı dostu hale getirir.

### Kaldırıldı

- 🧾 **ENABLE_AUDIT_LOGS Ayarı Kaldırıldı**: Eskimiş "ENABLE_AUDIT_LOGS" ayarı tamamen kaldırıldı—artık bunun yerine "AUDIT_LOG_LEVEL" tarafından kontrol ediliyor.

## [0.5.20] - 2025-03-05

### Eklendi

- **⚡ Kod Yürütmeyi Aç/Kapat**: Artık kod yürütmeyi etkinleştirebilir veya devre dışı bırakabilir, güvenlik üzerinde daha fazla kontrol sağlayabilir, daha güvenli ve daha özelleştirilebilir bir deneyim sağlayabilirsiniz.

### Düzeltildi

- **📜 Pinyin Klavye Enter Tuşu Artık Düzgün Çalışıyor**: Pinyin klavyeler için Enter tuşunun beklendiği gibi çalışmaması sorunu çözüldü, Çince kullanıcılar için sorunsuz giriş sağlandı.
- **🖼️ Web Manifest Yükleme Sorunu Düzeltildi**: 'site.webmanifest' ile ilgili tutarsızlıklar giderildi, uygulamanın farklı tarayıcılar ve cihazlar arasında doğru bir şekilde yüklenmesini ve temsil edilmesini garantiledi.
- **📦 Kök Olmayan Container Sorunu Çözüldü**: UI'nin kök olmayan container'larda doğru yüklenememesi gibi kritik bir sorun düzeltildi, çeşitli ortamlarda güvenilir dağıtım sağlandı.

## [0.5.19] - 2025-03-04

### Eklendi

- **📊 Logit Bias Parametre Desteği**: Sohbet ayarlarında Logit Bias parametresini doğrudan ayarlayarak konuşma dinamiklerini ince ayar yapın, model yanıtları üzerinde daha fazla kontrol sağlayın.
- **⌨️ Özelleştirilebilir Enter Davranışı**: Artık Ayarlar > Arayüz aracılığıyla Enter'ı yalnızca Ctrl ile birleştirildiğinde (Ctrl+Enter) mesaj gönderecek şekilde yapılandırabilirsiniz, kazara mesaj göndermeleri önler.
- **📝 Daraltılabilir Kod Blokları**: Sohbetinizi dağınıklıktan arındırmak ve önemli ayrıntılara odaklanmayı kolaylaştırmak için uzun kod bloklarını kolayca daraltın.
- **🏷️ Model Seçicide Etiket Seçici**: Model Seçici'deki yeni etiket filtreleme sistemi ile modelleri hızlıca bulun ve kategorize edin, model keşfini kolaylaştırın.
- **📈 Deneysel Elasticsearch Vektör DB Desteği**: Artık Elasticsearch'i bir vektör veritabanı olarak destekliyor, Retrieval-Augmented Generation (RAG) iş akışlarında veri alımı için daha fazla esneklik sunuyor.
- **⚙️ Genel Güvenilirlik Geliştirmeleri**: WebUI genelinde çeşitli kararlılık iyileştirmeleri, daha pürüzsüz, daha tutarlı bir deneyim sağlar.
- **🌍 Güncellenmiş Çeviriler**: Daha iyi yerelleştirme ve çeşitli dillerde doğruluk için iyileştirilmiş çok dilli destek.

### Düzeltildi

- **🔄 "Stream" Hook Aktivasyonu**: "Stream" hook'unun yalnızca global olarak etkinleştirildiğinde çalışması sorunu düzeltildi, güvenilir gerçek zamanlı filtreleme sağlandı.
- **📧 LDAP E-posta Büyük/Küçük Harf Duyarlılığı**: LDAP girişinin e-posta büyük/küçük harf duyarlılığı uyuşmazlıkları nedeniyle başarısız olması sorunu çözüldü, kimlik doğrulama güvenilirliği iyileştirildi.
- **💬 WebSocket Sohbet Olayı Kaydı**: Oturum açıldığında sohbet olay dinleyicilerinin kaydedilmesini engelleyen bir hata düzeltildi, gerçek zamanlı güncellemelerin düzgün çalışması sağlandı.

## [0.5.18] - 2025-02-27

### Düzeltildi

- **🌐 Open WebUI Artık Güvenli Olmayan Bağlamda LAN Üzerinde Çalışıyor**: Open WebUI'nin yerel bir ağ üzerinden güvenli olmayan bir bağlamda erişildiğinde işlev görememesi sorunu çözüldü, sorunsuz bağlantı sağlandı.
- **🔄 UI Artık Silinen Bağlantıları Anında Yansıtıyor**: Bir bağlantının silinmesinin UI'yi gerçek zamanlı olarak güncellememesi sorunu düzeltildi, doğru sistem durumu görünürlüğü sağlandı.
- **🛠️ ENABLE_FORWARD_USER_INFO_HEADERS ile Modeller Artık Doğru Görüntüleniyor**: ENABLE_FORWARD_USER_INFO_HEADERS ayarı yapıldığında modellerin görünmemesi sorunu giderildi, doğru model listelemesi geri getirildi.

## [0.5.17] - 2025-02-27

### Eklendi

- **🚀 Bypass Embedding & Retrieval ile Anında Belge Yükleme**: Yöneticiler artık Admin Ayarları > Belgeler'de "Bypass Embedding & Retrieval" özelliğini etkinleştirerek belge yüklemelerini önemli ölçüde hızlandırabilir ve tüm belge bağlamının parçalanmadan korunmasını sağlayabilir.
- **🔎 Gerçek Zamanlı Filtreleme için "Stream" Hook'u**: Yeni "stream" hook'u, dinamik gerçek zamanlı mesaj filtrelemesine olanak tanır. Daha fazla bilgiyi dokümantasyonumuzda bulabilirsiniz (https://docs.openwebui.com/features/plugin/functions/filter).
- ☁️ **OneDrive Entegrasyonu**: OneDrive depolama entegrasyonu için erken destek eklendi, dosya içe aktarma seçeneklerini genişletti.
- 📈 **Loguru ile Gelişmiş Günlükleme**: Backend günlükleme, Loguru ile iyileştirildi, hata ayıklama ve sorun takibini çok daha verimli hale getirdi.
- ⚙️ **Genel Kararlılık Geliştirmeleri**: Backend ve frontend yeniden yapılandırması performansı iyileştirir, daha pürüzsüz ve daha güvenilir bir kullanıcı deneyimi sağlar.
- 🌍 **Güncellenmiş Çeviriler**: Daha iyi yerelleştirme ve çeşitli dillerde doğruluk için iyileştirilmiş çok dilli destek.

### Düzeltildi

- 🔄 **Topluluk Platformundan Güvenilir Model İçe Aktarımları**: İçe aktarma hataları çözüldü, topluluk tarafından paylaşılan modellerin hatasız bir şekilde sorunsuz entegrasyonunu sağladı.
- 📊 **OpenAI Kullanım İstatistikleri Geri Getirildi**: OpenAI kullanım metriklerinin doğru görüntülenmemesi sorunu düzeltildi, kullanım verilerinin doğru takibini sağladı.
- 🗂️ **Alınan Belgeler için Tekrarlananları Kaldırma**: Aramalar sırasında alınan belgeler artık akıllıca tekrarlananlardan arındırılıyor, bu da gereksiz sonuçları ortadan kaldırarak bilginin kısa ve ilgili kalmasına yardımcı oluyor.

### Değiştirildi

- 📝 **"Tam Bağlam Modu" Netlik için Yeniden Adlandırıldı**: Web Arama ayarlarındaki "Tam Bağlam Modu" geçiş anahtarı, UI genelinde tutarlılık için artık "Bypass Embedding & Retrieval" olarak etiketlendi.

## [0.5.16] - 2025-02-20

### Düzeltildi

- 🔍 **Web Arama Alımı Geri Getirildi**: Tekrarlananları kaldırma değişikliklerini geri alarak web arama alımını bozan kritik bir sorun çözüldü, bu da tam ve doğru arama sonuçlarını tekrar sağladı.

## [0.5.15] - 2025-02-20

### Eklendi

- 📄 **Yerel Belge Araması için Tam Bağlam Modu (RAG)**: Admin Ayarları > Belgeler'den tam bağlam modunu açarak tüm belge içeriğini bağlama enjekte edin, büyük bağlam pencereli modeller için doğruluğu artırın—derin bağlam anlama için idealdir.
- 🌍 **Ajan Tabanlı İş Akışlarıyla Daha Akıllı Web Araması**: Web aramaları artık birden fazla ilgili terimi akıllıca toplar ve iyileştirir, RAG işleme benzer şekilde, daha doğru bilgi alımı için önemli ölçüde daha iyi arama sonuçları sunar.
- 🔎 **Web Yükleyici için Deneysel Playwright Desteği**: Playwright destekli kazıma ile web içeriği alımı bir sonraki seviyeye taşındı, çıkarılan web verilerinde artırılmış doğruluk için.
- ☁️ **Deneysel Azure Depolama Sağlayıcısı**: Azure Depolama entegrasyonu için erken aşama destek eklendi, Open WebUI içinde daha fazla bulut depolama esnekliği sağlıyor.
- 📊 **Plot'lar ile Geliştirilmiş Jupyter Kod Yürütme**: Etkileşimli kodlama artık sohbet etkileşimlerinde veri görselleştirmesini daha sorunsuz hale getirerek satır içi çizimler görüntüler.
- ⏳ **Jupyter Tercümanı için Ayarlanabilir Yürütme Zaman Aşımı**: İhtiyaçlarınıza göre daha uzun veya daha kısıtlı yürütme sağlamak için Jupyter tabanlı kod yürütme için yürütme zaman aşımını (varsayılan: 60s) özelleştirin.
- ▶️ **Jupyter Kod Yürütme için "Running..." Göstergesi**: Kod yürütme devam ederken görsel bir gösterge belirir, devam eden hesaplamalar hakkında gerçek zamanlı durum güncellemeleri sağlar.
- ⚙️ **Genel Backend ve Frontend Kararlılık Geliştirmeleri**: Kapsamlı yeniden yapılandırma, daha sorunsuz bir Open WebUI için güvenilirliği, performansı ve genel kullanıcı deneyimini iyileştirir.
- 🌍 **Çeviri Güncellemeleri**: Çeşitli uluslararası çeviri iyileştirmeleri, daha iyi yerelleştirme ve daha doğal bir kullanıcı arayüzü deneyimi sağlar.

### Düzeltildi

- 📱 **Mobil Üzerine Gelme Sorunu Çözüldü**: Kullanıcılar artık mobil cihazlarda yanıtları sorunsuz bir şekilde düzenleyebilir, uzun süreli üzerine gelme sorununu düzeltir.
- 🔄 **Geçici Sohbet Mesajı Tekrarlaması Düzeltildi**: Geçici sohbet modunda mesajların gereksiz yere tekrarlanmasına neden olan hatalı davranış ortadan kaldırıldı, sorunsuz ve tutarlı bir konuşma akışı sağlandı.

## [0.5.14] - 2025-02-17

### Düzeltildi

- 🔧 **Kritik İçe Aktarma Hatası Çözüldü**: 'open_webui.config' içinde 'override_static'in doğru şekilde içe aktarılmasını engelleyen dairesel bir içe aktarma sorunu düzeltildi, sorunsuz sistem başlatma ve kararlılık sağlandı.

## [0.5.13] - 2025-02-17

### Eklendi

- 🌐 **Web Araması için Tam Bağlam Modu**: Tam bağlam modunu kullanarak son derece doğru web aramalarını etkinleştirin—büyük bağlam pencereli modeller için idealdir, daha kesin ve bilgilendirici sonuçlar sağlar.
- ⚡ **Optimize Edilmiş Asenkron Web Araması**: Web aramaları, optimize edilmiş asenkron destekle önemli ölçüde daha hızlı yüklenir, kullanıcılara daha hızlı, daha verimli bilgi alımı sağlar.
- 🔄 **RTL Diller için Otomatik Metin Yönü**: Dil girişine göre otomatik metin hizalaması, Arapça, İbranice ve diğer sağdan sola betikler için sorunsuz konuşma akışı sağlar.
- 🚀 **Kod Yürütme için Jupyter Notebook Desteği**: Kod bloklarındaki "Run" düğmesi artık yürütme için Jupyter'ı kullanabilir, sohbet içinde güçlü, dinamik bir kodlama deneyimi sunar.
- 🗑️ **Mesaj Silme Onay Diyaloğu**: Mesajları kaldırmadan önce yeni bir onay istemiyle kazara silmeleri önleyin, sohbet geçmişinize ek bir güvenlik katmanı ekler.
- 📥 **SVG Diyagramları için İndirme Düğmesi**: Sohbet içinde oluşturulan SVG diyagramları artık anında indirilebilir, karmaşık görsel verileri kaydetmeyi ve paylaşmayı kolaylaştırır.
- ✨ **Genel UI/UX İyileştirmeleri ve Backend Kararlılığı**: Daha güvenilir, daha şık bir deneyim için daha pürüzsüz etkileşimler, iyileştirilmiş düzenler ve backend kararlılık geliştirmeleri ile yenilenmiş bir arayüz.

### Düzeltildi

- 🛠️ **Geçici Sohbet Mesajı Devam Düğmesi Düzeltildi**: Geçici sohbetler için "Yanıtı Devam Et" düğmesi artık beklendiği gibi çalışıyor, kesintisiz bir konuşma akışı sağlıyor.

### Değiştirildi

- 📝 **Prompt Değişkeni Güncellemesi**: Prompt değişkenleri için köşeli parantez '[]' göstergeleri eski haline getirildi; tutarlılık ve netlik için artık çift kıvrık parantez '{{}}' gerektiriyor.
- 🔧 **Kararlılık Geliştirmeleri**: Sohbet geçmişinde hata yönetimi iyileştirildi, önceki mesajları incelerken daha sorunsuz işlemler sağlandı.

## [0.5.12] - 2025-02-13

### Eklendi

- **🛠️ Yerel Fonksiyon Modu için Çoklu Araç Çağrısı Desteği**: Fonksiyonlar artık tek bir yanıtta birden fazla aracı çağırabilir, yerel fonksiyon çağırmayı kullanırken daha iyi otomasyon ve iş akışı esnekliği sağlar.

### Düzeltildi

- 📝 **Playground Metin Tamamlama Geri Getirildi**: Playground'da metin tamamlama işlevinin çalışmaması sorunu giderildi.
- 🔗 **Doğrudan Bağlantılar Artık Normal Kullanıcılar için Çalışıyor**: 'user' rolüne sahip kullanıcıların doğrudan API bağlantıları kuramaması hatası düzeltildi, tüm kullanıcı seviyeleri için sorunsuz model kullanımını etkinleştirdi.
- ⚡ **Açılış Sayfası Girişi Uzun Metinle Artık Gecikmiyor**: Açılış sayfasında giriş duyarlılığı iyileştirildi, uzun mesajlar girilirken bile hızlı ve pürüzsüz yazma deneyimleri sağlandı.
- 🔧 **Fonksiyonlardaki Parametre Düzeltildi**: Fonksiyonlarda ayrılmış parametrelerin tanınmaması sorunu düzeltildi, gelişmiş görev tabanlı otomasyon için tam işlevsellik geri getirildi.

## [0.5.11] - 2025-02-13

### Eklendi

- **🎤 Kokoro-JS TTS Desteği**: Yeni bir cihaz içi, yüksek kaliteli text-to-speech motoru entegre edildi, ses oluşturma kalitesini önemli ölçüde artırdı—her şey doğrudan tarayıcınızda çalışıyor.
- 🐍 **Kod Tercümanında Jupyter Notebook Desteği**: Artık Kod Tercümanı'nı Python kodunu sadece Pyodide aracılığıyla değil, Jupyter aracılığıyla da çalıştıracak şekilde yapılandırabilirsiniz, AI destekli hesaplamalar ve analizler için daha sağlam bir kodlama ortamı sunar.
- 🔗 **Özel ve Yerel Çıkarım için Doğrudan API Bağlantıları**: Open WebUI'yi özel veya localhost API çıkarım endpoint'lerinize bağlayabilirsiniz. CORS etkinleştirilmelidir, ancak bu, doğrudan, cihaz içi AI altyapısı desteğini açar.
- 🔍 **Web Araması için Gelişmiş Alan Filtreleme**: Web aramalarına hangi alanların dahil edilmesi veya hariç tutulması gerektiğini belirtebilirsiniz, daha ilgili bilgi alımı için sonuçları iyileştirir.
- 🚀 **Geliştirilmiş Resim Oluşturma Metadata İşlemesi**: Oluşturulan resimler, daha iyi organizasyon ve gelecekteki alım için metadata'yı korur.
- 📂 **S3 Anahtar Ön Ek Desteği**: Yapılandırılabilir anahtar ön ekleri ile S3 depolama dosyası yapılandırması üzerinde ayrıntılı kontrol.
- 📸 **Yalnızca Resim İçeren Mesajlar için Destek**: Yalnızca resim içeren mesajlar göndererek daha görsel odaklı etkileşimleri kolaylaştırın.
- 🌍 **Güncellenmiş Çeviriler**: Almanca, İspanyolca, Geleneksel Çince ve Katalanca çevirileri, daha iyi çok dilli destek için güncellendi.

### Düzeltildi

- 🔧 **OAuth Hata Ayıklama Logları ve Kullanıcı Adı İddia Düzeltmeleri**: OAuth rolü ve grup yönetimi için hata ayıklama logları eklendi, doğru OAuth kullanıcı adı alımı ve iddia işlemesi sağlandı.
- 📌 **Alıntılar Biçimlendirme ve Geçiş Anahtarı Düzeltmeleri**: Satır içi alıntı geçiş anahtarları artık doğru çalışıyor ve üçten fazla kaynağa sahip alıntılar artık genişletildiğinde tamamen görünür.
- 📸 **ComfyUI Maksimum Seed Değeri Kısıtlaması Düzeltildi**: ComfyUI için izin verilen maksimum seed değeri düzeltildi, istenmeyen davranışları önledi.
- 🔑 **Bağlantı Ayarları Kararlılığı**: Yapılandırmaları kaydederken kararsızlığa neden olan bağlantı ayarları sorunları giderildi.
- 📂 **GGUF Model Yükleme Kararlılığı**: GGUF modelleri için yükleme tutarsızlıkları düzeltildi, güvenilir yerel model işleme sağlandı.
- 🔧 **Web Arama Yapılandırma Hatası**: Web arama filtreleri ve ayarlarının doğru uygulanmaması sorunları düzeltildi.
- 💾 **Kullanıcı Ayarları Kalıcılığı Düzeltmesi**: Kullanıcıya özgü ayarların oturumlar arasında doğru bir şekilde kaydedilmesi ve uygulanması sağlandı.
- 🔄 **OpenID Kullanıcı Adı Alımı Geliştirmesi**: OpenID Connect (OIDC) girişleri için kullanıcı adları artık doğru bir şekilde alınır ve atanır.

## [0.5.10] - 2025-02-05

### Düzeltildi

- ⚙️ **Sistem Prompt'ları Artık API aracılığıyla Düzgün Şablonlandı**: Sistem prompt'larının API aracılığıyla kullanıldığında doğru bir şekilde işlenmemesi sorunu çözüldü, şablon değişkenlerinin beklendiği gibi çalışması sağlandı.
- 📝 **'<thinking>' Etiketi Görüntüleme Sorunu Düzeltildi**: 'thinking' etiketinin içerik oluşturmayı bozması hatası düzeltildi, temiz ve doğru metin görüntülemesi sağlandı.
- 💻 **Özel Fonksiyonlarla Kod Tercümanı Kararlılığı**: Anthropic gibi belirli özel fonksiyonlarla Kod Tercümanı kullanılırken oluşan hatalar giderildi, daha sorunsuz yürütme ve daha iyi uyumluluk sağlandı.

## [0.5.9] - 2025-02-05

### Düzeltildi

- 💡 **"Think" Etiketi Görüntüleme Sorunu**: "Think" etiketinin doğru çalışmaması hatası çözüldü, yanıtları vermeden önce modelin düşünme sürecinin doğru görselleştirilmesi sağlandı.

## [0.5.8] - 2025-02-05

### Eklendi

- 🖥️ **Kod Tercümanı**: Modeller artık yanıtlarını dinamik olarak iyileştirmek için kodu gerçek zamanlı olarak yürütebilir, Pyodide kullanarak güvenli bir sandboxed tarayıcı ortamında çalışır. Hesaplamalar, veri analizi ve AI destekli kodlama görevleri için mükemmel!
- 💬 **Yeniden Tasarlanmış Sohbet Giriş UI'si**: Geliştirilmiş özellik seçimi ile daha şık ve sezgisel bir mesaj girişinin keyfini çıkarın, araçları açıp kapatmayı, aramayı etkinleştirmeyi ve AI ile sorunsuz bir şekilde etkileşim kurmayı her zamankinden daha kolay hale getirir.
- 🛠️ **Yerel Araç Çağırma Desteği (Deneysel)**: Desteklenen modeller artık araçları yerel olarak çağırabilir, sorgu gecikmesini azaltır ve bağlamsal yanıtları iyileştirir. Daha fazla geliştirme yakında geliyor!
- 🔗 **Exa Arama Motoru Entegrasyonu**: Yeni bir arama sağlayıcısı eklendi, kullanıcıların sohbet arayüzünden ayrılmadan güncel ve ilgili bilgilere erişmesine olanak tanır.
- 🌍 **Yerelleştirilmiş Tarihler ve Saatler**: Tarih ve saat formatları artık sistem yerel ayarınızla eşleşiyor, daha doğal, bölgeye özgü bir deneyim sağlıyor.
- 📎 **Harici Embedding API'leri için Kullanıcı Başlıkları**: Harici embedding hizmetlerine yapılan API çağrıları artık kullanıcıyla ilgili başlıkları içeriyor.
- 🌍 **"Her Zaman Açık" Web Arama Geçiş Anahtarı**: Ayarlar > Arayüz altında yeni bir seçenek, kullanıcıların Web Aramayı varsayılan olarak etkinleştirmesine olanak tanır—Open WebUI'yi ana arama motorunuz haline getirin, her sorguyla AI destekli sonuçlar sağlayın.
- 🚀 **Genel Performans ve Kararlılık**: Daha hızlı, daha güvenilir bir deneyim için platform genelinde önemli iyileştirmeler.
- 🖼️ **UI/UX Geliştirmeleri**: Okunabilirliği, duyarlılığı ve erişilebilirliği iyileştiren çok sayıda tasarım iyileştirmesi.
- 🌍 **Geliştirilmiş Çeviriler**: Çince, Korece, Fransızca, Ukraynaca ve Sırpça çevirileri, daha iyi netlik için iyileştirilmiş terminolojilerle güncellendi.

### Düzeltildi

- 🔄 **OAuth Ad Alanı Yedeklemesi**: Bir ad eksik olduğunda e-posta alanını yedek olarak kullanarak OAuth giriş hatalarını çözer.
- 🔑 **Google Drive Kimlik Bilgileri Kısıtlaması**: Gelişmiş güvenlik için yalnızca kimliği doğrulanmış kullanıcıların Google Drive kimlik bilgilerine erişmesini sağlar.
- 🌐 **DuckDuckGo Arama Hızı Sınırı İşlemesi**: DuckDuckGo için web araması kullanıldığında kullanıcıların hız limitleri nedeniyle 202 hatalarıyla karşılaşması sorunlarını düzeltir.
- 📁 **Dosya Yükleme İzin Göstergesi**: Kullanıcılara dosya yükleme izinleri olmadığında artık bildirimde bulunulur, sistem kısıtlamaları hakkında netliği artırır.
- 🔧 **Maksimum Token Sorunu**: 'max_tokens'ın doğru uygulanmadığı durumları düzeltir, doğru model davranışını sağlar.
- 🔍 **RAG Web Arama URL'leri için Doğrulama**: Web tabanlı retrieval augmentation kullanılırken geçersiz veya desteklenmeyen URL'leri filtreler.
- 🖋️ **Başlık Oluşturma Hatası**: Başlık oluşturmadaki tutarsızlıkları düzeltir, doğru sohbet organizasyonunu sağlar.

### Kaldırıldı

- ⚡ **Eskimiş Web Worker Pyodide Yürütmesi**: Daha iyi performans ve güvenlik için tamamen tarayıcı sandboxing'ine geçildi.

## [0.5.7] - 2025-01-23

### Eklendi

- **🌍 Gelişmiş Uluslararasılaşma (i18n)**: Daha fazla küresel erişilebilirlik ve uluslararası kullanıcılar için daha sorunsuz bir deneyim için iyileştirilmiş ve genişletilmiş çeviriler.

### Düzeltildi

- 🔗 **Bağlantı Modeli ID Çözünürlüğü**: Model ID'lerinin bağlantılarda kaydolmasını engelleyen bir sorun çözüldü.
- 💡 **Ollama Bağlantıları için Ön Ek ID**: Ollama bağlantılarındaki ön ek ID'lerinin işlevsiz olması hatası düzeltildi.
- 🔧 **Ollama Modeli Etkinleştirme/Devre Dışı Bırakma İşlevselliği**: Ollama temel modelleri için etkinleştirme/devre dışı bırakma geçiş anahtarlarının çalışmaması sorunu giderildi.
- 🔒 **Araçlar ve Modeller için RBAC İzinleri**: Araçlar ve modeller için yanlış Rol Tabanlı Erişim Kontrolü (RBAC) izinleri düzeltildi, böylece kullanıcılar artık yalnızca atanan ayrıcalıklarına göre özelliklere erişir, güvenliği ve rol netliğini artırır.

## [0.5.6] - 2025-01-22

### Eklendi

- **🧠 OpenAI Modelleri için Çaba Gerektiren Muhakeme Kontrolü**: Desteklenen OpenAI modelleri için sohbet kontrollerine `reasoning_effort` parametresi tanıtıldı, kullanıcıların bir modelin yanıtlarına ne kadar bilişsel çaba harcayacağını ince ayar yapmasına olanak tanıyarak karmaşık sorgular ve muhakeme görevleri için daha fazla özelleştirme sunar.

### Düzeltildi

- 🔄 **Sohbet Kontrolleri Yükleme UI Hatası**: Daraltılabilir sohbet kontrollerinin "yükleniyor" olarak görünmesi sorunu çözüldü, sohbet ayarlarını yönetmek için daha sorunsuz ve daha sezgisel bir kullanıcı deneyimi sağlandı.

### Değiştirildi

- 🔧 **Güncellenmiş Ollama Model Oluşturma**: Ollama model oluşturma yöntemi, yeni JSON payload formatlarına uyum sağlamak için yeniden düzenlendi, sorunsuz uyumluluk ve daha verimli model kurulum iş akışları sağlandı.

## [0.5.5] - 2025-01-22

### Eklendi

- 🤔 **Yerel 'Think' Etiketi Desteği**: Modelin ne kadar düşündüğünü görsel olarak gösteren yeni 'think' etiketi desteği tanıtıldı, muhakeme içeriğini bir sonraki adıma kadar atlar. Daha düzenli ve odaklanmış bir etkileşim deneyimi oluşturmak için idealdir.
- 🖼️ **Görüntü Oluşturmayı Aç/Kapat**: Sohbet giriş menüsünde, sohbetleri başlatmadan önce görüntü oluşturmayı kolayca açıp kapatabilirsiniz, ihtiyaçlarınıza uygun daha fazla kontrol ve esneklik sağlar.
- 🔒 **Sohbet Kontrolleri İzinleri**: Yöneticiler artık kullanıcılar için sohbet kontrolleri erişimini devre dışı bırakabilir, kullanıcı etkileşimleri üzerinde daha sıkı yönetim ve özelleştirme sunar.
- 🔍 **Web Araması ve Görüntü Oluşturma İzinleri**: Belirli kullanıcılar için web aramasını ve görüntü oluşturmayı kolayca devre dışı bırakın, belirli ortamlar için iş akışı yönetişimini ve güvenliğini iyileştirin.
- 🗂️ **S3 ve GCS Depolama Sağlayıcısı Desteği**: Ölçeklendirilmiş dağıtımlar artık Amazon S3 ve Google Cloud Storage'ın sorunsuz entegre edilmiş sağlayıcılar olarak genişletilmiş depolama seçeneklerinden yararlanır.
- 🎨 **Gelişmiş Model Yönetimi**: Kullanıcı karışıklığını en aza indirmek ve verimli model yönetimini sağlamak için yönetici modelleri ayarları sayfasında modelleri doğrudan indirme ve silme yeteneği yeniden tanıtıldı.
- 🔗 **Geliştirilmiş Bağlantı İşleme**: Birden fazla aynı temel URL'yi sorunsuz bir şekilde işlemek için backend geliştirildi, daha az sorunla daha esnek çoklu örnek yapılandırmalarına izin veriyor.
- ✨ **Genel UI/UX İyileştirmeleri**: WebUI genelinde gezinmeyi ve kullanılabilirliği daha da kullanıcı dostu ve sezgisel hale getiren çok sayıda ince ayar.
- 🌍 **Çeviri Geliştirmeleri**: Uluslararası kullanıcılar için daha sorunsuz ve daha şık etkileşimler sağlamak amacıyla çeşitli çeviri güncellemeleri.

### Düzeltildi

- ⚡ **Mac Kullanıcıları için MPS İşlevselliği**: MPS desteği düzeltildi, MPS'yi kullanan Mac kullanıcıları için sorunsuz performans ve uyumluluk sağlandı.
- 📡 **Ollama Bağlantı Yönetimi**: Tüm Ollama bağlantılarının silinmesinin yenilerini eklemeyi engellemesi sorunu çözüldü.

### Değiştirildi

- ⚙️ **Genel Kararlılık Yeniden Yapılandırması**: Backend yeniden yapılandırması daha kararlı, sağlam bir platform sunar.
- 🖥️ **Masaüstü Uygulaması Hazırlıkları**: Gelecek Open WebUI masaüstü uygulamasını desteklemek için devam eden çalışmalar. Gelişmelerimizi ve güncellemelerimizi buradan takip edin: https://github.com/open-webui/desktop

## [0.5.4] - 2025-01-05

### Eklendi

- 🔄 **Paylaşılan Sohbetleri Klonla**: Zamandan tasarruf etmek ve işbirliğini kolaylaştırmak için paylaşılan sohbetleri zahmetsizce klonlayın, bilgilendirici tartışmaları veya özel kurulumları yeniden kullanmak için mükemmeldir.
- 📣 **Kanal Mesajları için Yerel Bildirimler**: Kanal mesajları için entegre masaüstü bildirimleriyle haberdar olun, çoklu görev yaparken önemli güncellemeleri asla kaçırmamanızı sağlayın.
- 🔥 **Torch MPS Desteği**: Open WebUI doğrudan yüklendiğinde Mac kullanıcıları için MPS desteği, AI iş yükleri için daha iyi performans ve uyumluluk sunar.
- 🌍 **Gelişmiş Çeviriler**: Çeşitli çevirilere küçük iyileştirmeler yapıldı, daha sorunsuz bir küresel kullanıcı deneyimi sağlandı.

### Düzeltildi

- 🖼️ **Kanallarda Yalnızca Resim İçeren Mesajlar**: Kanallarda artık ek metin veya içerik olmadan resim gönderebilirsiniz.
- ❌ **Doğru İstisna İşleme**: İstisnaların açıkça yükseltilmesi sağlanarak hata geri bildirimi geliştirildi, kafa karışıklığını azalttı ve daha sorunsuz hata ayıklamayı teşvik etti.
- 🔍 **RAG Sorgu Oluşturma Geri Getirildi**: Retrieval-Augmented Generation için sorgu oluşturma sorunları düzeltildi, retrieval doğruluğunu artırdı ve sorunsuz işlevsellik sağlandı.
- 📩 **MOA Yanıt İşlevselliği Düzeltildi**: MOA yanıt oluşturma özelliğiyle ilgili bir hata giderildi.
- 💬 **50+ Mesajlı Kanal Konusu Yüklemesi**: Kanal konularının 50 mesajı aştığında takılması sorunu çözüldü, aktif tartışmalarda sorunsuz gezinme sağlandı.
- 🔑 **API Endpoint Kısıtlamaları Çözünürlüğü**: 'API_KEY_ALLOWED_ENDPOINTS' ayarının amaçlandığı gibi çalışmaması gibi kritik bir hata düzeltildi, geliştirilmiş güvenlik için API erişiminin belirtilen endpoint'lerle sınırlı kalmasını sağladı.
- 🛠️ **Eylem Fonksiyonları Geri Getirildi**: Eylem fonksiyonlarının çalışmasını engelleyen bir sorun düzeltildi, özelleştirilmiş otomasyonlar ve iş akışları için kullanışlılıkları geri getirildi.
- 📂 **Geçici Sohbet JSON Dışa Aktarma Düzeltmesi**: Geçici sohbetlerin JSON formatında dışa aktarılmasını engelleyen bir hata düzeltildi, sorunsuz veri taşınabilirliği sağlandı.

### Değiştirildi

- 🎛️ **Kenar Çubuğu UI Ayarları**: Sohbet klasörleri, sabitlenmiş klasörler dahil, daha iyi organizasyon için Sohbetler bölümünün altında görüntülenir; "Yeni Klasör" düğmesi, daha sezgisel bir iş akışı için Sohbetler bölümüne taşındı.
- 🏗️ **Gerçek Zamanlı Kaydetme Varsayılan Olarak Devre Dışı**: 'ENABLE_REALTIME_CHAT_SAVE' ayarı artık varsayılan olarak kapalıdır, yüksek tempolu iş akışlarında veya daha az kritik senaryolarda performansı önceliklendiren kullanıcılar için yanıt hızını artırır.
- 🎤 **Ses Girişi Yankı İptali**: Ses girişi artık varsayılan olarak yankı iptali özelliğine sahiptir, konuşmalar veya ses tabanlı etkileşimler sırasında daha iyi netlik için ses geri bildirimini azaltır.
- 🔧 **Genel Güvenilirlik İyileştirmeleri**: Platform kararlılığını artırmak, genel performansı yükseltmek ve iş akışları genelinde daha sorunsuz, daha güvenilir bir deneyim sağlamak için perde arkasında sayısız iyileştirme yapıldı.

## [0.5.3] - 2024-12-31

### Eklendi

- 💬 **Kanal Reaksiyonları ve Yerleşik Emoji Seçici**: Kanallardaki konulara ve mesajlara reaksiyonlarla kolayca kendinizi ifade edin, sorunsuz seçim için sezgisel yerleşik bir emoji seçici içerir.
- 🧵 **Kanallar için Konular**: Kanallar içindeki tartışmaları konular oluşturarak düzenleyin, netliği artırın ve odaklanmış konuşmaları teşvik edin.
- 🔄 **SVG Pan/Zoom için Sıfırla Düğmesi**: SVG Pan/Zoom'a kullanışlı bir sıfırla düğmesi eklendi, kullanıcıların diyagramları veya görselleri zahmetsizce varsayılan durumlarına hızla döndürmelerini sağlar.
- ⚡ **Gerçek Zamanlı Sohbet Kaydetme Ortam Değişkeni**: ENABLE_REALTIME_CHAT_SAVE ortam değişkeni tanıtıldı. Gerçek zamanlı sohbet kaydını devre dışı bırakarak daha hızlı yanıtlar veya kritik işlemler için parça parça veri kalıcılığı sağlayarak seçim yapın.
- 🌍 **Çeviri Geliştirmeleri**: Birden fazla dilde güncellenmiş ve iyileştirilmiş çeviriler, uluslararası kullanıcılar için daha sorunsuz bir deneyim sağlar.
- 📚 **Geliştirilmiş Dokümantasyon**: Fonksiyonlar hakkında genişletilmiş dokümantasyon, fonksiyon eklentileri hakkında daha net rehberlik ve v0.5'e geçiş için ayrıntılı talimatlar içerir. Bu, kullanıcıların yeni güncellemeleri daha etkili bir şekilde uyarlamasını ve kullanmasını sağlar. (https://docs.openwebui.com/features/plugin/)

### Düzeltildi

- 🛠️ **Ollama Parametreleri Dikkat Ediliyor**: Ollama için giriş parametrelerinin göz ardı edilmesi sorunu çözüldü, hassas ve tutarlı model davranışı sağlandı.
- 🔧 **Fonksiyon Eklentisi Çıkış Hook'u Güvenilirliği**: Filtre fonksiyonu eklentilerindeki 'event_emitter' ve çıkış hook'larında sorunlara neden olan bir hata düzeltildi, özel uzantılar içinde daha sorunsuz çalışma garantisi verildi.
- 🖋️ **Tuhaf Özel Durum Açıklamaları**: Özel kullanıcı durumlarının biçimlendirilmesi ve işlevselliği ayarlandı, doğru ve sezgisel bir şekilde görüntülenmeleri sağlandı.
- 🔗 **Geri Getirilen API İşlevselliği**: Belirli yapılandırmalar için API'lerin çalışmaması gibi kritik bir sorun düzeltildi, kesintisiz erişim sağlandı.
- ⏳ **Özel Pipe Fonksiyonu Tamamlama**: Belirli özel pipe fonksiyon eklentilerini kullanan sohbetlerin düzgün bir şekilde bitmemesi sorunu çözüldü, tutarlı sohbet iş akışları geri getirildi.
- ✅ **Genel Kararlılık Geliştirmeleri**: Genel güvenilirliği artırmak için perde arkasında çeşitli iyileştirmeler yapıldı, WebUI genelinde daha sorunsuz ve daha tutarlı performans sağlandı.

## [0.5.2] - 2024-12-26

### Eklendi

- 🖊️ **Kanallarda Yazma Göstergeleri**: Kanallarınızda kimin gerçek zamanlı olarak yazdığını tam olarak bilin, işbirliğini artırın ve herkesi etkileşimde tutun.
- 👤 **Kullanıcı Durum Göstergeleri**: Daha iyi koordinasyon ve uygunluk içgörüleri için kanallarda bir kullanıcının profil resmine tıklayarak durumunu hızla görüntüleyin.
- 🔒 **Yapılandırılabilir API Anahtarı Kimlik Doğrulama Kısıtlamaları**: API anahtarı kimlik doğrulaması için endpoint kısıtlamalarını esnek bir şekilde yapılandırın, güvenilir ortamlarda daha sorunsuz bir kurulum için artık varsayılan olarak kapalıdır.

### Düzeltildi

- 🔧 **Playground İşlevselliği Geri Getirildi**: Playground'ın çalışmaması gibi kritik bir sorun çözüldü, sorunsuz deneme ve sorun giderme iş akışları sağlandı.
- 📊 **Düzeltilmiş Ollama Kullanım İstatistikleri**: Ollama'nın kullanım istatistiklerindeki bir hesaplama hatası düzeltildi, daha doğru izleme ve daha iyi kaynak yönetimi için içgörüler sağlandı.
- 🔗 **Pipelines Outlet Hook Kaydı**: Pipeline'lar için çıkış hook'larının kaydedilmemesi sorunu giderildi, pipeline iş akışlarında işlevsellik ve tutarlılık geri getirildi.
- 🎨 **Görüntü Oluşturma Hatası**: Sorunsuz görüntü oluşturma iş akışları sağlamak için 'get_automatic1111_api_auth()' ile ilgili hatalara neden olan sürekli bir sorun çözüldü.
- 🎙️ **Text-to-Speech Hatası**: Eleven Labs'ın 'get_available_voices()' içinde eksik bağımsız değişken düzeltildi, kesintisiz ses etkileşimleri için tam metin-konuşma yetenekleri geri getirildi.
- 🖋️ **Başlık Oluşturma Sorunu**: Belirli durumlarda başlık oluşturmanın çalışmaması hatası düzeltildi, tutarlı ve güvenilir sohbet organizasyonu sağlandı.

## [0.5.1] - 2024-12-25

### Eklendi

- 🔕 **Bildirim Sesi Geçiş Anahtarı**: Ayarlar > Arayüz altında bildirim seslerini devre dışı bırakmak için yeni bir ayar eklendi, çalışma alanı ortamınız ve odaklanmanız üzerinde daha fazla kontrol sağlar.

### Düzeltildi

- 🔄 **Akışsız Yanıt Görünürlüğü**: Akışsız yanıtların görüntülenmemesi sorunu çözüldü, artık tüm yanıtlar konuşmalarınızda güvenilir bir şekilde gösteriliyor.
- 🖋️ **OpenAI API'leri ile Başlık Oluşturma**: OpenAI API'lerini kullanırken başlık oluşturmayı engelleyen bir hata düzeltildi, daha sorunsuz organizasyon için sohbet başlıklarını otomatik olarak oluşturma yeteneği geri getirildi.
- 👥 **Yönetici Paneli Kullanıcı Listesi**: Yönetici panelinde sadece 50 kullanıcının görünmesi sorunu giderildi. Artık tüm kullanıcıları kısıtlama olmaksızın yönetebilir ve görüntüleyebilirsiniz.
- 🖼️ **Görüntü Oluşturma Hatası**: Görüntü oluşturmada 'get_automatic1111_api_auth()' hatalarına neden olan sorun düzeltildi, sorunsuz yaratıcı iş akışları sağlandı.
- ⚙️ **Pipeline Ayarları Yükleme Sorunu**: Pipeline ayarlarının yükleme ekranında takılı kalması sorunu çözüldü, yönetici panelinde tam yapılandırılabilirlik geri getirildi.

## [0.5.0] - 2024-12-25

### Eklendi

- 💬 **Gerçek Asenkron Sohbet Desteği**: Sohbetler oluşturun, başka yere gidin ve yanıtlar hazır olduğunda istediğiniz zaman geri dönün. Muhakeme modelleri ve çoklu ajan iş akışları için idealdir, çoklu görevi daha önce hiç olmadığı kadar geliştirir.
- 🔔 **Sohbet Tamamlama Bildirimleri**: Tamamlanmış bir yanıtı asla kaçırmayın. Etkin olmayan bir sekmede bir sohbet bittiğinde anında UI içi bildirimler alın, başka yerde çalışırken sizi güncel tutar.
- 🌐 **Bildirim Webhook Entegrasyonu**: Sekmeniz kapalıyken bile webhook'lar aracılığıyla uyarılar alın! Ayarlar > Hesap'tan webhook URL'nizi yapılandırın ve uzun süreli sohbetler veya harici entegrasyon ihtiyaçları için zamanında güncellemeler alın.
- 📚 **Kanallar (Beta)**: Kullanıcılar ve AI'lar arasında gerçek zamanlı işbirliği için tasarlanmış Discord/Slack tarzı sohbet odalarını keşfedin. Kanallar için botlar oluşturun ve proaktif çoklu ajan iş akışları için asenkron iletişimin kilidini açın. Yönetici Ayarları > Genel aracılığıyla katılın. Kapsamlı bir Bot SDK öğreticisi (https://github.com/open-webui/bot) geliyor, bu yüzden takipte kalın!
- 🖼️ **Client-Side Görüntü Sıkıştırma**: Artık yüklemeden önce görüntüleri sıkıştırın (Ayarlar > Arayüz), bant genişliğinden tasarruf edin ve performansı sorunsuz bir şekilde iyileştirin.
- 🛠️ **Kullanıcı Grupları için OAuth Yönetimi**: İşbirlikçi ortamlarda gelişmiş kontrol ve ölçeklenebilirlik için OAuth entegrasyonu aracılığıyla grup düzeyinde yönetimi etkinleştirin.
- ✅ **Ollama için Yapılandırılmış Çıktı**: Yapılandırılmış veri çıktısını doğrudan Ollama'ya geçirin, kolaylaştırılmış otomasyon ve hassas veri işleme için yeni olanaklar açın.
- 📜 **Çevrimdışı Swagger Dokümantasyonu**: Geliştirici dostu Swagger API dokümanları artık çevrimdışı olarak kullanılabilir, nerede olursanız olun tam erişilebilirlik sağlar.
- 📸 **Hızlı Ekran Yakalama Düğmesi**: Mesaj giriş menüsünden tek tıklamayla ekranınızı zahmetsizce yakalayın.
- 🌍 **i18n Güncellemeleri**: Ukraynaca, Almanca, Brezilya Portekizcesi, Katalanca ve daha fazlası dahil olmak üzere birçok dilde iyileştirilmiş ve rafine edilmiş çeviriler, sorunsuz bir küresel kullanıcı deneyimi sağlar.

### Düzeltildi

- 📋 **CSV'ye Tablo Dışa Aktarma**: Başlıkların eksik olması veya virgül içeren değerler nedeniyle hatalar oluşması gibi CSV dışa aktarma sorunları çözüldü, sorunsuz ve güvenilir veri işleme sağlandı.
- 🔓 **BYPASS_MODEL_ACCESS_CONTROL**: Kullanıcıların modelleri görebilmesi ancak 'BYPASS_MODEL_ACCESS_CONTROL=True' ile kullanamaması sorunu düzeltildi, bu ayarı kullanan ortamlar için doğru işlevsellik geri getirildi.

### Değiştirildi

- 💡 **API Anahtarı Kimlik Doğrulama Kısıtlaması**: Gelişmiş güvenlik ve daha iyi API yönetimi için API anahtarı kimlik doğrulama izinleri '/api/models' ve '/api/chat/completions' ile sınırlandırıldı.
- ⚙️ **Performans için Backend Revizyonu**: Büyük backend yeniden yapılandırması; dahili değişkenleri kullanan bazı "Fonksiyonlar"ın uyumluluk sorunlarıyla karşılaşabileceği konusunda bir uyarı. İleride, Open WebUI'nin sorunsuz çalışmasını sağlamak için websocket desteği zorunludur.

### Kaldırıldı

- ⚠️ **Eski İşlevsellik Temizliği**: Gereksiz veya daha yeni uygulamalarla çakışan eski backend sistemleri kullanımdan kaldırıldı, daha yalın, daha verimli bir platform için.

## [0.4.8] - 2024-12-07

### Eklendi

- 🔓 **Model Erişim Kontrolünü Atla**: 'BYPASS_MODEL_ACCESS_CONTROL' ortam değişkeni tanıtıldı. Erişim kontrolü gerekmediğinde kullanıcı rolleri için model erişim kontrollerini kolayca atlayın, güvenilir ortamlar için iş akışlarını basitleştirin.
- 📝 **Banner'larda Markdown**: Banner'lar için Markdown desteği eklendi, daha zengin, görsel olarak daha çekici duyurulara olanak tanır.
- 🌐 **Uluslararasılaşma Güncellemeleri**: Çoklu dillerde geliştirilmiş çeviriler, erişilebilirliği ve küresel kullanıcı deneyimini daha da iyileştiriyor.
- 🎨 **Stil Geliştirmeleri**: Daha temiz ve daha şık bir arayüz için genel UI stil iyileştirmeleri.
- 📋 **Zengin Metin Güvenilirliği**: Daha sorunsuz etkileşimler için sohbetlerde zengin metin girişinin güvenilirliği ve kararlılığı iyileştirildi.

### Düzeltildi

- 💡 **Tailwind Build Sorunu**: Tailwind'den kaynaklanan kritik bir hata düzeltildi, daha sorunsuz build'ler ve genel sistem güvenilirliği sağlandı.
- 📚 **Bilgi Koleksiyonu Sorgu Düzeltmesi**: Bilgi koleksiyonlarını sorgulamayla ilgili API endpoint sorunları giderildi, doğru ve güvenilir bilgi alımı sağlandı.

## [0.4.7] - 2024-12-01

### Eklendi

- ✨ **Prompt Girişi Otomatik Tamamlama**: Bir prompt yazın ve AI'nın girişlerinizi akıllıca önermesine ve tamamlamasına izin verin. Onaylamak için mobil cihazda 'Tab' tuşuna basın veya sağa kaydırın. Yalnızca Zengin Metin Girişi (varsayılan ayar) ile kullanılabilir. Tam kontrol için Yönetici Ayarları'ndan devre dışı bırakın.
- 🌍 **Geliştirilmiş Çeviriler**: Çoklu diller için geliştirilmiş yerelleştirme, uluslararası kullanıcılar için daha şık ve erişilebilir bir deneyim sağlar.

### Düzeltildi

- 🛠️ **Araçlar Dışa Aktarma Sorunu**: Araçları dışa aktarmanın işlevsiz olduğu kritik bir sorun çözüldü, sorunsuz dışa aktarma yetenekleri geri getirildi.
- 🔗 **Model ID Kaydı**: Model ID'lerinin model düzenleyicide doğru bir şekilde kaydedilmemesi sorunu düzeltildi, güvenilir model kurulumu ve takibi sağlandı.
- 🖋️ **Textarea Otomatik Genişleme**: Textarea'ların belirli tarayıcılarda otomatik olarak genişlememesi hatası düzeltildi, çok satırlı girişler için kullanılabilirliği iyileştirdi.
- 🔧 **Ollama Embed Endpoint**: /ollama/embed endpoint'i arızası giderildi, tutarlı performans ve işlevsellik sağlandı.

### Değiştirildi

- 🎨 **Bilgi Tabanı Stilizasyonu**: Daha temiz, daha modern bir görünüm için bilgi tabanı görselleri iyileştirildi, gelecek sürümlerde daha fazla geliştirme için zemin hazırlandı.

## [0.4.6] - 2024-11-26

### Eklendi

- 🌍 **Gelişmiş Çeviriler**: WebUI'yi dünya çapında daha erişilebilir ve kullanıcı dostu hale getirmek için çeşitli dil çevirileri iyileştirildi.

### Düzeltildi

- ✏️ **Textarea Kaydırma Hatası**: Textarea'nın beklenmedik şekilde kayması sorunu çözüldü, daha sorunsuz bir yazma deneyimi sağlandı.
- ⚙️ **Model Yapılandırma Modalı**: 0.4.5'te tanıtılan modeller yapılandırma modalının bazı kullanıcılar için çalışmaması sorunu düzeltildi.
- 🔍 **Eski Sorgu Desteği**: Eski prompt'lar kullanılırken RAG'de özel sorgu oluşturma işlevselliği geri getirildi, hem varsayılan hem de özel şablonların artık sorunsuz çalışması sağlandı.
- ⚡ **Geliştirilmiş Genel Güvenilirlik**: Çeşitli küçük düzeltmeler, platform kararlılığını artırır ve iş akışları genelinde daha sorunsuz bir genel deneyim sağlar.

## [0.4.5] - 2024-11-26

### Eklendi

- 🎨 **Model Sırası/Varsayılanlar Yeniden Tanıtıldı**: Model sırasını ve varsayılan modelleri ayarlama yeteneği geri getirildi, artık Yönetici Ayarları > Modeller > Yapılandır (Dişli Simgesi) aracılığıyla yapılandırılabilir.

### Düzeltildi

- 🔍 **Sorgu Oluşturma Sorunu**: Web arama sorgusu oluşturmada bir hata çözüldü, arama doğruluğu artırıldı ve daha sorunsuz arama iş akışları sağlandı.
- 📏 **Textarea Otomatik Yükseklik Hatası**: Textarea giriş yüksekliğinin öngörülemeyen bir şekilde kayması, özellikle sistem prompt'larını düzenlerken oluşan bir düzen sorunu düzeltildi.
- 🔑 **Ollama Kimlik Doğrulaması**: Ollama'nın yetkilendirme başlıklarıyla ilgili bir sorun düzeltildi, tüm endpoint'lerde güvenilir kimlik doğrulaması sağlandı.
- ⚙️ **Eksik Min_P Kaydetme**: 'min_p' parametresinin yapılandırmalara kaydedilmemesi sorunu çözüldü.
- 🛠️ **Araçlar Açıklaması**: Araçlar payload'ında araç açıklamalarını atlayan önemli bir sorun düzeltildi.

## [0.4.4] - 2024-11-22

### Eklendi

- 🌐 **Çeviri Güncellemeleri**: Katalanca, Brezilya Portekizcesi, Almanca ve Ukraynaca çevirileri yenilendi, platformun erişilebilirliğini daha da artırdı ve uluslararası kullanıcılar için deneyimi iyileştirdi.

### Düzeltildi

- 📱 **Mobil Kontroller Görünürlüğü**: Mobil kullanıcılar için yeni sohbetler sayfasında kontroller düğmesinin görüntülenmemesi sorunu çözüldü, daha küçük ekranlarda daha sorunsuz gezinme ve işlevsellik sağlandı.
- 📷 **LDAP Profil Resmi Sorunu**: Profil resimleriyle ilgili bir LDAP entegrasyon hatası düzeltildi, kullanıcılar için sorunsuz kimlik doğrulama ve güvenilir bir giriş deneyimi sağlandı.
- ⏳ **RAG Sorgu Oluşturma Sorunu**: Ekli dosyalar olmadan RAG sorgu oluşturmanın gereksiz yere gerçekleşmesi gibi önemli bir sorun giderildi, sohbet tamamlamaları sırasında hızı önemli ölçüde artırdı ve gecikmeleri azalttı.

### Değiştirildi

- ⚙️ **Eski Event Emitter Desteği**: Araçlar ve fonksiyonlardaki event emitter'lar için eski "citation" türleriyle uyumluluk yeniden tanıtıldı, kullanıcılar için daha sorunsuz iş akışları ve daha geniş araç desteği sağlandı.

## [0.4.3] - 2024-11-21

### Eklendi

- 📚 **RAG Sonuçları için Satır İçi Atıflar**: Varsayılan RAG prompt'unu kullanarak Retrieval-Augmented Generation (RAG) yanıtları için sorunsuz satır içi atıflar alın. Not: Bu özellik yalnızca yeni yüklenen dosyaları destekler, izlenebilirliği artırır ve kaynak netliği sağlar.
- 🎨 **Daha İyi Zengin Metin Giriş Desteği**: Sohbetler için daha sorunsuz ve daha güvenilir zengin metin biçimlendirmesinin keyfini çıkarın, iletişim kalitesini artırır.
- ⚡ **Daha Hızlı Model Alımı**: Daha hızlı model yüklemesi için önbellekleme optimizasyonları uygulandı, iş akışları genelinde fark edilir bir hız artışı sağlar. Daha fazla iyileştirme yolda!

### Düzeltildi

- 🔗 **Pipelines Özelliği Geri Getirildi**: Daha önce Pipelines'ın işlev görmesini engelleyen kritik bir sorun çözüldü, sorunsuz iş akışları sağlandı.
- ✏️ **Ollama Formunda Eksik Son Ek Alanı**: Ollama generate formuna eksik "suffix" alanı eklendi, özelleştirme seçeneklerini geliştiriyor.

### Değiştirildi

- 🗂️ **"Citations" (Atıflar) "Sources" (Kaynaklar) Olarak Yeniden Adlandırıldı**: Mesajlardaki "citations" alanının "sources" olarak yeniden adlandırılmasıyla netlik ve tutarlılık iyileştirildi.

## [0.4.2] - 2024-11-20

### Düzeltildi

- 📁 **Bilgi Dosyaları Görünürlük Sorunu**: Bilgi koleksiyonlarındaki tek tek dosyaların '#' ile referans verildiğinde görüntülenmesini engelleyen hata çözüldü.
- 🔗 **OpenAI Endpoint Ön Eki**: Resmi API spec'inden sapan belirli OpenAI bağlantılarının ön eklerle doğru çalışmaması sorunu düzeltildi.
- ⚔️ **Arena Model Erişim Kontrolü**: Arena model erişim kontrol ayarlarının kaydedilmemesi sorunu düzeltildi.
- 🔧 **Kullanım Yeteneği Seçici**: Model düzenleyicideki bozuk kullanım yetenekleri seçicisi düzeltildi.

## [0.4.1] - 2024-11-19

### Eklendi

- 📊 **Gelişmiş Geri Bildirim Sistemi**: Daha hassas model ince ayarı ve geri bildirim kalitesini iyileştirmek için başparmak yukarı/aşağı ile birlikte 1-10 arası ayrıntılı bir derecelendirme ölçeği tanıtıldı.
- ℹ️ **Üzerine Gelince Araç Açıklamaları**: Mesaj girişinin üzerine gelerek araç açıklamalarına kolayca erişin, araçları kullanırken daha fazla bağlamla daha sorunsuz bir iş akışı sağlar.

### Düzeltildi

- 🗑️ **Silinmiş Kullanıcıların Zarif İşlenmesi**: Silinmiş kullanıcıların çalışma alanı öğelerinin (modeller, bilgi tabanları, prompt'lar, araçlar) başarısız olmasına neden olan bir sorun çözüldü, güvenilir çalışma alanı yüklemesi sağlandı.
- 🔑 **API Anahtarı Oluşturma**: Kullanıcıların yeni API anahtarları oluşturmasını engelleyen bir sorun düzeltildi, güvenli ve sorunsuz API yönetimini geri getirdi.
- 🔗 **HTTPS Proxy Düzeltmesi**: '/api/v1/models/' endpoint'ini etkileyen HTTPS proxy sorunları düzeltildi, daha sorunsuz, kesintisiz model yönetimi sağlandı.

## [0.4.0] - 2024-11-19

### Eklendi

- 👥 **Kullanıcı Grupları**: Artık kullanıcı grupları oluşturabilir ve yönetebilirsiniz, bu da kullanıcı organizasyonunu sorunsuz hale getirir.
- 🔐 **Grup Tabanlı Erişim Kontrolü**: Kullanıcı gruplarına göre modellere, bilgi tabanlarına, prompt'lara ve araçlara ayrıntılı erişim ayarlayın, daha kontrollü ve güvenli ortamlar sağlayın.
- 🛠️ **Grup Tabanlı Kullanıcı İzinleri**: Çalışma alanı izinlerini kolayca yönetin. Kullanıcılara dosya yükleme, silme, düzenleme veya geçici sohbetler oluşturma yeteneği verin, ayrıca modeller, bilgi tabanları, prompt'lar ve araçlar oluşturma yeteneklerini tanımlayın.
- 🔑 **LDAP Desteği**: Yeni tanıtılan LDAP kimlik doğrulaması, kullanıcı yönetimine sağlam güvenlik ve ölçeklenebilirlik katıyor.
- 🌐 **Gelişmiş OpenAI Uyumlu Bağlantılar**: Model ID çakışmalarını önlemek için ön ek ID desteği eklendi, '/models' endpoint desteği olmayan API'ler için açık model ID desteği eklendi, özel kurulumlarla sorunsuz çalışmayı sağlıyor.
- 🔐 **Ollama API Anahtar Desteği**: Artık proxy'lerin arkasına ayarlandığında Ollama için kimlik bilgilerini yönetin, birden çok Ollama örneği arasında doğru ayrım için ön ek ID'si kullanma seçeneği dahil.
- 🔄 **Bağlantı Etkinleştirme/Devre Dışı Bırakma Geçiş Anahtarı**: Gerektiğinde tek tek OpenAI ve Ollama bağlantılarını kolayca etkinleştirin veya devre dışı bırakın.
- 🎨 **Yeniden Tasarlanmış Model Çalışma Alanı**: Kullanıcılar ve gruplar arasında modelleri yönetmek için kullanılabilirliği iyileştirmek amacıyla yeni tasarlanmış.
- 🎨 **Yeniden Tasarlanmış Prompt Çalışma Alanı**: Prompt'ları rahatça düzenlemek ve yönetmek için yeni bir UI.
- 🧩 **Sıralanmış Fonksiyonlar Çalışma Alanı**: Fonksiyonlar artık yönetimini kolaylaştırmak için otomatik olarak türe göre (Eylem, Filtre, Boru) kategorize ediliyor.
- 💻 **Yeniden Tasarlanmış İşbirlikçi Çalışma Alanı**: Modeller, bilgi tabanları, prompt'lar veya araçlara katkıda bulunan birden fazla kullanıcı için gelişmiş destek, işbirliğini iyileştiriyor.
- 🔧 **Model Düzenleyicide Otomatik Seçilen Araçlar**: Model düzenleyici aracılığıyla etkinleştirilen araçlar artık otomatik olarak seçilirken, daha önce sadece kullanıcılara aracı etkinleştirme seçeneği sunuluyordu, bu da manuel adımları azaltır ve verimliliği artırır.
- 🔔 **Web Araması ve Araçlar Göstergesi**: Web araması veya araçlar aktif olduğunda açık bir gösterge görüntülenir, kafa karışıklığını azaltır.
- 🔑 **API Anahtarı Kimlik Doğrulamasını Aç/Kapat**: Open WebUI için API anahtarı kimlik doğrulama seçeneğini kolayca etkinleştirerek veya devre dışı bırakarak güvenliği artırın.
- 🗂️ **Ajan Tabanlı Alım**: Alım öncesinde en iyi sorguları belirlemek için sohbet geçmişini akıllıca ön işlemden geçirerek RAG doğruluğunu iyileştirin.
- 📁 **Büyük Metni Dosya Olarak Seçeneği**: İsteğe bağlı olarak büyük yapıştırılan metni bir dosya yüklemesine dönüştürün, sohbet arayüzünü daha temiz tutar.
- 🗂️ **Modeller için Atıfları Aç/Kapat**: Model düzenleyicide atıfları devre dışı bırakma yeteneği eklendi.
- 🔍 **Kullanıcı Ayarları Araması**: Ayarlar alanlarını hızlıca arayın, kullanım kolaylığını ve gezinmeyi iyileştirir.
- 🗣️ **Deneysel SpeechT5 TTS**: Geliştirilmiş text-to-speech yetenekleri için yerel SpeechT5 desteği eklendi.
- 🔄 **Modeller için Birleşik Sıfırlama**: Yönetici Ayarları'ndan tüm modelleri sıfırlamak ve kaldırmak için tek tıklamayla bir seçenek eklendi.
- 🛠️ **İlk Kurulum Sihirbazı**: Kurulum süreci artık, kullanıcıların ilk kurulum sırasında bir yönetici hesabı oluşturduklarını açıkça bildiriyor, netlik sağlıyor. Daha önce, kullanıcılar bu ayrım olmaksızın doğrudan giriş sayfasına geliyordu.
- 🌐 **Gelişmiş Çeviriler**: Ukraynaca, Norveççe ve Brezilya Portekizcesi dahil olmak üzere çeşitli dil çevirileri, platform genelinde daha yerelleştirilmiş ve kapsayıcı bir arayüz için iyileştirildi.

### Düzeltildi

- 🎥 **YouTube Video Ekleri**: YouTube videolarının dosya olarak doğru şekilde yüklenmesini ve eklenmesini engelleyen sorunlar düzeltildi.
- 🔄 **Paylaşılan Sohbet Güncellemesi**: Paylaşılan sohbetlerin güncellenmemesi sorunları düzeltildi, işbirliği tutarlılığı iyileştirildi.
- 🔍 **DuckDuckGo Hız Limiti Düzeltmesi**: DuckDuckGo arama entegrasyonuyla ilgili sorunlar giderildi, hız limitleri içinde çalışırken arama kararlılığı ve performansı artırıldı.
- 🧾 **Atıfların Alaka Düzeyi Düzeltmesi**: Atıflar için alaka düzeyi yüzdesi hesaplaması ayarlandı, böylece Open WebUI, RAG'deki alınan bir belgenin doğruluğunu doğru bir şekilde yansıtır ve kullanıcılara kaynaklar hakkında daha net içgörüler sağlar.
- 🔑 **Jina Arama API Anahtarı Gereksinimi**: Jina Arama için bir API anahtarı girme seçeneği eklendi, anahtarlar artık zorunlu olduğundan sorunsuz işlevsellik sağlandı.

### Değiştirildi

- 🛠️ **Fonksiyonlar Yönetici Paneline Taşındı**: Fonksiyonlar gelişmiş eklentiler olarak çalıştığı için artık çalışma alanı yerine Yönetici Panelinden erişilebilir.
- 🛠️ **Ollama Bağlantılarını Yönet**: Yönetici Ayarları'ndaki "Modeller" bölümü, Yönetici Ayarları > "Bağlantılar" > Ollama Bağlantıları'na taşındı. Artık Ollama örneklerini "Bağlantılar"daki özel bir "Ollama'yı Yönet" modalı aracılığıyla yönetebilir, Ollama modellerinin kurulumunu ve yapılandırmasını kolaylaştırır.
- 📊 **Yönetici Ayarlarındaki Temel Modeller**: Yöneticiler artık "Modeller" Yönetici ayarındaki tüm temel modelleri, bağlantıları veya fonksiyonları bulabilirler. Genel model erişilebilirliği buradan etkinleştirilebilir veya devre dışı bırakılabilir. Modeller varsayılan olarak özeldir ve kullanıcı erişimi için açıkça izin atanması gerekir.
- 📌 **Yeni Sohbetler için Yapışkan Model Seçimi**: Önceki bir sohbetten seçilen model, yeni bir sohbet oluşturulduğunda devam eder. Yeni sohbet sayfasından tekrar "Yeni Sohbet"e tıklarsanız, varsayılan modelinize geri döner.
- 🎨 **Tasarım Yeniden Yapılandırması**: Genel tasarım iyileştirmeleri platform genelinde yapıldı, daha tutarlı ve şık bir kullanıcı deneyimi sağlandı.

### Kaldırıldı

- 📂 **Model Listesi Yeniden Sıralama**: Geçici olarak kaldırıldı ve gelecek kullanıcı grubu ayarları iyileştirmelerinde yeniden tanıtılacak.
- ⚙️ **Varsayılan Model Ayarı**: Kullanıcılar için varsayılan model ayarlama yeteneği kaldırıldı, gelecekte kullanıcı grubu ayarlarıyla yeniden tanıtılacak.

## [0.3.35] - 2024-10-26

### Eklendi

- **🌐 Çeviri Güncellemesi**: SearchInput ve CreateCollection bileşenlerinde çeviri etiketleri eklendi ve Brezilya Portekizcesi çevirisi (pt-BR) güncellendi.
- **📁 Sağlam Dosya İşleme**: Sohbet için geliştirilmiş dosya girişi işleme. İçerik çıkarımı başarısız olursa veya boşsa, kullanıcılar artık net bir uyarı alacak, sessiz hataları önleyecek ve yüklemelerinizle ne olduğunu her zaman bilmenizi sağlayacak.
- **🌍 Yeni Dil Desteği**: Macarca çeviriler tanıtıldı ve Fransızca çeviriler güncellendi, platformun daha küresel bir kullanıcı tabanı için dil erişilebilirliğini genişletti.

### Düzeltildi

- 📚 **Bilgi Tabanı Yükleme Sorunu**: Bilgi Tabanının yüklenmemesiyle ilgili kritik bir hata çözüldü, depolanan belgelerinize sorunsuz erişim sağlandı ve RAG ile geliştirilmiş iş akışlarında bilgi alımı iyileştirildi.
- 🛠️ **Araç Parametreleri Sorunu**: Gerekli parametreler eksik olduğunda araçların doğru çalışmaması hatası düzeltildi, güvenilir araç performansı ve daha verimli görev tamamlamaları sağlandı.
- 🔗 **Çok Modelli Sohbetlerde Birleştirilmiş Yanıt Kaybı**: Takip sorgularından sonra çok modelli sohbet iş akışlarında yanıtların silinmesi sorunu giderildi, tutarlılık iyileştirildi ve modeller arasında daha sorunsuz etkileşimler sağlandı.

## [0.3.34] - 2024-10-26

### Eklendi

- 🔧 **Geri Bildirim Dışa Aktarma Geliştirmeleri**: Geri bildirim geçmişi verileri artık JSON'a aktarılabilir, RLHF işlemede sorunsuz entegrasyon ve daha fazla analiz sağlar.
- 🗂️ **Embedding Model Tembel Yükleme**: Liderlik tablosu reranking için arama işlevselliği artık daha verimli, çünkü embedding modelleri yalnızca gerektiğinde tembel yükleniyor, performansı optimize ediyor.
- 🎨 **Zengin Metin Girişi Geçiş Anahtarı**: Kullanıcılar, daha basit metin girişini tercih ediyorlarsa sohbet için eski textarea girişine geri dönebilirler, ancak zengin metin hala kullanımdan kaldırılana kadar varsayılan ayardır.
- 🛠️ **Geliştirilmiş Araç Çağırma Mekanizması**: Araçları ayrıştırma ve çağırma yöntemi geliştirildi, araç fonksiyon çağrılarının güvenilirliğini ve sağlamlığını artırdı.
- 🌐 **Küreselleşme Geliştirmeleri**: Uluslararasılaşma (i18n) desteğine güncellemeler, çoklu dil uyumluluğunu ve doğruluğunu daha da iyileştiriyor.

### Düzeltildi

- 🖥️ **Firefox için Klasör Yeniden Adlandırma Düzeltmesi**: Kullanıcıların Firefox'ta enter tuşuna basarak klasörleri yeniden adlandıramaması gibi sürekli bir sorun giderildi, artık tarayıcılar arasında sorunsuz klasör yönetimi sağlanıyor.
- 🔠 **Tiktoken Model Metin Bölücü Sorunu**: Tiktoken metin bölücünün Docker kurulumlarında çalışmaması sorunu çözüldü, token'lı metin düzenleme için tam işlevsellik geri getirildi.
- 💼 **S3 Dosya Yükleme Sorunu**: S3 dosya yüklemelerini etkileyen bir sorun düzeltildi, dosyalarını bulut depolamada depolayanlar için sorunsuz işlemler sağlandı.
- 🔒 **Strict-Transport-Security Çökmesi**: Strict-Transport-Security (HSTS) başlığı ayarlanırken oluşan bir çökme düzeltildi, kararlılık ve güvenlik geliştirmeleri iyileştirildi.
- 🚫 **OIDC Boolean Erişim Düzeltmesi**: OIDC girişleri sırasında boolean değerlere doğru erişilememesi sorunu giderildi, giriş güvenilirliği sağlandı.
- ⚙️ **Zengin Metin Yapıştırma Davranışı**: Çeşitli içerik türlerini yapıştırırken daha sorunsuz ve sezgisel hale getirmek için zengin metin girişinde yapıştırma davranışı iyileştirildi.
- 🔨 **Arena Düzeltmesi için Model Dışlama**: Modelleri arenadan düzgün bir şekilde dışlamayan filtre fonksiyonu düzeltildi, model yönetimini iyileştirdi.
- 🏷️ **"Etiketler Oluşturma Prompt'u" Düzeltmesi**: Özel "etiketler oluşturma prompt'larının" düzgün bir şekilde kaydedilmesini engelleyen bir sorun giderildi, özel prompt'ların sorunsuz çalışması sağlandı.

## [0.3.33] - 2024-10-24

### Eklendi

- 🏆 **Değerlendirme Liderlik Tablosu**: Puanlarınızın Elo sistemine dayalı gerçek zamanlı bir sıralamaya katkıda bulunduğu yeni bir liderlik tablosu sistemi aracılığıyla performansınızı kolayca takip edin. Liderlik tablosunda puanlarınızın sayılması için kardeş yanıtlar (yeniden oluşturmalar, birçok model sohbeti) gereklidir. Ek olarak, geri bildirim geçmişinizi paylaşmayı ve topluluk genelindeki liderlik tablosunun bir parçası olmayı seçebilirsiniz. Algoritmayı iyileştirdikçe daha fazla iyileştirme bekleyin—en iyi topluluk liderlik tablosunu oluşturmamıza yardımcı olun!
- ⚔️ **Arena Model Değerlendirmesi**: İhtiyaçlarınız için en iyi modeli tam olarak belirlemek için Yönetici Ayarları > Değerlendirme'den modellerin kör A/B testini doğrudan etkinleştirin.
- 🎯 **Konu Tabanlı Liderlik Tablosu**: Deneysel konu tabanlı reranking ile daha doğru sıralamaları keşfedin, bu da liderlik tablosu sıralamalarını geri bildirimdeki etiket benzerliğine göre ayarlar. Belirli konulara dayalı daha ilgili içgörüler edinin!
- 📁 **Sohbetler için Klasör Desteği**: Sohbetlerinizi klasörler halinde gruplandırarak daha iyi düzenleyin. Sohbetleri klasörler arasında sürükleyip bırakın ve kolay paylaşım veya analiz için sorunsuz bir şekilde dışa aktarın.
- 📤 **Sürükle ve Bırak ile Kolay Sohbet İçe Aktarma**: Sohbet dışa aktarımlarını (JSON) doğrudan kenar çubuğuna sürükleyip bırakarak çalışma alanınıza aktarın—basitleştirilmiş, verimli ve sezgisel!
- 📚 **Gelişmiş Bilgi Koleksiyonu**: Artık bir bilgi koleksiyonundan tek tek dosyalara referans verebilirsiniz—daha hassas Retrieval-Augmented Generations (RAG) sorguları ve belge analizi için idealdir.
- 🏷️ **Gelişmiş Etiketleme Sistemi**: Etiketler artık daha az yer kaplıyor! Arayüzü karmaşıklaştırmadan konuşmalarınızı daha etkili bir şekilde yönetmek, aramak ve organize etmek için yeni 'tag:' sorgu sistemini kullanın.
- 🧠 **Sohbetler için Otomatik Etiketleme**: Konuşmalarınız, otomatik oluşturulan başlıkların verimliliğini yansıtarak daha iyi organizasyon için otomatik olarak etiketlenir.
- 🔍 **Backend Sohbet Sorgu Sistemi**: Sohbet filtrelemesi artık daha verimli, arama performansını ve doğruluğunu iyileştirerek tarayıcınız yerine backend aracılığıyla işleniyor.
- 🎮 **Yenilenmiş Playground**: Modellerinizin ve araçlarınızın daha sorunsuz testi, ince ayarı ve denemesi için yenilenmiş ve optimize edilmiş Playground deneyimini yaşayın.
- 🧩 **Token Tabanlı Metin Bölücü**: Metinlerin nasıl işlendiği üzerinde daha hassas kontrol sağlayan token tabanlı metin bölme (tiktoken) tanıtıldı. Daha önce sadece karakter tabanlı bölme mevcuttu.
- 🔢 **Ollama Toplu Embeddings**: Ollama embedding modelleriyle geliştirilmiş verimlilik ve performans için yeni toplu embedding desteğinden yararlanın.
- 🔍 **Gelişmiş Metin İçeriği Ekleme Modalı**: Bilgi çalışma alanımızdan yükseltilmiş bir giriş modalı ile bilgi içeriği ekleme ve düzenleme için daha temiz, daha sezgisel bir iş akışının keyfini çıkarın.
- 🖋️ **Sohbetler için Zengin Metin Girişi**: Zengin metin biçimlendirme desteği ile sohbet girişlerinizi daha dinamik hale getirin. Konuşmalarınız artık çok daha şık ve profesyonel hale geldi.
- ⚡ **Daha Hızlı Whisper Model Yapılandırılabilirliği**: Yerel daha hızlı whisper modelinizi doğrudan WebUI'den özelleştirin.
- ☁️ **Deneysel S3 Desteği**: S3 desteği ile durum bilgisi olmayan WebUI örneklerini etkinleştirin, ölçeklenebilirliği önemli ölçüde artırın ve ağır iş yüklerini dengeleyin.
- 🔕 **Güncelleme Toast'unu Devre Dışı Bırak**: Artık çalışma alanınızı daha da kolaylaştırabilirsiniz—daha odaklanmış bir deneyim için güncelleme bildirimlerini devre dışı bırakmayı seçin.
- 🌟 **RAG Atıf Alaka Düzeyi Yüzdesi**: RAG sonuçlarında alaka düzeyi yüzdelerinin eklenmesiyle atıf doğruluğunu kolayca değerlendirin.
- ⚙️ **Mermaid Kopyalama Düğmesi**: Mermaid diyagramları artık kullanışlı bir kopyalama düğmesiyle geliyor, diyagram içeriğini doğrudan iş akışınızda çıkarmayı ve kullanmayı basitleştiriyor.
- 🎨 **UI Yeniden Tasarımı**: Gezinmeyi daha sorunsuz hale getirecek, odağınızı önemli olana yönlendirecek ve modern bir görünüm sağlayacak büyük arayüz yeniden tasarımı.

### Düzeltildi

- 🎙️ **Sesli Not Mikrofon Durdurma Sorunu**: Sesli not kaydını bitirdikten sonra mikrofonun aktif kalması sorunu düzeltildi, ses iş akışınızın sorunsuz çalışmasını sağlandı.

### Kaldırıldı

- 👋 **Güçlü Kenar Çubuğu Etiketleri**: Kenar çubuğu etiket dağınıklığı gitti. Daha şık, daha çevik bir arayüz için etiket düğmelerini daha etkili sorgu tabanlı etiket filtrelemesine kaydırdık.

## [0.3.32] - 2024-10-06

### Eklendi

- 🔢 **Çalışma Alanı Geliştirmeleri**: Çalışma alanında modeller, prompt'lar, araçlar ve fonksiyonlar için bir gösterge sayacı eklendi, net bir genel bakış ve daha kolay yönetim sağlandı.

### Düzeltildi

- 🖥️ **Web ve YouTube Ek Düzeltmesi**: Web bağlantıları ve YouTube videolarını eklemenin arızalı olması sorunu çözüldü, sohbetlerde sorunsuz entegrasyon ve görüntüleme sağlandı.
- 📞 **Açılış Sayfasında Çağrı Modu Aktivasyonu**: Çağrı modunun açılış sayfasından çalışmaması hatası düzeltildi.

### Değiştirildi

- 🔄 **URL Parametresi İyileştirmesi**: Daha sezgisel ve tutarlı kullanıcı deneyimi için 'tool_ids' URL parametresi 'tools' veya 'tool-ids' olarak güncellendi.
- 🎨 **Kayan Butonlar Stil Güncellemesi**: Kayan butonların stili yeniden düzenlendi, sağ tarafta yeterli yer olmadığında akıllıca sol tarafa ayarlanarak arayüz kullanılabilirliği ve estetiği iyileştirildi.
- 🔧 **Kayan Butonlar için Gelişmiş Erişilebilirlik**: Kayan butonları 'Esc' tuşuyla kapatma yeteneği uygulandı, klavye aracılığıyla gezinen kullanıcılar için iş akışını daha sorunsuz ve verimli hale getirdi.
- 🖇️ **Güncellenmiş Bilgi URL'si**: Bilgi URL'leri artık kullanıcıları sürüme özgü bir URL yerine genel bir sürüm sayfasına yönlendiriyor, tüm ilgili ayrıntılara tek bir yerden erişim sağlıyor.
- 📦 **Kütüphane Bağımlılıkları Güncellemesi**: pip kurulumları için uyumluluk ve performans optimizasyonu sağlamak amacıyla bağımlılıklar yükseltildi.

## [0.3.31] - 2024-10-06

### Eklendi

- 📚 **Bilgi Özelliği**: Yeniden tasarlanan belgeler özelliği, gelişmiş organizasyon için daha iyi bir UI ile daha performanslı; Retrieval-Augmented Generation (RAG) için kolaylaştırılmış API entegrasyonu içerir. Ayrıntılı dokümantasyon yakında geliyor: https://docs.openwebui.com/
- 🌐 **Yeni Açılış Sayfası**: Yeni tasarlanmış açılış sayfası; kişiselleştirilmiş bir deneyim için Ayarlar > Arayüz'den yeni UI ve klasik sohbet UI'si arasında geçiş yapın.
- 📁 **Tam Belge Alımı Modu**: Dosya öğesine tıklayarak tam belge alımı veya geleneksel snippet'ler arasında geçiş yapın. Bu mod, belge yeteneklerini geliştirir ve RAG yerine tüm içeriği kullanarak özetleme gibi kapsamlı görevleri destekler.
- 📄 **Çıkarılan Dosya İçeriği Görüntüsü**: Dosya öğesine tıklayarak çıkarılan içeriği doğrudan görüntüleyin, dosya analizini basitleştirin.
- 🎨 **Artifacts Özelliği**: Web içeriğini ve SVG'leri doğrudan arayüzde oluşturun, hızlı yinelemeleri ve canlı değişiklikleri destekleyin.
- 🖊️ **Düzenlenebilir Kod Blokları**: Süper güçlendirilmiş kod blokları, LLM yanıtında doğrudan canlı düzenlemeye izin verir, artifact'ler tarafından canlı yeniden yüklemeler desteklenir.
- 🔧 **Kod Bloğu Geliştirmeleri**: Kaydırma yapmadan daha kolay kod kopyalamayı sağlamak için kod bloklarına kayan bir kopyalama düğmesi eklendi.
- 🔍 **SVG Pan/Zoom**: Mermaid diyagramları dahil olmak üzere SVG görüntülerle yeni pan ve zoom yetenekleri aracılığıyla geliştirilmiş etkileşim.
- 🔍 **Metin Seçimi Hızlı Eylemleri**: LLM yanıtlarında metin vurgulandığında yeni kayan düğmeler belirir, "Soru Sor" veya "Açıkla" gibi daha derin etkileşimler sunar.
- 🗃️ **Veritabanı Havuzu Yapılandırması**: Ölçeklenebilir kullanıcı büyümesini desteklemek için geliştirilmiş veritabanı işleme.
- 🔊 **Deneysel Ses Sıkıştırma**: OpenAI'nin speech-to-text işleme için 25MB sınırını aşmak amacıyla ses dosyalarını sıkıştırın.
- 🔍 **Sorgu Embedding'i**: Sorgu embedding'ini tekrarlamayarak sistem performansını artırmak için embedding davranışı ayarlandı.
- 💾 **Tembel Yükleme Optimizasyonları**: İlk bellek kullanımını en aza indirmek ve performansı artırmak için büyük bağımlılıkların tembel yüklemesi uygulandı.
- 🍏 **Apple Touch İkon Desteği**: Apple mobil cihazlarda web yer imleri için ikonların görüntülenmesini optimize eder.
- 🔽 **Genişletilebilir İçerik Markdown Desteği**: Markdown'da genişletilebilir içerik bölümleri oluşturmak için 'details', 'summary' etiket desteği tanıtıldı, daha temiz, düzenli dokümantasyon ve etkileşimli içerik görüntülemesi sağlar.

### Düzeltildi

- 🔘 **Eylem Düğmesi Sorunu**: Eylem düğmelerinin çalışmaması hatası çözüldü, UI güvenilirliği artırıldı.
- 🔄 **Çok Modelli Sohbet Döngüsü**: Çok modelli sohbet ortamlarında sonsuz döngü sorunu düzeltildi, daha sorunsuz sohbet işlemleri sağlandı.
- 📄 **Sohbet PDF/TXT Dışa Aktarma Sorunu**: Sohbet loglarını PDF ve TXT formatlarına dışa aktarmayla ilgili sorunlar çözüldü.
- 🔊 **Text-to-Speech'e Çağrı Sorunları**: Ses etkileşimlerini iyileştirmek için text-to-speech fonksiyonlarındaki sorunlar giderildi.

### Değiştirildi

- ⚙️ **Endpoint Yeniden Adlandırma**: Daha net fonksiyon açıklaması için 'rag' endpoint'leri 'retrieval' olarak yeniden adlandırıldı.
- 🎨 **Stil ve Arayüz Güncellemeleri**: Görsel çekiciliği ve kullanıcı etkileşimini artırmak için platform genelinde çok sayıda iyileştirme.

### Kaldırıldı

- 🗑️ **Eskimiş 'DOCS_DIR'**: Eski 'docs_dir' değişkeni, daha entegre bir deneyim için daha doğrudan dosya yönetimi çözümleriyle birlikte kaldırıldı, doğrudan dosya dizini senkronizasyonu ve API yüklemeleri ile.

## [0.3.30] - 2024-09-26

### Düzeltildi

- 🍞 **Mevcut Güncelleme Toast'ı Kapatma**: Güncelleme mevcut bildirimi kapatıldıktan sonra 24 saat boyunca tekrar görünmemesini sağlayarak kullanıcı deneyimi geliştirildi.
- 📋 **Ollama /embed Form Verileri**: /embed form verilerindeki entegrasyon yanlışlıkları, Ollama'nın spesifikasyonlarıyla tam olarak eşleşmesini sağlamak için ayarlandı.
- 🔧 **O1 Maksimum Tamamlama Tokenları Sorunu**: Sorunsuz çalışma sağlamak için OpenAI'nin o1 modellerinin max_completion_tokens parametresiyle ilgili uyumluluk sorunları çözüldü.
- 🔄 **Pip Kurulum Veritabanı Sorunu**: Pip kurulumları sırasında veritabanı değişikliklerinin geri alınması ve sohbet loglarının kaydedilmemesi gibi kritik bir sorun düzeltildi, sohbet işlemlerinde veri kalıcılığı ve güvenilirliği sağlandı.
- 🏷️ **Sohbet Yeniden Adlandırma Sekmesi Güncellemesi**: Bir sohbet yeniden adlandırıldığında web tarayıcısının sekme başlığını eşzamanlı olarak değiştiren işlevsellik düzeltildi, sekme başlıkları tutarlı tutuldu.

## [0.3.29] - 2023-09-25

### Düzeltildi

- 🔧 **KaTeX Oluşturma İyileştirmesi**: Karmaşık matematiksel gösterimlerin görüntülenmesini iyileştirmek için KaTeX oluşturmadaki belirli uç durumlar çözüldü.
- 📞 **'Call' URL Parametresi Düzeltmesi**: URL tetikleyicileri aracılığıyla sesli aramaların güvenilir bir şekilde etkinleştirilmesini sağlayan 'call' URL arama parametresi için işlevsellik düzeltildi.
- 🔄 **Yapılandırma Sıfırlama Düzeltmesi**: Ayarların her başlangıçta doğru bir şekilde varsayılana dönmesini sağlamak için RESET_CONFIG_ON_START düzeltildi, yapılandırma yönetiminde güvenilirlik iyileştirildi.
- 🌍 **Filtre Çıkış Hook Düzeltmesi**: Tüm filtre fonksiyonlarının amaçlandığı gibi çalışmasını sağlayarak filtre çıkış hook'undaki sorunlar giderildi.

## [0.3.28] - 2024-09-24

### Düzeltildi

- 🔍 **Web Arama İşlevselliği**: Web arama seçeneğinin doğru çalışmaması sorunu düzeltildi.

## [0.3.27] - 2024-09-24

### Düzeltildi

- 🔄 **Periyodik Temizleme Hatası Çözüldü**: 'periodic_usage_pool_cleanup' coroutine ile ilgili kritik bir RuntimeError düzeltildi, pip kurulumu sonrası sorunsuz ve verimli performans sağlandı, sürüm 0.3.26'dan kalma bir sorun düzeltildi.
- 📊 **Gelişmiş LaTeX Oluşturma**: LaTeX içeriği için geliştirilmiş oluşturma, belgelerde ve matematiksel modellerde netliği ve görsel sunumu artırıyor.

## [0.3.26] - 2024-09-24

### Düzeltildi

- 🔄 **Olay Döngüsü Hatası Çözünürlüğü**: Eksik bir çalışan olay döngüsünün pip kurulumlarıyla 'periodic_usage_pool_cleanup'ın başarısız olmasına neden olan kritik bir hata giderildi. Bu düzeltme, genel sistem kararlılığını artırarak daha sorunsuz ve daha güvenilir güncellemeler ve kurulumlar sağlar.

## [0.3.25] - 2024-09-24

### Düzeltildi

- 🖼️ **Görüntü Oluşturma İşlevselliği**: Görüntü oluşturmanın işlevsiz olduğu bir sorun çözüldü, görsel içerik oluşturma için tam yetenek geri getirildi.
- ⚖️ **Yanıt Hızı Düzeltmeleri**: Yanıt hızlarının çalışmaması sorunu giderildi, güvenilir geri bildirim mekanizmalarının çalışır durumda olduğu sağlandı.

## [0.3.24] - 2024-09-24

### Eklendi

- **🚀 Oluşturma Optimizasyonu**: Mesaj oluşturma performansı önemli ölçüde iyileştirildi, kullanıcı deneyimi ve webui duyarlılığı artırıldı.
- **💖 Sohbet Genel Bakışında Favori Yanıt Özelliği**: Kullanıcılar artık sohbet genel bakışından yanıtları favori olarak işaretleyebilir, tercih edilen yanıtların kolayca alınmasını ve düzenlenmesini kolaylaştırır.
- **💬 Kısayolla Mesaj Çiftleri Oluşturma**: Cmd/Ctrl+Shift+Enter kullanarak yeni mesaj çiftleri oluşturma uygulandı, konuşma düzenlemesini daha hızlı ve daha sezgisel hale getiriyor.
- **🌍 Genişletilmiş Kullanıcı Prompt Değişkenleri**: Sistem prompt değişkenleriyle eşleşmesi için kullanıcı prompt'larına hafta içi, zaman dilimi ve dil bilgisi değişkenleri eklendi.
- 🎵 **Gelişmiş Ses Desteği**: Artık 'audio/x-m4a' dosyaları için destek içerir, platform içinde ses içeriğiyle uyumluluğu genişletiyor.
- 🔏 **Model URL Arama Parametresi**: URL parametreleri aracılığıyla doğrudan bir model seçme yeteneği eklendi, gezinmeyi ve model erişimini kolaylaştırıyor.
- 📄 **Gelişmiş PDF Atıfları**: PDF atıfları artık ilgili sayfada açılır, referans kontrollerini ve belge işlemeyi kolaylaştırır.
- 🔧 **Socketlerde Redis Kullanımı**: Websocket uygulamasını Redis'i tam olarak destekleyecek şekilde geliştirildi, ölçeklenebilir yük dengeleme için uygun durum bilgisi olmayan örnekleri etkinleştiriyor.
- 🌍 **Bireysel Model Yanıtlarını Akışa Alma**: Belirli modellerin bireysel akış ayarlarına sahip olmasına izin verir, performansı ve özelleştirmeyi artırır.
- 🕒 **Ollama Modelleri için Model Karma ve Son Değiştirilme Zaman Damgasını Görüntüle**: Modeller çalışma alanında gelişmiş izleme için kritik model ayrıntılarını doğrudan sağlar.
- ❗ **Yöneticiler için Güncelleme Bilgisi Bildirimi**: Yöneticilerin oturum açar açmaz anında güncellemeler almasını sağlar, en son değişiklikler ve sistem durumları hakkında bilgilendirir.

### Düzeltildi

- 🗑️ **Windows'ta Geçici Dosya İşleme**: Başka bir işlem tarafından kullanılan geçici bir dosyaya erişirken oluşan hatalara neden olan bir sorun düzeltildi, Araçlar ve Fonksiyonlar artık beklendiği gibi çalışmalıdır.
- 🔓 **Kimlik Doğrulama Geçiş Anahtarı Sorunu**: 'WEBUI_AUTH=False' ayarının kimlik doğrulamayı uygun şekilde devre dışı bırakmaması arızası çözüldü, kullanıcı deneyiminin ve sistem güvenlik ayarlarının yapılandırıldığı gibi çalışmasını sağlar.
- 🔧 **Birçok Model Sohbeti için Kopyala Olarak Kaydet Sorunu**: Kullanıcıların birçok model sohbetinde mesajları kopya olarak kaydetmesini engelleyen bir hata çözüldü.
- 🔒 **Mobil Üzerinde Kenar Çubuğu Kapatma**: Mobil kenar çubuğunun menü etkileşiminden sonra açık kalması sorunu çözüldü, kullanıcı arayüzü duyarlılığını ve konforunu iyileştirdi.
- 🛡️ **Araç İpucu XSS Güvenlik Açığı**: Araç ipuçlarındaki bir çapraz site betikleme (XSS) sorunu çözüldü, kullanıcı etkileşimleri sırasında geliştirilmiş güvenlik ve veri bütünlüğü sağlandı.

### Değiştirildi

- ↩️ **Eski Arayüz Akış Yanıt Ayarları Eski Haline Getirildi**: Arayüz ayarlarını kolaylaştırmak ve kullanıcı netliğini artırmak için gelişmiş parametrelere taşındı.
- ⚙️ **'speedRate' 'playbackRate' olarak yeniden adlandırıldı**: Terminolojiyi standartlaştırır, medya ayarlarında kullanılabilirliği ve anlaşmayı iyileştirir.

## [0.3.23] - 2024-09-21

### Eklendi

- 🚀 **WebSocket Redis Desteği**: Çoklu örnek kurulumları için geliştirilmiş yük dengeleme yetenekleri, WebUI'de daha iyi performans ve güvenilirlik sağlar.
- 🔧 **Ayarlanabilir Sohbet Kontrolleri**: Her sohbet oturumu için parametreleri kolayca ayarlayabilen genişliği ayarlanabilir sohbet kontrolleri tanıtıldı, etkileşimleriniz üzerinde daha hassas kontrol sunar.
- 🌎 **i18n Güncellemeleri**: Çince çeviriler iyileştirildi ve güncellendi.

### Düzeltildi

- 🌐 **Görev Modeli Kaldırma Sorunu**: Görev işlemini Ollama /api/chat endpoint'ini kullanacak şekilde değiştirildi, OpenAI uyumlu endpoint yerine, modellerin özel parametrelerle yüklü ve hazır kalmasını sağlayarak görev yürütmedeki gecikmeleri en aza indirdi.
- 📝 **OpenAI Uyumlu API'ler için Başlık Oluşturma Düzeltmesi**: Başlıkların oluşturulmasını engelleyen bir sorun çözüldü, birden fazla API sağlayıcısı kullanırken tutarlılık ve güvenilirlik artırıldı.
- 🗃️ **RAG Tekrarlanan Koleksiyon Sorunu**: Aynı yüklenen dosyanın tekrar tekrar işlenmesine neden olan bir hata düzeltildi. Artık gereksiz tekrarlamaları önlemek için dizine eklenmiş dosyalar kullanılıyor, kaynak kullanımını optimize ediyor.
- 🖼️ **Görüntü Oluşturma Geliştirmesi**: OpenAI görüntü oluşturma endpoint'i asenkron olacak şekilde yeniden düzenlendi, işleme sırasında WebUI'nin yanıt vermemesi önlenerek kullanıcı deneyimi artırıldı.
- 🔓 **Authlib Sürümünü Düşür**: OAuth işlevselliğiyle ilgili sorunları gidermek ve çözmek için Authlib sürümü 1.3.1'e geri alındı.

### Değiştirildi

- 🔍 **Geliştirilmiş Mesaj Etkileşimi**: Daha kolay odak yönlendirmesine basit bir tıklama ile izin vermek için mesaj düğüm arayüzü geliştirildi, kullanıcı etkileşimini kolaylaştırıyor.
- ✨ **Stil Yeniden Yapılandırması**: Daha temiz, daha modern bir görünüm için WebUI stili güncellendi, platform genelinde kullanıcı deneyimi artırıldı.

## [0.3.22] - 2024-09-19

### Eklendi

- ⭐ **Sohbet Genel Bakışı**: Konuşma akışlarının daha iyi görselleştirilmesi için düğüm tabanlı etkileşimli bir mesaj diyagramı tanıtıldı.
- 🔗 **Çoklu Vektör DB Desteği**: Artık yeni eklenen Milvus desteği de dahil olmak üzere çoklu vektör veritabanlarını destekliyor. Ek veritabanı desteği için topluluk katkıları şiddetle teşvik edilir!
- 📡 **Deneysel Akışsız Sohbet Tamamlama**: Akış desteği olmayan OpenAI o1 modellerinin kullanımına izin veren deneysel özellik, daha çok yönlü model dağıtımı sağlıyor.
- 🔍 **Deneysel Colbert-AI Reranker Entegrasyonu**: Arama alaka düzeyini ve doğruluğunu artırmak için "jinaai/jina-colbert-v2" bir reranker olarak desteklendi. Not: Düşük özellikli bilgisayarlarda hiç çalışmayabilir.
- 🕸️ **ENABLE_WEBSOCKET_SUPPORT**: Websocket yükseltmelerini yok saymak için ortam değişkeni eklendi, websocket sorunları olan platformlarda bağlantıları stabilize ediyor.
- 🔊 **Azure Speech Service Entegrasyonu**: Text-to-Speech (TTS) için Azure Speech hizmetleri desteği eklendi.
- 🎚️ **Özelleştirilebilir Çalma Hızı**: Çağrı modu ayarlarında çalma hızı kontrolü artık mevcut, kullanıcıların ses çalma hızını tercihlerine göre ayarlamalarına olanak tanıyor.
- 🧠 **Gelişmiş Hata Mesajlaşması**: Sohbet tamamlama sorunları sırasında sistem artık kullanıcılara doğrudan yararlı hata mesajları gösteriyor.
- 📂 **Modeli Şeffaf PNG Olarak Kaydet**: Model profil resimleri artık PNG olarak kaydediliyor, şeffaflığı destekliyor ve görsel entegrasyonu iyileştiriyor.
- 📱 **iPhone Uyumluluk Ayarları**: iPhone gezinme çubuğunu barındırmak için dolgu eklendi, bu cihazlarda UI görüntüsünü iyileştiriyor.
- 🔗 **Güvenli Yanıt Başlıkları**: Web uygulaması güvenliğini güçlendirmek için güvenlik yanıt başlıkları uygulandı.
- 🔧 **Gelişmiş AUTOMATIC1111 Ayarları**: Kullanıcılar artık yönetici ayarlarında 'CFG Scale', 'Sampler' ve 'Scheduler' parametrelerini doğrudan yapılandırabilir, kaynak kod modifikasyonları olmadan iş akışı esnekliğini artırıyor.
- 🌍 **i18n Güncellemeleri**: Çince, Ukraynaca, Rusça ve Fransızca için geliştirilmiş çeviriler, daha iyi yerelleştirilmiş bir deneyim sağlıyor.

### Düzeltildi

- 🛠️ **Sohbet Mesajı Silme**: Sohbet mesajı silme sorunları çözüldü, daha sorunsuz bir kullanıcı etkileşimi ve sistem kararlılığı sağlandı.
- 🔢 **Sıralı Liste Numaralandırması**: Listelerdeki yanlış sıralama düzeltildi.

### Değiştirildi

- 🎨 **Şeffaf İkon İşleme**: Model ikonlarının şeffaf arka planlarda görüntülenmesine izin verildi, UI estetiğini iyileştiriyor.
- 📝 **Geliştirilmiş RAG Şablonu**: Retrieval-Augmented Generation şablonu geliştirildi, daha hassas çalışma için bağlam işleme ve hata kontrolü optimize edildi.

## [0.3.21] - 2024-09-08

### Eklendi

- 📊 **Belge Sayısı Göstergesi**: Artık panoda doğrudan toplam belge sayısını gösteriyor.
- 🚀 **Ollama Embed API Endpoint**: /api/embed endpoint proxy desteği etkinleştirildi.

### Düzeltildi

- 🐳 **Docker Başlatma Sorunu**: Open-WebUI'nin Docker kullanırken doğru başlatılmasını engelleyen sorun çözüldü.

### Değiştirildi

- 🔍 **Gelişmiş Arama Prompt'ları**: Daha iyi doğruluk ve kullanıcı etkileşimi için arama sorgusu oluşturma prompt'ları iyileştirildi, genel arama deneyimini artırdı.

## [0.3.20] - 2024-09-07

### Eklendi

- 🌐 **Çeviri Güncellemesi**: Katalanca çeviriler, Katalanca konuşan kullanıcılar için kullanıcı deneyimini iyileştirmek üzere güncellendi.

### Düzeltildi

- 📄 **PDF İndirme**: Yazı tipleri diziniyle ilgili bir yapılandırma sorunu çözüldü, PDF'lerin artık doğru biçimlendirme ile indirildiği sağlandı.
- 🛠️ **Araçlar ve Fonksiyonlar Gereksinimleri Kurulumu**: Araçlar ve fonksiyonlar için gerekli gereksinimlerin düzgün bir şekilde kurulmaması hatası düzeltildi.
- 🔗 **Satır İçi Resim Bağlantısı Oluşturma**: Sohbet içinde bağlantılardan doğrudan resimlerin oluşturulması etkinleştirildi.
- 📞 **Çağrı Sonrası Kullanıcı Arayüzü Temizliği**: Sesli çağrı bittikten sonra sohbet kontrollerinin otomatik olarak kapanması için UI davranışı ayarlandı, ekran dağınıklığını azalttı.
- 🎙️ **Çağrı Sonrası Mikrofon Devre Dışı Bırakma**: Çağrılardan sonra mikrofonun aktif kalması sorunu giderildi.
- ✍️ **Markdown Boşluk Düzeltmesi**: Markdown oluşturmada boşluk düzeltildi, metnin düzgün ve beklendiği gibi görünmesini sağlandı.
- 🔄 **Mesaj Yeniden Oluşturma**: Her yeni mesajla birlikte tüm yanıt mesajlarının yeniden oluşturulmasına neden olan bir sorun düzeltildi, sohbet performansını iyileştirdi.

### Değiştirildi

- 🌐 **İyileştirilmiş Web Arama Entegrasyonu**: Arama Sorgusu Oluşturma Prompt eşiği eski haline getirildi; kullanıcıların web aramasını daha dikkatli kullanmayı seçmelerine olanak tanıyan "Web Arama Sorgusu Oluşturmayı Etkinleştir" için bir geçiş düğmesi tanıtıldı.
- 📝 **Varsayılan Prompt Şablonları Güncellemesi**: Arama ve başlık oluşturma için boş ortam değişkeni şablonları artık Open WebUI varsayılan prompt şablonlarına varsayılır, yapılandırma çabalarını basitleştirir.

## [0.3.19] - 2024-09-05

### Eklendi

- 🌐 **Çeviri Güncellemesi**: Çince çeviriler iyileştirildi.

### Düzeltildi

- 📂 **DATA_DIR Üzerine Yazma**: DATA_DIR'in üzerine yazmaktan kaçınmak için bir sorun düzeltildi, dizinler aynı ayarlandığında hataları önledi, daha sorunsuz çalışma ve veri yönetimi sağlandı.
- 🛠️ **Frontmatter Çıkarımı**: Araçlar ve fonksiyonlarda frontmatter'ın çıkarılması düzeltildi.

### Değiştirildi

- 🎨 **UI Stil Ayarları**: Gelişmiş görsel uyum ve kullanıcı deneyimi için kullanıcı arayüzü stili iyileştirildi.

## [0.3.18] - 2024-09-04

### Eklendi

- 🛠️ **Araçlar ve Fonksiyonlar için Doğrudan Veritabanı Yürütme**: Araçlar ve fonksiyonlar için Python dosyalarının yürütülmesi geliştirildi, artık daha düzenli bir backend süreci için doğrudan veritabanından yükleniyor.

### Düzeltildi

- 🔄 **Araçlar ve Fonksiyonlarda İçe Aktarma İfadelerinin Otomatik Yeniden Yazılması**: 'utils', 'apps', 'main', 'config'i içe aktaran araç ve fonksiyon betikleri artık bunları otomatik olarak 'open_webui.' ile yeniden adlandıracak, farklı modüller arasında uyumluluk ve tutarlılık sağlanacak.
- 🎨 **Stil Ayarları**: Kullanıcı deneyimini ve arayüz tutarlılığını iyileştirmek için küçük görsel stil düzeltmeleri.

## [0.3.17] - 2024-09-04

### Eklendi

- 🔄 **Yapılandırma İçe/Dışa Aktarma**: Kullanıcılar artık yönetici ayarlarından > Veritabanı aracılığıyla webui yapılandırmalarını içe ve dışa aktarabilir, sistemler arasında kurulum replikasyonunu basitleştirir.
- 🌍 **URL Parametresi ile Web Araması**: 'web-search=true' ayarlayarak URL aracılığıyla doğrudan web aramayı etkinleştirme desteği eklendi.
- 🌐 **SearchApi Entegrasyonu**: Platform içinde arama yeteneklerini geliştiren alternatif bir web arama sağlayıcısı olarak SearchApi desteği eklendi.
- 🔍 **Araçlarda Literal Tip Desteği**: Araçlar artık Literal tipini destekliyor.
- 🌍 **Güncellenmiş Çeviriler**: Çince, Ukraynaca ve Katalanca için geliştirilmiş çeviriler.

### Düzeltildi

- 🔧 **Pip Kurulum Sorunu**: Eksik 'alembic.ini' nedeniyle pip kurulumunun başarısız olması sorunu çözüldü, daha sorunsuz kurulum süreçleri sağlandı.
- 🌃 **Otomatik Tema Güncellemesi**: Renk temasının sistem değişiklikleriyle dinamik olarak güncellenmemesi sorunu düzeltildi.
- 🛠️ **ComfyUI'de Kullanıcı Aracısı**: Erişim sorunlarını düzeltmek için ComfyUI'de varsayılan başlıklar eklendi, ağ iletişimlerinde güvenilirlik iyileştirildi.
- 🔄 **Eksik Sohbet Tamamlama Yanıt Başlıkları**: Sohbet tamamlaması sırasında proxy'li yanıt başlıklarının doğru bir şekilde döndürülmesi sağlandı, API güvenilirliği iyileştirildi.
- 🔗 **Websocket Bağlantı Önceliği**: Bağlantı kararlılığını artırmak için websocket'leri tercih edecek ve daha güvenilir bir şekilde polling'e geri dönecek şekilde socket.io yapılandırması değiştirildi.
- 🎭 **Erişilebilirlik Geliştirmeleri**: Düğmeler için eksik ARIA etiketleri eklendi, görme engelli kullanıcılar için erişilebilirliği iyileştirdi.
- ⚖️ **Gelişmiş Parametre**: Gelişmiş parametrelerin tüm senaryolarda doğru bir şekilde uygulanmasını sağlayan bir sorun düzeltildi, kullanıcı tanımlı ayarların tutarlı davranışını sağlandı.

### Değiştirildi

- 🔁 **Ad Alanı Yeniden Düzenleme**: Proje yapısını kolaylaştırmak ve sürdürülebilirliği iyileştirmek için tüm Python dosyaları 'open_webui' ad alanı altında yeniden düzenlendi. 'utils'ten içe aktaran araçlar ve fonksiyonlar artık 'open_webui.utils' kullanmalıdır.
- 🚧 **Bağımlılık Güncellemeleri**: 'aiohttp', 'authlib', 'duckduckgo-search', 'flask-cors' ve 'langchain' gibi birkaç backend bağımlılığı, performans ve güvenliği artırmak için en son sürümlerine güncellendi.

## [0.3.16] - 2024-08-27

### Eklendi

- **🚀 Yapılandırma DB Geçişi**: Yapılandırma işleme config.json'dan veritabanına geçirildi, birden çok Open WebUI örneği genelinde yüksek kullanılabilirlik kurulumları ve yük dengeleme etkinleştirildi.
- 🔗 **URL aracılığıyla Çağrı Modu Aktivasyonu**: Çağrı modunu doğrudan URL aracılığıyla etkinleştirmek için 'call=true' URL arama parametresi eklendi, mobil cihazlarda kullanıcı etkileşimini geliştiriyor.
- ✨ **TTS İçerik Kontrolü**: Text-to-Speech (TTS) oluşturma istekleri için mesaj içeriğinin nasıl segmentlere ayrıldığını kontrol etme işlevselliği eklendi, daha esnek konuşma çıkış seçeneklerine izin veriyor.
- 😄 **Bilgi Arama Durumunu Göster**: Bilgi artırılmış modellerle çalışırken durumu göstererek model kullanım şeffaflığı artırıldı, kullanıcıların sorgular sırasında sistemin durumunu anlamasına yardımcı oluyor.
- 👆 **Codespan için Tıklayarak Kopyalama**: Kullanıcıların kod span'lerinden içeriği doğrudan tıklayarak kopyalamasına olanak tanıyarak WebUI'de etkileşimli deneyim geliştirildi.
- 🚫 **Model Filtresi aracılığıyla API Kullanıcısı Engelleme**: API erişimi üzerinde güvenlik ve kontrolü artıran özelleştirilmiş model filtrelerine göre API kullanıcılarını engelleme yeteneği tanıtıldı.
- 🎬 **Çağrı Katmanı Stil Ayarları**: Çağrı katmanı stil ayarları, tüm arayüzü değil, yalnızca sohbet kontrol alanını kapsayacak şekilde ayarlandı, daha dikkat çekmeyen bir etkileşim deneyimi için.

### Düzeltildi

- 🔧 **LaTeX Oluşturma Sorunu**: LaTeX'in doğru oluşturulmasını etkileyen bir sorun giderildi.
- 📁 **Dosya Sızıntısı Önleme**: Yüklenen dosyaların kullanıcı sohbetleri arasında yanlışlıkla erişilebilir olması sorunu çözüldü.
- 🔧 **'**files**' Parametresi ile Pipe Fonksiyonları**: Pipe fonksiyonlarında '**files**' parametresinin doğru çalışmaması sorunları düzeltildi.
- 📝 **RAG için Markdown İşleme**: Dosyalardaki Markdown işlemesiyle ilgili sorunlar düzeltildi.
- 🚫 **Yinelenen Sistem Prompt'ları**: Sistem prompt'larının yinelenmesine neden olan hatalar düzeltildi.

### Değiştirildi

- 🔋 **Wakelock İzni**: Wakelock aktivasyonu, yalnızca çağrı modu sırasında devreye girecek şekilde optimize edildi, cihaz kaynaklarını korudu ve boşta kalma sürelerinde pil performansını iyileştirdi.
- 🔍 **Ollama Sohbetleri için İçerik Tipi**: Ollama yanıtlarıyla eşleşmesi için '/api/chat' endpoint yanıtlarına 'application/x-ndjson' içerik tipi eklendi.
- ✋ **Koşullu Kayıtları Devre Dışı Bırak**: 'ENABLE_LOGIN_FORM' false olarak ayarlandığında kayıtları devre dışı bırakmak için koşullu mantık uygulandı.

## [0.3.15] - 2024-08-21

### Eklendi

- 🔗 **Geçici Sohbet Aktivasyonu**: Geçici sohbet oturumlarını doğrudan URL aracılığıyla etkinleştirmek için yeni bir URL parametresi 'temporary-chat=true' entegre edildi.
- 🌄 **ComfyUI Seed Node Desteği**: Görüntü oluşturma için ComfyUI'ye seed node desteği tanıtıldı, kullanıcıların rastgele seed ataması için düğüm ID'lerini belirlemesine olanak tanıyor.

### Düzeltildi

- 🛠️ **Araçlar ve Fonksiyonlar**: Araçlar ve Fonksiyonların düzgün bir şekilde çalışmaması gibi kritik bir sorun çözüldü, bu temel özelliklere tam yetenek ve güvenilirlik geri getirildi.
- 🔘 **Birçok Model Sohbetinde Sohbet Eylem Düğmesi**: Birçok model sohbet ortamında sohbet eylem düğmelerinin arızalı olması düzeltildi, daha sorunsuz ve daha duyarlı bir kullanıcı etkileşimi sağlandı.
- ⏪ **Birçok Model Sohbet Uyumluluğu**: Birçok model sohbeti için geriye dönük uyumluluk geri getirildi.

## [0.3.14] - 2024-08-21

### Eklendi

- 🛠️ **Özel ComfyUI İş Akışı**: Birkaç eski ortam değişkeni kullanımdan kaldırılıyor, bu geliştirme daha özel bir kullanıcı deneyimi için yeni, özelleştirilebilir bir iş akışı tanıtıyor.
- 🔀 **Birçok Model Sohbetinde Yanıtları Birleştir**: Çoklu modellerden gelen yanıtları tek, tutarlı bir yanıtta birleştirerek diyaloğu geliştirir, birçok model sohbetinde etkileşim kalitesini artırır.
- ✅ **Sohbetlerde Aynı Modelin Birden Fazla Örneği**: Aynı modelin birden fazla örneğini eklemeyi destekleyecek şekilde birçok model sohbeti geliştirildi.
- 🔧 **Model Çalışma Alanında Hızlı Eylemler**: Modelleri gizlemek/göstermek ve silmek için Shift tuşu hızlı eylemleri geliştirildi, daha sorunsuz bir iş akışı kolaylaştırıldı.
- 🗨️ **Kullanıcı Mesajlarında Markdown Oluşturma**: Kullanıcı mesajları artık Markdown'da oluşturulur, okunabilirliği ve etkileşimi artırır.
- 💬 **Geçici Sohbet Özelliği**: Eski sohbet geçmişi ayarını eski haline getirerek kullanıcı etkileşimi esnekliğini artırmak için geçici bir sohbet özelliği tanıtıldı.
- 🖋️ **Kullanıcı Mesajı Düzenleme**: Mesaj yönetiminde daha fazla esneklik sağlamak için kullanıcı sohbeti düzenleme özelliği geliştirildi, değişiklikleri göndermeden kaydetmeye olanak tanır.
- 🛡️ **Güvenlik Geliştirmeleri**: Daha güvenli kullanıcı deneyimleri sağlamak için platform genelinde çeşitli güvenlik iyileştirmeleri uygulandı.
- 🌍 **Güncellenmiş Çeviriler**: Çince, Ukraynaca ve Malayca için geliştirilmiş çeviriler, yerelleştirmeyi ve kullanıcı anlamayı iyileştiriyor.

### Düzeltildi

- 📑 **Mermaid Oluşturma Sorunu**: Temiz ve net görsel veri temsilini sağlamak için Mermaid çizelgesi oluşturma sorunları giderildi.
- 🎭 **PWA İkon Maskelenebilirliği**: Progresif Web Uygulaması ikonunun maskelenebilir olması düzeltildi, çeşitli cihaz ana ekranlarında doğru görüntüleme sağlandı.
- 🔀 **Klonlanmış Model Sohbet Dondurma Sorunu**: Birçok model sohbetinin klonlanmasının donmaya neden olduğu bir hata düzeltildi, kararlılık ve duyarlılık artırıldı.
- 🔍 **Genel Hata İşleme ve İyileştirmeler**: Daha önce izlenmeyen sorunları gidermek için çeşitli küçük düzeltmeler ve iyileştirmeler, daha sorunsuz işlemler sağlıyor.

### Değiştirildi

- 🖼️ **Görüntü Oluşturma Yeniden Yapılandırması**: Daha iyi verimlilik ve kalite için görüntü oluşturma süreçleri revize edildi.
- 🔨 **Araç ve Fonksiyon Çağrısı Yeniden Yapılandırması**: Daha iyi netlik ve sürdürülebilirlik için araç ve fonksiyon çağırma mekanizmaları yeniden yapılandırıldı.
- 🌐 **Backend Kütüphane Güncellemeleri**: SQLAlchemy, uvicorn[standard], faster-whisper, bcrypt ve boto3 dahil olmak üzere kritik backend kütüphaneleri, geliştirilmiş performans ve güvenlik için en son sürümlerine güncellendi.

### Kaldırıldı

- 🚫 **Eskimiş ComfyUI Ortam Değişkenleri**: ComfyUI ayarlarıyla ilgili birkaç eski ortam değişkeni kaldırıldı, yapılandırma yönetimini basitleştiriyor.

## [0.3.13] - 2024-08-14

### Eklendi

- 🎨 **Gelişmiş Markdown Oluşturma**: LaTeX ve Mermaid çizelgelerinin sorunsuz ve güvenilir bir şekilde görüntülenmesini sağlayarak, daha sağlam görsel içerikle kullanıcı deneyimini artıran Markdown oluşturmada önemli iyileştirmeler.
- 🔄 **Araçlar ve Fonksiyonlar Python Bağımlılıklarını Otomatik Kur**: 'Araçlar' ve 'Fonksiyonlar' için Open WebUI artık frontmatter'da belirtilen ek python gereksinimlerini otomatik olarak kurar, kurulum süreçlerini ve özelleştirmeyi kolaylaştırır.
- 🌀 **OAuth E-posta İddia Özelleştirmesi**: Kimlik doğrulama süreçlerinde daha fazla esneklik sağlamak için OAuth yapılandırmaları içinde varsayılan "e-posta" iddiasını özelleştirmeye izin veren bir 'OAUTH_EMAIL_CLAIM' değişkeni tanıtıldı.
- 📶 **Websocket Yeniden Bağlantısı**: Bir websocket kapatıldığında otomatik olarak yeniden bağlanma yeteneği ile gelişmiş güvenilirlik, tutarlı ve kararlı iletişim sağlıyor.
- 🤳 **Desteklenen Cihazlarda Dokunsal Geri Bildirim**: Android cihazlar artık belirli etkileşimler sırasında sürükleyici bir dokunsal deneyim için dokunsal geri bildirimi destekliyor.

### Düzeltildi

- 🛠️ **ComfyUI Performans İyileştirmesi**: ComfyUI görüntü oluşturma aktifken FastAPI'nin takılmasına neden olan bir sorun giderildi; artık UI'nin yanıt vermemesi önlemek için ayrı bir iş parçacığında çalışıyor.
- 🔀 **Oturum İşleme**: Daha sorunsuz oturum yönetimi ve geçişleri sağlamak için istemci tarafında session_id'yi zorunlu kılan bir sorun düzeltildi.
- 🖋️ **Küçük Hata Düzeltmeleri ve Format Düzeltmeleri**: Yazım hataları düzeltmeleri, backend biçimlendirme iyileştirmeleri ve genel sistem kararlılığını ve performansını artıran test düzeltmeleri dahil olmak üzere çeşitli küçük düzeltmeler.

### Değiştirildi

- 🚀 **SvelteKit 2'ye Geçiş**: Daha iyi hız, daha iyi kod yapısı ve geliştirilmiş dağıtım yetenekleri sunan temel framework SvelteKit sürüm 2'ye yükseltildi.
- 🧹 **Genel Temizleme ve Yeniden Yapılandırma**: Kod verimliliğini iyileştirmek ve yüksek kod sağlığı standartlarını korumak için platform genelinde geniş çaplı temizleme ve yeniden yapılandırma yapıldı.
- 🚧 **Entegrasyon Testi İyileştirmeleri**: Cypress entegrasyon testlerinin sohbet mesajlarını algılama şekli değiştirildi ve daha iyi güvenilirlik ve doğruluk için paylaşım testleri güncellendi.
- 📁 **Standartlaştırılmış '.safetensors' Dosya Uzantısı**: ComfyUI iş akışları için '.sft' dosya uzantısı '.safetensors' olarak yeniden adlandırıldı, platform genelinde dosya formatları standartlaştırıldı.

### Kaldırıldı

- 🗑️ **Eskimiş Frontend Fonksiyonları**: Kod tabanını sadeleştirmek ve gereksizliği azaltmak için backend'e taşınan frontend fonksiyonları kaldırıldı.

## [0.3.12] - 2024-08-07

### Eklendi

- 🔄 **Kenar Çubuğu Sonsuz Kaydırma**: Daha verimli sohbet gezinmesi için kenar çubuğuna sonsuz kaydırma özelliği eklendi, yükleme sürelerini azaltıyor ve kullanıcı deneyimini geliştiriyor.
- 🚀 **Gelişmiş Markdown Oluşturma**: Tüm kod bloklarının oluşturulması ve resimlerin önizleme için tıklanabilir hale getirilmesi desteği; kodspan stilizasyonu da okunabilirliği ve kullanıcı etkileşimini artırmak için geliştirildi.
- 🔒 **Yönetici Paylaşılan Sohbet Görünürlüğü**: ENABLE_ADMIN_CHAT_ACCESS false olarak ayarlandığında yöneticiler artık paylaşılan sohbetler üzerinde varsayılan görünürlüğe sahip değil, kullanıcılar için güvenlik ve gizlilik ayarlarını sıkılaştırıyor.
- 🌍 **Dil Güncellemeleri**: Malayca (Bahasa Malaysia) çevirisi eklendi ve daha fazla kullanıcı için erişilebilirliği iyileştirmek amacıyla Katalanca ve Geleneksel Çince çevirileri güncellendi.

### Düzeltildi

- 📊 **Markdown Oluşturma Sorunları**: Markdown oluşturma sorunları çözüldü, bileşenler genelinde tutarlı ve doğru görüntüleme sağlandı.
- 🛠️ **Stil Sorunları**: Uygulama genelinde stile uygulanan birden fazla düzeltme, genel görsel deneyimi ve arayüz tutarlılığını iyileştiriyor.
- 🗃️ **Modal İşleme**: Çeşitli model sohbet senaryolarında modalların doğru kapanmaması sorunu düzeltildi, kullanılabilirliği ve arayüz güvenilirliği artırıldı.
- 📄 **Eksik OpenAI Kullanım Bilgileri**: OpenAI hizmetleri için kullanım istatistiklerinin doğru görüntülenmemesi sorunları çözüldü, kullanıcıların API tüketimlerini yönetmek ve izlemek için önemli verilere erişimini sağlıyor.
- 🔧 **Fonksiyonlar Eklentisi için Akışsız Destek**: Fonksiyonlar eklentisi ile akışsız işlemlerin amaçlandığı gibi çalışmamasıyla ilgili bir işlevsellik sorunu düzeltildi, platform içinde asenkron ve senkron entegrasyon için tam yetenekler geri getirildi.
- 🔄 **Ortam Değişkeni Türü Düzeltmesi (COMFYUI_FLUX_FP8_CLIP)**: 'COMFYUI_FLUX_FP8_CLIP' ortam değişkeninin veri türü dizeden boolean'a düzeltildi, ortam ayarlarının doğru uygulanmasını ve yapılandırma yönetimini geliştiriyor.

### Değiştirildi

- 🔧 **Backend Bağımlılık Güncellemeleri**: boto3, pypdf, python-pptx, validators ve black gibi birkaç backend bağımlılığı güncellendi, güncel güvenlik ve performans optimizasyonları sağlandı.

## [0.3.11] - 2024-08-02

### Eklendi

- 📊 **Model Bilgisi Göstergesi**: Daha sezgisel gezinme için model seçimleri için görseller eklendi, model adlarının yanında görüntüler dahil.
- 🗣 **ElevenLabs Ses Adaptasyonları**: Kişiselleştirilmiş vokal etkileşimler için ElevenLabs ses ID'si desteği de dahil olmak üzere ses geliştirmeleri.
- ⌨️ **Ok Tuşları Model Seçimi**: Kullanıcılar artık daha hızlı model seçimi için ok tuşlarını kullanabilir, erişilebilirliği artırıyor.
- 🔍 **Model Seçicide Bulanık Arama**: Model seçici, modelleri hızlı bir şekilde bulmak için bulanık arama ile geliştirildi, açıklamalar dahil.
- 🕹️ **ComfyUI Flux Görüntü Oluşturma**: Yeni Flux görüntü oluşturma modeli desteği eklendi; Ayarlar'da ağırlık hassasiyeti ve CLIP model seçenekleri gibi ortam kontrolleri tanıtıldı.
- 💾 **Yüklemeler için Dosya Boyutu Göstergesi**: Geliştirilmiş dosya arayüzü artık dosya boyutunu gösteriyor, gelecek yükleme kısıtlamalarına hazırlanıyor.
- 🎚️ **Gelişmiş Parametreler "Min P"**: Özelleştirilmiş model hassasiyet kontrolü için gelişmiş ayarlara 'Min P' parametresi eklendi.
- 🔒 **Gelişmiş OAuth**: Ters proxy'lerin arkasındaki OAuth için özel yönlendirme URI desteği tanıtıldı, daha güvenli kimlik doğrulama süreçleri etkinleştirildi.
- 🖥 **Gelişmiş Latex Oluşturma**: Latex oluşturma süreçlerinde ayarlamalar yapıldı, artık metinden latex girişlerini doğru bir şekilde algılıyor ve sunuyor.
- 🌐 **Uluslararasılaşma**: Yeni Romence ve güncellenmiş Vietnamca ve Ukraynaca çevirilerle geliştirildi, uluslararası kullanıcılar için erişilebilirliği genişletmeye yardımcı oluyor.

### Düzeltildi

- 🔧 **Belge Yüklemede Etiket İşleme**: Etiketler artık yükleme belgesi işleyicisine düzgün bir şekilde gönderiliyor, eksik metadata sorunları çözüldü.
- 🖥️ **Hassas Giriş Alanları**: Tarayıcının güvenli giriş alanlarını yanlış yorumlaması düzeltildi, parola alanları olarak yanlış sınıflandırmayı önledi.
- 📂 **PDF Oluşturmada Statik Yol Çözünürlüğü**: Çeşitli ortamlarda sorunları önlemek için dinamik olarak ayarlanan statik yollar düzeltildi.

### Değiştirildi

- 🎨 **UI/UX Stil Geliştirmeleri**: Daha temiz ve daha sezgisel bir kullanıcı arayüzü için birden fazla küçük stil güncellemesi.
- 🚧 **Çeşitli Bileşenlerin Yeniden Yapılandırılması**: Netlik ve performans için stil, dosya işleme ve fonksiyon basitleştirmelerinde çok sayıda yeniden yapılandırma değişikliği.
- 🎛️ **Kullanıcı Valve Yönetimi**: Kullanıcı valfleri, etkileşimler sırasında daha kullanıcı dostu erişim için ayarlardan doğrudan sohbet kontrollerine taşındı.

### Kaldırıldı

- ⚙️ **Sağlık Kontrolü Günlüğü**: Logları temizlemek ve backend performansını iyileştirmek için sağlık kontrolü süreçlerinden ayrıntılı günlük kaydı kaldırıldı.

## [0.3.10] - 2024-07-17

### Düzeltildi

- 🔄 **Geliştirilmiş Dosya Yükleme**: Dosya yüklemelerinin animasyonsuz olması sorunu giderildi.
- 💬 **Sohbet Sürekliliği**: Bazı durumlarda mevcut sohbetlerin düzgün çalışmaması sorunu düzeltildi.
- 🗂️ **Sohbet Dosya Sıfırlaması**: Yeni konuşmalar için sohbet dosyalarının sıfırlanmaması sorunu çözüldü, artık her sohbet oturumu için temiz bir sayfa sağlıyor.
- 📁 **Belge Çalışma Alanı Yüklemeleri**: Dosyalar API'sini kullanarak çalışma alanındaki belge yüklemelerinin işlenmesi düzeltildi.

## [0.3.9] - 2024-07-17

### Eklendi

- 📁 **Dosyalar Sohbet Kontrolleri**: Yüklenen dosyaların her zaman dahil edildiği eski dosya işleme davranışına geri döndük. Artık dosyaları doğrudan sohbet kontrolleri bölümünden yönetebilir, gerektiğinde dosyaları kaldırabilirsiniz.
- 🔧 **"Eylem" Fonksiyon Desteği**: Mesaj araç çubuğuna özel düğmeler yazmak için yeni bir "Eylem" fonksiyonu tanıtıldı. Bu özellik, daha etkileşimli mesajlaşmayı sağlar, dokümantasyon yakında geliyor.
- 📜 **Atıf İşleme**: Belgeler çalışma alanındaki yeni yüklenen dosyalar için, atıflar artık gerçek dosya adını gösterecektir. Ek olarak, daha kolay erişim için bu dosya adlarına tıklayarak dosyayı yeni bir sekmede açabilirsiniz.
- 🛠️ **Event Emitter ve Çağrı Güncellemeleri**: Mesaj değiştirmeye izin vermek için 'event_emitter' geliştirildi ve Araçlar ve Fonksiyonlar için metin girişini desteklemek için 'event_call' geliştirildi. Ayrıntılı dokümantasyon yakında sağlanacak.
- 🎨 **Stil Yeniden Yapılandırması**: Daha temiz ve daha tutarlı bir kullanıcı arayüzü için çeşitli stil güncellemeleri.
- 🌐 **Gelişmiş Çeviriler**: Katalanca, Ukraynaca ve Brezilya Portekizcesi için geliştirilmiş çeviriler.

### Düzeltildi

- 🔧 **Sohbet Kontrolleri Önceliği**: Sohbet Kontrolleri değerlerinin model bilgisi parametreleri tarafından üzerine yazılması sorunu çözüldü. Öncelik artık Sohbet Kontrolleri, ardından Genel Ayarlar, sonra Model Ayarlarıdır.
- 🪲 **Hata Ayıklama Logları**: Hata ayıklama loglarının düzgün bir şekilde loglanmaması sorunu düzeltildi.
- 🔑 **Automatic1111 Auth Key**: Automatic1111 için kimlik doğrulama anahtarı artık gerekli değil.
- 📝 **Başlık Oluşturma**: Başlık oluşturmanın tek sefer çalışması sağlandı, bir sohbette birden fazla model olsa bile.
- ✅ **Parametrelerde Boolean Değerler**: Parametrelerde boolean değerler için destek eklendi.
- 🖼️ **Dosyalar Katmanı Stil Ayarları**: Dosyalar katmanı stil sorunu düzeltildi.

### Değiştirildi

- ⬆️ **Bağımlılık Güncellemeleri**
  - 'pydantic' sürüm 2.7.1'den 2.8.2'ye yükseltildi.
  - 'sqlalchemy' sürüm 2.0.30'dan 2.0.31'e yükseltildi.
  - 'unstructured' sürüm 0.14.9'dan 0.14.10'a yükseltildi.
  - 'chromadb' sürüm 0.5.3'ten 0.5.4'e yükseltildi.

## [0.3.8] - 2024-07-09

### Eklendi

- 💬 **Sohbet Kontrolleri**: Her sohbet oturumu için parametreleri kolayca ayarlayın, etkileşimleriniz üzerinde daha hassas kontrol sunar.
- 📌 **Sabitlenmiş Sohbetler**: Önemli konuşmaları kolayca erişilebilir tutmanıza olanak tanıyan sabitlenmiş sohbetler için destek.
- 📄 **Apache Tika Entegrasyonu**: Belge işleme yeteneklerini geliştiren bir belge yükleyici olarak Apache Tika kullanımına destek eklendi.
- 🛠️ **OpenID Talepleri için Özel Ortam**: OpenID için özel talepler ayarlamaya izin verir, kullanıcı kimlik doğrulama süreçlerinde daha fazla esneklik sağlar.
- 🔧 **Gelişmiş Araçlar ve Fonksiyonlar API'si**: 'event_emitter' ve 'event_call' tanıtıldı, artık daha iyi dokümantasyon ve izleme için atıflar da ekleyebilirsiniz. Ayrıntılı dokümantasyon belgelerimizde sağlanacaktır.
- ↔️ **Ayarlarda Yana Kaydırma**: Ayarlar sekmeleri container'ı artık daha kolay gezinme için yatay kaydırmayı destekliyor.
- 🌑 **Daha Koyu OLED Tema**: Yeni, daha koyu bir OLED teması ve açık tema için geliştirilmiş stilizasyon içerir, görsel çekiciliği artırır.
- 🌐 **Dil Güncellemeleri**: Endonezyaca, Almanca, Fransızca ve Katalanca dilleri için güncellenmiş çeviriler, erişilebilirliği genişletiyor.

### Düzeltildi

- ⏰ **OpenAI Akış Zaman Aşımı**: 'AIOHTTP_CLIENT_TIMEOUT' ayarını kullanarak OpenAI akış yanıtıyla ilgili sorunlar çözüldü, güvenilir performans sağlandı.
- 💡 **Kullanıcı Valve'ları**: Arızalı kullanıcı valfleri düzeltildi, doğru işlevsellik sağlandı.
- 🔄 **Daraltılabilir Bileşenler**: Daraltılabilir bileşenlerin çalışmaması sorunları giderildi, beklenen davranış geri getirildi.

### Değiştirildi

- 🗃️ **Veritabanı Backend**: Geliştirilmiş eşzamanlılık desteği için Peewee'den SQLAlchemy'e geçildi, veritabanı performansını artırıyor.
- ⬆️ **ChromaDB Güncellemesi**: Sürüm 0.5.3'e yükseltildi. Uzak ChromaDB örneğinizin bu sürümle eşleştiğinden emin olun.
- 🔤 **Birincil Yazı Tipi Stil Ayarı**: Daha iyi görsel tutarlılık için birincil yazı tipi Archivo olarak güncellendi.
- 🔄 **Windows için Yazı Tipi Değişikliği**: Windows kullanıcıları için Arimo, Inter yazı tipi ile değiştirildi, okunabilirliği iyileştirildi.
- 🚀 **Tembel Yükleme**: Başlangıç belleği kullanımını azaltmak ve performansı artırmak için 'faster_whisper' ve 'sentence_transformers' için tembel yükleme uygulandı.
- 📋 **Görev Oluşturma Payload'ı**: Görev oluşturmaları artık "başlık" yerine gövdede sadece "görev" alanını içerir.

## [0.3.7] - 2024-06-29

### Eklendi

- **🌐 Gelişmiş Uluslararasılaşma (i18n)**: Yeni tanıtılan Endonezyaca çevirisi ve Türkçe, Çince ve Katalanca dilleri için güncellenmiş çeviriler, kullanıcı erişilebilirliğini iyileştiriyor.

### Düzeltildi

- 🕵️‍♂️ **Tarayıcı Dili Algılama**: Uygulamanın tarayıcının dil ayarlarını doğru bir şekilde algılayıp uyum sağlamaması sorunu düzeltildi.
- 🔐 **OIDC Yönetici Rolü Ataması**: OpenID Connect (OIDC) aracılığıyla kaydolan ilk kullanıcıya yönetici rolünün atanmaması hatası düzeltildi.
- 💬 **Sohbet/Tamamlama Endpoint'i**: Akış seçeneği False olarak ayarlandığında sohbet/tamamlama endpoint'inin işlevsiz olması sorunu çözüldü.
- 🚫 **'WEBUI_AUTH' Yapılandırması**: 'WEBUI_AUTH' ayarının False olarak ayarlanmasının doğru bir şekilde uygulanmaması sorunu giderildi.

### Değiştirildi

- 📦 **Bağımlılık Güncellemesi**: Daha iyi güvenlik ve performans geliştirmeleri sağlamak için 'authlib' sürüm 1.3.0'dan 1.3.1'e yükseltildi.

## [0.3.6] - 2024-06-27

### Eklendi

- ✨ **"Fonksiyonlar" Özelliği**: Artık WebUI içinde filtreler (middleware) ve pipe (model) fonksiyonları gibi "Fonksiyonları" kullanabilirsiniz. Pipeline'larla büyük ölçüde uyumlu olsalar da, bu yerel fonksiyonlar Open WebUI içinde kolayca yürütülebilir. Filtre fonksiyonları için örnek kullanım durumları arasında kullanım izleme, gerçek zamanlı çeviri, moderasyon ve otomatik bellek bulunur. Pipe fonksiyonları için kapsam, Cohere ve Anthropic entegrasyonundan doğrudan Open WebUI içinde, kullanıcı başına OpenAI API anahtar kullanımı için "Valf"leri etkinleştirmeye ve çok daha fazlasına kadar uzanır. Sorunlarla karşılaşırsanız, SAFE_MODE tanıtıldı.
- 📁 **Dosyalar API'si**: OpenAI ile uyumlu olan bu özellik, Filtre Fonksiyonu ile birlikte özel Retrieval-Augmented Generation (RAG) sağlar. Daha fazla örnek topluluk platformumuzda ve resmi dokümantasyon web sitemizde paylaşılacaktır.
- 🛠️ **Araç Geliştirmeleri**: Araçlar artık atıfları ve "Valf"leri destekliyor. Dokümantasyon yakında hazır olacak.
- 🔗 **Files API aracılığıyla Iframe Desteği**: Fonksiyonları ve araçları kullanarak HTML'i doğrudan sohbet arayüzünüze oluşturmayı sağlar. Kullanım durumları arasında DOOM ve Snake gibi oyunları oynamak, bir hava durumu uygulamasını görüntülemek ve Anthropic "artifact" benzeri özellikler uygulamak bulunur. Topluluk platformumuzdaki ve dokümantasyonumuzdaki güncellemeler için takipte kalın.
- 🔒 **Deneysel OAuth Desteği**: Yeni deneysel OAuth desteği. Daha fazla ayrıntı için dokümantasyonumuzu kontrol edin.
- 🖼️ **Özel Arka Plan Desteği**: Deneyiminizi kişiselleştirmek için Ayarlar > Arayüz'den özel bir arka plan ayarlayın.
- 🔑 **AUTOMATIC1111_API_AUTH Desteği**: AUTOMATIC1111 API için geliştirilmiş güvenlik.
- 🎨 **Kod Vurgulama Optimizasyonu**: Geliştirilmiş kod vurgulama özellikleri.
- 🎙️ **Ses Kesme Özelliği**: Yeniden tanıtıldı ve artık Ayarlar > Arayüz'den açılıp kapatılabilir.
- 💤 **Wakelock API**: Önemli görevler sırasında ekranın kararmasını önlemek için artık kullanılıyor.
- 🔐 **API Anahtarı Gizliliği**: Daha iyi güvenlik için tüm API anahtarları varsayılan olarak gizlidir.
- 🔍 **Yeni Web Arama Sağlayıcısı**: Yeni bir seçenek olarak jina_search eklendi.
- 🌐 **Gelişmiş Uluslararasılaşma (i18n)**: Geliştirilmiş Korece çevirisi ve güncellenmiş Çince ve Ukraynaca çeviriler.

### Düzeltildi

- 🔧 **Konuşma Modu Sorunu**: Konuşma Modunun ayarlardan kaldırıldıktan sonra aktif kalması sorunu düzeltildi.
- 📏 **Kaydırma Düğmesi Engeli**: ScrollToBottom düğme container'ının altındaki düğmelerin tıklanmasını engellemesi sorunu çözüldü.

### Değiştirildi

- ⏲️ **AIOHTTP_CLIENT_TIMEOUT**: Geliştirilmiş yapılandırma esnekliği için artık varsayılan olarak 'None' olarak ayarlandı.
- 📞 **Sesli Çağrı Geliştirmeleri**: Çağrılar sırasında kod bloklarını ve ifadeleri atlayarak geliştirildi.
- 🚫 **Hata Mesajı İşleme**: Hata mesajlarıyla işlemlerin devam etmesi devre dışı bırakıldı.
- 🗂️ **Playground Yeniden Konumlandırma**: Daha iyi kullanıcı deneyimi için Playground çalışma alanından kullanıcı menüsüne taşındı.

## [0.3.5] - 2024-06-16

### Eklendi

- 📞 **Gelişmiş Sesli Çağrı**: Text-to-speech (TTS) callback'i artık her cümle için gerçek zamanlı olarak çalışıyor, tamamlama için beklemeyerek gecikmeyi azaltıyor.
- 👆 **Dokunarak Kesme**: Bir arama sırasında, artık sesi durdurmak için sesli komut yerine sadece dokunarak konuşan kişinin sesinin yanlışlıkla giriş olarak kaydedilmesi sorununu çözebilirsiniz.
- 😊 **Emoji Çağrısı**: Ayarlar > Arayüz'den bu özelliği açın, LLM'lerin daha dinamik bir etkileşim için sesli aramalar sırasında emojiler kullanarak duygularını ifade etmelerine olanak tanır.
- 🖱️ **Hızlı Arşivle/Sil**: Sohbet listesinde Shift tuşu + fareyle üzerine gelerek öğeleri hızla arşivleyin veya silin.
- 📝 **Model Açıklamalarında Markdown Desteği**: Artık model açıklamalarını Markdown ile biçimlendirebilirsiniz, kalın metin, bağlantılar vb. etkinleştirilebilir.
- 🧠 **Düzenlenebilir Bellekler**: Bellekleri değiştirme yeteneği ekler.
- 📋 **Yönetici Paneli Sıralaması**: Yönetici panelinde kullanıcıları/sohbetleri sıralama yeteneği tanıtıldı.
- 🌑 **Hızlı Seçiciler için Koyu Mod**: Sohbet hızlı seçicileri (prompt'lar, modeller, belgeler) için koyu mod artık mevcut.
- 🔧 **Gelişmiş Parametreler "Min P"**: Özelleştirilmiş model hassasiyet kontrolü için gelişmiş ayarlara 'Min P' parametresi eklendi.
- 📅 **Dinamik Sistem Prompt'ları**: Sistem prompt'ları için yeni değişkenler '{{CURRENT_DATETIME}}', '{{CURRENT_TIME}}', '{{USER_LOCATION}}' eklendi. '{{USER_LOCATION}}'un Ayarlar > Arayüz'den açık olduğundan emin olun.
- 🌐 **Tavily Web Araması**: Bir web arama sağlayıcısı seçeneği olarak Tavily'yi içerir.
- 🖊️ **Birleşik Kimlik Doğrulama Kullanıcı Adları**: Birleşik kimlik doğrulama için kullanıcı adlarını ayarlama yeteneği.
- 🔗 **Otomatik Temiz URL'ler**: Bağlantı URL'leri eklerken, sondaki eğik çizgiler artık otomatik olarak kaldırılır.
- 🌐 **Gelişmiş Çeviriler**: Geliştirilmiş Çince ve İsveççe çeviriler.

### Düzeltildi

- ⏳ **AIOHTTP_CLIENT_TIMEOUT**: Ollama'ya yapılan istekler için 5 dakikadan uzun süren yeni bir ortam değişkeni 'AIOHTTP_CLIENT_TIMEOUT' tanıtıldı. Varsayılan 300 saniyedir; zaman aşımı olmaması için boş ('') olarak ayarlayın.
- ❌ **Mesaj Silme Donması**: Mesaj silmenin bazen web UI'sinin donmasına neden olduğu bir sorun çözüldü.

## [0.3.4] - 2024-06-12

### Düzeltildi

- 🔒 **HTTPS ile Karışık İçerik Sorunu**: Karışık içerik (HTTP ve HTTPS) güvenlik uyarılarına neden olan ve HTTPS sitelerinde kaynakları engelleyen bir sorun çözüldü.
- 🔍 **Web Arama Sorunu**: Web arama işlevselliğinin doğru çalışmaması sorunu giderildi. Doğru web arama yeteneklerini geri yüklemek için 'ENABLE_RAG_LOCAL_WEB_FETCH' seçeneği yeniden tanıtıldı.
- 💾 **RAG Şablonunun Kaydedilmemesi**: RAG şablonunun doğru kaydedilmemesi sorunu düzeltildi, böylece özel şablonlarınızın artık beklendiği gibi korunmasını sağlandı.

## [0.3.3] - 2024-06-12

### Eklendi

- 🛠️ **Yerel Python Fonksiyon Çağırma**: Open WebUI içinde yerel Python fonksiyon çağırma özelliği tanıtıldı. Ayrıca, 'Araçlar' çalışma alanında fonksiyon kodunu sorunsuz bir şekilde geliştirmek ve entegre etmek için yerleşik bir kod düzenleyici de ekledik. Böylece, özel RAG pipeline'ları, web arama araçları ve hatta Discord mesajları göndermek gibi ajan benzeri özellikler oluşturarak LLM'nizin yeteneklerini önemli ölçüde artırabilirsiniz.
- 🌐 **DuckDuckGo Entegrasyonu**: Daha fazla arama seçeneği sunan bir web arama sağlayıcısı olarak DuckDuckGo eklendi.
- 🌏 **Gelişmiş Çeviriler**: Vietnamca ve Çince dilleri için geliştirilmiş çeviriler, arayüzü daha erişilebilir hale getiriyor.

### Düzeltildi

- 🔗 **Web Arama URL Hata İşleme**: Tek bir URL hatasının Web Arama modunda veri yükleme sürecini kesintiye uğratması sorunu düzeltildi. Artık bu tür hatalar sorunsuz bir şekilde ele alınacak ve kesintisiz veri yüklemesi sağlanacak.
- 🖥️ **Frontend Duyarlılığı**: Backend bir model indirirken hata ile karşılaşırsa frontend'in yanıt vermeyi durdurması sorunu çözüldü. Frontend kararlılığını korumak için hata işleme iyileştirildi.
- 🔧 **pip'teki Bağımlılık Sorunları**: pip kurulumlarıyla ilgili sorunlar düzeltildi, tüm bağımlılıkların doğru bir şekilde yönetilmesi sağlanarak kurulum hataları önlendi.

## [0.3.2] - 2024-06-10

### Eklendi

- 🔍 **Web Arama Sorgusu Durumu**: Web arama sorgusu, daha kolay hata ayıklama ve arama sorgularının takibi için sonuçlar bölümünde kalıcı olacak.
- 🌐 **Yeni Web Arama Sağlayıcısı**: Arama ihtiyaçlarınız için daha fazla seçenek sunan yeni bir web arama sağlayıcısı olarak Serply eklendi.
- 🌏 **Geliştirilmiş Çeviriler**: Çince ve Portekizce çevirilerimiz geliştirildi.

### Düzeltildi

- 🎤 **Ses Dosyası Yükleme Sorunu**: Sohbet girişinde ses dosyalarının yüklenmesini engelleyen hata düzeltildi, sorunsuz iletişim sağlandı.
- 💬 **Mesaj Girişi İşleme**: Görüntüleri ve metni gönderdikten sonra anında temizleyerek, bir yanıt mesajı yüklenirken anında görsel göstergelerle mesaj girişlerinin işlenmesi iyileştirildi, kullanıcı geri bildirimi artırıldı.
- ⚙️ **Parametre Kaydı ve Doğrulama**: Parametrelerin belirli durumlarda kaydedilmemesi sorunu ve kullanıcıların geçersiz giriş hataları nedeniyle kaydedememesi sorunu giderildi.

## [0.3.1] - 2024-06-09

### Düzeltildi

- 💬 **Sohbet İşlevselliği**: Belirli modeller için sohbet işlevselliğinin çalışmaması sorunu çözüldü.

## [0.3.0] - 2024-06-09

### Eklendi

- 📚 **Modeller için Bilgi Desteği**: Belgeleri modeller çalışma alanından doğrudan modellere ekleyin, her model için mevcut bilgileri artırın.
- 🎙️ **Eller Serbest Sesli Çağrı Özelliği**: Etkileşimleri daha sorunsuz hale getirerek ellerinizi kullanmadan sesli çağrılar başlatın.
- 📹 **Video Çağrı Özelliği**: Llava ve GPT-4o gibi desteklenen vision modelleriyle görüntülü aramaları etkinleştirin, iletişimlerinize görsel bir boyut katın.
- 🎛️ **Ses Kaydı için Gelişmiş UI**: Ses kaydı özelliği için geliştirilmiş kullanıcı arayüzü, daha sezgisel ve kullanıcı dostu hale getirildi.
- 🌐 **Harici STT Desteği**: Artık harici Speech-To-Text hizmetleri desteği, STT sağlayıcınızı seçerken daha fazla esneklik sağlıyor.
- ⚙️ **Birleşik Ayarlar**: Belge ayarları da dahil olmak üzere ayarlar, daha kolay yönetim için yeni bir yönetici ayarları bölümünde birleştirildi.
- 🌑 **Koyu Mod Açılış Ekranı**: Koyu mod kullanıcıları için tutarlı ve görsel olarak çekici bir deneyim sağlayan koyu mod için yeni bir açılış ekranı.
- 📥 **Pipeline Yükleme**: Yönetici ayarları > pipeline'lar bölümünden doğrudan pipeline'ları yükleyin, pipeline yönetim sürecini kolaylaştırın.
- 🌍 **Gelişmiş Dil Desteği**: Çince ve Ukraynaca dilleri için geliştirilmiş destek, daha küresel bir kullanıcı tabanına daha iyi hizmet veriyor.

### Düzeltildi

- 🛠️ **Playground Sorunu**: Playground'ın düzgün çalışmaması düzeltildi, daha sorunsuz bir kullanıcı deneyimi sağlandı.
- 🔥 **Sıcaklık Parametresi Sorunu**: Sıcaklık değeri '0'ın doğru bir şekilde geçirilmemesi sorunu düzeltildi.
- 📝 **Prompt Girişi Temizleme**: Prompt giriş textarea'sının hemen temizlenmemesi sorunu çözüldü, yeni girişler için temiz bir sayfa sağlandı.
- ✨ **Çeşitli UI Stil Sorunları**: Daha tutarlı bir görünüm için çok sayıda kullanıcı arayüzü stil sorunu düzeltildi.
- 👥 **Aktif Kullanıcılar Göstergesi**: Aktif kullanıcıların gerçek kullanıcılar yerine aktif oturumları göstermesi düzeltildi, artık doğru kullanıcı etkinliğini yansıtıyor.
- 🌐 **Topluluk Platformu Uyumluluğu**: Topluluk Platformu tekrar çevrimiçi ve Open WebUI ile tamamen uyumlu.

### Değiştirildi

- 📝 **RAG Uygulaması**: RAG (Retrieval-Augmented Generation) uygulaması, kullanıcının prompt'unu üzerine yazmak yerine bağlam için bir sistem prompt'u kullanacak şekilde güncellendi.
- 🔄 **Ayarların Yeniden Konumlandırılması**: Modeller, Bağlantılar, Ses ve Görüntü ayarları, daha iyi organizasyon için yönetici ayarlarına taşındı.
- ✍️ **Geliştirilmiş Başlık Oluşturma**: Başlık oluşturma için varsayılan prompt geliştirildi, daha iyi sonuçlar verdi.
- 🔧 **Backend Görev Yönetimi**: Başlık oluşturma ve arama sorgusu oluşturma gibi görevler artık backend tarafında yönetiliyor ve yalnızca yönetici tarafından kontrol ediliyor.
- 🔍 **Düzenlenebilir Arama Sorgusu Prompt'u**: Arama sorgusu oluşturma prompt'unu artık düzenleyebilirsiniz, sorguların nasıl oluşturulduğu üzerinde daha fazla kontrol sağlar.
- 📏 **Prompt Uzunluk Eşiği**: Yönetici ayarlarından arama sorgusu oluşturma için prompt uzunluk eşiğini ayarlayın, daha fazla özelleştirme seçeneği sunar.
- 📣 **Ayarlar Konsolidasyonu**: Banner'lar yönetici ayarları, daha düzenli bir ayarlar alanı için Arayüz yönetici ayarlarıyla birleştirildi.

## [0.2.5] - 2024-06-05

### Eklendi

- 👥 **Aktif Kullanıcılar Göstergesi**: Artık kaç kişinin aktif olduğunu ve ne çalıştıklarını görebilirsiniz. Bu, yüksek kullanıcı sayısı nedeniyle performansın ne zaman yavaşlayabileceğini anlamanıza yardımcı olur.
- 🗂️ **Ollama Modelfile Oluştur**: Ollama için bir modelfile oluşturma seçeneği, Ayarlar > Modeller bölümüne geri getirildi, modellerinizi yönetmeyi kolaylaştırıyor.
- ⚙️ **Varsayılan Model Ayarı**: Ayarlar > Arayüz'den varsayılan modeli ayarlama seçeneği eklendi. Bu özellik, daha önce gizli olduğu için özellikle mobil kullanıcılar için artık kolayca erişilebilir.
- 🌐 **Gelişmiş Çeviri**: Çince çevirileri geliştirildi ve arayüzü küresel olarak daha erişilebilir hale getirmek için Türkmence ve Norveççe dilleri için destek eklendi.

### Düzeltildi

- 📱 **Mobil Görünüm İyileştirmeleri**: UI artık vh (viewport height) yerine dvh (dynamic viewport height) kullanıyor, mobil kullanıcılar için daha iyi ve daha duyarlı bir deneyim sağlıyor.

## [0.2.4] - 2024-06-03

### Eklendi

- 👤 **Geliştirilmiş Hesap Beklemedeki Sayfa**: Hesap beklemedeki sayfası artık varsayılan olarak yönetici ayrıntılarını göstererek kafa karışıklığını önler. Gerektiğinde yönetici ayarlarından bu özelliği devre dışı bırakabilirsiniz.
- 🌐 **HTTP Proxy Desteği**: OpenAI ve Ollama API çağrılarında 'http_proxy' ortam değişkeninin kullanımını etkinleştirdik, ağ ayarlarını yapılandırmayı kolaylaştırıyor.
- ❓ **Dokümantasyona Hızlı Erişim**: Artık ekranın sağ alt köşesinde bulunan bir soru işareti düğmesi aracılığıyla Open WebUI dokümanlarına kolayca erişebilirsiniz (PC gibi daha büyük ekranlarda kullanılabilir).
- 🌍 **Gelişmiş Çeviri**: Çevirilerde iyileştirmeler yapıldı.

### Düzeltildi

- 🔍 **SearxNG Web Araması**: SearxNG web arama işlevselliğinin düzgün çalışmaması sorunu düzeltildi.

## [0.2.3] - 2024-06-03

### Eklendi

- 📁 **Sohbeti JSON Olarak Dışa Aktar**: Artık tek tek sohbetleri, gezinme çubuğu menüsünden 'İndir > Sohbeti Dışa Aktar' seçeneğine giderek JSON dosyaları olarak dışa aktarabilirsiniz. Bu, belirli konuşmaları paylaşmayı kolaylaştırır.
- ✏️ **Başlıkları Çift Tıklamayla Düzenle**: Başlıkları hızla ve verimli bir şekilde yeniden adlandırmak için çift tıklayın.
- 🧩 **Birden Fazla Embedding'i Toplu İşle**: Büyük veri kümeleri için performansı artıran birden fazla embedding'i toplu olarak işlemek için 'RAG_EMBEDDING_OPENAI_BATCH_SIZE' tanıtıldı.
- 🌍 **Geliştirilmiş Çeviriler**: Daha iyi bir kullanıcı deneyimi için çeşitli dillerde çeviri kalitesi artırıldı.

### Düzeltildi

- 🛠️ **Modelfile Geçiş Betiği**: Geçersiz bir modelfile ile karşılaşıldığında modelfile geçiş betiğinin başarısız olması sorunu düzeltildi.
- 💬 **Mac'te Zhuyin Giriş Yöntemi**: Mac'te Web UI'de Zhuyin giriş yöntemi kullanılırken metnin enter tuşuna basıldığında hemen gönderilmesi sorunu çözüldü, yanlış girişe neden oluyordu.
- 🔊 **Yerel TTS Ses Seçimi**: Ayarlarda seçilen yerel Text-to-Speech (TTS) sesinin görüntülenmemesi sorunu düzeltildi.

## [0.2.2] - 2024-06-02

### Eklendi

- 🌊 **Mermaid Oluşturma Desteği**: Mermaid oluşturma desteği eklendi. Bu, Open WebUI içinde doğrudan güzel diyagramlar ve akış şemaları oluşturmanıza olanak tanır.
- 🔄 **Yeni Ortam Değişkeni 'RESET_CONFIG_ON_START'**: Yeni bir ortam değişkeni tanıtıldı: 'RESET_CONFIG_ON_START'. Uygulamayı başlatırken yapılandırma ayarlarınızı sıfırlamak için bu değişkeni ayarlayın, varsayılan ayarlara dönmeyi kolaylaştırır.

### Düzeltildi

- 🔧 **Pipelines Filtre Sorunu**: Pipeline'larda filtrelerin beklendiği gibi çalışmaması sorunu giderildi.

## [0.2.1] - 2024-06-02

### Eklendi

- 🖱️ **Tek Model Dışa Aktar Düğmesi**: Yeni tek model dışa aktar düğmesini kullanarak modelleri tek tıklamayla kolayca dışa aktarın.
- 🖥️ **Gelişmiş Parametre Desteği**: Ollama için 'num_thread', 'use_mmap' ve 'use_mlock' parametreleri için destek eklendi.
- 🌐 **Geliştirilmiş Vietnamca Çeviri**: Vietnamca konuşan topluluğumuz için daha iyi bir kullanıcı deneyimi sağlamak amacıyla Vietnamca dil desteği geliştirildi.

### Düzeltildi

- 🔧 **OpenAI URL API Kaydetme Sorunu**: OpenAI URL API ayarlarının kaydedilmesini engelleyen bir sorun düzeltildi.
- 🚫 **Devre Dışı Ollama API ile Görüntüleme Sorunu**: Ollama API devre dışı bırakıldığında modellerin ayarlarda görünmesine neden olan görüntüleme hatası düzeltildi.

### Değiştirildi

- 💡 **Sürüm Güncellemesi**: Önceki güncellememizden bir hatırlatma olarak, 0.2.y sürümü öncelikli olarak hata düzeltmelerine odaklanacakken, ana güncellemeler bundan sonra daha iyi sürüm takibi için 0.x olarak belirlenecektir.

## [0.2.0] - 2024-06-01

### Eklendi

- 🔧 **Pipelines Desteği**: Open WebUI artık geliştirilmiş özelleştirme ve işlevsellik için bir eklenti framework'ü içerir (https://github.com/open-webui/pipelines). AI ajanlarından ev otomasyonu API'lerine kadar özel mantık ekleyin ve Python kütüphanelerini entegre edin.
- 🔗 **Pipelines aracılığıyla Fonksiyon Çağırma**: Pipelines aracılığıyla fonksiyon çağırmayı sorunsuz bir şekilde entegre edin.
- ⚖️ **Pipelines aracılığıyla Kullanıcı Hız Sınırlaması**: API kullanımını verimli bir şekilde yönetmek için kullanıcıya özgü hız sınırları uygulayın.
- 📊 **Langfuse ile Kullanım İzleme**: Pipelines aracılığıyla Langfuse entegrasyonu ile kullanım istatistiklerini izleyin ve analiz edin.
- 🕒 **Konuşma Turu Limitleri**: Pipelines aracılığıyla etkileşimleri daha iyi yönetmek için konuşma turu limitleri ayarlayın.
- 🛡️ **Zararlı Mesaj Filtreleme**: Pipelines kullanarak güvenli bir ortam sağlamak için zararlı mesajları otomatik olarak filtreleyin.
- 🔍 **Web Arama Desteği**: RAG API aracılığıyla yerleşik web arama yetenekleri tanıtıldı, kullanıcıların SearXNG, Google Programmatic Search Engine, Brave Search, serpstack ve serper kullanarak arama yapmasına olanak tanır. Belge ayarları > Web Parametreleri'nden gerekli değişkenleri ekleyerek zahmetsizce etkinleştirin.
- 🗂️ **Modeller Çalışma Alanı**: Hem Ollama/OpenAI API için model ön ayarları oluşturun ve yönetin. Not: Eski Modelfile'lar çalışma alanı kullanımdan kaldırıldı.
- 🛠️ **Model Oluşturucu Özelliği**: Kalıcı oluşturucu modu ile tüm modelleri oluşturun ve düzenleyin.
- 🏷️ **Model Etiketleme Desteği**: Modelleri modeller çalışma alanında etiketleme özellikleriyle düzenleyin.
- 📋 **Model Sıralama Desteği**: Modelleri modeller çalışma alanında sürükleyip bırakarak istediğiniz konumlara zahmetsizce düzenleyin.
- 📈 **OpenAI Oluşturma İstatistikleri**: OpenAI modelleri için ayrıntılı oluşturma istatistiklerine erişin.
- 📅 **Sistem Prompt Değişkenleri**: Dinamik prompt'lar için yeni değişkenler eklendi: '{{CURRENT_DATE}}' ve '{{USER_NAME}}'.
- 📢 **Global Banner Desteği**: Yönetici ayarları > banner'lardan global banner'ları yönetin.
- 🗃️ **Gelişmiş Arşivlenmiş Sohbetler Modalı**: Arşivlenmiş sohbetleri kolayca arayın ve dışa aktarın.
- 📂 **Tümünü Arşivle Düğmesi**: Ayarlar > sohbetler'den tüm sohbetleri hızla arşivleyin.
- 🌐 **Geliştirilmiş Çeviriler**: Fransızca, Hırvatça, Cebuano ve Vietnamca için çeviriler eklendi ve iyileştirildi.

### Düzeltildi

- 🔍 **Arşivlenmiş Sohbetler Görünürlüğü**: Yönetici panelinde arşivlenmiş sohbetlerin gösterilmemesi sorunu çözüldü.
- 💬 **Mesaj Stili**: Mesaj görünümünü etkileyen stil sorunları düzeltildi.
- 🔗 **Paylaşılan Sohbet Yanıtları**: Paylaşılan sohbet yanıt mesajlarının salt okunur olmaması sorunu düzeltildi.
- 🖥️ **UI Geliştirmesi**: Kullanıcı arayüzünde mesaj kutusu ile kaydırma çubuğu çakışması sorunu düzeltildi.

### Değiştirildi

- 💾 **Kullanıcı Ayarları Depolama**: Kullanıcı ayarları artık backend'de kaydediliyor, tüm cihazlarda tutarlılık sağlanıyor.
- 📡 **Birleşik API İstekleri**: Modelleri almak için API isteği, daha kolay kullanım için '/api/models' olarak birleştirildi.
- 🔄 **Sürüm Güncellemesi**: Sürümlendirmemiz artık ana güncellemeler için 0.x formatını ve patch'ler için 0.x.y formatını takip edecek.
- 📦 **Tüm Sohbetleri Dışa Aktar (Tüm Kullanıcılar)**: Bu işlevsellik, daha iyi organizasyon ve erişilebilirlik için Yönetici Paneli ayarlarına taşındı.

### Kaldırıldı

- 🚫 **Paketlenmiş LiteLLM Desteği Kullanımdan Kaldırıldı**: LiteLLM config.yaml'inizi kendi barındırdığınız bir LiteLLM örneğine taşıyın. LiteLLM hala OpenAI Bağlantıları aracılığıyla eklenebilir. LiteLLM config.yaml'i yönetici ayarları > veritabanı > LiteLLM config.yaml'i dışa aktar'dan indirin.

## [0.1.125] - 2024-05-19

### Eklendi

- 🔄 **Güncellenmiş UI**: Sohbet arayüzü sohbet balonları ile yeniden tasarlandı. Ayarlar > arayüz > sohbet balonu UI aracılığıyla eski stile kolayca geri dönebilirsiniz.
- 📂 **Gelişmiş Kenar Çubuğu UI'si**: Model dosyaları, belgeler, prompt'lar ve playground, kolay erişim için Çalışma Alanı'nda birleştirildi.
- 🚀 **Geliştirilmiş Çok Modelli Etkileşim**: Daha sorunsuz bir deneyim için tüm yanıtlar artık eşzamanlı olarak görüntülenir.
- 🐍 **Python Kod Yürütme**: Python kodunu 'requests', 'beautifulsoup4', 'numpy', 'pandas', 'seaborn', 'matplotlib', 'scikit-learn', 'scipy', 'regex' gibi kütüphanelerle yerel olarak tarayıcıda yürütün.
- 🧠 **Deneysel Bellek Özelliği**: LLM'lerin hatırlamasını istediğiniz kişisel bilgileri Ayarlar > Kişiselleştirme > Bellek aracılığıyla manuel olarak girin.
- 💾 **Kalıcı Ayarlar**: Ayarlar artık kolaylık sağlamak için config.json olarak kaydediliyor.
- 🩺 **Sağlık Kontrolü Endpoint'i**: Docker dağıtımı için eklendi.
- ↕️ **RTL Desteği**: Ayarlar > arayüz > sohbet yönü aracılığıyla sohbet yönünü değiştirin.
- 🖥️ **PowerPoint Desteği**: RAG pipeline artık PowerPoint belgelerini destekliyor.
- 🌐 **Dil Güncellemeleri**: Ukraynaca, Türkçe, Arapça, Çince, Sırpça, Vietnamca güncellendi; Pencapça eklendi.

### Değiştirildi

- 👤 **Paylaşılan Sohbet Güncellemesi**: Paylaşılan sohbet artık oluşturucu kullanıcı bilgilerini içeriyor.

## [0.1.124] - 2024-05-08

### Eklendi

- 🖼️ **Geliştirilmiş Sohbet Kenar Çubuğu**: Artık zaman aralıklarını rahatça gösterir ve sohbetleri bugün, dün ve daha fazlasına göre düzenler.
- 📜 **RAG Özelliğinde Alıntılar**: RAG özelliğine eklenen alıntılarla LLM'ye beslenen bağlamı kolayca takip edin. Not: Bu özellik yalnızca yeni yüklenen dosyaları destekler, izlenebilirliği artırır ve kaynak netliği sağlar.
- 🔒 **Kimlik Doğrulamayı Devre Dışı Bırak Seçeneği**: Kimlik doğrulamayı devre dışı bırakma yeteneği tanıtıldı. Kimlik doğrulamayı devre dışı bırakmak için 'WEBUI_AUTH'u False olarak ayarlayın. Not: Yalnızca mevcut kullanıcılar olmadan yeni kurulumlar için geçerlidir.
- 📹 **Gelişmiş YouTube RAG Pipeline'ı**: Zenginleştirilmiş bir deneyim için İngilizce olmayan videoları da destekleyen YouTube videoları için özel RAG pipeline'ı tanıtıldı.
- 🔊 **OpenAI TTS Modellerini Belirt**: OpenAI TTS modellerini belirterek TTS deneyiminizi özelleştirin.
- 🔧 **Ek Ortam Değişkenleri**: Kapsamlı dokümantasyonumuzda (https://docs.openwebui.com) daha fazla ortam değişkeni keşfedin, bellek kullanımını yönetmek için 'ENABLE_LITELLM' seçeneği dahil.
- 🌐 **Dil Desteği**: Arapça, Fince ve Hintçe eklendi; Almanca, Vietnamca ve Çince için geliştirilmiş destek.

### Düzeltildi

- 🛠️ **Model Seçici Stili**: Geliştirilmiş kullanıcı deneyimi için stil sorunları giderildi.
- ⚠️ **Uyarı Mesajları**: Backend uyarı mesajları çözüldü.

### Değiştirildi

- 📝 **Başlık Oluşturma**: Çıktı 50 token ile sınırlıdır.
- 📦 **Helm Charts**: Helm chart'ları kaldırıldı, artık ayrı bir depoda (https://github.com/open-webui/helm-charts) mevcut.

## [0.1.123] - 2024-05-02

### Eklendi

- 🎨 **Yeni Açılış Sayfası Tasarımı**: Daha modern bir görünüm ve ekran alanının optimize edilmiş kullanımı için yenilenmiş tasarım.
- 📹 **Youtube RAG Pipeline'ı**: Doğrudan video transkripsiyonlarıyla etkileşimi sağlayan Youtube videoları için özel RAG pipeline'ı tanıtıldı.
- 🔧 **Gelişmiş Yönetici Paneli**: Kullanıcıları doğrudan veya CSV içe aktarma yoluyla toplu olarak ekleme seçenekleriyle kolaylaştırılmış kullanıcı yönetimi.
- 👥 **'@' Model Entegrasyonu**: Konuşmalar sırasında belirli modellere kolayca geçiş yapın; eski işbirlikçi sohbet özelliği aşamalı olarak kaldırıldı.
- 🌐 **Dil Geliştirmeleri**: İsveççe çeviri eklendi, ayrıca Almanca, İspanyolca için iyileştirmeler ve Doge çevirisi eklendi.

### Düzeltildi

- 🗑️ **Sohbet Sil Kısayolu**: Kısayolun çalışmaması sorunu giderildi.
- 🖼️ **Modal Kapanma Hatası**: İçinden sürüklerken modalın beklenmedik şekilde kapanması sorunu çözüldü.
- ✏️ **Düzenleme Düğmesi Stili**: Düzenleme düğmelerindeki stil tutarsızlığı düzeltildi.
- 🌐 **Görüntü Oluşturma Uyumluluk Sorunu**: Üçüncü taraf API'leri ile görüntü oluşturma uyumluluk sorunu düzeltildi.
- 📱 **iOS PWA İkon Düzeltmesi**: iOS PWA ana ekran ikon şekli düzeltildi.
- 🔍 **Kaydırma Hareketi Hatası**: Mobil cihazda kod üzerinde kaydırma yaparken kazara etkinleştirmeyi önlemek için hareket duyarlılığı ayarlandı; artık kenar çubuğunu açmak için en soldan kaydırma gerektirir.

### Değiştirildi

- 🔄 **Sınırsız Bağlam Uzunluğu**: Gelişmiş ayarlar artık sınırsız maksimum bağlam uzunluğuna izin veriyor (daha önce 16000 ile sınırlıydı).
- 👑 **Süper Yönetici Ataması**: İlk kayıt olan kullanıcı otomatik olarak diğer yöneticiler tarafından değiştirilemeyen bir süper yönetici rolüne atanır.
- 🛡️ **Yönetici Kullanıcı Kısıtlamaları**: Yönetici panelindeki kullanıcı eylem düğmeleri, yönetici rolüne sahip kullanıcılar için artık devre dışıdır.
- 🔝 **Varsayılan Model Seçici**: Varsayılan model seçeneği artık yalnızca açılış sayfasında kullanılabilir.

## [0.1.122] - 2024-04-27

### Eklendi

- 🌟 **Gelişmiş RAG Pipeline'ı**: Artık 'BM25' aracılığıyla hibrit arama, 'CrossEncoder' tarafından desteklenen yeniden sıralama ve yapılandırılabilir alaka düzeyi puanı eşikleri ile.
- 🛢️ **Harici Veritabanı Desteği**: 'DATABASE_URL' ortam değişkenini kullanarak özel SQLite veya Postgres veritabanlarına sorunsuz bir şekilde bağlanın.
- 🌐 **Uzak ChromaDB Desteği**: Uzak ChromaDB sunucularına bağlanma yeteneği tanıtıldı.
- 👨‍💼 **Geliştirilmiş Yönetici Paneli**: Yöneticiler artık kullanıcıların sohbet listelerini ve son aktif durumlarını doğrudan yönetici panelinden rahatça kontrol edebilir.
- 🎨 **Açılış Ekranı**: Daha sorunsuz bir kullanıcı deneyimi için bir yükleme açılış ekranı tanıtıldı.
- 🌍 **Dil Desteği Genişletme**: Bengalce (bn-BD) desteği eklendi, ayrıca Çince, İspanyolca ve Ukraynaca çevirilerinde geliştirmeler yapıldı.
- 💻 **Geliştirilmiş LaTeX Oluşturma Performansı**: LaTeX denklemleri için daha hızlı oluşturma sürelerinin keyfini çıkarın.
- 🔧 **Daha Fazla Ortam Değişkeni**: Dokümantasyonumuzda (https://docs.openwebui.com) ek ortam değişkenlerini keşfedin, bellek kullanımını yönetmek için 'ENABLE_LITELLM' seçeneği dahil.

### Düzeltildi

- 🔧 **Ollama Uyumluluğu**: Ollama sunucu sürümünün SHA build'ları veya RC'ler gibi bir tam sayı olmaması durumunda oluşan hatalar çözüldü.
- 🐛 **Çeşitli OpenAI API Sorunları**: OpenAI API ile ilgili çeşitli sorunlar giderildi.
- 🛑 **Durdurma Sırası Sorunu**: Ters eğik çizgi '\' ile durdurma sırasının çalışmaması sorunu düzeltildi.
- 🔤 **Yazı Tipi Yedeklemesi**: Yazı tipi yedeklemesi sorunu düzeltildi.

### Değiştirildi

- ⌨️ **Mobil Üzerinde Prompt Giriş Davranışı**: Mobil cihazlarda enter tuşu prompt gönderimi, geliştirilmiş kullanıcı deneyimi için devre dışı bırakıldı.

## [0.1.121] - 2024-04-24

### Düzeltildi

- 🔧 **Çeviri Sorunları**: Çeşitli çeviri farklılıkları giderildi.
- 🔒 **LiteLLM Güvenlik Düzeltmesi**: Bir güvenlik açığını gidermek için LiteLLM sürümü güncellendi.
- 🖥️ **HTML Etiketi Görüntüsü**: '< br >' etiketinin doğru görüntülenmemesi sorunu düzeltildi.
- 🔗 **WebSocket Bağlantısı**: ComfyUI sunucusu için HTTPS güvenliği altında WebSocket bağlantısının başarısız olması çözüldü.
- 📜 **FileReader Optimizasyonu**: Çoklu dosya sürükle ve bırak işleminde her görüntü için FileReader başlatılması uygulandı, yeniden kullanılabilirliği sağlandı.
- 🏷️ **Etiket Görüntüsü**: Etiket görüntü tutarsızlıkları düzeltildi.
- 📦 **Arşivlenmiş Sohbet Stili**: Arşivlenmiş sohbette stil sorunları düzeltildi.
- 🔖 **Safari Kopyalama Düğmesi Hatası**: Safari'de kopyalama düğmesinin bağlantıları kopyalayamaması hatası giderildi.

## [0.1.120] - 2024-04-20

### Eklendi

- 📦 **Arşiv Sohbet Özelliği**: Yeni bir kenar çubuğu düğmesiyle sohbetleri kolayca arşivleyin ve profil düğmesi > arşivlenmiş sohbetler aracılığıyla arşivlenmiş sohbetlere erişin.
- 🔊 **Yapılandırılabilir Text-to-Speech Endpoint'i**: Yapılandırılabilir OpenAI endpoint'leri ile Text-to-Speech deneyiminizi özelleştirin.
- 🛠️ **Geliştirilmiş Hata İşleme**: Bağlantı hataları için geliştirilmiş hata mesajı işleme.
- ⌨️ **Gelişmiş Kısayol**: Mesajları düzenlerken, kaydetmek ve göndermek için ctrl/cmd+enter kullanın ve kapatmak için esc kullanın.
- 🌐 **Dil Desteği**: Gürcüce desteği eklendi ve Portekizce ve Vietnamca çevirileri geliştirildi.

### Düzeltildi

- 🔧 **Model Seçici**: Varsayılan model seçiminin kaydedilmemesi sorunu çözüldü.
- 🔗 **Paylaş Bağlantısı Kopyalama Düğmesi**: Kopyalama düğmesinin Safari'de bağlantıları kopyalayamaması hatası düzeltildi.
- 🎨 **Açık Tema Stili**: Açık tema ile ilgili stil sorunu giderildi.

## [0.1.119] - 2024-04-16

### Eklendi

- 🌟 **Gelişmiş RAG Embedding Desteği**: Ollama ve OpenAI modelleri artık RAG embedding modeli için kullanılabilir.
- 🔄 **Sorunsuz Entegrasyon**: Ollama sayfasından doğrudan 'ollama run <model adı>' komutunu kopyalayarak modelleri kolayca seçin ve çekin.
- 🏷️ **Etiketleme Özelliği**: Kenar çubuğu sohbet menüsünden sohbetlere doğrudan etiketler ekleyin.
- 📱 **Mobil Erişilebilirlik**: Kenar çubuğunu zahmetsizce açıp kapatmak için mobil cihazda sola ve sağa kaydırın.
- 🔍 **Geliştirilmiş Gezinme**: Yönetici paneli artık kullanıcı listesi için sayfalandırmayı destekliyor.
- 🌍 **Ek Dil Desteği**: Lehçe dil desteği eklendi.

### Düzeltildi

- 🌍 **Dil Geliştirmeleri**: Vietnamca ve İspanyolca çevirileri geliştirildi.
- 🔧 **Helm Düzeltmeleri**: Helm sondaki eğik çizgi ve manifest.json ile ilgili sorunlar çözüldü.

### Değiştirildi

- 🐳 **Docker Optimizasyonu**: 'pip3'e kıyasla önemli ölçüde daha hızlı build'ler için 'uv' kullanmak üzere docker imajı build süreci güncellendi.

## [0.1.118] - 2024-04-10

### Eklendi

- 🦙 **Ollama ve CUDA İmajları**: ':ollama' ve ':cuda' etiketli imajlar için destek eklendi.
- 👍 **Gelişmiş Yanıt Derecelendirmesi**: Artık daha iyi geri bildirim için derecelendirmelerinizi açıklayabilirsiniz.
- 👤 **Kullanıcı Baş Harfleri Profil Fotoğrafı**: Kullanıcı baş harfleri artık varsayılan profil fotoğrafıdır.
- 🔍 **RAG Embedding Modelini Güncelle**: Belge ayarlarından doğrudan RAG embedding modelini özelleştirin.
- 🌍 **Ek Dil Desteği**: Türkçe dil desteği eklendi.

### Düzeltildi

- 🔒 **Sohbet Paylaşma İzni**: Sohbet paylaşma izinleriyle ilgili sorun çözüldü.
- 🛠 **Modal Kapatma**: Modallar artık Esc tuşu kullanılarak kapatılabilir.

### Değiştirildi

- 🎨 **Yönetici Paneli Stili**: Yönetici paneli için yenilenen stil.
- 🐳 **Docker İmajı Oluşturma**: Geliştirilmiş verimlilik için docker imajı oluşturma süreci güncellendi.


## [0.1.117] - 2024-04-03
### Eklendi

🗨️ Yerel Sohbet Paylaşımı: Kullanıcılar arasında sohbet bağlantılarını sorunsuz bir şekilde paylaşın.

🔑 API Anahtarı Oluşturma Desteği: OpenAI kütüphaneleriyle Open WebUI'yi kullanmak için gizli anahtarlar oluşturun.

📄 Sohbeti PDF Olarak İndir: Sohbetleri kolayca PDF formatında indirin.

📝 Geliştirilmiş Günlükleme: Günlükleme işlevselliğine geliştirmeler.

📧 Güvenilir E-posta Kimlik Doğrulaması: Güvenilir bir e-posta başlığı kullanarak kimlik doğrulayın.

### Düzeltildi

🌷 Gelişmiş Hollandaca Çeviri: Hollandalı kullanıcılar için geliştirilmiş çeviri.

⚪ Beyaz Tema Stili: Beyaz tema ile ilgili stil sorunu çözüldü.

📜 LaTeX Sohbet Ekranı Taşması: LaTeX oluşturmayla ilgili ekran taşması sorunu düzeltildi.

🔒 Güvenlik Yamaları: Gerekli güvenlik yamaları uygulandı.

## [0.1.116] - 2024-03-31
### Eklendi

🔄 Gelişmiş UI: Model seçici artık gezinme çubuğunda kolayca bulunur, konuşmalar sırasında birden fazla model arasında sorunsuz geçişi sağlar.

🔍 İyileştirilmiş Model Seçici: Seçiciden doğrudan bir model çekin/Modeller artık daha iyi anlamak için ayrıntılı bilgi gösterir.

💬 Webhook Desteği: Artık Google Chat ve Microsoft Teams ile uyumlu.

🌐 Yerelleştirme: Korece çeviri (I18n) artık mevcut.

🌑 Koyu Tema: Uzun süreli kullanım sırasında göz yorgunluğunu azaltmak için OLED koyu tema tanıtıldı.

🏷️ Etiket Otomatik Tamamlama: Zahmetsiz sohbet etiketleme için açılır menü özelliği eklendi.

### Düzeltildi

🔽 Otomatik Kaydırma: OpenAI otomatik kaydırma sorunu giderildi.

🏷️ Etiket Doğrulama: Boş dize etiketlerini önlemek için etiket doğrulama uygulandı.

🚫 Model Beyaz Listesi: LiteLLM model beyaz listeleme sorunu çözüldü.

✅ Yazım: Daha iyi okunabilirlik için çeşitli yazım hataları düzeltildi.

## [0.1.115] - 2024-03-24
### Eklendi

🔍 Özel Model Seçici: Yeni arama filtresi özelliği ile özel modelleri kolayca bulun ve seçin.

🛑 Model İndirmeyi İptal Et: Model indirmelerini iptal etme yeteneği eklendi.

🎨 Görüntü Oluşturma ComfyUI: Görüntü oluşturma artık ComfyUI'yi destekliyor.

🌟 Güncellenmiş Açık Tema: Yeni bir görünüm için açık tema güncellendi.

🌍 Ek Dil Desteği: Artık Bulgarca, İtalyanca, Portekizce, Japonca ve Hollandaca destekleniyor.

### Düzeltildi

🔧 Bozuk Deneysel GGUF Yüklemesi Düzeltildi: Deneysel GGUF yükleme işlevselliğiyle ilgili sorunlar çözüldü.

### Değiştirildi

🔄 Vektör Depolama Sıfırla Düğmesi: Vektör depolama sıfırlama düğmesi belge ayarlarına taşındı.

## [0.1.114] - 2024-03-20
### Eklendi

🔗 Webhook Entegrasyonu: Artık webhook aracılığıyla yeni kullanıcı kayıt olaylarına abone olabilirsiniz. Yönetici paneli > yönetici ayarları > webhook URL'ye gitmeniz yeterli.

🛡️ Gelişmiş Model Filtreleme: Ollama, OpenAI proxy model beyaz listesine ek olarak, LiteLLM proxy için model filtreleme işlevselliği ekledik.

🌍 Genişletilmiş Dil Desteği: İspanyolca, Katalanca ve Vietnamca dilleri artık mevcut, diğer dillerde de iyileştirmeler yapıldı.

### Düzeltildi

🔧 Giriş Alanı Yazımı: Giriş alanlarındaki yazım hataları giderildi.

🖊️ Açık Mod Stili: Belge eklemede açık mod stili sorunu düzeltildi.

### Değiştirildi

🔄 Dil Sıralama: Diller artık daha iyi organizasyon için kodlarına göre alfabetik olarak sıralanıyor.

## [0.1.113] - 2024-03-18
### Eklendi

🌍 Yerelleştirme: Artık UI dilini Ayarlar > Genel'den değiştirebilirsiniz. Ukraynaca, Almanca, Farsça (Persian), Geleneksel ve Basitleştirilmiş Çince ve Fransızca çevirilerini destekliyoruz. UI'yi kendi dilinize çevirmemize yardımcı olabilirsiniz! Daha fazla bilgi için CONTRIBUTION.md belgesine bakın.

🎨 Sistem Genelinde Tema: Gelişmiş görsel deneyim için yeni bir sistem genelinde tema tanıtıldı.

### Düzeltildi

🌑 Seçim Alanlarında Koyu Arka Plan: Belirli tarayıcılarda/cihazlarda sorunları gidererek seçim alanlarına koyu bir arka plan ekleyerek okunabilirlik iyileştirildi.

Birden Fazla OPENAI_API_BASE_URLS Sorunu: Birinin çalışmaması durumunda birden fazla temel URL'nin çakışmaya neden olması sorunu çözüldü.

RAG Kodlama Sorunu: RAG'deki kodlama problemi düzeltildi.

npm Denetim Düzeltmesi: npm denetim bulguları giderildi.

Azaltılmış Kaydırma Eşiği: Kaydırma eşiği 50px'ten 5px'e düşürülerek otomatik kaydırma deneyimi iyileştirildi.

Değiştirildi

🔄 Kenar Çubuğu UI Güncellemesi: Daha iyi gezinme için iki ikonun yerini alan bir sohbet menüsü açılır penceresi içerecek şekilde kenar çubuğu UI güncellendi.

## [0.1.112] - 2024-03-15
### Düzeltildi

🗨️ Görüntü oluşturulduktan sonra sohbet arızası çözüldü.

🎨 Çeşitli RAG sorunları düzeltildi.

🧪 Deneysel bozuk GGUF yükleme mantığı düzeltildi.

## [0.1.111] - 2024-03-10
### Eklendi

🛡️ Model Beyaz Listesi: Yöneticiler artık 'user' rolüne sahip kullanıcılar için modelleri beyaz listeye alma yeteneğine sahip.

🔄 Tüm Modelleri Güncelle: Tüm modelleri tek seferde güncellemek için kullanışlı bir düğme eklendi.

📄 PDF OCR'yi Aç/Kapat: Kullanıcılar artık daha iyi ayrıştırma performansı için PDF OCR seçeneğini açıp kapatabilir.

🎨 DALL-E Entegrasyonu: automatic1111'e ek olarak görüntü oluşturma için DALL-E entegrasyonu tanıtıldı.

🛠️ RAG API Yeniden Yapılandırması: RAG mantığı yeniden yapılandırıldı ve API'si açık hale getirildi, ek dokümantasyonlar yakında gelecek.

### Düzeltildi

🔒 Maksimum Token Ayarları: Anthropic/claude-3-sonnet-20240229 için maksimum token ayarları eklendi (Sorun #1094).

🔧 Hizalama Sorunu: Sohbet Başlığı Boşken Düzenle ve Sil İkonlarının Yanlış Hizalanması düzeltildi (Sorun #1104).

🔄 Bağlam Kaybı Düzeltmesi: API anahtarı aracılığıyla Groq modelleriyle model yanıtı yeniden oluşturmada RAG'nin bağlam kaybetmesi çözüldü (Sorun #1105).

📁 Dosya İşleme Hatası: Konuşma Öğesi Bırakıldığında Dosya Bulunamadı Bildirimi giderildi (Sorun #1098).

🖱️ Sürüklenen Dosya Stili: Sürüklenen dosya katmanı stil sorunu düzeltildi.

## [0.1.110] - 2024-03-06
### Eklendi

🌐 Çoklu OpenAI Sunucusu Desteği: Artık yerel olarak desteklenen birden fazla OpenAI uyumlu API ile sorunsuz entegrasyonun keyfini çıkarın.

### Düzeltildi

🔍 OCR Sorunu: OCR arızasından kaynaklanan PDF ayrıştırma sorunu çözüldü.

🚫 RAG Sorunu: RAG işlevselliği düzeltildi, sorunsuz çalıştığı sağlandı.

📄 "Belgeleri Ekle" Model Düğmesi: "Belgeleri Ekle" model düğmesinin işlevsel olmayan davranışı giderildi.

## [0.1.109] - 2024-03-06
### Eklendi

🔄 Çoklu Ollama Sunucusu Desteği: Tek bir WebUI'de birden fazla Ollama sunucusu desteği ile gelişmiş ölçeklenebilirlik ve performansın keyfini çıkarın. Yük dengeleme özellikleri artık mevcut, geliştirilmiş verimlilik sağlıyor (#788, #278).

🔧 Claude 3 ve Gemini Desteği: Kullanıcı isteklerine yanıt olarak, araç setimizi Claude 3 ve Gemini'yi içerecek şekilde genişlettik, platformumuz içinde daha geniş bir işlevsellik yelpazesi sunuyoruz (#1064).

🔍 PDF Yükleyici için OCR İşlevselliği: PDF yükleyicimizi Optik Karakter Tanıma (OCR) yetenekleri ile güçlendirdik. Artık PDF'lerdeki taranmış belgelerden ve resimlerden metin çıkarın, içerik işleme kapsamını genişletiyor (#1050).

### Düzeltildi

🛠️ RAG Koleksiyonu: Kullanıcıların güncel ve doğru verilere sahip olmasını sağlayan RAG koleksiyonlarını yeniden oluşturmak için dinamik bir mekanizma uygulandı (#1031).

📝 Kullanıcı Aracısı Başlıkları: RAG web isteklerinin boş user_agent başlıklarıyla gönderilmesi sorunu düzeltildi, belirli web sitelerinden gelen retleri azalttı. Bu istekler için artık gerçekçi başlıklar kullanılıyor (#1024).

⏹️ Playground İptal İşlevselliği: Playground'da Ollama oluşturmayı durdurmak için yeni bir "İptal" seçeneği tanıtıldı, kullanıcı kontrolünü ve kullanılabilirliği artırıyor (#1006).

🔤 'ASSISTANT' Alanında Tipografik Hata: Doğruluk ve tutarlılık için GGUF model yükleme şablonundaki 'ASSISTANT' alanında tipografik bir hata düzeltildi (#1061).

### Değiştirildi

🔄 Mesaj Silme Mantığı Yeniden Yapılandırıldı: Geliştirilmiş verimlilik ve kullanıcı deneyimi için mesaj silme süreci kolaylaştırıldı, platform içindeki etkileşimler basitleştirildi (#1004).

⚠️ OLLAMA_API_BASE_URL'nin Kullanımdan Kaldırılması: OLLAMA_API_BASE_URL ortam değişkeni kullanımdan kaldırıldı; bunun yerine OLLAMA_BASE_URL kullanılması önerilir. Daha fazla ayrıntı için dokümantasyonumuza bakın.

## [0.1.108] - 2024-03-02
### Eklendi

🎮 Playground Özelliği (Beta): Yönetici erişimine sahip sezgisel bir UI aracılığıyla ham API'nin tüm potansiyelini keşfedin. Erişmek için kenar çubuğunun alt ad alanına tıklamanız yeterli. Playground özelliği iki mod sunar: metin tamamlama (notebook) ve sohbet tamamlama. Beta aşamasında olduğu için karşılaştığınız sorunları bildirin.

🛠️ Yönetici için Doğrudan Veritabanı İndirme: Yöneticiler artık veritabanını WebUI'den yönetici ayarları aracılığıyla doğrudan indirebilirler.

🎨 Ek RAG Ayarları: TOP K değerini düzenleme yeteneği ile RAG sürecinizi özelleştirin. Belgeler > Ayarlar > Genel'e giderek değişiklikleri yapabilirsiniz.

🖥️ UI İyileştirmeleri: Giriş alanında ve kenar çubuğu tutamacında artık araç ipuçları mevcut. UI'nin diğer bölümlerine de daha fazla araç ipucu eklenecek.

### Düzeltildi

Kenar çubuğu açıkken mobil cihazda giriş otomatik odaklama sorunu çözüldü, kullanımı kolaylaştırdı.

Safari'de numaralı liste görüntüleme sorunu düzeltildi (#963).

Uygun izinler olmadan kullanıcıların sohbetleri silme yeteneği kısıtlandı (#993).

### Değiştirildi

Basitleştirilmiş Ollama Ayarları: Ollama ayarları artık /api soneki gerektirmiyor. Artık Ollama temel URL'sini doğrudan kullanabilirsiniz, örn. http://localhost:11434. Ayrıca, bir OLLAMA_BASE_URL ortam değişkeni eklendi.

Veritabanı Yeniden Adlandırma: Bu sürümden itibaren ollama.db otomatik olarak webui.db olarak yeniden adlandırılacaktır.

## [0.1.107] - 2024-03-01
### Eklendi

🚀 Makefile ve LLM Güncelleme Betiği: Depoya Makefile ve LLM güncellemeleri için bir betik dahil edildi.

### Düzeltildi

Ayarlar modalındaki bağlantıların tıklanamaz görünmesi sorunu düzeltildi (#960).

run-compose.sh'de yanlış ortam değişkeni adı nedeniyle web UI portunun etkili olmaması sorunu düzeltildi (#996).

Tarayıcı başlığında sohbeti görüntüleyerek ve otomatik olarak aşağıya kaydırmayı etkinleştirerek kullanıcı deneyimi geliştirildi (#992).

Değiştirildi

Daha şık bir UI için toast kütüphanesi svelte-french-toast'ten svelte-sonner'e yükseltildi.

Kimlik doğrulama sayfasında koyu mod eklenerek erişilebilirlik artırıldı.

## [0.1.106] - 2024-02-27
### Eklendi

🎯 Otomatik Odaklanma Özelliği: Sohbet başlatıldığında veya açıldığında giriş alanı otomatik olarak odaklanır.

### Düzeltildi

"HuggingFace" yazım hatası "Hugging Face" olarak düzeltildi (Sorun #924).

Eksik "num_ctx" parametresi nedeniyle OpenAI'ye yapılan sohbet tamamlama API çağrılarında hatalara neden olan hata düzeltildi (Sorun #927).

Giriş alanında metin düzenleme, seçme ve imleç tutma sorunları düzeltildi (Sorun #940).

'OPENAI_API_BASE_URL' içeren 'openai' dizgisi içeren bir OpenAI uyumlu API sunucusu tanımlandığında, 'gpt' dizgisi içermeyen modellerin model menüsünden gizlenmesi sorunu düzeltildi. (Sorun #930)

## [0.1.105] - 2024-02-25
### Eklendi

📄 Belge Seçimi: Artık daha kolay yönetim için birden fazla belgeyi aynı anda seçebilir ve silebilirsiniz.

### Değiştirildi

🏷️ Belge Ön Etiketleme: Üstteki "+" düğmesine tıklayın, açılır pencerede etiket adlarını girin veya mevcut etiketler listesinden seçin. Ardından, kolaylaştırılmış organizasyon için eklenen etiketlerle dosyaları yükleyin.

## [0.1.104] - 2024-02-25
### Eklendi

🔄 Güncellemeleri Kontrol Et: Ayarlar > Hakkında'da uygun bir şekilde bulunan güncellemeleri kontrol ederek sisteminizi güncel tutun.

🗑️ Otomatik Etiket Silme: Kenar çubuğundaki kullanılmayan etiketler artık tek bir tıklamayla otomatik olarak silinecek.

### Değiştirildi

🎨 Modernleştirilmiş Stil: Daha çağdaş bir deneyim için güncellenmiş stil ile yenilenmiş bir görünümün keyfini çıkarın.

## [0.1.103] - 2024-02-25
### Eklendi

🔗 Yerleşik LiteLLM Proxy: Gelişmiş işlevsellik için artık Open WebUI içinde LiteLLM proxy içerir.

Mevcut LiteLLM yapılandırmalarını -v /path/to/config.yaml:/app/backend/data/litellm/config.yaml bayrağını kullanarak kolayca entegre edin.

Open WebUI'yi çalıştırmak için Docker container kullanırken, localhost'a bağlantıların host.docker.internal kullanılarak yapıldığından emin olun.

🖼️ Görüntü Oluşturma Geliştirmeleri: Görüntü Önizleme Özelliği ile Gelişmiş Ayarlar tanıtıldı.

Adım sayısını ayarlayarak görüntü oluşturmayı özelleştirin; varsayılan A1111 değeridir.

### Düzeltildi

RAG taramasının desteklenmeyen MIME türleri veya istisnalar nedeniyle belge yüklemesini durdurması sorunu çözüldü (Sorun #866).

### Değiştirildi

Ollama artık Open WebUI'yi çalıştırmak için gerekli değil.

Kapsamlı dokümantasyonumuza Open WebUI Dokümantasyonu adresinden erişin.

## [0.1.102] - 2024-02-22
### Eklendi

🖼️ Görüntü Oluşturma: AUTOMATIC1111/stable-diffusion-webui API'sini kullanarak Görüntüler Oluşturun. Bunu Ayarlar > Görüntüler'den ayarlayabilirsiniz.

📝 Başlık oluşturma prompt'unu değiştir: Sohbetleriniz için başlık oluşturmakta kullanılan prompt'u değiştirin. Bunu Ayarlar > Arayüz'den ayarlayabilirsiniz.

🤖 Embedding modelini değiştir: Dockerfile'da sohbetleriniz için embedding oluşturmakta kullanılan embedding modelini değiştirin. huggingface.co'dan herhangi bir sentence transformer modelini kullanın.

📢 CHANGELOG.md/Açılır Pencere: Bu açılır pencere size en son değişiklikleri gösterecektir.

## [0.1.101] - 2024-02-22
### Düzeltildi

LaTeX çıktı biçimlendirme sorunu (#828)

### Değiştirildi

Önceki 1.0.0-alpha.101 sürümü yerine, küresel kurallara uymak için semantik sürümlemeye geçtik.

Çeviri Burak Can Öğüt
