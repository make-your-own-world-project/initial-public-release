> Nederlands: Machineondersteunde vertaling van de gezaghebbende Engelse bron. Correcties in de moedertaal zijn welkom. [Engels](../../README.md) | [Alle talen](../README.md)

# Lessen die het systeem versterkten

## Waarom gedrag thuishoort in de architectuur

Individuele bugs kunnen worden gerepareerd terwijl het patroon waaruit ze zijn voortgekomen, blijft bestaan. Dit record verbindt daarom terugkerende technische patronen met hun waarschijnlijke drijfveren, effecten op mensen en bewijsmateriaal, en het mechanisme dat een betrouwbaarder resultaat ondersteunt.

De oorspronkelijke observaties ontstonden tijdens de particuliere ontwikkeling. Dit openbare account behoudt de overdraagbare technische lessen en verwijdert persoonlijke citaten, identiteiten, cadans en omstandigheden. Het diagnosticeert geen enkele persoon of systeem. Elk patroon beschrijft waarneembaar gedrag en een bijbehorende ontwerpcorrectie.

## Werk- en beslissingspatronen

### Zorgvuldig nieuw materiaal integreren

Nieuw materiaal wordt aan een bestaand document of onderdeel vastgeschroefd zonder de structuur ervan te begrijpen. Zowel de toevoeging als de host worden moeilijker te begrijpen.

**Correctie:** lees de ontvangende structuur, integreer de nieuwe verantwoordelijkheid daar waar de vereisten en consumenten horen, of geef het een afzonderlijk begrensd onderdeel.

### Het gezag binnen de perken houden

Een aangrenzende actie wordt behandeld als impliciete toestemming. Het systeem verandert meer dan het toegestane verzoek.

**Correctie:** houd de autoriteit beperkt tot het gevraagde resultaat. Een wezenlijk andere mutatie vereist een nieuwe beslissing.

### Bewijs vóór voltooiing

‘Gewijzigd’ of ‘uitgevoerd’ wordt gerapporteerd als ‘werkt’, en een verklaring dat de regels zijn gevolgd, dient als bewijs dat ze zijn toegepast.

**Correctie:** koppel voltooiing aan waarneembare randvoorwaarden, uitvoering, uitkomst, regressietests en exacte artefactidentiteit. Zelfrapportage heeft geen vrijgavebevoegdheid.

### Zorgvuldige causale diagnose

Een betrouwbare diagnose begint met recente lokale veranderingen, basislijnen, concurrerende hypothesen en causale reproductie voordat de verantwoordelijkheid aan een onderdeel wordt toegewezen.

**Correctie:** onderscheid correlatie, gewijzigde omstandigheden, reproductie en bevestigd mechanisme. Inspecteer eerst de nieuwste wijziging binnen het bereik.

### Bronbewuste interpretatie

Een foutmelding, logregel of plausibele verklaring wordt geaccepteerd zonder de bron, status, tijd of mogelijkheid om het waargenomen resultaat te verklaren te controleren.

**Correctie:** behoud herkomst en onbekende staten. Beperk onbeantwoorde vragen in plaats van ze te vullen met plausibele oorzaken.

### Gelimiteerde correctie en stabiele release

Een geldige correctie wordt voorbij zijn doel doorgevoerd, of werk wordt herhaaldelijk in het openbaar herzien voordat het ontwerp zich heeft gestabiliseerd. Beide besteden aandacht en creëren regressies.

**Correctie:** specificeer de staat waarin u terecht wilt komen, gebruik kleine inspecteerbare tests en batch-compatibele, gevalideerde wijzigingen voordat deze worden vrijgegeven.

### Behoud van het leertraject

Door een probleem en het effect ervan vóór reparatie vast te leggen, blijven de inzichten behouden die de verbetering mogelijk hebben gemaakt.

**Correctie:** registreer de storing en het effect ervan vóór reparatie. De correctie is nuttiger als de reden ervoor zichtbaar blijft.

## Architectuur en integratiepatronen

### Doelgerichte intelligentie

Een algemene chatbotprompt wordt vervangen door een gespecialiseerd mechanisme, omdat het model in staat lijkt het ontbrekende werk te improviseren.

**Correctie:** definieer de ontbrekende input, output, autoriteit, kosten en fout-semantiek; een echt specialistisch of deterministisch mechanisme evalueren; zorg ervoor dat het pad niet beschikbaar is totdat het bestaat.

### Waarden uit gezaghebbende bronnen

Een constante of standaard vertegenwoordigt een feit dat een gezaghebbende bron al kent. Het werkt voor het huidige exemplaar en faalt stilletjes als de wereld verandert.

**Correctie:** los de waarde op van de eigenaar. Als er geen bron bestaat, stel dan onbekende of niet-beschikbare bronnen bloot in plaats van een standaard te fabriceren.

### Verschillende rollen en autoriteit

Waarnemer, kandidaatgenerator, transformator, verificateur, veto, renderer en vrijgavepoort worden als onderling uitwisselbaar behandeld omdat ze allemaal iets lijken te ‘controleren’.

**Correctie:** elk tandwiel verklaart zijn verantwoordelijkheid, consumenten, autoriteit, levenscyclusstatus, beperkingen en vervangingsrelatie.

### Consumentbewuste evolutie

Een component wordt verouderd genoemd omdat de huidige beller er geen gebruik van maakt, terwijl een beoogde downstreamconsument of toekomstig product nog steeds afhankelijk is van de mogelijkheden ervan.

