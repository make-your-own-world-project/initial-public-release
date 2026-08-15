> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../README.md) | [Tüm diller](../README.md)

# Gerekçeyi Denetlenebilir Tutmak

![Bağımsız uzmanlar, kabul edilen ve reddedilen akıl yürütme yollarını kesin kanıtlara kadar takip ediyor](../../assets/reasoning-engine-inspectable-path.png)

## Denetlenebilir muhakeme

Akıl yürütme motoru, sınırlı uzmanların ve deterministik projeksiyonların bir dizisidir. Amacı, kesin kaynak kanıtlarından incelenebilir bir önerme ve ilişki grafiği oluşturmaktır. Bu, belgenin tamamının anlaşılmasını isteyen genel bir tamamlama istemi değildir.

```text
EXACT EVIDENCE ITEMS AND SOURCE SPANS
        |
DISCOURSE AND REFERENCE PREPROCESSING
        |
PROPOSITION AND RELATION CANDIDATES
        |
ARGUMENT RELATION CLASSIFICATION
        |
TYPED PROVENANCE GRAPH
        |
DETERMINISTIC DEPENDENCY AND WHY PROJECTION
        |
PRODUCT-SPECIFIC SELECTION AND RECONSTRUCTION
        |
INDEPENDENT VERIFIER AND RECEIPT
```

## Dilsel ön işleme

Kanıtlar, değişmez kaynak kimliklerine ve karakter uzaklıklarına bağlı sınırlı, boşluksuz dilimlere bölünür. Koreferans analizi referans zincirleri önerir. Retorik Yapı Teorisi analizi söylem yapısını ve işlenen çiftlerini önerir. Büyük boyutlu veya ilişkisiz yapılar, sessizce kesilmek veya ilk eşleşen ifadeyle eşlenmek yerine açık olarak kalır.

Bu araçlar dilsel yapıyı ortaya çıkarır. Kendi başlarına kişisel güdü veya argüman gerçeğini oluşturmazlar.

## Argüman ilişkisi sınıflandırması

Söylemden türetilmiş önerme çiftleri; destek, çatışma, eşdeğerlik veya yetkili ilişki yokluğu dahil olmak üzere küçük bir ilişki envanteri halinde sınıflandırılır. Her girişim işlenenlerini, puan dağılımını, model kimliğini ve düzenini korur. Eşiğin altındaki sonuç görünür kalır ve bir avantaj yaratmaz.

Kabul edilen ilişkiler, tam kaynak aralıklarına ve yöntem kimliğine sahip yönlendirilmiş grafik kenarları haline gelir. Belirsiz kaynak bağlama kapatılmıyor.

## Grafik projeksiyonu

Bağımlılık ve “neden” görüşü, halihazırda sınıflandırılmış kenarların deterministik bir yansımasıdır. Bir destek veya çatışma zincirini daha kullanışlı bir biçimde ortaya çıkarabilir. Yeni nedenler, çıkarlar veya sonuçlar icat edemez ve bunları bir uzmanın çıkardığını iddia edemez.

Grafik, yerleşik argüman değişim yapıları yoluyla dışarı aktarılabilir, ancak değişim gösterimi ikinci bir doğruluk deposu değildir ve bir model veya hızlandırıcı gerektirmez.

## Kaynak sınırları

Bu modeller sınırlı ön işleme işleri için yüklendiğinden, çekirdek referans ve söylem ayrıştırma, kiralanan hızlandırıcı kapasitesini kullanabilir. Bağımsız değişken sınıflandırması, kompakt bir uzman çıkarım yolundan geçecek şekilde tasarlanmıştır. Grafik projeksiyonu, seçim, kısıtlama çözme, kaynak kontrolleri ve alındı ​​doğrulaması sıradan CPU işleridir.

Tasarım, her modelin yerleşik kalmasını önler ve paylaşılan kiralama mekanizmasından kaçınmak için kopya çalışanların başlatılmasını yasaklar.

## Doğrulayıcının kanıtladığı ve kanıtlamadığı şey

Doğrulayıcı, gerekli bileşenlerin çalıştığını, kesin aralıkların korunduğunu, grafik projeksiyonunun tekrarlanabilir olduğunu, ürün bağlamalarının tutarlı olduğunu ve yükseltilen baytların kabul edilen paketle eşleştiğini kanıtlayabilir. Politikası dahilindeki uydurma bildirimleri, desteklenmeyen düzyazıyı, yanlış uç yönlendirmeyi, gizli geri dönüşleri ve eksik yetenekleri reddedebilir.

Yapısal doğruluk, her ilişki etiketinin uzman insan yargısıyla uyumlu olduğunu otomatik olarak kanıtlamaz. İlişki kalitesinin değerlendirilmesi, bağımsız olarak etiketlenmiş örnekler ve kesinlik, geri çağırma, yönlendirme ve kalibrasyon analizi gerektirir. Bu anlamsal kalite kapısı ayrı bir sorumluluk olmaya devam ediyor.

Bu sınır aynı zamanda aşağı yönlü bir dış modelin muhakeme otoritesi olmasını da engeller. Sınırlı bir gerçekleştirme görevi için desteklenen önermeleri ve yazılan ilişkileri alabilirken, kanıtlar, girişimler, grafik ve kabul kriterleri bağımsız olarak kullanılabilir durumda kalır. Akıcılık, yükü faydalı kılan mantığın sahipliğini üstlenmez.
