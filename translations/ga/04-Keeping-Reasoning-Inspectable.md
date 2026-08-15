> Gaeilge: Aistriúchán meaisín-chuidithe ar an bhfoinse údarásach Béarla. Tá fáilte roimh cheartúcháin dhúchais. [Béarla](../../README.md) | [Gach teanga](../README.md)

# Réasúnaíocht a Choinneáil Inspectable

![Speisialtóirí neamhspleácha ag rianú cosáin réasúnaíochta ar glacadh leo agus ar diúltaíodh dóibh filleadh ar fhianaise bheacht](../../assets/reasoning-engine-inspectable-path.png)

## Réasúnaíocht inspectable

Is seicheamh speisialtóirí teorannacha agus réamh-mheastacháin cinntitheacha an t-inneall réasúnaíochta. Is é an cuspóir atá leis ná graf tairisc-agus-gaol in-iniúchta a thógáil ó fhianaise foinse cruinn. Ní leid comhlánaithe cineálach é a iarrtar chun an doiciméad iomlán a thuiscint.

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

## Réamhphróiseáil teanga

Roinntear an fhianaise i slisní teorannacha gan bhearna atá ceangailte le féiniúlachtaí foinse do-athlasta agus fritháirimh charachtair. Molann anailís croíláir slabhraí tagartha. Struchtúr Rhetorical Molann anailís teoirice struchtúr dioscúrsa agus péirí operand. Fanann struchtúir rómhóra nó neamhcheangailte soiléir seachas iad a theorannú go ciúin nó a mhapáil go dtí an chéad abairt chomhoiriúnach.

Nochtann na huirlisí seo struchtúr teanga. Ní bhunaíonn siad cúis phearsanta ná fírinne argóinte leo féin.

## Aicmiú maidir le hargóintí

Rangaítear péirí tairiscintí díorthaithe i bhfardal caidrimh bhig, lena n-áirítear tacaíocht, coinbhleacht, coibhéis, nó gan aon ghaol údarásach. Coinníonn gach iarracht a oibriúcháin, a scóráil, a sainaitheantas agus a diúscairt. Tá toradh faoi bhun na tairsí fós le feiceáil agus ní chruthaíonn sé imeall.

Déantar imill ghraif dhírithe de chaidreamh a nglactar leo agus a bhfuil réisí foinse cruinn acu agus céannacht mhodhanna. Teipeann ar cheangal foinse débhríoch dúnta.

## Teilgean graf

Is réamh-mheastachán cinntitheach é an dearcadh spleáchais agus “cén fáth” ar imill aicmithe cheana féin. Féadfaidh sé slabhra tacaíochta nó coinbhleachta a nochtadh i bhfoirm níos inúsáidte. Ní fhéadfaidh sé cúiseanna, geallta nó iarmhairtí nua a chumadh agus a éileamh go ndearna speisialtóir iad a dhíorthaítear.

Is féidir an graf a easpórtáil trí struchtúir idirmhalartaithe argóinte seanbhunaithe, ach ní dara stór fírinne é léiriú idirmhalartaithe agus níl múnla nó luasaire ag teastáil uaidh.

## Teorainneacha acmhainní

Is féidir le croí-phasáil agus parsáil dioscúrsa úsáid a bhaint as acmhainn luasaire léasaithe toisc go bhfuil na samhlacha sin luchtaithe le haghaidh jabanna réamhphróiseála teorannaithe. Tá aicmiú argóinte deartha chun rith trí chonair dhlúth tátail speisialtóra. Is gnáthobair LAP iad teilgean graf, roghnú, réiteach srianta, seiceálacha bunáitíochta, agus fíorú fáltais.

Seachnaíonn an dearadh gach múnla cónaitheach agus cuireann sé cosc ​​ar oibrithe dúblacha a thosú chun an meicníocht léasa roinnte a imghabháil.

## An rud a chruthaíonn an fíoraitheoir, agus nach gcruthóidh

Is féidir leis an bhfíoraitheoir a chruthú gur rith na comhpháirteanna riachtanacha, gur mhair na raonta beachta, go bhfuil teilgean graif in-atáirgthe, go bhfuil ceangail an táirge comhsheasmhach, agus go bhfuil beart curtha chun cinn ag teacht leis an mbeart glactha. Is féidir leis diúltú do léirsithe déanta, prós gan tacaíocht, treo mícheart, cúlchistí ceilte, agus cumais in easnamh laistigh dá pholasaí.

Ní chruthaíonn cruinneas struchtúrach go huathoibríoch go n-aontaíonn gach lipéad caidrimh le breithiúnas daonna saineolach. Teastaíonn samplaí lipéadaithe neamhspleácha le meastóireacht ar cháilíocht an chaidrimh chomh maith le hanailís beachtas, aisghairme, treo agus calabraithe. Is freagracht ar leith fós an geata cáilíochta shéimeantach sin.

Coimeádann an teorainn seo samhail sheachtrach iartheachtacha ó bheith ina údarás réasúnaíochta. D’fhéadfadh sé go bhfaigheadh ​​sé tairiscintí tacaithe agus caidreamh clóscríofa do thasc réadaithe teorann, fad a bheidh an fhianaise, na hiarrachtaí, an graf agus na critéir glactha ar fáil go neamhspleách. Ní ghlacann líofacht úinéireacht ar an réasúnaíocht a rinne an pálasta úsáideach.
