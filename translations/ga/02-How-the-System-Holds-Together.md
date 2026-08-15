> Gaeilge: Aistriúchán meaisín-chuidithe ar an bhfoinse údarásach Béarla. Tá fáilte roimh cheartúcháin dhúchais. [Béarla](../../README.md) | [Gach teanga](../README.md)

# Mar a Choimeád an Córas le Chéile

![Tacaíonn an taifead caomhnaithe le speisialtóirí in-athsholáthair agus eitleán rialaithe in-iniúchta](../../assets/core-architecture-layers.png)

## Scaradh freagrachtaí

Scarann ​​an t-ardán ceithre ábhar imní a chomhoibríonn gan a bheith ina chéile:

1. Coinníonn **Caomhnú** an bhunfhianaise agus an bhunáitíocht bhreathnaithe.
2. Cuireann **Tuiscint** leis réada shéimeantacha leaganacha, caidrimh, stáit ama,
  agus léirmhínithe tacaithe.
3. Cuireann **aisghabháil agus idirghníomhaíocht** le chéile fianaise iarratas-shonrach le haghaidh ceisteanna,
  taiscéalaíocht, agus comhrá.
4. Tiontaíonn **Atógáil Déantán** saol fianaise teoranta ina shaol dearbhaithe
  táirge le haghaidh glacadóir dearbhaithe.

Ní sceitheann treoracha táirge ar gcúl i bhfírinne an chorpais. Baineann caibidil, lucht féachana, seánra, bogadh reitriciúil, nó buiséad focal le tarraingt siar amháin. Ní lipéad intreach é ar dhéantán foinse.

## Topology sraitheach

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

## Ní ligeann aontachas go bhfuil a fhios

Féadfaidh an taifead teachta a lua gur shroich bearta áirithe an córas trí chainéal ar leith. Ní chinneann sé go ciúin cé a chruthaigh an déantán, cé atá le feiceáil ann, cathain a tharla an t-ábhar, cibé an bhfuil ainm comhaid cruinn, cén fáth a raibh tábhacht leis, nó cé leis a bhfuil a ábhar. Is tuairimí ar leith iad sin a bhfuil fianaise agus údarás ar leith acu.

Déanann an ailtireacht idirdhealú idir an déantán bunaidh agus léiriúcháin a fhaightear uaidh. Is féidir téacs asbhainte, tuairiscí, leabú, aicmithe, achoimrí, agus gaolta a athghiniúint nó a ionadú. Ní chuireann siad in ionad an fhoinse.

## Cosáin idirghníomhacha agus doiciméad

Comhroinneann freagairt idirghníomhach agus giniúint déantán fianaise, foinse, caidreamh clóscríofa, éiginnteacht, agus meicníochtaí bailíochtaithe. Fanann siad scartha ón sreabhadh oibre céanna.

D’fhéadfadh go mbeadh comhrá iomlán, saolré tasc, trasnú caidrimh cúng, nó soiléiriú ag teastáil ó iarratas idirghníomhach. Ní gá coimeádán leabhar a thógáil agus crann stairiúil a thitim ar fud an domhain.

Teastaíonn táirge dearbhaithe, glacadóir, buiséad agus plean déantáin iomlán chun déantúsán a ghiniúint. Caithfidh sé an struchtúr sealadach ábhartha a fheiceáil roimh bearradh agus ní mór cuntas a thabhairt ar an méid a fágadh amach.

## Ailtireacht dhinimiciúil seachas slabhra seasta

Tá an líne tionóil le chéile don táirge. Is féidir le haschuir éagsúla speisialtóirí éagsúla a úsáid, na speisialtóirí céanna a ordú go héagsúil, nó is féidir le cásanna iolracha de chumas amháin a bheith ag teastáil. Úsáideann an bainisteoir conarthaí cumais agus réamhfhianaise seachas ainmneacha stáitse códaithe amháin.

Fanann athróga uilíocha cobhsaí trasna gach líne: céannacht foinse, úinéireacht, staid eipistéimeach, éiginnteacht, cuntasaíocht chaillteanais, aistrithe clóscríofa, breathnadóireacht chostais, fíorú neamhspleách, agus rolladh siar.

Is féidir le samhail ghinearálta sheachtrach a bheith i stáisiún clóscríofa amháin nuair a thugann a ranníocaíocht tomhaiste údar leis an aistriú. Ní fhaigheann sé ach an pálasta arna scóip iarratais a éilíonn an stáisiún sin, ní an corpas faoi chothabháil nó an t-údarás atá ionchódaithe ag an eitleán rialaithe níos leithne. Má dhéantar an stáisiún sin a ionadú nó a bhaint de, fágtar an taifead buan agus an cumas atógáil amach anseo slán. Is féidir leis an stáisiún teorann rannchuidiú gan an t-eolas daonna a fháil, dhéanfadh córas láraithe cothrom le luach institiúideach ar shlí eile.
