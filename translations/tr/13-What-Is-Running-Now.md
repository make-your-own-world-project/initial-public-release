> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../README.md) | [Tüm diller](../README.md)

# Şimdi Ne Çalışıyor?

![Paylaşılan kontrollü bir omurga etrafında sorumlulukla organize edilen yerel makineler](../../assets/public-machinery-catalog.png)

## Bu kataloğu nasıl okuyabilirim?

Katalog, Görev Kontrolündeki Veri Merkezi görünümünün genel karşılığıdır. Her bir çarkın neye katkıda bulunduğunu ve özel adresler, makine düzeni, kimlik bilgileri, dosya yolları veya çalışma ritmi yayınlanmadan ortadan kaybolması durumunda nelerin kaybolacağını açıklar. Canlı grafik, gerçeğin operasyonel kaynağı olmaya devam ediyor.

Bileşen durumu önemlidir. Bir araç etkin olabilir, kaynak sistem olarak tutulabilir, değerlendirilebilir ancak benimsenmemiş olabilir veya kullanımdan kaldırılmış bir öncül olabilir. Bu katalogda yer almak, belirtilen rolünün ötesinde bir bileşen yetkisi vermez.

Bu kural dış sınır kabiliyetini de içermektedir. Kullanıldığında sınırlı bir istasyonu işgal eder ve korunan derlemlere sınırsız erişim yerine amaca yönelik olarak oluşturulmuş bir yük alır. Yük, beyan edilen işlemi destekler ancak daha geniş sistemi yeniden yapılandırmak veya gelecekte bağımsız olarak geri çekilmeler üretmek için gereken dayanıklı durumu atlar. İstasyon, merkezi bir kurumun kalıcı değer elde edebileceği insan kayıtlarının velayetini değil, işi alır.

## Sisteme giriş ve sistem etrafındaki yollar

### Robot Beyni (LibreChat)


