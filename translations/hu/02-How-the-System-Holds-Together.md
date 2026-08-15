> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../README.md) | [Minden nyelv](../README.md)

# Hogyan tart össze a rendszer

![A megőrzött nyilvántartás cserélhető szakembereket és ellenőrizhető vezérlősíkot támogat](../../assets/core-architecture-layers.png)

## A felelősségek szétválasztása

A platform négy olyan konszernt választ el egymástól, amelyek anélkül működnek együtt, hogy egymásé válnának:

1. **A megőrzés** megtartja az eredeti bizonyítékokat és a megfigyelt származást.
2. Az **Megértés** verziószámú szemantikai objektumokat, kapcsolatokat, időbeli állapotokat,
  és támogatott értelmezéseket.
3. **A visszakeresés és interakció** kérésspecifikus bizonyítékokat gyűjt össze a kérdésekhez,
  felfedezés, beszélgetés.
4. A **Artefact rekonstrukció** a behatárolt bizonyítékok világát deklarálttá alakítja
  termék egy bejelentett vevő számára.

A termékre vonatkozó utasítások nem szivárognak vissza a korpusz igazságába. Egy fejezet, közönség, műfaj, retorikai lépés vagy szóköltségvetés egy visszavonáshoz tartozik. Ez nem a forrás műtermék belső címkéje.

## Réteges topológia

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

## A csatlakozás nem úgy tesz, mintha tudná

Az érkezési rekord tartalmazhatja, hogy bizonyos bájtok egy adott csatornán keresztül jutottak el a rendszerhez. Nem dönti el csendben, hogy ki készítette a műtárgyat, ki jelenik meg benne, mikor fordult elő a tárgya, pontos-e a fájlnév, miért számított, vagy kié a tartalom. Ezek különálló megfigyelések, külön bizonyítékokkal és tekintéllyel.

Az építészet megkülönbözteti az eredeti műtárgyat az abból származó ábrázolásoktól. A kivonatolt szöveg, leírások, beágyazások, osztályozások, összefoglalások és kapcsolatok újragenerálhatók vagy felülírhatók. Nem helyettesítik a forrást.

## Interaktív és dokumentum útvonalak

Az interaktív válaszadás és a műtermékek generálása megosztja a bizonyítékokat, a származást, a típusos kapcsolatokat, a bizonytalanságot és az érvényesítési mechanizmusokat. Különböznek ugyanattól a munkafolyamattól.

Egy interaktív kéréshez szükség lehet egy teljes beszélgetésre, egy feladat életciklusára, egy szűk kapcsolat bejárására vagy egy tisztázásra. Nem kell könyvtárolót építenie, és nem kell globálisan összecsuknia egy történelmi fát.

A műtermékek létrehozásához deklarált termékre, vevőegységre, költségvetésre és teljes műtermékre van szükség. A metszés előtt látnia kell a vonatkozó ideiglenes szerkezetet, és számolnia kell azzal, ami kimaradt.

## Dinamikus architektúra, nem pedig rögzített lánc

Az összeszerelősort a termékhez állítják össze. A különböző kimenetek különböző szakembereket használhatnak, ugyanazokat a szakembereket eltérően rendelhetik meg, vagy egy képesség több példányát igényelhetik. A menedzser a képességszerződéseket és az előzetes bizonyítékokat használja, nem csupán a kódolt színpadi neveket.

Az univerzális invariánsok minden vonalon stabilak maradnak: forrásazonosság, tulajdonjog, episztemikus állapot, bizonytalanság, veszteségelszámolás, típusos átadások, költségmegfigyelés, független ellenőrzés és visszaállítás.

Egy külső általános modell elfoglalhat egy tipizált állomást, ha annak mért hozzájárulása indokolja az átadást. Csak az adott állomás által igényelt, kérésre kiterjedő hasznos terhelést kapja, a karbantartott korpuszt vagy a szélesebb vezérlősík által kódolt jogosultságot nem. Az állomás cseréje vagy eltávolítása a tartós rekordot és a jövőbeni rekonstrukciós képességet érintetlenül hagyja. A behatárolt állomás az emberi tudás átvétele nélkül is hozzájárulhat ahhoz, hogy egy központosított rendszer egyébként intézményi értékké laposodna.
