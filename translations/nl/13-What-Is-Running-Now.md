> Nederlands: Machineondersteunde vertaling van de gezaghebbende Engelse bron. Correcties in de moedertaal zijn welkom. [Engels](../../README.md) | [Alle talen](../README.md)

# Wat draait er nu

![De lokale machinerie is op verantwoordelijkheid georganiseerd rond een gedeelde, gecontroleerde ruggengraat](../../assets/public-machinery-catalog.png)

## Hoe leest u deze catalogus?

De catalogus is de openbare tegenhanger van de Datacenter-weergave in Mission Control. Het beschrijft wat elk tandwiel bijdraagt ​​en wat verloren zou gaan als het zou verdwijnen, zonder privéadressen, machine-indeling, inloggegevens, bestandspaden of bedieningsfrequentie te publiceren. De livegrafiek blijft de operationele bron van waarheid.

De status van componenten is belangrijk. Een tool kan actief zijn, behouden als bronsysteem, geëvalueerd maar niet overgenomen, of een gepensioneerde voorganger. Aanwezigheid in deze catalogus verleent geen componentbevoegdheid die verder gaat dan de aangegeven rol.

Deze regel omvat ook de capaciteit voor de buitengrenzen. Wanneer het wordt gebruikt, bezet het een begrensd station en ontvangt het een speciaal gebouwde lading in plaats van onbeperkte toegang tot het onderhouden corpus. De lading ondersteunt de aangegeven operatie, maar laat de duurzame staat achterwege die nodig is om het bredere systeem te reconstrueren of zelfstandig toekomstige opnames te bewerkstelligen. Het station ontvangt werk, en niet de voogdij over het menselijk archief waaruit een gecentraliseerde instelling duurzame waarde zou kunnen halen.

## Wegen in en rond het systeem

### Robotbrein (LibreChat)


