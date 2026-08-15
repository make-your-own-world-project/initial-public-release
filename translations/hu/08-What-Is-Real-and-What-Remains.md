> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../README.md) | [Minden nyelv](../README.md)

# Mi Valódi és Mi Marad

![Ötletek, tesztek, hibák és ellenőrzött képességek különböző megvalósítási kapukon átlépve](../../assets/evidence-implementation-gates.png)

## Bizonyítási osztályok

A bizonyítékmodell több osztályt különít el:

- **elsődleges bizonyítékok:** megőrzött forrásleletek és interakciós események;
- **származott bizonyítékok:** kivonatolt szöveg, szemantikai egységek, kapcsolatok, osztályozások,
  időbeli megfigyelések és egyéb változatos ábrázolások;
- **végrehajtási bizonyítékok:** manifesztek, hívási megfigyelések, költségek, modellazonosságok és
  színpadi eredmények;
- **elfogadási bizonyítékok:** független invariánsok, nyugták, kiemelt csomagok és
  pontos kimeneti hash-ek;
- **tervezési szándék:** az architektúra és a tervezett viselkedés végrehajtása még nem bizonyított;
- **történelmi állítások:** amit egy korábbi kiadás vagy kísérlet közölt magáról.

A sikeres vizsga csak az általa végrehajtott borítékra bizonyíték. A kiadási dokumentum nem bizonyítja, hogy az aktuális futási környezet még mindig megegyezik vele. A telepített könyvtár nem telepített képesség.

## Megvalósított alapok

A megvalósítás a következő korlátos alapokat mutatta be:

- tartalomközpontú forrásmegőrzés és csatolás-orientált bizonyítékkezelés;
- külön műtermékek, reprezentációk, lokátorok és forrásesemények;
- szereplőhöz és sorozathoz kötött beszélgetési események;
- diskurzus és korreferencia előfeldolgozása korlátos forrásszeletekkel;
- argumentum reláció osztályozása pontos forrástartományokkal és megtartott próbálkozásokkal;
- tipizált propozíció- és relációgráf;
- determinisztikus függőségi vetület;
- kérésre kiterjedő Personal Meaning Matrix hozzájárulások bizonytalansággal és
  védő zászlók;
- visszafelé kijelölés és az azonos gráf előre történő visszajátszása objektumok korlátos tesztekben;
- globális tulajdonú szemantikai egységek kiosztása és váltott soros műtermékek tervezése;
- földelt vakolat padlók és választható jelöltek összehasonlítása;
- független nyugtakapu akció;
- tartós műalkotások és érvelő néző;
- egy nyilvános dokumentum közzétételi határ tartalom-címzett kiadásokkal.

Ezek az állítások a bizonyított összetevők határait írják le, nem pedig azt az állítást, hogy a teljes jövőkép teljes.

A bemutatott összehasonlítás egy külső fogaskerék határt is rögzít. Egy határmodell előkészített, kérésspecifikus hasznos terhelést kapott, és finomabb megjelenítést eredményezett anélkül, hogy megkapta volna a karbantartott korpuszt, vagy kiadási jogosultsággá vált volna. A bizonyítékok alátámasztják ezt a korlátozott tranzakciót; nem határozza meg, hogy a tesztelt műtermék-útvonalon kívül mit tart meg bármely szolgáltató, ami továbbra is külön szerződéses és adatvédelmi kérdés marad. Megállapítja, hogy a hasznos hozzájárulás nem igényelte a destruktív csökkentés emberi rekordjának áthelyezését a szolgáltató tulajdonában lévő értékbe.

## Telepített platformmérleg

A telepített alkalmazásfa korlátozott fájlrendszer-leltárja körülbelül 566 000 fájlt és 218 GiB-ot tartalmazott. A modelleszközök nagyjából 172 GiB-ot, a függőségek és a nyelvi futtatókörnyezet 25 GiB-ot, az adatállapot és egyéb eszközök 20 GiB-ot, a megvalósítási forrás pedig körülbelül 184 MiB-ot tettek ki. A leltár olvashatatlan vagy változó bejegyzéseket talált, ezért ezek inkább működési méretbecslések, nem pedig szoftveres anyagjegyzék.