**Sorumluluk.** Değiştirilebilir, insanlara yönelik konuşma penceresini sağlayın. Kalıcı hafıza, geri çağırma, akıl yürütme ve doğrulama, altındaki hizmetlerde kalırken istekleri ve yanıtları taşır.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[LibreChat](https://github.com/danny-avila/LibreChat),[Node.js](https://github.com/nodejs/node)

### Konuşma Ayırıcı


**Sorumluluk.** Bir sohbetin iki konuya dönüştüğünü fark eder ve biten konuyu ayrı ayrı dosyalamayı teklif eder.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[FastAPI](https://github.com/fastapi/fastapi)

### Görev Kontrolü


**Sorumluluk.** Makineye açılan pencere: Neyin çalıştığı, nelerin dikkat edilmesi gerektiği ve makinenin şu anda ne yaptığı. Bu yayın sınırında, durum sayfası yerel kurulumda izlenen tüm sistemlerin çalışır durumda olduğunu bildirir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Operasyonel durum, hizmet durumunu bildirir; kabul edilen eserler ve makbuzlar, ayrı yürütme ve anlamsal kanıt sınırlarını oluşturur.

**Temel kamu araçları.**[FastAPI](https://github.com/fastapi/fastapi),[Grafikviz](https://gitlab.com/graphviz/graphviz),[psikopat](https://github.com/psycopg/psycopg)

### Anlamsal Yönlendirici


**Sorumluluk.** Sınırlı istekleri uygun yerel motora yönlendirin ve harici çıkarımı kullanmadan önce açık yetkilendirmeyi zorunlu kılın. Pahalı yetenek yalnızca talep ölçülen maliyeti haklı çıkardığında seçilir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[FastAPI](https://github.com/fastapi/fastapi). Elçi ve vLLM Semantik Yönlendirici, mevcut çalışma zamanı bağımlılıkları olarak değil, denetlenen veya kullanımdan kaldırılan öncüller olarak kaynak dizininde kredilendirilmeye devam eder.

### Temsilci Geçmişlerini Tamamlayın


**Sorumluluk.** İnsan sıraları, asistan sıraları, araçlar, hatalar ve düzeltmeler dahil olmak üzere eksiksiz, sıralı temsilci olay akışlarını etkileşim kanıtı olarak koruyun. Tarihler olup bitenleri kaydeder; temsilci beyanlarını doğrulanmış gerçeklere dönüştürmezler.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca kaynağının ve menşeinin belirlediğini sağlar; aşağı yönde yorumlama ayrı kalır.

### Proje Dokümanları


**Sorumluluk.** Platformun neden var olduğunu ve mimarisinin nasıl değiştiğini açıklayan özel tasarımı, kanıtları ve proje kayıtlarını koruyun. Kamu ürünleri, özel belge konumunu açığa çıkarmak yerine incelenen türevleri tüketir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca kaynağının ve menşeinin belirlediğini sağlar; aşağı yönde yorumlama ayrı kalır.

### Vikunja


**Sorumluluk.** Harici görev sistemini, platformdan önce gelen bağımsız bir kaynak olarak koruyun. Entegrasyon, görev sistemini bütünlüğe dahil etmeden veya yaşam döngüsünü değiştirmeden yetkili görev kanıtlarını okuyabilir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca kaynağının ve menşeinin belirlediğini sağlar; aşağı yönde yorumlama ayrı kalır.

**Temel kamu araçları.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Koruma ve geri alma

### Bilgi Alımı


**Sorumluluk.** İşlerin içeri girme şekli. Bir belgeyi, bir dışa aktarmayı, bir yığın notu bırakın ve hiçbir yere varmak yerine, bulunabilecek bir yere düşer.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### MongoDB


**Sorumluluk.** Söylendiği gibi konuşmaları kendisi yürütür.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Kullanılabilirlik ve bütünlük gereklidir; saklanan veriler kendi kendini yorumlamaz veya doğrulamaz.

**Temel kamu araçları.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Sorumluluk.** Değiştirilebilir uygulama hizmetlerinden daha uzun süre dayanması amaçlanan dayanıklı yapılandırılmış proje kayıtlarını, türetilmiş durumu ve arama dizinlerini tutun. Saklanan kayıtlar, farklılaşmamış tek bir hafızaya dönüşmek yerine, farklı otoriteyi ve kaynağı korur.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Kullanılabilirlik ve bütünlük gereklidir; saklanan veriler kendi kendini yorumlamaz veya doğrulamaz.

**Temel kamu araçları.**[PostgreSQL](https://github.com/postgres/postgres),[pgvektör](https://github.com/pgvector/pgvector)

## Muhakeme ve yeniden yapılanma

### Argüman İlişkisi Sınıflandırıcısı

sabitlenmiş AMF_ARI OpenVINO CPU sınıflandırması çıkarım, çakışma, yeniden ifade etme veya ilişki yok

**Sorumluluk.** Sağlanan iki önerme arasındaki ilişkiyi sınıflandırın; ne bir öneri yaratır ne de kişisel bir güdü ortaya çıkarır. Örnek: bir diğerini destekleyen bir ifadeyi onunla çelişen bir ifadeden ayırın veya desteklenen bir ilişki döndürmeyin.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[AMF ARI RoBERTa OpenVINO modeli](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### İnsan Eserleri


**Sorumluluk.** Montaj hattının oluşturabileceği, insana yönelik ürünleri tanımlayın. Her ürün, tek bir genel taslağı paylaşmak yerine kendi alıcısını, amacını, yapısını, kanıt politikasını ve teslimat sözleşmesini taşır.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Topraklama + Teslimat Doğrulaması

aslına uygunluk, menşe, kayıp, buluş, dokuma ve anlama kontrolleri üzerinde bağımsız alındı ​​kapısı

**Sorumluluk.** Yayınlanmadan önce yapının desteklenen anlamı koruduğunu ve beyan edilen teslimat sözleşmesini karşıladığını bağımsız olarak kontrol edin. Örnek: bir sonuca varan okunabilir bir paragrafı reddedin ve yapısı hedef okuyucu için kullanılamaz olan temellendirilmiş bir belgeyi ayrıca reddedin.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Kitle Çözünürlüğü

alıcı durumu, önkoşullar, kayıt ve alaka

**Sorumluluk.** Varsayımları açık tutarken hedeflenen alıcının neyi bilmesi, ihtiyaç duyması ve tolere etmesi beklendiğini açıklayın. Örnek: Bir havuz teknisyeninin aşina olduğu kısaltmaları kullanmadan önce pH'ı açıklayan bir ev sahibi kılavuzuna ihtiyacınız var.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Tüm Ağaç Çöküşü + Paketler

kapsayıcıyla kısıtlı bölüm, seçim, kazançlar ve kayıplar

**Sorumluluk.** İhmal edilenleri kaydederken ve ağacın anlamlı şeklini korurken, istenen yapıya neyin uyabileceğini seçin ve dengeleyin. Örnek: En büyük kaynak dalının bütçenin tamamını tüketmesine izin vermek yerine, her bir ana dalın 1000 kelimelik bir makalede temsil edilmesini sağlayın.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[alt modlib](https://github.com/decile-team/submodlib),[diz çökmüş](https://github.com/arvkevi/kneed)

### Kompakt Çalışma Modeli

Seçilen birimler, ilişkiler, yörüngeler, kaynak bloklar, planlar, tanıtıcılar ve devir defterleri için taşınabilir istek kapsamlı taşıyıcı

**Sorumluluk.** Seçilen gerçekleri, ilişkileri, kronolojiyi, belirsizliği, arızaları ve kaynak tanıtıcılarını taşınabilir, işe özel bir bağlamda paketleyin. Örnek: Editöre havuz bakım zincirini ve bu zincirin adımlarının neden tüm derlemi yüklemeden veya bağlantıları bırakmadan bağlandığını verin.

**Korunmalıdır.** source_spans; ilişki_idleri; kronoloji; belirsizlik; başarısızlıklar; yerine geçme; bilinmeyenler

**Kaynak şekli.** Sınırlı seçimle orantılı CPU ve RAM; GPU veya kiralama yok

**Sınır.** Kalite, üretime yönelik ilişki ve mevduat devleti kapsamıyla sınırlıdır

### Teslimat Mekaniği

kayıt, modlar, örgü profilleri, ilerleme hızı, yoğunluk ve gelişim kontrolleri

**Sorumluluk.** Bu ürün ve hedef kitle için ilerleme hızı, yoğunluk, kayıt ve örgü yörüngesi gibi ölçülen teslimat kısıtlamalarını sağlayın. Örnek: Bir çocuk açıklamasına, temel gerçekleri değiştirmeden, teknik bir rapora göre daha kısa paketler ve farklı bir yineleme modeli verin.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Söylem Ön İşleme

kesin sınırlı dilimler, FastCoref referans adayları ve kiralanan isanlp RST işlenen bağlantıları

**Sorumluluk.** Kesin kaynak koordinatlarını koruyarak sınıflandırmayı akıl yürütmeden önce aday referansları ve söylem kapsamlarını belirleyin. Örnek: 'it'i adı geçen pompa adayına bağlayın ve nedensel bir söylem ilişkisiyle birleştirilen iki cümleyi ortaya çıkarın.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Tüm Yapının İleriye Yönelik Yeniden Yapılanması

önkoşullar, referanslar, nedensel bağlantı, ilerleme, giriş ve sonuç

**Sorumluluk.** Önkoşulları, referansları, nedensel bağlantıları, ilerlemeyi ve dürüst bir sonu geri yükleyerek seçilen materyali okuyucu sırasına göre yeniden oluşturun. Örnek: Prosedürden önce hedefi tanıtın ve sonuç olmadığında çözülmemiş bir soruyu kapatın.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Grafik Nedeni ve Bağımlılık Projeksiyonu

Yeni akıl yürütme iddiaları getiremeyen sınıflandırılmış grafik kenarlarının deterministik görünümü

**Sorumluluk.** Kabul edilen ilişki kenarlarını yorum eklemeden incelenebilir bağımlılığa ve neden görüşlerine çevirin. Örnek: B sonucunun A öncülüne bağlı olduğunu gösterin çünkü tam olarak sınıflandırılmış kenar mevcuttur.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[AğX](https://github.com/networkx/networkx)

### Topraklanmış Etkileşimli Cevap


**Sorumluluk.** İlgili muhakeme, kaynak, belirsizlik ve genişleme yollarını içeren, konuşmaya dayalı bir yanıt verin. Yanıt yolu, bir belge oluşturma işlemi gibi görünmeden konuşmaların ve kanıt yaşam döngülerinin tamamını geçebilir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### İnsan Protokolü Köprüsü

Sabit desteklenen yükün alıcı odaklı kodlanması

**Sorumluluk.** Sabit, desteklenen bir yükü, ürün sözleşmesini ve ölçülü teslimat modelini kullanarak hedeflenen kişinin izleyebileceği bir biçime dönüştürün; delilleri değiştiremez. Örnek: Sonuçları değil, dağıtım yapısını değiştirerek aynı temelli akıl yürütme zincirini kısa bir e-postaya veya aşamalı bir kılavuza dönüştürün.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### İnteraktif Bağlam Montajı


**Sorumluluk.** Kronolojiyi, düzeltmeleri, hataları, kaynak kimliğini ve yetkilendirmeyi koruyarak mevcut soru için sınırlı bir kanıt ve akıl yürütme grafiği oluşturun. Derlemi arama parçacıkları halinde düzleştirmeden cevaba bağlam sağlar.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Kayıpsız Katılım


**Sorumluluk.** Orijinal baytları ve yerel olayları yorumlamadan önce kabul edin ve yalnızca gözlemlenen varış gerçeklerini kaydedin. İçerikten, kimliklerden ve ilişkilerden çıkarılan açıklamalar, zaman damgaları ayrı versiyonlu gözlemler olarak kalır.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Birincil Kanıt


**Sorumluluk.** Daha sonraki temsilciliklerin ve ürünlerin izini sürebilmesi gereken yetkili mevduatları elinde bulundurun. Sistem henüz anlamlarını veya ilişkilerini açıklayamadığında bile onların varlığı ayaktadır.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Geçici Ağacı Tamamla

tam budama öncesi kanıt, bağımlılık, alternatif ve başarısızlık yapısı

**Sorumluluk.** Alternatifler, hatalar, bilinmeyenler ve değiştirilen görünümler de dahil olmak üzere istek kapsamlı aday ağacının tamamını tutun; böylece daraltma, ne kaybedeceğini görebilir. Örnek: Bir kılavuz için malzeme seçmeden önce hem başarısız olan tedaviyi hem de sonraki düzeltmeyi saklayın.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Muhakeme Grafiği

kronoloji, yazılı ilişkiler, talep yaşam döngüleri, başarısızlıklar ve belirsizlik

**Sorumluluk.** Tekliflerin, kronolojinin, girişimlerin, sonuçların, çatışmaların, bağımlılıkların ve belirsizliğin istek kapsamlı haritasını koruyun. Örnek: Başarısız bir tedaviyi, her iki durumu da silmeden, onun yerine geçen düzeltmeye bağlayın.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Talep + Eser Sözleşmesi

amaç, alıcı, kapsayıcı, kanal, bütçe ve doğruluk

**Sorumluluk.** Amacı, alıcıyı, ürünü, kanalı, bütçeyi ve doğruluk standardını dondurun, böylece her alt çark aynı işi çözer. Örnek: Kanıt seçimi başlamadan önce 500 kelimelik genel okuyucu açıklamasını teknik olay raporundan ayırın.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Ters Genişleme

budamadan geriye doğru toplayın; marjinal katkıyı ölç

**Sorumluluk.** Talepten veya daha sonraki kanıtlardan daha önceki ilgili kayıtlara doğru ilerleyin ve herhangi bir şey atılmadan önce aday yolculuğunun tamamını toplayın. Örnek: Mevcut bir alg sorusunu önceki pH, havuz boyutu, bakım ve kullanım bağlamı kayıtlarına göre takip edin.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Yazılan Retorik Hareketler

anlamsal işler ve bağımlılıklar, asla alt dizelere yönelmez

**Sorumluluk.** Seçilen her birime, eşleşen bir başlık kelimesine değil, ürün sözleşmesine dayalı olarak iletişimsel bir iş ve bağımlılık atayın. Örnek: Her ikisini de 'arka plan' olarak adlandırmak yerine, kanıtları bir iddiayı destekleyen ve bir başarısızlığı kurtarmayı ayarlayan olarak işaretleyin.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Anlamsal Yeniden Yapılanma

varlıklar, önermeler, bölümler, girişimler, sonuçlar ve sorular

**Sorumluluk.** Nihai önemine veya sunumuna karar vermeden, kaynak gözlemlerini atfedilen anlamsal nesnelere dönüştürün. Örnek: önerilen bir düzeltmeyi, girişimi, başarısızlığı ve kalan soruyu ayrı bağlantılı kayıtlar olarak temsil edin.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Sürümlendirilmiş Gösterimler


**Sorumluluk.** transkriptler, yapı, metin, OCR, düzen ve türetilmiş görünümler

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Neden Önemliydi?

atfedilen motivasyon, endişe, sonuç ve mevcut alaka

**Sorumluluk.** Desteklenmeyen nedenleri bilinmeden bırakarak, neden ilgi gösterildiğine ilişkin doğrudan ve açıkça atfedilen kanıtları taşıyın. Örnek: Bir bakım görevinin, bu amacı yalnızca teknik bir sorudan yola çıkarak tahmin etmek yerine, kayıt desteklediğinde paylaşılan ekipmanı kullanan insanları koruduğu için önemli olduğunu savunun.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Muhakeme + Artifact Motoru

Makbuz kapılı yeniden yapılandırma, çökme, İnsan Protokolü ve atomik Markdown oluşturma

**Sorumluluk.** Sınırlı yeniden oluşturma ve oluşturma yolunu koordine edin ve her aşamanın alındığını açıklayın; uzman kararının yerini almaz. Örnek: seçme, planlama, gerçekleştirme, doğrulama ve atomik yazma yoluyla bir oluşturma isteğini taşıyın.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Montaj + Yetenek Yöneticisi

gerekli alanları geriye doğru yürür, önkoşulları fiyatlandırır, dürüst uzmanları seçer, bağımlılık dalgalarını emreder ve sıfır değerli çalışmayı atlar

**Sorumluluk.** Hangi uzmanlara ihtiyaç olduğunu, hangi sırayla çalışacaklarını ve hangi işin değer katmadığını seçin; görevlerini yerine getirmiyor. Örnek: Cümle gerçekleştirmeden önce ilişki gerçekleştirmeyi programlayın ve gerekli hiçbir katkıda bulunmayan, kullanılamayan bir biçimsel geçişi atlayın.

**Korunmalı.** must_preserve_fields; field_lineage; açık_kullanılamayabilirlik

**Kaynak şekli.** CPU; düşük hafıza; GPU veya kiralama yok

**Sınır.** Maliyet ve değer gözlemleri kararları ortaya çıkarır ancak insanın önemini asla tanımlamaz

### Atomic Carrier Bütçe Uzlaştırmacı

bölünmez kaynak, yapıştırıcı ve ilişki taşıyıcılarını gerçekleşmeden önce ölçer ve sabit tüm ürün bütçesini gerçek bölüm bolluğuna göre yeniden dağıtır

**Sorumluluk.** Bölünemez gerçeklerin ve ilişki taşıyıcılarının her bölüme uyup uymadığını kontrol edin, ardından toplam belge bütçesini koruyarak yalnızca mevcut bolluğu hareket ettirin. Örnek: başka bir bölümden kullanılmayan kelimeleri ödünç alarak gerekli 120 kelimelik atomik talimatı içeren 90 kelimelik bir prosedür bölümünü genişletin.

**Korunmalı.** bütün_artifact_budget; gerekli_rhetorical_jobs; kaynak_yetkisi; grafik_şekli

**Kaynak şekli.** CPU; sıfıra yakın çalışma süresi; Aşama 8 GPU/model/doğrulayıcı çalışmasının boşa harcanmasını önler

**Sınır.** bölünmez bir önermeyi sıkıştıramaz; gerekli tüm taşıyıcıların beyan edilen ürün bütçesini aşması durumunda başarısız olur

### Kaynağa Bağlı Yeniden Bağlama Yöneticisi

kendisine atanan ürün işi uyumsuz olduğunda ve bir hedefin uyumlu olduğu kanıtlanabilir olduğunda yalnızca tamamen yalıtılmış bir şubeyi taşır

**Sorumluluk.** Belirsiz veya ilişki içeren hamleleri reddederken, eksiksiz, izole edilmiş bir kanıt dalını işinin meşru olarak kullanabileceği bir bölüme taşıyın. Örnek: müstakil bir kurtarma notunu her iki bölümde de çoğaltmadan kurulumdan sorun gidermeye yeniden atayın.

**Korunmalıdır.** Branch_identity; kaynak_spans; ilişki_idleri; marjinal_kazanç_ledger

**Kaynak şekli.** CPU; düşük gecikme; GPU veya kiralama yok

**Sınır.** ilişki içeren, belirsiz, kısmi veya kapasite aşımı hareketlerini reddeder

### Belge Genelinde İlişki Gerçekleştirici

kabul edilen aynı kesit ve kesit akıl yürütme kenarlarını, her iki işleneni tekrarlamadan kompakt, bağımsız olarak yeniden oynatılabilir bağlantı diline dönüştürür

**Sorumluluk.** Yönü, işlenenleri ve kaynak aralıklarını bağımsız olarak yeniden oynatılabilir halde tutarken kabul edilen grafik ilişkilerini kısa bağlayıcı dile dönüştürün. Örnek: A ve B'yi ilgisiz bitişik gerçekler olarak yazdırmak yerine, A-nedenleri-B'yi sınırlı bir nedensel köprü olarak gerçekleştirin.

**Korunmalı.** ilişki_yön; işlenen_kimlik; kesin_carrier_spans; kaynak_spans; bölüm_lineage

**Kaynak şekli.** CPU; sıfıra yakın çalışma süresi; GPU veya kiralama yok

**Sınır.** yalnızca açıkça kabul edilen ilişki türlerini gerçekleştirir; kompakt köprüler, yazılan kenar kimliğini korur ancak mekanik olarak ifade edilmiş olarak kalır; aynı taşıyıcı, belirsiz, örtülü ve bilinmeyen kenarlar grafikte görünür durumda kalır ancak düzyazı olarak iddia edilmez

### Bilgi Motoru


**Sorumluluk.** Katılımı, türetilmiş temsilleri, aramayı, menşei ve kalıcı işleri, bu sorumlulukları tek bir doğruluk durumunda birleştirmeden koordine edin. Desteklenen arayüzleri tüketicilere sunarken birincil kanıtlar bağımsız olarak ele alınabilir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Yazılan Cümle / Cümle Mikro Planlayıcısı

kaynağa bağlı taşıyıcıları yazılı retorik işlere atar ve cümle, cümle ve paragraf planlarını derler

**Sorumluluk.** Onaylanan anlam ve ilişkileri, kaynak bağlarını korurken yan tümce, cümle ve paragraf işlerine ayırın; ifadeler veya iddialar icat etmez. Örnek: yüzeysel gerçekleştirici için bir neden cümlesi ve ardından sonucunu ve geçişini planlayın.

**Korunmalı.** semantic_unit_ids; ilişki_idleri; kaynak_formları

**Kaynak şekli.** CPU; düşük gecikme; GPU veya kiralama yok

**Sınır.** eksik bir önerme icat etmez veya sınıflandırılmamış bir ilişkiyi onarmaz

**Temel kamu araçları.**[uzay](https://github.com/explosion/spaCy),[BlingAteş](https://github.com/microsoft/BlingFire)

### Ürün Sözleşme Yöneticisi

türü, alıcıyı, amacı, kanalı, doğruluğu, dikkati ve bütçeyi gerekli ürün alanlarına ve retorik çalışmaya dönüştürür

**Sorumluluk.** Kanıt seçmeden veya yazmadan, talebi bitmiş ürün için somut bir kontrol listesine dönüştürün. Örnek: Bir kullanım kılavuzu için, herhangi bir düzenleyici başlamadan önce önkoşulları, sıralı eylemleri, kurtarma kılavuzunu ve kapanışı zorunlu kılın.

**Korunmalı.** ilan_amaç; alıcı; doğruluk; kanal

**Kaynak şekli.** CPU; sıfıra yakın çalışma süresi; GPU veya kiralama yok

**Sınır.** kaynak anlamını çıkarmaz veya gerçekleri seçmez

### Sözleşme Yüzey Gerçekleştiricisi

sınırlı dilbilgisi, morfoloji, tipografi, perspektif ve yazılı dönüşümleri dağıtım birimlerine uygular

**Sorumluluk.** Halihazırda onaylanmış bir plana dilbilgisi, morfoloji, tipografi ve izin verilen perspektifi uygulayın; yeni anlama karar veremez. Örnek: Yazılı bir emir planını, hiçbir zaman sağlanmayan bir güvenlik iddiasını eklemeden dilbilgisi talimatına dönüştürün.

**Korunmalı.**claim_authority; kaynak_ve_ilişki_bağlamaları; retorik_iş

**Kaynak şekli.** CPU; isteğe bağlı aday editör mevcut bir GPU kiralamasını kullanabilir ancak yetkisi yoktur

**Sınır.** Kapalı dil bilgisi aslına sadıktır ancak biçimsel olarak katı kalabilir

**Temel kamu araçları.**[uzay](https://github.com/explosion/spaCy)

## Yönetim, doğrulama ve operasyonlar

### Amf Ari


**Sorumluluk.** Sabitlenmiş argüman-ilişki sınıflandırıcısını sağlanan önerme çiftleri üzerinde çalıştırın ve puanlanan destek, çakışma, yeniden ifade etme veya ilişkisizlik girişimlerini döndürün. Önermeler yaratmaz, güdüleri ortaya çıkarmaz veya kendi etiketlerini tasdik etmez.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[AçıkVINO](https://github.com/openvinotoolkit/openvino),[AMF ARI RoBERTa OpenVINO modeli](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Sohbet Dizini Oluşturucu


**Sorumluluk.** Konuşmaları sohbet penceresinde bırakmak yerine uzun kayıtta tutar.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Dosya Dizin Oluşturucu


**Sorumluluk.** Uygun dosyaları keşfedin ve sınırlı, kaynağı koruyan indeksleme çalışması gönderin. Dosya sistemi tarihlerini, dosya adlarını veya çıkarılan metni yetkili oluşturma zamanı, kimlik veya amaç olarak değerlendirmemelidir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Donanım Telemetrisi


**Sorumluluk.** Arızaların güç, sıcaklık, bellek ve hızlandırıcı durumuyla karşılaştırılabilmesi için sınırlı makine durumu geçmişini kaydedin. Genel açıklama, özel örnekleme ritmini ve makine düzenini içermez.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[psutil](https://github.com/giampaolo/psutil)

### Resim


**Sorumluluk.** Görsel konseptin harici bir çıkarım sınırını aşmasına gerek kalmaması için görselleri yerel olarak üretin. Görüntü oluşturma, kanıt yetkisinden ve yayın izninden ayrı kalır.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[stabil-difüzyon.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Resim-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Z-Image-Turbo-Windows paketleme referansı](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Sorumluluk.** Ağır zihin. Daha yavaş ve daha büyük, gerçekten hızdan daha fazla düşünmeyi gerektiren sorular için saklanıyor.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Ollama Göm


**Sorumluluk.** Yazıyı tam kelimeler yerine anlamlara göre aranabilir hale getirir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[Ollama](https://github.com/ollama/ollama),[Nomik Gömülü Metin](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Güç Kiralama


**Sorumluluk.** Makinenin sessizce boşta kalmasını ve gerçek iş için tamamen uyanmasını sağlar.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Konuşmayı Yeniden Düzenleyen


**Sorumluluk.** Konuşmalara bir anlam ifade eden adlar verir, böylece liste ilk cümlelerden oluşan bir duvar yerine bulunabilir.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Anlamsal Gözlemci


**Sorumluluk.** Bir yanıtın, geldiğini iddia ettiği materyal tarafından desteklenip desteklenmediğini kontrol eder.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[Transformatörler](https://github.com/huggingface/transformers),[MiniKontrol](https://github.com/Liyan06/MiniCheck),[GerçekCG](https://github.com/derenlei/FactCG)

### Eğim Analizi


**Sorumluluk.** Her bir zihnin nasıl başarısız olduğunun ve bu durumun iyiye mi yoksa kötüye mi gittiğinin kaydını tutar.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[uzay](https://github.com/explosion/spaCy),[BlingAteş](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Konuşmalar


**Sorumluluk.** Konuşmayı metne dönüştürür; dolayısıyla konuşmak, bir şeyleri yazmanın bir yoludur.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[Konuşmalar](https://github.com/speaches-ai/speaches),[daha hızlı fısıltı](https://github.com/SYSTRAN/faster-whisper),[daha hızlı-damıtma-fısıltı-büyük-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Görev Hizmeti


**Sorumluluk.** Yetkili görev kayıtlarını, bunları hatırlatıcılara, çıkarımsal amaçlara veya derlem gerçeğe dönüştürmeden, planlanan çalışmayla ilgili kanıt olarak okuyun.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### vLLM


**Sorumluluk.** Gündelik zihin. Hızlı, her zaman dolu, hemen hemen her şeye cevap veriyor.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

**Temel kamu araçları.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Dayanıklı Sahne İşleri

sınırlı gruplar, kontrol noktaları, iptal, devam ettirme ve kısmi arıza

**Sorumluluk.** Uzun yapay aşamaları tek bir tarayıcı isteğine bağlamak yerine, doğru terminal durumlarıyla sürdürülebilen sınırlı işler olarak çalıştırın. Örnek: Kesintiden sonra pahalı bir muhakeme geçişini tekrarlamak yerine, doğrulanmış bir terfi kontrol noktasından sonra devam edin.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Yürütme + Bildirim Yöneticisi

atanan bağdaştırıcıyı çalıştırır ve fiziksel yöntemi, uç noktayı, model revizyonunu, karmaları, çağrı kenarlarını, zamanlamayı, yeniden denemeleri ve düzeni kaydeder

**Sorumluluk.** Atanan her uzmanı çalıştırın ve fiziksel olarak yürütülenleri girdileri, kimliği, zamanlaması, yeniden denemeleri ve sonuçlarıyla birlikte kaydedin. Örnek: sabitlenmiş AMF sınıflandırıcısının yalnızca yaptığını söyleyen bir bildirim etiketine güvenmek yerine Aşama 2'yi işlediğini gösterin.

**Korunmalıdır.** input_hashes; adaptör_kimliği; başarısızlık_durumu

**Kaynak şekli.** CPU koordinatörü; delegeler GPU yalnızca beyan edilen kira sahipleri aracılığıyla çalışır

**Sınır.** yürütmeyi kaydeder; kendi başarısını belgeleyemiyor

### GPU Kira Tahkimi


**Sorumluluk.** Fiziksel cihaz kimliğini açığa çıkarmadan veya halihazırda yayında olan işleri engellemeden, platform tarafından yönetilen hızlandırıcı iş yükleri arasındaki tavsiye niteliğindeki aktarımları koordine edin.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Güç İkamet Koordinatörü

**Sorumluluk.** Dağıtılmış platform gücü ve ikamet mekanizmalarında tek bir AKTİF, SICAK, BOŞTA ve ASLA durumu modelini koruyun.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

### Beklenen / Gözlemlenen Yük Defteri

her dişli sorumluluğunu gözlemlenen alanlara, hazırlığa, ihmallere, değere, maliyete, zamanlamaya, yeniden denemelere ve onarım talebine bağlar

**Sorumluluk.** Maliyet ve eksik girdiler de dahil olmak üzere, her dişli çarkın katkıda bulunması beklenenleri gerçekte dağıttıklarıyla karşılaştırın. Örnek: ilişki analizinin 40 saniye boyunca çalıştığını ancak editöre kullanılabilir bir bağlantı noktası sağlamadığını ortaya çıkarın.

**Korunmalı.** handoff_identity; sindirir; eksik_alanlar; maliyet_basis

**Kaynak şekli.** CPU; muhakeme ve doğrulama açısından sıfıra yakın

**Sınır.** taşınabilir bölüm zamanlaması, yürütme bildirimindeki fiziksel aşama/model zamanlamasının yerini almaz

### Ürün Farkındalıklı Kalite Müdürü

talep edilen ürün için retorik tamamlamayı, bağlantısal akıl yürütmeyi, okunabilirliği, tipografiyi, çoğaltmayı, dikkati, bütçeyi, örgüyü, eğimi ve yürütülebilir eylemleri kontrol eder

**Sorumluluk.** Bu spesifik ürünün beyan edilen okuyucusu ve amacı için ayrı kalite eksenlerinde çalışıp çalışmadığını değerlendirin ve ardından sorumlu onarım aşamasını belirleyin. Örnek: Bir kılavuz, her cümle dilbilgisi kurallarına uygun ve temele dayalı olsa bile kurtarma rehberini kaçırmakta başarısız olabilir.

**Korunmalıdır.** bireysel_axis_results; reddedilen_aday_evidence

**Kaynak şekli.** CPU artı sınırlı doğrulayıcı/deslop HTTP; tarihsel olarak en büyük 8. Aşama payı

**Sınır.** Tür eksenleri ölçülmeli ve versiyonlanmalıdır; bir opak kalite puanı yasaktır

### Makbuz + Promosyon Müdürü

Bağımsız olarak değişmezleri yeniden hesaplar ve yalnızca bir PASS makbuzundan yükseltmeye ve atomik yapıt yazmaya izin verir

**Sorumluluk.** Paketi bağımsız olarak doğrulayın ve yapıyı yalnızca gerekli her değişmez geçişten sonra yazın. Örnek: Oluşturucu başarılı olduğunu bildirdiğinde ancak makbuzu kaynak bağlamayı yeniden oluşturamadığında promosyonu reddedin.

**Korunmalı.** Failure_results; bilinmeyenler; yayın_kimliği; rollback_boundary

**Kaynak şekli.** CPU ve G/Ç; GPU veya kiralama yok

**Sınır.** bildirimin özgünlüğü sonuçta incelenen değişmez sürüm/yapılandırma bağlamasına bağlıdır

### Kaynak + Kayıp Kontrolü

kaynak kimliği, epistemik durum, çıkarım, icat ve reddedilen dallar

**Sorumluluk.** Her ifadeyi, onu kim veya ne sağladığına, ne zaman uygulandığına ve dikkate alındığı, çıkarıldığı, değiştirildiği, reddedildiği veya bilinmediği ile bağlantılı tutun. Örnek: Bir eylemi gerçekten yönlendiren önceki inancın üzerine yazmadan daha sonraki bir yeniden yorumlamayı koruyun.

**Korunmalıdır.** Tam grafik kimliği, ilişkinin kaynağı ve bildirilen bileşen sınırı.

**Kaynak şekli.** Canlı dağıtım, gerçek CPU, bellek, depolama, hızlandırıcı ve kiralama kullanımını kaydeder; bu genel katalog makine yerleşimini açığa çıkarmaz.

**Sınır.** Yalnızca beyan edilen grafik sorumluluğunu yerine getirebilir ve eksik veya desteklenmeyen yukarı akış kanıtlarını onaramaz.

## Bildirilen ek bileşenler

### Güvenli Web Ağ Geçidi

Özel platform hizmetlerini doğrudan genel internete maruz bırakmadan, onaylı istemcilerden kimliği doğrulanmış uzaktan erişim sağlar.

### Platform Sorumlusu

Hizmetleri bağımlılık sırasına göre başlatır, durumlarını gözlemler ve sınırlı yeniden başlatma eylemlerini gerçekleştirir. Başarısızlığı, çalışmaya devam eden hizmetlerin durumunu yeniden tanımlamadan koordineli denetimi ortadan kaldırır.

## Tamlık sınırı

Katalog, her çalışma zamanı tarafından yüklenen her geçişli paketi değil, bakımı yapılan mimari grafiğindeki aktif mantıksal bileşenleri kapsar. Gelecekteki bir yazılım sürümü, dağıtılan belirli baytlardan oluşturulan tam bir yazılım malzeme listesi ve lisans paketi gerektirir.