**Verantwoordelijkheid.** Zorg voor het vervangbare, op mensen gerichte gespreksvenster. Het draagt ​​verzoeken en antwoorden over, terwijl duurzaam geheugen, ophalen, redeneren en verificatie in de onderliggende diensten blijven.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[LibreChat](https://github.com/danny-avila/LibreChat),[Knooppunt.js](https://github.com/nodejs/node)

### Gespreksplitser


**Verantwoordelijkheid.** Merkt op wanneer een chat in twee onderwerpen verandert en biedt aan om het voltooide onderwerp afzonderlijk in te dienen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[SnelleAPI](https://github.com/fastapi/fastapi)

### Missiecontrole


**Verantwoordelijkheid.** Het venster op de machine: wat draait, wat aandacht vereist en wat de machine op dit moment doet. Op deze publicatiegrens rapporteert de statuspagina alle bewaakte systemen die operationeel zijn op de lokale installatie.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Grens.** Operationele status rapporteert servicestatus; geaccepteerde artefacten en ontvangstbewijzen bepalen de afzonderlijke uitvoerings- en semantische bewijsgrenzen.

**Belangrijkste publieke tools.**[SnelleAPI](https://github.com/fastapi/fastapi),[Grafviz](https://gitlab.com/graphviz/graphviz),[Psycopg](https://github.com/psycopg/psycopg)

### Semantische router


**Verantwoordelijkheid.** Routeer begrensde verzoeken naar de juiste lokale engine en vereis expliciete autorisatie voordat externe inferentie wordt gebruikt. Dure mogelijkheden worden alleen geselecteerd als het verzoek de gemeten kosten ervan rechtvaardigt.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[SnelleAPI](https://github.com/fastapi/fastapi). Envoy en vLLM Semantic Router blijven in de bronindex vermeld als geïnspecteerde of buiten gebruik gestelde voorgangers, en niet als huidige runtime-afhankelijkheden.

### Volledige agentgeschiedenis


**Verantwoordelijkheid.** Bewaar volledige, geordende agentgebeurtenisstreams als interactiebewijs, inclusief menselijke beurten, assistent-beurten, tools, fouten en correcties. De geschiedenissen leggen vast wat er gebeurde; ze veranderen de verklaringen van agenten niet in geverifieerde feiten.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Grens.** Levert alleen wat de bron en herkomst vaststellen; de downstream-interpretatie blijft gescheiden.

### Projectdocumenten


**Verantwoordelijkheid.** Bewaar de privé-ontwerp-, bewijs- en projectgegevens die uitleggen waarom het platform bestaat en hoe de architectuur ervan is veranderd. Publieke producten verbruiken beoordeelde derivaten in plaats van de locatie van het privédocument bloot te leggen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Grens.** Levert alleen wat de bron en herkomst vaststellen; de downstream-interpretatie blijft gescheiden.

### Vikunja


**Verantwoordelijkheid.** Behoud het externe taaksysteem als een onafhankelijke bron die ouder is dan het platform. Integratie kan geautoriseerd taakbewijs lezen zonder het taaksysteem in het corpus op te nemen of de levenscyclus ervan te veranderen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Grens.** Levert alleen wat de bron en herkomst vaststellen; de downstream-interpretatie blijft gescheiden.

**Belangrijkste publieke tools.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Bewaren en ophalen

### Kennisinname


**Verantwoordelijkheid.** De manier waarop dingen binnenkomen. Laat een document vallen, een export, een stapel aantekeningen, en het belandt ergens vindbaar in plaats van nergens.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### MongoDB


**Verantwoordelijkheid.** Voert de gesprekken zelf, zoals ze werden gezegd.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Grens.** Beschikbaarheid en integriteit zijn noodzakelijk; opgeslagen gegevens interpreteren of verifiëren zichzelf niet.

**Belangrijkste publieke tools.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Verantwoordelijkheid.** Houd duurzame, gestructureerde projectrecords, afgeleide statussen en zoekindexen bij die bedoeld zijn om vervangbare applicatieservices te overleven. Opgeslagen documenten behouden hun eigen autoriteit en herkomst, in plaats van één ongedifferentieerde herinnering te worden.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Grens.** Beschikbaarheid en integriteit zijn noodzakelijk; opgeslagen gegevens interpreteren of verifiëren zichzelf niet.

**Belangrijkste publieke tools.**[PostgreSQL](https://github.com/postgres/postgres),[vector](https://github.com/pgvector/pgvector)

## Redeneren en reconstrueren

### Classificator voor argumentrelaties

vastgezette AMF_ARI OpenVINO CPU-classificatie van gevolgtrekking, conflict, herformulering of geen relatie

**Verantwoordelijkheid.** Classificeer de relatie tussen twee aangeleverde proposities; het creëert geen voorstel en leidt er geen persoonlijk motief uit af. Voorbeeld: onderscheid een verklaring die een andere ondersteunt, van een verklaring die deze tegenspreekt, of retourneer geen ondersteunde relatie.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[AMF ARI RoBERTa OpenVINO-model](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Menselijke artefacten


**Verantwoordelijkheid.** Definieer de op de mens gerichte producten die de lopende band kan construeren. Elk product heeft zijn eigen ontvanger, doel, structuur, bewijsbeleid en leveringscontract, in plaats van één algemeen overzicht te delen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Aarding + leveringsvalidatie

onafhankelijke ontvangstcontrole over controles op trouw, herkomst, verlies, uitvinding, weefsel en begrip

**Verantwoordelijkheid.** Controleer onafhankelijk of het artefact de ondersteunde betekenis behoudt en voldoet aan het opgegeven leveringscontract voordat het wordt vrijgegeven. Voorbeeld: verwerp een leesbare paragraaf die een conclusie verzint, en verwerp afzonderlijk een gefundeerd document waarvan de structuur onbruikbaar is voor de beoogde lezer.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Doelgroepresolutie

status van de ontvanger, vereisten, register en relevantie

**Verantwoordelijkheid.** Beschrijf wat de beoogde ontvanger geacht wordt te weten, nodig te hebben en te tolereren, terwijl de aannames expliciet blijven. Voorbeeld: heb een huiseigenaargids nodig om de pH uit te leggen voordat u afkortingen gebruikt die bekend zijn bij een zwembadtechnicus.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Volledige boom samenvouwen + pakketten

container-beperkte partitie, selectie, winsten en verliezen

**Verantwoordelijkheid.** Selecteer en balanceer wat bij het gevraagde artefact past, terwijl u vastlegt wat is weggelaten en de betekenisvolle vorm van de boom behoudt. Voorbeeld: houd elke grote tak vertegenwoordigd in een artikel van 1000 woorden, in plaats van de grootste brontak het hele budget te laten opslokken.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[submodlib](https://github.com/decile-team/submodlib),[knielde](https://github.com/arvkevi/kneed)

### Compact werkmodel

draagbare, op verzoeken gerichte drager voor geselecteerde eenheden, relaties, trajecten, bronblokken, plannen, handvatten en overdrachtsgrootboeken

**Verantwoordelijkheid.** Verpak de geselecteerde feiten, relaties, chronologie, onzekerheid, mislukkingen en bronhandvatten in een draagbare, taakspecifieke context. Voorbeeld: geef de redacteur de onderhoudsketen van de pool en waarom de stappen ervan aansluiten zonder het hele corpus te laden of de links te laten vallen.

**Moet behouden.** source_spans; relatie_ids; chronologie; onzekerheid; mislukkingen; vervanging; onbekenden

**Bronvorm.** CPU en RAM proportioneel aan begrensde selectie; geen GPU of lease

**Grens.** De kwaliteit wordt begrensd door de upstream-relatie en de dekking door de staat

### Leveringsmechanica

register, modi, weefprofielen, pacing, dichtheid en deslop-bedieningselementen

**Verantwoordelijkheid.** Lever gemeten leveringsbeperkingen, zoals tempo, dichtheid, register en weeftraject, voor dit product en deze doelgroep. Voorbeeld: geef een kinderuitleg kortere pakketjes en een ander herhalingspatroon dan een technisch rapport zonder de onderliggende feiten te veranderen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Voorverwerking van discours

exact begrensde segmenten, FastCoref-referentiekandidaten en geleasde isanlp RST-operandkoppelingen

**Verantwoordelijkheid.** Identificeer kandidaat-referenten en discoursreeksen voordat u de classificatie beredeneert, terwijl u de exacte broncoördinaten behoudt. Voorbeeld: koppel 'it' aan de genoemde pompkandidaat en stel de twee clausules bloot die met elkaar verbonden zijn door een causale discoursrelatie.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[SnelCoref](https://github.com/shon-otmazgin/fastcoref)

### Voorwaartse reconstructie van het hele artefact

vereisten, referenten, causale lijm, progressie, introductie en conclusie

**Verantwoordelijkheid.** Herbouw het geselecteerde materiaal in lezersvolgorde, waarbij de vereisten, referenten, causale verbanden, voortgang en een eerlijk einde worden hersteld. Voorbeeld: introduceer het doel vóór de procedure en sluit af met een onopgeloste vraag als er geen conclusie is.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Grafiek Waarom en afhankelijkheidsprojectie

deterministische weergave van geclassificeerde grafiekranden die geen nieuwe redeneringsclaims kunnen introduceren

**Verantwoordelijkheid.** Vertaal geaccepteerde relatieranden naar inspecteerbare afhankelijkheid en waarom-opvattingen zonder er interpretatie aan toe te voegen. Voorbeeld: laat zien dat conclusie B afhangt van premisse A omdat die exacte geclassificeerde voorsprong bestaat.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[NetwerkX](https://github.com/networkx/networkx)

### Gegrond interactief antwoord


**Verantwoordelijkheid.** Retourneer een conversatieantwoord met de relevante redenering, herkomst, onzekerheid en uitbreidingspaden. Het antwoordpad kan volledige gesprekken en levenscycli van bewijsmateriaal doorkruisen zonder de pretentie te hebben een documentgeneratierun te zijn.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Menselijke Protocolbrug

ontvangergerichte codering van de vaste ondersteunde payload

**Verantwoordelijkheid.** Zet een vaste, ondersteunde lading om in een vorm die de beoogde persoon kan volgen, met behulp van het productcontract en het gemeten leveringspatroon; het kan het bewijsmateriaal niet veranderen. Voorbeeld: verander dezelfde gegronde redeneringsketen in een beknopte e-mail of een geënsceneerde handleiding door de leveringsstructuur te veranderen, niet de conclusies.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Interactieve contextmontage


**Verantwoordelijkheid.** Maak een begrensde bewijs- en redeneringsgrafiek voor de huidige vraag, waarbij de chronologie, correcties, mislukkingen, bronidentiteit en autorisatie behouden blijven. Het biedt context aan het antwoord zonder het corpus af te vlakken in zoekfragmenten.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Verliesloze toetreding


**Verantwoordelijkheid.** Geef originele bytes en native gebeurtenissen toe vóór interpretatie, waarbij alleen waargenomen aankomstfeiten worden vastgelegd. Beschrijvingen, tijdstempels afgeleid van inhoud, identiteiten en relaties blijven afzonderlijke versiewaarnemingen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Primair bewijs


**Verantwoordelijkheid.** Bewaar de gezaghebbende deposito's waar latere representaties en producten naar moeten kunnen herleiden. Hun bestaan ​​heeft stand, zelfs als het systeem hun betekenis of relatie nog niet kan verklaren.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Volledige voorlopige boom

volledig pre-snoei bewijs, afhankelijkheid, alternatief en faalstructuur

**Verantwoordelijkheid.** Houd de volledige kandidaatstructuur bij, inclusief alternatieven, mislukkingen, onbekenden en vervangen weergaven, zodat de samenvouwing kan zien wat het zou verliezen. Voorbeeld: bewaar zowel een mislukte behandeling als de latere correctie voordat u materiaal selecteert voor een gids.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Redeneringsgrafiek

chronologie, getypeerde relaties, levenscycli van claims, mislukkingen en onzekerheid

**Verantwoordelijkheid.** Onderhoud de op verzoeken gerichte kaart van voorstellen, chronologie, pogingen, uitkomsten, conflicten, afhankelijkheden en onzekerheid. Voorbeeld: koppel een mislukte behandeling aan de correctie die deze heeft vervangen, zonder een van beide toestanden te verwijderen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Verzoek + Artefactcontract

doel, ontvanger, container, kanaal, budget en waarheidsgetrouwheid

**Verantwoordelijkheid.** Bevries het doel, de ontvanger, het product, het kanaal, het budget en de waarheidsnorm, zodat elk stroomafwaarts radertje hetzelfde probleem oplost. Voorbeeld: onderscheid een algemene lezersuitleg van 500 woorden van een technisch incidentrapport voordat de bewijsselectie begint.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Omgekeerde uitbreiding

achterwaarts verzamelen zonder snoeien; marginale bijdrage meten

**Verantwoordelijkheid.** Loop van het verzoek of later bewijsmateriaal naar eerdere gerelateerde documenten en verzamel het volledige kandidaattraject voordat er iets wordt weggegooid. Voorbeeld: volg een huidige algenvraag door eerdere records op het gebied van pH, zwembadgrootte, onderhoud en gebruikscontext.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Getypte retorische bewegingen

semantische taken en afhankelijkheden, nooit subtekenreeksen

**Verantwoordelijkheid.** Wijs elke geselecteerde eenheid een communicatieve taak en afhankelijkheid toe op basis van het productcontract, niet een bijbehorend kopwoord. Voorbeeld: markeer bewijsmateriaal als ondersteuning van een claim en een mislukking als het opzetten van herstel in plaats van beide 'achtergrond' te noemen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Semantische reconstructie

entiteiten, stellingen, episoden, pogingen, resultaten en vragen

**Verantwoordelijkheid.** Zet bronwaarnemingen om in toegeschreven semantische objecten zonder hun uiteindelijke belang of presentatie te bepalen. Voorbeeld: representeer een voorgestelde oplossing, de poging, de mislukking ervan en de resterende vraag als afzonderlijke gekoppelde records.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Versiebeheerde representaties


**Verantwoordelijkheid.** transcripties, structuur, tekst, OCR, lay-out en afgeleide weergaven

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Waarom het ertoe deed

toegeschreven motivatie, zorg, gevolg en huidige relevantie

**Verantwoordelijkheid.** Zorg voor direct en expliciet toegeschreven bewijsmateriaal over de reden waarom aandacht is geïnvesteerd, waardoor niet-ondersteunde redenen onbekend blijven. Voorbeeld: behoud dat een onderhoudstaak er toe deed omdat het mensen beschermde die gedeelde apparatuur gebruikten wanneer de gegevens dit ondersteunen, in plaats van dat motief alleen op basis van een technische vraag te raden.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Redenering + Artefact Engine

reconstructie met ontvangstpoort, ineenstorting, menselijk protocol en atomaire markdown-weergave

**Verantwoordelijkheid.** Coördineer het begrensde reconstructie- en weergavepad en maak de ontvangsten van elke fase zichtbaar; het vervangt geen specialistisch oordeel. Voorbeeld: voer een opstelverzoek uit via selectie, planning, realisatie, validatie en atomic write.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Assemblage- en capaciteitsmanager

loopt de vereiste velden achteruit, prijst de vereisten, selecteert waarheidsgetrouwe specialisten, bestelt afhankelijkheidsgolven en slaat nul-waardewerk over

**Verantwoordelijkheid.** Kies welke specialisten nodig zijn, in welke volgorde ze werken en welk werk geen waarde toevoegt; het vervult hun werk niet. Voorbeeld: plan de realisatie van relaties vóór de realisatie van de zin en sla een niet-beschikbare stilistische passage over die niets bijdraagt.

**Moet behouden.** must_preserve_fields; veld_lijn; expliciete_onbeschikbaarheid

** Bronvorm. ** CPU; weinig geheugen; geen GPU of lease

**Grens.** Kosten- en waardewaarnemingen leggen beslissingen bloot, maar definiëren nooit het menselijke belang

### Atomic Carrier Budget Reconciler

meet ondeelbare bron-, lijm- en relatiedragers vóór realisatie en herverdeelt het vaste budget voor het hele product door echte sectie-slapte

**Verantwoordelijkheid.** Controleer of ondeelbare feiten- en relatiedragers in elke sectie passen en verplaats vervolgens alleen de beschikbare speling met behoud van het totale documentbudget. Voorbeeld: vergroot een proceduresectie van 90 woorden die een vereiste atomaire instructie van 120 woorden bevat door ongebruikte woorden uit een andere sectie te lenen.

**Moet behouden blijven.** Whole_artifact_budget; vereiste_retorische_jobs; bron_autoriteit; grafiekvorm

** Bronvorm. ** CPU; bijna nul looptijd; voorkomt verspild Stage 8 GPU/model/verificatiewerk

**Boundary.** kan een ondeelbare propositie niet comprimeren; mislukt als alle benodigde vervoerders het aangegeven productbudget overschrijden

### Brongebonden Rebinding Manager

verplaatst alleen een volledig geïsoleerde tak wanneer de toegewezen producttaak incompatibel is en één bestemming aantoonbaar compatibel is

**Verantwoordelijkheid.** Verplaats een complete, geïsoleerde bewijsvertakking naar de ene sectie waarvan de taak deze op legitieme wijze kan gebruiken, terwijl dubbelzinnige of relatiebepalende zetten worden geweigerd. Voorbeeld: wijs een op zichzelf staande herstelnotitie opnieuw toe van installatie naar probleemoplossing zonder deze in beide secties te dupliceren.

**Moet behouden.** branch_identity; bron_spans; relatie_ids; marginale_winst_grootboek

** Bronvorm. ** CPU; lage latentie; geen GPU of lease

**Boundary.** weigert relationele, dubbelzinnige, gedeeltelijke of overcapaciteitsbewegingen

### Realisator voor documentbrede relaties

zet geaccepteerde redeneerranden van dezelfde sectie en dwarsdoorsnede om in compacte, onafhankelijk herspeelbare verbindende taal zonder beide operanden te herhalen

**Verantwoordelijkheid.** Zet geaccepteerde grafiekrelaties om in korte verbindende taal, terwijl richting, operanden en bronbereiken onafhankelijk van elkaar afspeelbaar blijven. Voorbeeld: realiseer A-oorzaken-B als een begrensde causale brug in plaats van A en B af te drukken als niet-gerelateerde aangrenzende feiten.

**Moet behouden blijven.** relation_direction; operand_identiteit; exacte_carrier_spans; bron_spans; sectie_lijn

** Bronvorm. ** CPU; bijna nul looptijd; geen GPU of lease

**Boundary.** realiseert alleen expliciet geaccepteerde relatietypen; compacte bruggen behouden de getypte randidentiteit, maar blijven mechanisch geformuleerd; dezelfde drager, dubbelzinnige, impliciete en onbekende randen blijven zichtbaar in de grafiek, maar worden niet als proza ​​bevestigd

### Kennismotor


**Verantwoordelijkheid.** Coördineer toetreding, afgeleide representaties, zoeken, herkomst en duurzame banen zonder deze verantwoordelijkheden samen te voegen tot één waarheidsstaat. Het stelt ondersteunde interfaces bloot aan consumenten, terwijl primair bewijsmateriaal onafhankelijk adresseerbaar blijft.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Getypte clausule/zin Microplanner

wijst brongebonden dragers toe aan getypte retorische taken en stelt clausule-, zin- en alineaplannen samen

**Verantwoordelijkheid.** Verdeel de goedgekeurde betekenis en relaties in clausule-, zin- en alineataken met behoud van hun bronbindingen; het verzint geen bewoordingen of beweringen. Voorbeeld: plan een oorzaakclausule, gevolgd door het gevolg en de overgang ervan voor de oppervlakte-realisator.

**Moet behouden.** semantic_unit_ids; relatie_ids; bronformulieren

** Bronvorm. ** CPU; lage latentie; geen GPU of lease

**Boundary.** bedenkt geen ontbrekende stelling en repareert geen niet-geclassificeerde relatie

**Belangrijkste publieke tools.**[spaCy](https://github.com/explosion/spaCy),[BlingVuur](https://github.com/microsoft/BlingFire)

### Productcontractmanager

zet genre, ontvanger, doel, kanaal, waarheidsgetrouwheid, aandacht en budget om in vereiste productvelden en retorisch werk

**Verantwoordelijkheid.** Verander het verzoek in een concrete checklist voor het eindproduct, zonder bewijs te kiezen of op te schrijven. Voorbeeld: voor een gebruikershandleiding zijn vereisten, geordende acties, herstelbegeleiding en een sluiting vereist voordat een editor start.

**Moet behouden.** declare_purpose; ontvanger; waarheidsgetrouwheid; kanaal

** Bronvorm. ** CPU; bijna nul looptijd; geen GPU of lease

**Boundary.** leidt geen bronbetekenis af en kiest geen feiten

### Contractoppervlak Realizer

past begrensde grammatica, morfologie, typografie, perspectief en getypte transformaties toe op leveringseenheden

**Verantwoordelijkheid.** Pas grammatica, morfologie, typografie en toegestaan ​​perspectief toe op een reeds goedgekeurd plan; het kan niet beslissen over een nieuwe betekenis. Voorbeeld: verander een getypt imperatief plan in een grammaticale instructie zonder een veiligheidsclaim toe te voegen die nooit is geleverd.

**Moet behouden.** claim_authority; bron_en_relatie_bindingen; retorische_job

** Bronvorm. ** CPU; optionele kandidaat-editor mag een bestaande GPU-lease gebruiken, maar heeft geen bevoegdheid

**Grens.** gesloten grammatica is getrouw, maar kan stilistisch stijf blijven

**Belangrijkste publieke tools.**[spaCy](https://github.com/explosion/spaCy)

## Beheer, verificatie en bewerkingen

### Amf Ari


**Verantwoordelijkheid.** Voer de vastgezette argument-relatie-classifier uit over de opgegeven propositieparen en retourneer gescoorde ondersteunings-, conflict-, herformulerings- of geen-relatiepogingen. Het creëert geen voorstellen, leidt geen motieven af, of certificeert zijn eigen labels.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[OpenVINO](https://github.com/openvinotoolkit/openvino),[AMF ARI RoBERTa OpenVINO-model](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Chat-indexer


**Verantwoordelijkheid.** Houdt gesprekken in het lange verslag in plaats van ze in het chatvenster achter te laten.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Bestandsindexeerder


**Verantwoordelijkheid.** Ontdek in aanmerking komende bestanden en dien begrensd indexeringswerk in met behoud van de herkomst. Het mag bestandssysteemdatums, bestandsnamen of geëxtraheerde tekst niet behandelen als gezaghebbende aanmaaktijd, identiteit of motief.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Hardware-telemetrie


**Verantwoordelijkheid.** Leg de begrensde geschiedenis van de machinecondities vast, zodat storingen kunnen worden vergeleken met de stroom-, temperatuur-, geheugen- en gaspedaalstatus. In de openbare beschrijving worden de privébemonsteringsfrequentie en de machine-indeling weggelaten.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[psutil](https://github.com/giampaolo/psutil)

### Afbeelding


**Verantwoordelijkheid.** Produceer afbeeldingen lokaal, zodat een visueel concept geen externe gevolgtrekkingsgrens hoeft te overschrijden. Het genereren van afbeeldingen blijft gescheiden van bewijsautoriteit en publicatietoestemming.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[stabiele diffusie.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Image-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Z-Image-Turbo-Windows-verpakkingsreferentie](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Verantwoordelijkheid.** De zware geest. Langzamer en groter, bedoeld voor vragen die echt meer denkvermogen dan snelheid vergen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Ollama Embedden


**Verantwoordelijkheid.** Maakt schrijven doorzoekbaar op betekenis in plaats van op exacte woorden.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[Ollama](https://github.com/ollama/ollama),[Nomic-tekst insluiten](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Stroomlease


**Verantwoordelijkheid.** Laat de machine rustig stationair draaien en volledig ontwaken voor het echte werk.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Conversatie retitler


**Verantwoordelijkheid.** Geeft namen aan gesprekken die iets betekenen, zodat de lijst vindbaar is in plaats van een muur van eerste zinnen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Semantische waarnemer


**Verantwoordelijkheid.** Controleert of een antwoord wordt ondersteund door het materiaal waarvan het beweert afkomstig te zijn.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[Transformatoren](https://github.com/huggingface/transformers),[MiniCheck](https://github.com/Liyan06/MiniCheck),[FeitCG](https://github.com/derenlei/FactCG)

### Slop-analyse


**Verantwoordelijkheid.** Houdt bij hoe elke geest faalt en of dat beter of slechter wordt.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[spaCy](https://github.com/explosion/spaCy),[BlingVuur](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Toespraken


**Verantwoordelijkheid.** Zet spraak om in tekst, dus praten is een manier om dingen op te schrijven.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[Toespraken](https://github.com/speaches-ai/speaches),[sneller-gefluister](https://github.com/SYSTRAN/faster-whisper),[sneller-destilleren-fluisteren-groot-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Taakdienst


**Verantwoordelijkheid.** Lees geautoriseerde taakregistraties als bewijsmateriaal over gepland werk, zonder ze om te zetten in herinneringen, afgeleide motieven of corpuswaarheid.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### vLLM


**Verantwoordelijkheid.** De dagelijkse geest. Snel, altijd geladen, beantwoordt bijna alles.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

**Belangrijkste publieke tools.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Duurzame podiumbanen

begrensde batches, controlepunten, annulering, hervatten en gedeeltelijke mislukking

**Verantwoordelijkheid.** Voer lange artefactfasen uit als hervatbare begrensde taken met waarheidsgetrouwe terminalstatussen in plaats van ze aan één browserverzoek te koppelen. Voorbeeld: hervatten na een geverifieerd promotiecontrolepunt in plaats van het herhalen van een dure redeneringspas na onderbreking.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Uitvoering + Manifest Manager

voert de toegewezen adapter uit en registreert de fysieke methode, eindpunt, modelrevisie, hashes, oproepranden, timing, nieuwe pogingen en dispositie

**Verantwoordelijkheid.** Geef leiding aan elke toegewezen specialist en leg vast wat fysiek is uitgevoerd, met de input, identiteit, timing, nieuwe pogingen en resultaat. Voorbeeld: laat zien dat de vastgezette AMF-classificator fase 2 heeft afgehandeld in plaats van een manifestlabel te vertrouwen dat alleen maar zegt dat dit het geval is.

**Moet behouden.** input_hashes; adapter_identiteit; mislukking_status

** Bronvorm. ** CPU-coördinator; afgevaardigden GPU-werk alleen via aangegeven lease-eigenaren

**Grens.** registreert uitvoering; kan zijn eigen succes niet garanderen

### GPU-leasearbitrage


**Verantwoordelijkheid.** Coördineer adviesoverdrachten tussen platformbeheerde accelerator-workloads zonder de identiteit van het fysieke apparaat bloot te leggen of werk dat al in uitvoering is, uit te sluiten.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Coördinator Power Residency

**Verantwoordelijkheid.** Handhaaf één ACTIEF, WARM, IDLE en NOOIT statusmodel voor gedistribueerde platformkracht- en verblijfsmechanismen.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

### Verwachte/geobserveerde payloadgrootboek

verbindt elke tandwielverantwoordelijkheid met de waargenomen velden, gereedheid, weglatingen, waarde, kosten, timing, nieuwe pogingen en reparatieverzoek

**Verantwoordelijkheid.** Vergelijk wat elk radertje naar verwachting zou bijdragen met wat het feitelijk zou opleveren, inclusief de kosten en ontbrekende input. Voorbeeld: laat zien dat de relatieanalyse 40 seconden duurde, maar geen bruikbare verbindingsrand voor de editor opleverde.

**Moet behouden.** handoff_identity; verteert; ontbrekende_velden; kostenbasis

** Bronvorm. ** CPU; bijna nul ten opzichte van redenering en verificatie

**Boundary.** De timing van draagbare secties vervangt niet de fysieke fase-/modeltiming in het uitvoeringsmanifest

### Productbewuste kwaliteitsmanager

controleert retorische voltooiing, verbindende redenering, leesbaarheid, typografie, duplicatie, aandacht, budget, weven, slop en uitvoerbare acties voor het gevraagde product

**Verantwoordelijkheid.** Evalueer of dit specifieke product werkt voor de aangegeven lezer en doel over afzonderlijke kwaliteitsassen heen, en identificeer vervolgens de verantwoordelijke reparatiefase. Voorbeeld: een handleiding kan mislukken als er herstelbegeleiding ontbreekt, zelfs als elke zin grammaticaal en gefundeerd is.

**Moet behouden.** individual_axis_results; afgewezen_kandidaat_bewijs

**Resourcevorm.** CPU plus begrensde verifier/deslop HTTP; historisch gezien het grootste Stage 8-aandeel

**Grens.** genre-assen moeten worden gemeten en versiebeheer; één ondoorzichtige kwaliteitsscore is verboden

### Ontvangst + Promotiemanager

herberekent onafhankelijk invarianten en staat promotie en atomaire artefacten alleen toe vanaf een PASS-ontvangstbewijs

**Verantwoordelijkheid.** Verifieer de bundel onafhankelijk en schrijf het artefact pas nadat elke vereiste invariant is doorgegeven. Voorbeeld: promotie weigeren wanneer de renderer succes rapporteert, maar de ontvangstbevestiging kan geen bronbinding reproduceren.

**Moet behouden blijven.** fail_results; onbekenden; release_identiteit; terugdraai_grens

**Resourcevorm.** CPU en I/O; geen GPU of lease

**Boundary.** De manifeste authenticiteit hangt uiteindelijk af van de beoordeelde onveranderlijke release/configuratie-binding

### Herkomst + verliescontrole

bronidentiteit, epistemische staat, gevolgtrekking, uitvinding en afgewezen vertakkingen

**Verantwoordelijkheid.** Houd elke verklaring gekoppeld aan wie of wat deze heeft verstrekt, wanneer deze van toepassing was en of deze werd waargenomen, afgeleid, vervangen, afgewezen of onbekend. Voorbeeld: behoud een latere herinterpretatie zonder de eerdere overtuiging te overschrijven die feitelijk een actie leidde.

**Moet behouden blijven.** Exacte grafiekidentiteit, herkomst van de relatie en opgegeven componentgrens.

**Resourcevorm.** De live-implementatie registreert het daadwerkelijke CPU-, geheugen-, opslag-, accelerator- en leasegebruik; deze openbare catalogus maakt de plaatsing van machines niet openbaar.

**Boundary.** Mag alleen de aangegeven grafische verantwoordelijkheid uitvoeren en kan ontbrekend of niet-ondersteund stroomopwaarts bewijsmateriaal niet repareren.

## Extra aangegeven componenten

### Veilige webgateway

Biedt geauthenticeerde toegang op afstand van goedgekeurde clients zonder privéplatformdiensten rechtstreeks bloot te stellen aan het openbare internet.

### Platformtoezichthouder

Start services in afhankelijkheidsvolgorde, observeert hun status en voert begrensde herstartacties uit. Als dit mislukt, wordt gecoördineerd toezicht overbodig, zonder dat de staat van de diensten die nog steeds actief zijn opnieuw wordt gedefinieerd.

## Volledigheidsgrens

De catalogus omvat actieve logische componenten in de onderhouden architectuurgrafiek, en niet elk transitief pakket dat door elke runtime wordt geïnstalleerd. Voor een toekomstige softwareversie is een exacte softwarestuklijst en licentiebundel vereist, gegenereerd op basis van de specifieke bytes die worden gedistribueerd.
