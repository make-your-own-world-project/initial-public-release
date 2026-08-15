> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../README.md) | [Minden nyelv](../README.md)

# Az érvelés ellenőrizhető tartása

![Független szakemberek, akik az elfogadott és az elutasított érvelési utakat pontos bizonyítékokhoz vezetik vissza](../../assets/reasoning-engine-inspectable-path.png)

## Ellenőrizhető érvelés

Az érvelési motor korlátozott szakemberek és determinisztikus vetületek sorozata. Célja, hogy pontos forrásból származó bizonyítékokból ellenőrizhető propozíció- és összefüggésgráfot építsen fel. Ez nem egy általános kitöltési felszólítás, amely a teljes dokumentumra következtet.

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

## Nyelvi előfeldolgozás

Az evidencia korlátos, hézagmentes szeletekre oszlik, amelyek megváltoztathatatlan forrásazonosságokhoz és karaktereltolásokhoz vannak kötve. A referencia-elemzés referencialáncokat javasol. A retorikai struktúraelmélet elemzése diskurzusszerkezetet és operanduspárokat javasol. A túlméretezett vagy kötetlen szerkezetek explicitek maradnak, ahelyett, hogy csendben csonkolnák vagy leképeznék őket az első egyező kifejezésre.

Ezek az eszközök feltárják a nyelvi szerkezetet. Nem maguk állapítják meg a személyes indítékot vagy az érvelési igazságot.

## Az argumentumreláció osztályozása

A diskurzusból származó állításpárok egy kis relációs leltárba vannak besorolva, beleértve a támogatást, a konfliktust, az ekvivalenciát vagy a nem hiteles relációt. Minden kísérlet megtartja operandusait, pontszámeloszlását, modellazonosságát és diszpozícióját. A küszöb alatti eredmény látható marad, és nem hoz létre élt.

Az elfogadott relációk irányított gráfélekké válnak, pontos forrástartományokkal és metódusazonossággal. A kétértelmű forrás-összerendelés lezárása sikertelen.

## Grafikon vetítés

A függőségi és „miért” nézet a már besorolt ​​élek determinisztikus vetülete. Előfordulhat, hogy egy támogatási vagy konfliktusláncot használhatóbb formában tár fel. Nem találhat ki új okokat, téteket vagy következményeket, és nem állíthatja, hogy ezeket egy szakember vezette le.

A gráf exportálható beépített argumentumcsere-struktúrákon keresztül, de a cserereprezentáció nem egy második igazságtároló, és nem igényel modellt vagy gyorsítót.

## Az erőforrások határai

A referencia- és diskurzuselemzés bérelt gyorsítókapacitást használhat, mivel ezek a modellek korlátos előfeldolgozási feladatokhoz vannak betöltve. Az argumentumok osztályozását úgy tervezték, hogy egy kompakt speciális következtetési útvonalon haladjanak keresztül. A grafikonok vetítése, a kijelölés, a kényszerfeloldás, a származási ellenőrzés és a nyugtaellenőrzés a CPU szokásos munkája.

A kialakítás elkerüli, hogy minden modell rezidens maradjon, és megtiltja a duplikált dolgozók elindítását, hogy elkerüljék a megosztott bérleti mechanizmust.

## Amit a hitelesítő bizonyít, és mit nem

Az ellenőrző bizonyítani tudja, hogy a szükséges összetevők lefutottak, a pontos tartományok fennmaradtak, a grafikon vetülete reprodukálható, a termék-összerendelések konzisztensek, és a kiemelt bájtok egyeznek az elfogadott köteggel. Elutasíthatja a koholt manifeszteket, a nem támogatott prózát, a rossz élirányt, a rejtett visszaeséseket és a hiányzó képességeket az irányelvén belül.

A szerkezeti helyesség nem bizonyítja automatikusan, hogy minden kapcsolatcímke megegyezik a szakértő emberi megítélésével. A kapcsolatminőség-értékelés önállóan felcímkézett példákat, valamint pontosságot, visszahívást, irányt és kalibrálást igényel. Ez a szemantikai minőségi kapu továbbra is külön felelősséget jelent.

Ez a határ azt is megakadályozza, hogy egy downstream külső modell váljon érvelési tekintélyré. Kaphat támogatott propozíciókat és tipizált kapcsolatokat egy korlátos megvalósítási feladathoz, miközben a bizonyítékok, próbálkozások, grafikon és elfogadási kritériumok egymástól függetlenül elérhetőek maradnak. A folyékonyság nem vállalja az érvelést, amely hasznossá tette a hasznos terhet.
