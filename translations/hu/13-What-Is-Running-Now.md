> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../README.md) | [Minden nyelv](../README.md)

# Mi fut most

![A felelősség által szervezett helyi gépezet egy közös, ellenőrzött gerinc köré](../../assets/public-machinery-catalog.png)

## Hogyan kell olvasni ezt a katalógust

A katalógus a Mission Control adatközponti nézetének nyilvános megfelelője. Leírja, hogy az egyes fogaskerekek mihez járulnak hozzá, és mi veszne el, ha eltűnnének, anélkül, hogy nyilvánosságra hoznák a privát címeket, a gépelrendezést, a hitelesítő adatokat, a fájl elérési utat vagy a működési ütemet. Az élő gráf marad az igazság operatív forrása.

A komponens állapota számít. Egy eszköz lehet aktív, forrásrendszerként megtartott, kiértékelt, de nem elfogadott, vagy visszavonult elődje. A jelen katalógusban való jelenlét nem ad egy komponensnek a meghatározott szerepkörén túlmutató jogosultságot.

Ez a szabály magában foglalja a külső határmenti képességet is. Használatkor egy behatárolt állomást foglal el, és a karbantartott korpuszhoz való korlátlan hozzáférés helyett egy célra épített hasznos terhet kap. A hasznos teher támogatja a deklarált működést, de kihagyja a tágabb rendszer rekonstrukciójához vagy a jövőbeni kivonások önálló előállításához szükséges tartós állapotot. Az állomás munkát kap, nem pedig az emberi nyilvántartás őrzését, amelyből egy központosított intézmény tartós értéket tudna kinyerni.

## Utak a rendszerbe és a rendszer körül

### Robot Brain (LibreChat)


