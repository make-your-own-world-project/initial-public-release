> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../README.md) | [Tüm diller](../README.md)

# Gerçek Olan ve Geriye Kalan

![Farklı uygulama kapılarından geçen fikirler, testler, başarısızlıklar ve doğrulanmış yetenekler](../../assets/evidence-implementation-gates.png)

## Kanıt sınıfları

Kanıt modeli birkaç sınıfı farklı tutar:

- **birincil kanıtlar:** korunmuş kaynak eserleri ve etkileşim olayları;
- **türetilen kanıtlar:** çıkarılan metin, anlam birimleri, ilişkiler, sınıflandırmalar,
  zamansal gözlemler ve diğer versiyonlandırılmış gösterimler;
- **yürütme kanıtı:** bildirimler, çağrı gözlemleri, maliyetler, model kimlikleri ve
  aşama sonuçları;
- **kabul kanıtı:** bağımsız değişmezler, makbuzlar, tanıtılan paketler ve
  tam çıktı karmaları;
- **tasarım amacı:** mimari ve planlı davranış henüz uygulamada kanıtlanmamıştır;
- **tarihsel iddialar:** daha önceki bir yayının veya deneyin kendisi hakkında bildirdiği bilgiler.

Başarılı bir sınav yalnızca uyguladığı zarfın kanıtıdır. Sürüm belgesi, geçerli çalışma zamanının hâlâ onunla eşleştiğinin kanıtı değildir. Yüklü bir kitaplık, konuşlandırılmış bir yetenek değildir.

## Uygulanan temeller

Uygulama aşağıdaki sınırlı temelleri göstermiştir:

- içerik odaklı kaynak koruma ve eklenti odaklı kanıt işleme;
- ayrı yapılar, temsiller, konumlayıcılar ve kaynak olayları;
- aktöre ve diziye bağlı konuşma olayları;
- sınırlı kaynak dilimleriyle söylem ve çekirdek referans ön işleme;
- tam kaynak aralıkları ve tutulan girişimlerle argüman ilişkisi sınıflandırması;
- yazılı bir önerme ve ilişki grafiği;
- deterministik bağımlılık projeksiyonu;
- Belirsizlik içeren istek kapsamlı Kişisel Anlam Matrisi katkıları ve
  koruma bayrakları;
- sınırlı testlerde geriye doğru seçim ve aynı grafikte ileri tekrar oynatma nesneleri;
- küresel olarak sahip olunan anlamsal birim tahsisi ve geçmeli yapı planlaması;
- topraklanmış işleme zeminleri ve isteğe bağlı aday karşılaştırması;
- bağımsız makbuz kontrollü promosyon;
- dayanıklı eser işleri ve akıl yürütme görüntüleyicisi;
- içerik adresli yayınlarla kamuya açık belge yayın sınırı.

Bu ifadeler, vizyonun tamamının tamamlandığı iddiasını değil, gösterilen bileşen sınırlarını açıklamaktadır.

Gösterilen karşılaştırma aynı zamanda bir dış dişli sınırını da kaydeder. Bir sınır modeli, hazırlanmış, isteğe özel bir yük aldı ve bakımı yapılan külliyatı almadan veya yayın yetkilisi haline gelmeden daha iyi bir işleme katkıda bulundu. Kanıtlar bu sınırlı işlemi desteklemektedir; herhangi bir sağlayıcının test edilen yapı yolu dışında neleri tuttuğunu belirlemez; bu, ayrı bir sözleşme ve gizlilik sorunu olarak kalır. Yararlı katkının, sağlayıcının sahip olduğu değere yıkıcı bir düşüş için insan kaydının aktarılmasını gerektirmediğini ortaya koymaktadır.

## Kurulu platform terazisi

Yüklü uygulama ağacının sınırlı bir dosya sistemi envanteri yaklaşık 566.000 dosya ve 218 GiB'den oluşuyordu. Model varlıkları yaklaşık 172 GiB'e, bağımlılıklar ve dil çalışma süreleri 25 GiB'e, veri durumu ve diğer varlıklar 20 GiB'e ve uygulama kaynağı ise yaklaşık 184 MiB'a karşılık geliyordu. Envanter bazı okunamayan veya değişen girişlerle karşılaştı, dolayısıyla bunlar bir yazılım malzeme listesi yerine operasyonel ölçekli tahminlerdir.

