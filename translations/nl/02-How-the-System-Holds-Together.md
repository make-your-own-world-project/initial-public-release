> Nederlands: Machineondersteunde vertaling van de gezaghebbende Engelse bron. Correcties in de moedertaal zijn welkom. [Engels](../../README.md) | [Alle talen](../README.md)

# Hoe het systeem bij elkaar blijft

![Het bewaarde record ondersteunt vervangbare specialisten en een inspecteerbaar controlevlak](../../assets/core-architecture-layers.png)

## Scheiding van verantwoordelijkheden

Het platform onderscheidt vier concerns die samenwerken zonder elkaar te worden:

1. **Behoud** behoudt origineel bewijsmateriaal en waargenomen herkomst.
2. **Begrijpen** voegt semantische objecten, relaties, tijdelijke toestanden,
  en ondersteunde interpretaties.
3. **Ophalen en interactie** verzamelt verzoekspecifiek bewijsmateriaal voor vragen,
  verkenning en gesprek.
4. **Artefact-reconstructie** verandert een begrensde bewijswereld in een verklaarde
  product voor een aangegeven ontvanger.

Productinstructies lekken niet terug in de corpuswaarheid. Een hoofdstuk, publiek, genre, retorische zet of woordbudget behoort tot één opname. Het is geen intrinsiek label op een bronartefact.

## Gelaagde topologie

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

## Toetreding pretendeert het niet te weten

In het aankomstrecord kan worden vermeld dat bepaalde bytes het systeem via een bepaald kanaal hebben bereikt. Het beslist niet stilzwijgend wie het artefact heeft gemaakt, wie erin voorkomt, wanneer het onderwerp ervan plaatsvond, of een bestandsnaam juist is, waarom het er toe deed, of wie de eigenaar is van de inhoud ervan. Dat zijn afzonderlijke observaties met afzonderlijk bewijs en autoriteit.

De architectuur onderscheidt het originele artefact van de representaties die ervan zijn afgeleid. Geëxtraheerde tekst, beschrijvingen, insluitingen, classificaties, samenvattingen en relaties kunnen opnieuw worden gegenereerd of vervangen. Ze vervangen de bron niet.

## Interactieve en documentpaden

Interactieve antwoorden en het genereren van artefacten delen bewijsmateriaal, herkomst, getypte relaties, onzekerheid en validatiemechanismen. Ze blijven verschillend van dezelfde workflow.

Voor een interactief verzoek is mogelijk een volledig gesprek, een taaklevenscyclus, een nauwgezette relatiedoorloop of verduidelijking nodig. Het is niet nodig om een ​​boekencontainer te bouwen en een historische boom wereldwijd in te laten storten.

Voor het genereren van artefacten is een gedeclareerd product, ontvanger, budget en plan voor het hele artefact nodig. Het moet vóór het snoeien de relevante voorlopige structuur zien en verantwoording afleggen over wat er is weggelaten.

## Dynamische architectuur in plaats van een vaste keten

Voor het product wordt de assemblagelijn samengesteld. Verschillende outputs kunnen verschillende specialisten gebruiken, dezelfde specialisten op een andere manier ordenen of meerdere exemplaren van één mogelijkheid vereisen. De manager gebruikt bekwaamheidscontracten en voorafgaand bewijsmateriaal in plaats van alleen maar hardgecodeerde artiestennamen.

Universele invarianten blijven op elke lijn stabiel: bronidentiteit, eigendom, epistemische toestand, onzekerheid, verliesverantwoording, getypte overdrachten, kostenobservatie, onafhankelijke verificatie en terugdraaiing.

Een extern algemeen model kan één getypeerd station bezetten als de gemeten bijdrage de overdracht rechtvaardigt. Het ontvangt alleen de op verzoek gerichte payload die door dat station wordt vereist, niet het onderhouden corpus of de autoriteit die is gecodeerd door het bredere besturingsvlak. Door dat station te vervangen of te verwijderen, blijven de duurzame reputatie en de toekomstige reconstructiemogelijkheden intact. Het begrensde station kan een bijdrage leveren zonder de menselijke kennis te ontvangen die een gecentraliseerd systeem anders zou afvlakken tot institutionele waarde.