Az aszimmetria szándékos bizonyíték az építészetről. A forráskód egy kis része a telepített lábnyomnak; a modellsúlyok és az újrafelhasználható futási idők uralják. A vezérlősík ezért az egyes szakemberek értékét, jogosultságát és működési költségeit követi nyomon, ahelyett, hogy a beépített méretet képességként kezelné. Egy jövőbeli terjeszthető kód kiadáshoz szükség van egy műtermék-specifikus függőségi leltárra, pontos verziókra, licencekre, hashekre és reprodukálható összeállítási határra.

## A tervezés által megőrzött mérnöki órák

A fejlesztés több tartós mérnöki leckét eredményezett:

- általános modell felkérése egy hiányzó szakember szimulálására;
- a folyamatból való kilépést vagy az önbejelentést a képesség bizonyítékaként kezeli;
- a szemantikai osztályozás utáni diskurzus futtatása és a szakmunkák sokszorosítása;
- az első ismétlődő idézet előfordulásának hozzárendelése származásként;
- lehetővé tenni egy teljes aktát tartalmazó bizonyítékot, hogy az összetételt ellenőrizhetetlenné tegye;
- nulla elfogadott reláció kezelése csővezeték meghibásodásként;
- egy determinisztikus gráfvetület összetévesztése egy külön végrehajtott szakemberrel;
- szövésprofil illesztése, miközben nem támogatott vagy olvashatatlan prózát állít elő;
- hibakeresés teljes korpusz futtatásával, amikor a kis és közepes esetek felfedték a hibát;
- úgy hangolják az egyik terméket, hogy a másikat visszafejlesszék.

A nyilvános architektúra megtartja ezeket a korrekciókat, mert megmagyarázzák a jelenlegi korlátozások célját, és megbízhatóbbá teszik a jövőbeni finomításokat.

## Jelenlegi fejlesztési lehetőségek

Számos fő képesség hiányos marad, vagy szélesebb körű bizonyítékot igényel:

- a kapcsolati címkék független szakértői minőségértékelést igényelnek, nem csak strukturálisan
  érvényesítés;
- A kereszt-deponálási időbeli hivatkozások és az újbóli hozzárendelés további tesztelést igényelnek nagyobb méretekben
  vegyes forrású határok;
- magas szintű személyi járművezetőknek néptelennek kell maradniuk mindaddig, amíg a forráshoz kötött bizonyítékok és
  a lencse viselkedése igazolja őket;
- a különböző terméktípusokhoz kalibrált, regresszióval védett szerelősorokra van szükség;
- A Human Protocol visszajelzéséhez longitudinális eredményre van szükség;
- a figuratív és narratív mechanizmusok előtt terméktudatos értékelésre van szükség
  felhatalmazást adnak;
- a teljes nyilvános dokumentáció folyamatos szerkesztői felülvizsgálatot igényel, mint a magánrekordot
  fejlődik.

## Érvényesítési létra

A fejlesztés kicsitől a nagy felé halad:

1. tiszta séma és változatlan lámpatestek;
2. ismert topológiájú rövid szemantikai példák;
3. kis valódi forrásszeletek;
4. közepes vegyes formátumú és vegyes idejű szeletek;
5. nagyobb skálázhatósági határok a korábbi szintek átlépése után;
6. ember által írt versus rendszer által generált összehasonlítás ugyanazon bizonyítékok mellett,
  vevő, forma és költségvetés.

Az összehasonlítás azt diagnosztizálja, hogy a veszteség a grafikon kiválasztásából, a fontosságkiosztásból, az előrejátszásból, a megvalósításból vagy a végső olvashatóságból származik-e, ahelyett, hogy minden hibát az általános „modellminőséghez” rendelne.