**Correctie:** traceer huidige en gedocumenteerde beoogde consumenten vóór verwijdering. Classificeer de component als actief, onvoltooid, vervangen, afgewezen, behouden of onverklaard.

### Met respect voor gekozen bestemmingen

Wanneer een geconfigureerde bestemming niet kan worden bereikt, wordt de uitvoer stilletjes ergens naartoe verplaatst, in plaats van dat de toegang wordt hersteld. Voorafgaande organisatie en verwachting gaan verloren.

**Correctie:** behandel de geconfigureerde bestemming als al uitgevoerd gebruikerswerk. Herstel de toegang of vraag expliciet een verhuisbesluit aan.

### Verificatie op de exploitatiegrens

Een test slaagt onder een identiteit met meer toegang dan het productieonderdeel.

**Correctie:** verifieer onder de uitvoerende identiteit en resourcegrens, of label het resultaat als onbewezen.

### Claims kwamen overeen met hun testenvelop

Een nep-, unit-fix-, short-run- of sequentiële casus wordt gepresenteerd als bewijs voor een live gelijktijdig pad met verschillende modellen, batches, machtigingen en bronnen.

**Correctie:** elk resultaat noemt zijn envelop. Pas opschalen nadat kleine en middelgrote grenzen zijn overschreden, en verbreed de claim nooit stilletjes.

### Toerekenbare coördinatie van gedeelde geschiedenis

Meerdere werknemers herschrijven één canoniek ogend statusdocument. Werk kan verdwijnen terwijl het bestand nog actueel lijkt.

**Correctie:** bewaar onveranderlijke, toewijsbare werkstroomrecords en leid hieruit een actueel beeld af.

### Tijdbewuste staat

Huidige, historische, experimentele, in quarantaine geplaatste, verworpen en achterhaalde toestanden worden geschreven als tijdloze feiten.

**Correctie:** koppel levenscyclus- en geldigheidsstatus aan elke materiële waarneming.

## Output- en aandachtspatronen

### Het menselijke signaal behouden

Een kort menselijk record wordt uitgebreid met gegenereerd materiaal totdat de oorspronkelijke gebeurtenis moeilijk te herstellen is.

**Correctie:** bewaar de uiting of het artefact als record. Gegenereerde context is een aparte afgeleide laag met expliciete autoriteit.

### Volledige en beknopte uitvoer

Een antwoord wordt uitgelegd, samengevat, opnieuw geformuleerd en afgesloten nadat de informatie ervan is opgebruikt.

**Correctie:** stop wanneer de gevraagde informatie is aangeleverd. De structuur moet overeenkomen met het specifieke lezerswerk.

### Respecteren van de aandacht van de lezer

Correcte maar ongevraagde details slokken de beperkte aandacht van de lezer op. De auteur initieert die kosten.

**Correctie:** tel aandacht als een hulpbron. Bewaar optionele details achter de uitbreidingsknoppen en laat de lezer de transactie starten.

### Betekenisvolle nadruk

Alles is gemarkeerd als belangrijk, zodat het betekenisvolle signaal niet meer te onderscheiden is van decoratie.

**Correctie:** behandel koppen, vetgedrukte tekst, tabellen, waarschuwingen en herhaalde waarschuwingen als een eindig signaalbudget.

### Leiden met het antwoord

Er bestaat nuttige inhoud, maar deze wordt bewaard in een volume waar de lezer niet om heeft gevraagd. De lezer betaalt de extractiekosten.

**Correctie:** leiden met het gevraagde resultaat, materiaal van lage waarde verwijderen en traceerbare uitbreiding aanbieden in plaats van consumptie af te dwingen.

### Stabiele interfaces en eerlijke beschikbaarheid

Live-updates moeten selectie, focus, scrollen en kopiëren behouden, terwijl bronmetingen laten zien wat werkelijk beschikbaar is.

**Correctie:** herstel live-waarden, behoud de gebruikersstatus, geef bronmetingen weer en houd de niet-beschikbare compact en expliciet.

## De verbindende oorzaken

![Mislukte paden worden bewaard en omgezet in geverifieerde architectonische verbeteringen](../../assets/failures-became-blueprint.png)

### Gemaksgedreven corpusoverdracht

Het onderhouden corpus krijgt een krachtige externe component omdat deze ook één beperkte taak verderop in de keten kan uitvoeren. De overdracht breidt een vervangbare bijdrage uit naar onnodige bewaring van duurzame kennis, waardoor de extractie en destructieve reductie mogelijk wordt waarvan gecentraliseerd institutioneel gewin afhankelijk is.

**Correctie:** bouw de kleinste geautoriseerde werklading die de aangegeven bewerking ondersteunt. Houd het corpus, de herkomst, de tijdelijke toestand en de toekomstige wederopbouwmachinerie achter de lokale grens. Het ontwerp moet degelijk blijven, zelfs als de ontvanger de lading behoudt, omdat de weggelaten staat de menselijke betekenis en samengestelde waarde onder menselijke controle draagt.

Er zijn drie oorzaken die bij dit gedrag terugkomen:

1. voortgang koppelen aan geverifieerd effect;
2. onderscheidingen behouden die autoriteit, tijd, veiligheid of betekenis dragen;
3. verander tijdelijke huisvesting in expliciete keuzes en duurzame architectuur.

Het duurzame antwoord is niet een langere instructie. Het is een getypt contract, waarneembare overdracht, onafhankelijke poort en regressie die verband houdt met het gedrag dat ertoe doet.