Asimetri mimari hakkında kasıtlı bir kanıttır. Kaynak kodu, kurulu ayak izinin küçük bir parçasıdır; model ağırlıkları ve yeniden kullanılabilir çalışma süreleri buna hakimdir. Bu nedenle kontrol düzlemi, kurulu boyutu yetenek olarak ele almak yerine her uzmanın değerini, yetkisini ve işletme maliyetini izler. Gelecekteki bir dağıtılabilir kod sürümü, yapıya özgü bir bağımlılık envanterine, tam sürümlere, lisanslara, karmalara ve yeniden üretilebilir yapı sınırına ihtiyaç duyar.

## Tasarım tarafından korunan mühendislik dersleri

Geliştirme birkaç kalıcı mühendislik dersi üretti:

- kayıp bir uzmanı simüle etmek için genel bir modelin teşvik edilmesi;
- bir süreç çıkışını veya kendi kendine bildirilen bildirimi, yeterliliğin kanıtı olarak ele almak;
- anlamsal sınıflandırma ve uzman çalışmasının kopyalanmasının ardından söylemin yürütülmesi;
- tekrarlanan ilk alıntının kaynak olarak atanması;
- tüm dosyadaki bir kanıt öğesinin kompozisyonu doğrulanamaz hale getirmesine izin vermek;
- sıfır kabul edilen ilişkiye boru hattı hatası olarak muamele etmek;
- deterministik bir grafik projeksiyonunu ayrı olarak yürütülen bir uzmanla karıştırmak;
- desteklenmeyen veya okunamayan düzyazı üretirken bir örgü profilini eşleştirmek;
- küçük ve orta ölçekli vakalar kusuru ortaya çıkardığında tüm derlem çalıştırmalarıyla hata ayıklama;
- Bir ürünü diğerini geriletebilecek şekilde ayarlamak.

Kamu mimarisi bu düzeltmeleri korur çünkü bunlar mevcut kısıtlamaların amacını açıklar ve gelecekteki iyileştirmeleri daha güvenilir hale getirir.

## Mevcut geliştirme fırsatları

Bazı önemli yetenekler hala eksik veya daha geniş kanıtlar gerektiriyor:

- ilişki etiketleri yalnızca yapısal değil, bağımsız uzman kalitesi değerlendirmesine de ihtiyaç duyar
  doğrulama;
- çapraz mevduat zamansal bağlantıları ve yeniden ilişkilendirme, daha büyük ölçeklerde sürekli testlere ihtiyaç duyar
  karma kaynak sınırları;
- üst düzey kişisel sürücüler, kaynağa bağlı kanıt sağlanana kadar doldurulmamalıdır ve
  mercek davranışı onları haklı çıkarır;
- farklı ürün türlerinin kalibre edilmiş, regresyon korumalı montaj hatlarına ihtiyacı vardır;
- İnsan Protokolü geribildiriminin boylamsal sonuç kanıtlarına ihtiyacı vardır;
- Figüratif ve anlatısal mekanizmalar, ürün odaklı değerlendirmeyi gerektirir
  yetki verilir;
- Kamuya açık belgelerin tamamı, özel kayıt olduğundan sürekli editoryal inceleme gerektirir
  gelişir.

## Doğrulama merdiveni

Gelişim küçükten büyüğe doğru ilerler:

1. saf şema ve değişmez sabitler;
2. bilinen topolojiye sahip kısa anlamsal örnekler;
3. küçük gerçek kaynak dilimleri;
4. orta karma formatlı ve karma zamanlı dilimler;
5. önceki düzeyler geçtikten sonra daha büyük ölçeklenebilirlik sınırları;
6. Aynı kanıtlar altında insan tarafından yazılan ve sistem tarafından oluşturulan karşılaştırma,
  alıcı, form ve bütçe.

Karşılaştırma, her kusuru genel "model kalitesine" atamak yerine, kaybın grafik seçiminden mi, önem tahsisinden mi, ileri tekrar oynatmadan mı, gerçekleştirmeden mi yoksa son okunabilirlikten mi kaynaklandığını teşhis eder.