**Felelősség.** Biztosítsa a cserélhető, ember felé néző beszélgetési ablakot. Kéréseket és válaszokat hordoz, miközben a tartós memória, a visszakeresés, az érvelés és az ellenőrzés az alatta lévő szolgáltatásokban marad.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[LibreChat](https://github.com/danny-avila/LibreChat),[Node.js](https://github.com/nodejs/node)

### Beszélgetés Splitter


**Felelősség.** Észreveszi, ha egy csevegés két témává vált, és felajánlja, hogy a befejezett tárgyat külön iktatja.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[FastAPI](https://github.com/fastapi/fastapi)

### Küldetésirányítás


**Felelősség.** Az ablak a gépre: mi fut, mi igényel figyelmet, és mit csinál éppen. Ezen a közzétételi határon az állapotoldal jelenti a helyi telepítésen működő összes felügyelt rendszert.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Működési állapot jelentések szolgáltatás állapota; elfogadott műtermékek és nyugták határozzák meg a külön végrehajtási és szemantikai bizonyíték határait.

**Fő nyilvános eszközök.**[FastAPI](https://github.com/fastapi/fastapi),[Graphviz](https://gitlab.com/graphviz/graphviz),[Psycopg](https://github.com/psycopg/psycopg)

### Szemantikus útválasztó


**Felelősség.** A korlátozott kéréseket a megfelelő helyi motorhoz irányítsa, és külső következtetések használata előtt kifejezett engedély szükséges. A költséges képességet csak akkor választja ki, ha a kérés igazolja a mért költségét.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[FastAPI](https://github.com/fastapi/fastapi). Az Envoy és a vLLM Semantic Router továbbra is a forrásindexben szerepel, mint ellenőrzött vagy megszüntetett elődök, nem pedig a jelenlegi futásidejű függőségek.

### Teljes ügynöktörténetek


**Felelősség.** Megőrzi a teljes, rendezett ügynöki eseményfolyamokat interakciós bizonyítékként, beleértve az emberi fordulatokat, a segédfordulókat, az eszközöket, a hibákat és a javításokat. Az előzmények rögzítik, mi történt; nem változtatják az ügynöki nyilatkozatokat ellenőrzött tényekké.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak azt szállítja, amit a forrása és eredete megállapít; a downstream értelmezés külön marad.

### Projekt dokumentumok


**Felelősség.** Őrizze meg a magánterveket, bizonyítékokat és projektrekordokat, amelyek elmagyarázzák, miért létezik a platform, és hogyan változott az architektúrája. A nyilvános termékek felülvizsgált származékokat fogyasztanak, ahelyett, hogy a magándokumentum helyét fednék fel.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak azt szállítja, amit a forrása és eredete megállapít; a downstream értelmezés külön marad.

### Vikunja


**Felelősség.** A külső feladatrendszer megőrzése a platform előtti, független tulajdonú forrásként. Az integráció elolvashatja az engedélyezett feladatbizonyítékokat anélkül, hogy a feladatrendszert beépítené a korpuszba vagy megváltoztatná az életciklusát.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak azt szállítja, amit a forrása és eredete megállapít; a downstream értelmezés külön marad.

**Fő nyilvános eszközök.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Megőrzés és visszakeresés

### Tudásfelvétel


**Felelősség.** A dolgok bejutásának módja. Dobj le egy dokumentumot, egy export dokumentumot, egy halom feljegyzést, és a semmi helyett valahol megtalálható helyen landol.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### MongoDB


**Felelősség.** Maguk a beszélgetések, ahogy mondták.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** A rendelkezésre állás és az integritás szükséges; a tárolt adatok nem értelmezik és nem igazolják magukat.

**Fő nyilvános eszközök.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Felelősség.** Tartós strukturált projektrekordokat, származtatott állapotokat és keresési indexeket őriz, amelyek célja a cserélhető alkalmazásszolgáltatások túlélése. A tárolt iratok külön tekintélyt és eredetet őriznek meg, ahelyett, hogy egyetlen megkülönböztethetetlen emlékké válnának.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** A rendelkezésre állás és az integritás szükséges; a tárolt adatok nem értelmezik és nem igazolják magukat.

**Fő nyilvános eszközök.**[PostgreSQL](https://github.com/postgres/postgres),[pgvector](https://github.com/pgvector/pgvector)

## Érvelés és rekonstrukció

### Érvkapcsolat osztályozó

rögzített AMF_ARI OpenVINO CPU besorolása következtetés, ütközés, újrafogalmazás vagy kapcsolat hiánya esetén

**Felelősség.** Osztályozza két benyújtott javaslat közötti kapcsolatot; nem hoz létre sem javaslatot, sem kikövetkeztető személyes indítékot. Példa: különböztesse meg a másikat alátámasztó állításokat az ellentmondó állításoktól, vagy ad vissza nem támogatott összefüggést.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[AMF ARI RoBERTa OpenVINO modell](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Emberi tárgyak


**Felelősség.** Határozza meg azokat az emberrel szembeni termékeket, amelyeket az összeszerelősor tud építeni. Minden terméknek megvan a maga vevője, célja, szerkezete, bizonyítékokra vonatkozó szabályzata és szállítási szerződése, nem pedig egy általános vázlatot osztanak meg.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Földelés + szállítás érvényesítése

független átvételi kapu a hűség, származás, elvesztés, találmány, szövés és szövegértés ellenőrzése felett

**Felelősség.** Függetlenül ellenőrizze, hogy a műtárgy megőrzi-e a támogatott jelentést, és megfelel-e a bejelentett szállítási szerződésének a kiadás előtt. Példa: utasítson el egy olvasható bekezdést, amely következtetést kitalál, és külön utasítson el egy megalapozott dokumentumot, amelynek szerkezete használhatatlan a célolvasó számára.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Közönség felbontása

vevő állapota, előfeltételei, nyilvántartása és relevancia

**Felelősség.** Írja le, mit kell tudnia, mire van szüksége és mit kell tolerálnia a megcélzott vevőnek, miközben a feltételezéseket egyértelműen meg kell őriznie. Példa: kérjen otthoni útmutatót a pH magyarázatához, mielőtt a medencetechnikus által ismert rövidítéseket használná.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Egész fa összecsukása + csomagok

konténer-korlátozott partíció, kijelölés, nyereség és veszteség

**Felelősség.** Válassza ki és egyensúlyozza ki, hogy mi fér bele a kért műtermékbe, miközben rögzíti a kihagyottakat, és megőrzi a fa értelmes alakját. Példa: tartsa meg minden fő ágat egy 1000 szavas cikkben, ahelyett, hogy a legnagyobb forráság felemésztené a teljes költségvetést.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[submodlib](https://github.com/decile-team/submodlib),[letérdelt](https://github.com/arvkevi/kneed)

### Kompakt működő modell

hordozható kérési hatókörű hordozó kiválasztott egységekhez, kapcsolatokhoz, pályákhoz, forrásblokkokhoz, tervekhez, fogantyúkhoz és átadási főkönyvekhez

**Felelősség.** Csomagolja a kiválasztott tényeket, összefüggéseket, kronológiát, bizonytalanságot, kudarcokat és forrásmegoldásokat egy hordozható munkaspecifikus kontextusba. Példa: adja meg a szerkesztőnek a készlet-karbantartási láncot, és azt, hogy lépései miért kapcsolódnak egymáshoz anélkül, hogy betöltené a teljes korpuszt vagy eldobná a hivatkozásokat.

**Meg kell őrizni.** source_spans; relációazonosítók; kronológia; bizonytalanság; kudarcok; szupersession; ismeretlenek

**Erőforrás alakja.** CPU és RAM arányos a korlátozott kijelöléssel; nincs GPU vagy bérlet

**Határ.** A minőséget az upstream kapcsolat és a betéti állam lefedettsége határolja

### Szállítási mechanika

regiszter, módok, szövési profilok, ingerlés, sűrűség és deslop vezérlők

**Felelősség.** Adjon meg mért szállítási korlátokat, például az ingerlést, a sűrűséget, a regisztert és a szövési pályát ehhez a termékhez és a közönséghez. Példa: adjon meg egy gyerekmagyarázatot rövidebb csomagokról és más ismétlődési mintáról, mint egy technikai jelentés, anélkül, hogy megváltoztatná a mögöttes tényeket.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### A diskurzus előfeldolgozása

pontos korlátos szeletek, FastCoref referencia jelöltek és bérelt isanlp RST operandus hivatkozások

**Felelősség.** A pontos forráskoordináták megőrzése mellett azonosítsa a jelölt referenseket és a diskurzus terjedelmét, mielőtt osztályozást végezne. Példa: kapcsolja az 'it'-t a megnevezett pumpajelölthez, és tárja fel a két tagmondatot, amelyeket ok-okozati diskurzuskapcsolat köt össze.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Egész műtárgy előrekonstrukció

előfeltételek, referensek, oksági ragasztó, előrehaladás, bevezetés és következtetés

**Felelősség.** A kiválasztott anyag újjáépítése az olvasók sorrendjében, helyreállítva az előfeltételeket, referenciákat, ok-okozati összefüggéseket, előrehaladást és őszinte befejezést. Példa: mutassa be a célt az eljárás előtt, és zárja le a megválaszolatlan kérdést, amikor nincs következtetés.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Grafikon Miért és függőségi vetület

osztályozott gráfélek determinisztikus nézete, amely nem vezethet be új érvelési állításokat

**Felelősség.** Az elfogadott relációélek lefordítása ellenőrizhető függőségekké és miért nézetek értelmezés hozzáadása nélkül. Példa: mutassuk meg, hogy a B következtetés az A premisszától függ, mert létezik az a pontos osztályozott él.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[NetworkX](https://github.com/networkx/networkx)

### Földelt interaktív válasz


**Felelősség.** Adjon vissza egy társalgási választ a megfelelő érveléssel, eredettel, bizonytalansággal és bővítési útvonalakkal. A válaszútvonal bejárhat teljes beszélgetéseket és bizonyítékok életciklusait anélkül, hogy dokumentumgenerálásnak tenné ki magát.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Emberi protokoll híd

a rögzített támogatott hasznos terhelés vevő-orientált kódolása

**Felelősség.** A rögzített, támogatott rakományt a termékszerződés és a mért szállítási minta felhasználásával a kívánt személy által követhető formává alakíthatja; a bizonyítékokon nem változtathat. Példa: alakítsa át ugyanazt a megalapozott érvelési láncot tömör e-maillé vagy szakaszos útmutatóvá a kézbesítési struktúra megváltoztatásával, nem pedig következtetésekkel.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Interaktív kontextus-összeállítás


**Felelősség.** Készítsen korlátos bizonyítékokat és érvelési grafikont az aktuális kérdéshez, megőrizve a kronológiát, a javításokat, a hibákat, a forrásazonosítót és a jogosultságot. Kontextust biztosít a válaszhoz anélkül, hogy a korpuszt keresési kivonatokká simítaná.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Veszteségmentes csatlakozás


**Felelősség.** Az értelmezés előtt fogadjon el eredeti bájtokat és natív eseményeket, csak a megfigyelt érkezési tényeket rögzítse. A leírások, a tartalomból kikövetkeztetett időbélyegek, az identitások és a kapcsolatok külön verziójú megfigyelések maradnak.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Elsődleges bizonyíték


**Felelősség.** Tartsa meg azokat a mérvadó letéteket, amelyekre a későbbi képviseletek és termékek visszavezethetők. Létezésük akkor is érvényes, ha a rendszer még nem tudja megmagyarázni jelentésüket vagy kapcsolatukat.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Teljes ideiglenes fa

teljes pre-metszés bizonyíték, függőség, alternatíva és hibastruktúra

**Felelősség.** Tartsa meg a teljes kérési hatókörű jelöltfát, beleértve az alternatívákat, a hibákat, az ismeretleneket és a helyettesített nézeteket, így az összecsukás láthatja, mit veszítene. Példa: tartsa meg a sikertelen kezelést és a későbbi korrekciót is, mielőtt kiválasztaná az útmutató anyagát.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Érvelési grafikon

kronológia, típusos kapcsolatok, követelések életciklusai, kudarcok és bizonytalanság

**Felelősség.** Fenntartja a javaslatok, kronológia, próbálkozások, eredmények, konfliktusok, függőségek és bizonytalanságok kérés szerinti térképét. Példa: csatlakoztasson egy sikertelen kezelést az azt felváltó korrekcióhoz anélkül, hogy bármelyik állapotot törölné.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Kérelem + Műtárgy szerződés

cél, vevő, konténer, csatorna, költségvetés és valóság

**Felelősség.** Rögzítse a célt, a vevőegységet, a terméket, a csatornát, a költségvetést és az igazságszabványt, hogy minden alsó fogaskerék ugyanazt a feladatot oldja meg. Példa: különböztesse meg az 500 szavas általános olvasói magyarázatot a technikai eseményről szóló jelentéstől a bizonyítékok kiválasztásának megkezdése előtt.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Fordított bővítés

metszés nélkül visszafelé gyűjteni; határhozzájárulás mérése

**Felelősség.** A kéréstől vagy a későbbi bizonyítékoktól a korábbi kapcsolódó feljegyzések felé haladva gyűjtse össze a jelölt teljes útját, mielőtt bármit is eldobna. Példa: kövesse az aktuális algákkal kapcsolatos kérdést a korábbi pH, medenceméret, karbantartás és használati kontextus rekordokon keresztül.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Gépelt retorikai mozdulatok

szemantikai munkák és függőségek, soha nem fejlécek részkarakterláncok

**Felelősség.** Minden kiválasztott egységhez rendeljen hozzá egy kommunikációs munkát és függőséget a termékszerződés alapján, ne pedig egy megfelelő címszót. Példa: a bizonyítékokat jelölje meg a követelés alátámasztójaként, a kudarcot pedig a helyreállítás beállításaként, ahelyett, hogy mindkettőt „háttérnek” nevezné.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Szemantikai rekonstrukció

entitások, javaslatok, epizódok, próbálkozások, eredmények és kérdések

**Felelősség.** A forrásmegfigyeléseket tulajdonított szemantikai objektumokká alakíthatja anélkül, hogy eldöntené azok végső fontosságát vagy megjelenítését. Példa: a javasolt javítást, a kísérletet, a sikertelenséget és a fennmaradó kérdést külön csatolt rekordként ábrázolja.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Verziós ábrázolások


**Felelősség.** átiratok, szerkezet, szöveg, OCR, elrendezés és származtatott nézetek

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Miért számított

a tulajdonított motivációt, aggodalmat, következményt és aktuális relevanciát

**Felelősség.** Közvetlen és kifejezetten tulajdonított bizonyítékot hordozzon arra vonatkozóan, hogy miért fordították rá a figyelmet, így a megalapozatlan okok ismeretlenek maradnak. Példa: őrizze meg, hogy egy karbantartási feladat fontos volt, mert megvédte a megosztott eszközöket használó embereket, ha a rekord támogatja, ahelyett, hogy pusztán technikai kérdésből tippelné ki az indítékot.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Érvelés + Artifact Engine

nyugtafüggő rekonstrukció, összeomlás, Human Protocol és atomic Markdown rendering

**Felelősség.** Koordinálja a korlátos rekonstrukciós és renderelési útvonalat, és tegye közzé az egyes szakaszok nyugtáját; nem helyettesíti a szakvéleményt. Példa: szerkesztési kérés szállítása kijelölésen, tervezésen, megvalósításon, érvényesítésen és atomi íráson keresztül.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Assembly + Capability Manager

visszafelé járja a kötelező mezőket, árazza az előfeltételeket, becsületes szakembereket választ ki, függőségi hullámokat rendel, és kihagyja a nulla értékű munkát

**Felelősség.** Válassza ki, mely szakemberekre van szükség, milyen sorrendben futnak be, és melyik munka nem ad hozzáadott értéket; nem látja el a feladatukat. Példa: ütemezze a reláció megvalósítását a mondatmegvalósítás előtt, és hagyjon ki egy nem elérhető stilisztikai lépést, amely nem járul hozzá semmi szükségeshez.

**Meg kell őrizni.** must_preserve_fields; field_lineage; explicit_unavailability

**Erőforrás alakja.** CPU; alacsony memória; nincs GPU vagy bérlet

**Határ.** A költség- és értékmegfigyelések feltárják a döntéseket, de soha nem határozzák meg az emberi fontosságot

### Atomic Carrier költségvetési egyeztető

megméri az oszthatatlan forrás-, ragasztó- és relációhordozókat a megvalósítás előtt, és újraelosztja a rögzített teljes termékköltségvetést valódi szakasz-lazával

**Felelősség.** Ellenőrizze, hogy az oszthatatlan tények és kapcsolathordozók beleférnek-e az egyes szakaszokba, majd csak a rendelkezésre álló lazaságot mozgassa, miközben megőrzi a dokumentum teljes költségvetését. Példa: nagyítson ki egy 90 szavas eljárási részt, amely a szükséges 120 szavas atomi utasítást tartalmazza úgy, hogy egy másik szakaszból kölcsönöz fel nem használt szavakat.

**Meg kell őrizni.** teljes_termékköltségvetés; kötelező_retorikai_munkák; forrás_hatóság; graph_shape

**Erőforrás alakja.** CPU; közel nulla futásidő; megakadályozza az elpazarolt Stage 8 GPU/modell/ellenőrző munkát

**Határ.** nem tömöríthet oszthatatlan propozíciót; sikertelen, ha az összes szükséges fuvarozó meghaladja a bejelentett termékköltségvetést

### Source-Bound Rebinding Manager

csak egy teljes elszigetelt ágat helyez át, ha a hozzárendelt termékfeladat nem kompatibilis, és egy cél bizonyíthatóan kompatibilis

**Felelősség.** Helyezzen át egy teljes, elszigetelt bizonyíték ágat arra a részlegre, akinek a feladata jogosan használhatja azt, miközben elutasítja a kétértelmű vagy összefüggést hordozó lépéseket. Példa: rendeljen hozzá egy önálló helyreállítási megjegyzést a beállításból a hibaelhárításhoz anélkül, hogy mindkét szakaszban megkettőzné.

**Meg kell őrizni.** ág_identitás; source_spans; relációazonosítók; marginális_nyereség_főkönyv

**Erőforrás alakja.** CPU; alacsony késleltetési idő; nincs GPU vagy bérlet

**Határ.** elutasítja a kapcsolattartó, kétértelmű, részleges vagy túlzott kapacitású mozgásokat

### Dokumentumszintű kapcsolatmegvalósító

az elfogadott azonos metszetű és keresztmetszetű érvelési éleket kompakt, egymástól függetlenül újrajátszható összekötő nyelvvé alakítja mindkét operandus megismétlése nélkül

**Felelősség.** Változtassa át az elfogadott gráfviszonyokat rövid összekötő nyelvvé, miközben az irány, az operandusok és a forrástartományok egymástól függetlenül újrajátszhatók. Példa: valósítsa meg az A-ok-B-t korlátos ok-okozati hídként, ahelyett, hogy A-t és B-t egymáshoz nem kapcsolódó tényekként nyomtatná ki.

**Meg kell őrizni.** reláció_iránya; operandus_identitás; pontos_hordozó_távolságok; source_spans; section_lineage

**Erőforrás alakja.** CPU; közel nulla futásidő; nincs GPU vagy bérlet

**Határ.** csak explicit elfogadott kapcsolatfajtákat valósít meg; a kompakt hidak megőrzik a tipizált élazonosságot, de mechanikusan megfogalmazottak maradnak; az azonos hordozójú, kétértelmű, implicit és ismeretlen élek láthatóak maradnak a gráfban, de prózai értelemben nem érvényesülnek

### Knowledge Engine


**Felelősség.** Koordinálja a csatlakozást, a származtatott ábrázolásokat, a keresést, a származást és a tartós munkákat anélkül, hogy ezeket a felelősségeket egyetlen igazságállapotba vonná össze. A támogatott interfészeket a fogyasztók elé tárja, miközben az elsődleges bizonyítékok egymástól függetlenül kezelhetők maradnak.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Gépelt záradék/mondat mikrotervező

forráshoz kötött hordozókat rendel a gépelt retorikai feladatokhoz, és záradék-, mondat- és bekezdésterveket állít össze

**Felelősség.** A jóváhagyott jelentéseket és kapcsolatokat tagmondat-, mondat- és bekezdésmunkákra bontja, miközben megőrzi forráskötéseiket; nem talál ki fogalmazást vagy állításokat. Példa: tervezzen egy ok-klauzulát, majd a következményt és az átmenetet a felületmegvalósító számára.

**Meg kell őrizni.** szemantikai_egységazonosítók; relációazonosítók; forrás_űrlapok

**Erőforrás alakja.** CPU; alacsony késleltetési idő; nincs GPU vagy bérlet

**Határ.** nem talál ki hiányzó javaslatot, és nem javít egy besorolatlan kapcsolatot

**Fő nyilvános eszközök.**[borsos](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire)

### Termékszerződés menedzser

átalakítja a műfajt, a vevőt, a célt, a csatornát, a valódiságot, a figyelmet és a költségvetést a szükséges termékmezőkké és retorikai munkává

**Felelősség.** Változtassa a kérést a késztermék konkrét ellenőrzőlistájává anélkül, hogy bizonyítékot választana vagy megírna. Példa: felhasználói kézikönyv esetén előfeltételek, elrendelt műveletek, helyreállítási útmutatás és bezárás szükséges a szerkesztő elindulása előtt.

**Meg kell őrizni.** deklarált_cél; vevő; igazságosság; csatorna

**Erőforrás alakja.** CPU; közel nulla futásidő; nincs GPU vagy bérlet

**Határ.** nem következtet a forrás jelentésére, és nem választ tényeket

### Szerződés felületi megvalósítója

korlátos nyelvtant, morfológiát, tipográfiát, perspektívát és tipizált transzformációkat alkalmaz a szállítási egységekre

**Felelősség.** Alkalmazza a nyelvtant, a morfológiát, a tipográfiát és a megengedett perspektívát egy már jóváhagyott tervre; nem dönthet új jelentésről. Példa: alakítson át egy gépelt felszólító tervet nyelvtani utasítássá anélkül, hogy olyan biztonsági állítást adna hozzá, amelyet soha nem adtak meg.

**Meg kell őrizni.** követelés_hatóság; forrás_és_kapcsolat_kötések; retorikai_munka

**Erőforrás alakja.** CPU; Az opcionális szerkesztőjelölt használhat meglévő GPU-bérletet, de nincs jogosultsága

**Határ.** A zárt nyelvtan hű, de stilisztikailag merev maradhat

**Fő nyilvános eszközök.**[borsos](https://github.com/explosion/spaCy)

## Kezelés, ellenőrzés és műveletek

### Amf Ari


**Felelősség.** Futtassa a rögzített argumentum-reláció osztályozót a megadott javaslatpárokon, és adja vissza a pontozott támogatást, ütközést, újrafogalmazást vagy kapcsolat nélküli kísérletet. Nem hoz létre javaslatokat, nem következtet motívumokra, és nem tanúsítja saját címkéit.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[OpenVINO](https://github.com/openvinotoolkit/openvino),[AMF ARI RoBERTa OpenVINO modell](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Chat Indexelő


**Felelősség.** A beszélgetéseket hosszú ideig rögzíti ahelyett, hogy a csevegőablakban hagyná őket.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Fájl indexelő


**Felelősség.** Fedezze fel a megfelelő fájlokat, és küldjön be korlátozott, származást megőrző indexelési munkát. Nem kezelheti a fájlrendszer dátumait, fájlneveit vagy kivonatolt szövegét mérvadó létrehozási időként, identitásként vagy indítékként.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Hardveres telemetria


**Felelősség.** Rögzítse a gép állapotának korlátos előzményeit, hogy a meghibásodásokat össze lehessen hasonlítani a teljesítmény, a hőmérséklet, a memória és a gyorsító állapotával. A nyilvános leírás elhagyja a privát mintavételezési ütemet és a gépi elrendezést.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[psutil](https://github.com/giampaolo/psutil)

### Kép


**Felelősség.** Készítsen képeket helyben, így a vizuális koncepciónak nem kell átlépnie egy külső következtetési határt. A képalkotás elkülönül a bizonyítékhatóságtól és a közzétételi engedélytől.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[stabil diffúzió.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Image-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Z-Image-Turbo-Windows csomagolási hivatkozás](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Felelősség.** A nehéz elme. Lassabb és nagyobb, olyan kérdésekhez tartva, amelyek valóban több gondolkodást igényelnek, mint sebességet.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Ollama Embed


**Felelősség.** A pontos szavak helyett jelentés alapján kereshetővé teszi az írást.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[Ollama](https://github.com/ollama/ollama),[Névleges szöveg beágyazása](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Power Lease


**Felelősség.** Lehetővé teszi, hogy a gép csendesen járjon, és teljesen felébredjen a valódi munkához.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Beszélgetés újracímzője


**Felelősség.** Olyan neveket ad a beszélgetéseknek, amelyek jelentenek valamit, így a lista inkább megtalálható, mint az első mondatok fala.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Szemantikai megfigyelő


**Felelősség.** Ellenőrzi, hogy a választ alátámasztja-e az az anyag, amelyről azt állítja, hogy származik.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[Transzformátorok](https://github.com/huggingface/transformers),[MiniCheck](https://github.com/Liyan06/MiniCheck),[FactCG](https://github.com/derenlei/FactCG)

### Slop elemzés


**Felelősség.** Nyilvántartást vezet arról, hogy az egyes elmék hogyan hibáznak, és hogy ez egyre jobb vagy rosszabb lesz.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[borsos](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Beszédek


**Felelősség.** A beszédet szöveggé alakítja, így a beszéd a dolgok lejegyzésének egyik módja.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[Beszédek](https://github.com/speaches-ai/speaches),[gyorsabb-suttog](https://github.com/SYSTRAN/faster-whisper),[gyorsabb-desztil-súg-nagy-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Feladatszolgáltatás


**Felelősség.** Olvassa el az engedélyezett feladatrekordokat a tervezett munka bizonyítékaként anélkül, hogy emlékeztetőkké, kikövetkeztetett indítékokká vagy korpusz-igazsággá alakítaná azokat.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### vLLM


**Felelősség.** A mindennapi elme. Gyors, mindig feltöltött, szinte mindenre válaszol.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

**Fő nyilvános eszközök.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Tartós színpadi munkák

korlátozott kötegek, ellenőrző pontok, törlés, folytatás és részleges meghibásodás

**Felelősség.** Futtasson hosszú műtermék-szakaszokat folytatható, korlátos munkákként valós terminálállapotokkal, ahelyett, hogy egyetlen böngészőkéréshez kötné őket. Példa: folytassa az ellenőrzött előléptetési ellenőrzőpont után, ahelyett, hogy megszakítás után megismételne egy drága érvelést.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Végrehajtás + Manifest Manager

futtatja a hozzárendelt adaptert, és rögzíti a fizikai metódust, a végpontot, a modell revízióját, a kivonatokat, a hívási éleket, az időzítést, az újrapróbálkozásokat és az elhelyezést

**Felelősség.** Futtasson minden kijelölt szakembert, és rögzítse a fizikailag végrehajtott adatokat a bemenetekkel, azonosítóval, időzítéssel, újrapróbálkozásokkal és kimenetelével. Példa: mutassa meg, hogy a rögzített AMF osztályozó kezelte a 2. szakaszt, ahelyett, hogy megbízott volna egy jegyzékcímkében, amely csupán azt mondja, hogy igen.

**Meg kell őrizni.** input_hashes; adapter_identitás; hibaállapot

**Erőforrás alakja.** CPU koordinátor; csak a bejelentett bérbeadó tulajdonosokon keresztül delegálja a GPU-munkát

**Határ.** rögzíti a végrehajtást; nem tudja igazolni saját sikerét

### GPU bérleti választottbíróság


**Felelősség.** Koordinálja a tanácsadó átadásokat a platform által kezelt gyorsító munkaterhelései között anélkül, hogy felfedné a fizikai eszköz azonosságát, vagy megelőzné a már repülés közben végzett munkát.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Power Residency koordinátor

**Felelősség.** Egyetlen AKTÍV, MELEG, ÜKÉSZENLÉTI és SOHA állapotmodell fenntartása az elosztott platform teljesítmény- és tartózkodási mechanizmusai között.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

### Várható / megfigyelt hasznos teher főkönyve

csatlakozik minden egyes fogaskerekű felelősség a megfigyelt mezőihez, a készenléthez, a kihagyásokhoz, az értékhez, a költségekhez, az időzítéshez, az újrapróbálkozásokhoz és a javítási kéréshez

**Felelősség.** Hasonlítsa össze azt, amit minden fogaskeréktől elvártak, azzal, amit ténylegesen átadott, beleértve a költségeket és a hiányzó inputokat. Példa: tegye közzé, hogy a kapcsolatelemzés 40 másodpercig futott, de nem biztosított használható csatlakozási élt a szerkesztő számára.

**Meg kell őrizni.** handoff_identity; megemészti; hiányzó_mezők; költség_alap

**Erőforrás alakja.** CPU; közel nulla az érveléshez és az ellenőrzéshez képest

**Határ.** A hordozható szakasz időzítése nem helyettesíti a fizikai szakasz/modell időzítést a végrehajtási jegyzékben

### Terméktudatos minőségügyi vezető

ellenőrzi a retorikai befejezettséget, a konnektív érvelést, az olvashatóságot, a tipográfiát, a duplikációt, a figyelmet, a költségvetést, a szövést, a görbületet és a végrehajtható műveleteket a kért terméknél

**Felelősség.** Értékelje fel, hogy ez az adott termék megfelel-e a deklarált olvasónak és célnak külön minőségi tengelyeken keresztül, majd határozza meg a felelős javítási szakaszt. Példa: egy kézikönyv meghibásodhat, ha hiányzik a helyreállítási útmutatás, még akkor is, ha minden mondat nyelvtanilag és megalapozott.

**Meg kell őrizni.** egyéni_tengely_eredmények; elutasított_jelölt_bizonyíték

**Erőforrás alakja.** CPU plusz korlátos ellenőrző/deslop HTTP; történelmileg a legnagyobb Stage 8 részesedés

**Határ.** műfaji tengelyeket kell mérni és verziózni; egy átlátszatlan minőségi pontszám tilos

### Nyugta + Promóciókezelő

függetlenül újraszámolja az invariánsokat, és csak a PASS nyugtából engedélyezi a promóciót és az atomi műtermékek írását

**Felelősség.** Függetlenül ellenőrizze a köteget, és csak minden szükséges invariáns átadása után írja meg a műterméket. Példa: elutasítja a promóciót, ha a megjelenítő sikerről számol be, de a nyugta nem tudja reprodukálni a forráskötést.

**Meg kell őrizni.** hiba_eredmények; ismeretlenek; release_identity; rollback_boundary

**Erőforrás alakja.** CPU és I/O; nincs GPU vagy bérlet

**Határ.** A manifeszt hitelesség végső soron a felülvizsgált változatlan kiadás/konfig-kötéstől függ

### Származási hely + Veszteségkontroll

forrásazonosság, episztemikus állapot, következtetés, találmány és elutasított ágak

**Felelősség.** Minden állítást kössön ahhoz, hogy ki vagy mi szolgáltatta, mikor alkalmazták, és hogy megfigyelték-e, kikövetkeztették, felülírták, elutasították vagy ismeretlenek. Példa: őrizzen meg egy későbbi újraértelmezést anélkül, hogy felülírná a korábbi hiedelmet, amely valójában egy cselekvést irányított.

**Meg kell őrizni.** Pontos gráf azonosság, kapcsolat eredete és deklarált komponenshatár.

**Az erőforrás alakja.** Az élő telepítés rögzíti a tényleges CPU-, memória-, tárhely-, gyorsító- és bérlethasználatot; ez a nyilvános katalógus nem teszi közzé a gépek elhelyezését.

**Határ.** Csak a deklarált grafikonfelelősséget teljesítheti, és nem tudja kijavítani a hiányzó vagy nem támogatott bizonyítékokat.

## További bejelentett alkatrészek

### Biztonságos webes átjáró

Hitelesített távoli hozzáférést biztosít a jóváhagyott ügyfelektől anélkül, hogy a privát platformszolgáltatásokat közvetlenül kitenné a nyilvános internetnek.

### Platform felügyelő

Elindítja a szolgáltatásokat függőségi sorrendben, figyeli azok állapotát, és korlátozott újraindítási műveleteket hajt végre. Meghibásodása megszünteti az összehangolt felügyeletet anélkül, hogy újradefiniálná a továbbra is működő szolgáltatások állapotát.

## A teljesség határa

A katalógus a karbantartott architektúra gráf aktív logikai összetevőit fedi le, nem pedig minden egyes futási környezet által telepített tranzitív csomagot. Egy jövőbeli szoftverkiadáshoz pontos szoftveranyag-jegyzékre és a terjesztett bájtokból előállított licenccsomagra van szükség.
