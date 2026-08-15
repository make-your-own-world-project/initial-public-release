> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../README.md) | [Tüm diller](../README.md)

# Sistem Nasıl Bir Arada Tutulur?

![Değiştirilebilir uzmanları ve incelenebilir bir kontrol düzlemini destekleyen korunmuş kayıt](../../assets/core-architecture-layers.png)

## Sorumlulukların ayrılması

Platform, birbirine dönüşmeden işbirliği yapan dört kaygıyı birbirinden ayırıyor:

1. **Koruma** orijinal kanıtları ve gözlemlenen kaynağı korur.
2. **Anlama** sürümlendirilmiş anlamsal nesneler, ilişkiler, zamansal durumlar,
  ve yorumları destekledi.
3. **Alma ve etkileşim** sorular için isteğe özel kanıtları bir araya getirir,
  keşif ve konuşma.
4. **Yapı yeniden inşası** sınırlı bir kanıt dünyasını ilan edilmiş bir dünyaya dönüştürür
  Bildirilen bir alıcı için ürün.

Ürün talimatları külliyat gerçeğine geriye doğru sızmaz. Bir bölüm, izleyici kitlesi, tür, retorik hareket veya kelime bütçesi tek bir çekilmeye aittir. Bu, kaynak eserin üzerindeki içsel bir etiket değildir.

## Katmanlı topoloji

```text
PRIMARY EVIDENCE
  immutable artifacts, interaction events, source identity, observed arrival
        |
        v
VERSIONED REPRESENTATIONS
  extracted text, media observations, chunks, entities, embeddings, locators
        |
        v
SEMANTIC AND TEMPORAL MAPS
  propositions, discourse links, argument edges, chronology, supersession,
  uncertainty, open attachment points, Personal Meaning Matrix contributions
        |
        +---------------------------+
        |                           |
        v                           v
INTERACTIVE CONTEXT             ARTIFACT CONTRACT
  request-scoped traversal        receiver, purpose, form, budget, evidence rules
        |                           |
        |                           v
        |                       REVERSE EXPANSION
        |                           |
        |                       WHOLE-TREE COLLAPSE
        |                           |
        |                       FORWARD RECONSTRUCTION
        |                           |
        +----------------------> HUMAN PROTOCOL + WEAVE
                                    |
                                INDEPENDENT GATES
                                    |
                              RECEIPT-GATED PRODUCT
```

## Katılım biliyormuş gibi davranmıyor

Varış kaydı, belirli baytların sisteme belirli bir kanal aracılığıyla ulaştığını belirtebilir. Yapıyı kimin yarattığına, içinde kimin göründüğüne, konusunun ne zaman ortaya çıktığına, bir dosya adının doğru olup olmadığına, neden önemli olduğuna veya içeriğinin kime ait olduğuna sessizce karar vermez. Bunlar ayrı kanıtları ve otoriteleri olan ayrı gözlemlerdir.

Mimari, orijinal eseri ondan türetilen temsillerden ayırır. Çıkarılan metin, açıklamalar, yerleştirmeler, sınıflandırmalar, özetler ve ilişkiler yeniden oluşturulabilir veya bunların yerine başkaları geçebilir. Kaynağın yerini almazlar.

## Etkileşimli ve belge yolları

Etkileşimli yanıtlama ve yapı oluşturma, kanıtları, kaynağı, yazılı ilişkileri, belirsizliği ve doğrulama mekanizmalarını paylaşır. Aynı iş akışından farklı kalırlar.

Etkileşimli bir istek, tam bir konuşmaya, görev yaşam döngüsüne, dar bir ilişki geçişine veya açıklamaya ihtiyaç duyabilir. Bir kitap kabı inşa etmeye ve tarihi bir ağacı küresel olarak çökertmeye gerek yok.

Artefakt üretiminin beyan edilmiş bir ürüne, alıcıya, bütçeye ve tüm artefakt planına ihtiyacı vardır. Budamadan önce ilgili geçici yapıyı görmeli ve dışarıda kalanların muhasebesini yapmalıdır.

## Sabit bir zincir yerine dinamik mimari

Montaj hattı ürün için derlenir. Farklı çıktılar farklı uzmanları kullanabilir, aynı uzmanları farklı şekilde sipariş edebilir veya bir yeteneğin birden fazla örneğini gerektirebilir. Yönetici, tek başına kodlanmış aşama adları yerine yetenek sözleşmelerini ve önceki kanıtları kullanır.

Evrensel değişmezler her satırda sabit kalır: kaynak kimliği, sahiplik, epistemik durum, belirsizlik, zarar muhasebesi, yazılı aktarımlar, maliyet gözlemi, bağımsız doğrulama ve geri alma.

Harici bir genel model, ölçülen katkısı aktarımı haklı çıkardığında, yazılan bir istasyonu işgal edebilir. Bakımı yapılan derlemi veya daha geniş kontrol düzlemi tarafından kodlanan yetkiyi değil, yalnızca o istasyonun ihtiyaç duyduğu istek kapsamlı yükü alır. Bu istasyonu değiştirmek veya kaldırmak, dayanıklı kaydı ve gelecekteki yeniden inşa kabiliyetini sağlam bırakır. Sınırlı istasyon, merkezi bir sistemin kurumsal değere dönüşeceği insan bilgisini almadan katkıda bulunabilir.
