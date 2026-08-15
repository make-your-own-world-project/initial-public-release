> Italiano: Traduzione assistita da macchina dell'autorevole fonte inglese. Sono gradite correzioni nella lingua madre. [Inglese](../../README.md) | [Tutte le lingue](../README.md)

# Come il sistema tiene insieme

![Il record conservato che supporta specialisti sostituibili e un piano di controllo ispezionabile](../../assets/core-architecture-layers.png)

## Separazione delle responsabilità

La piattaforma separa quattro realtà che collaborano senza diventare l’una l’altra:

1. La **Conservazione** conserva le prove originali e la provenienza osservata.
2. **Comprensione** aggiunge oggetti semantici con versione, relazioni, stati temporali,
  e interpretazioni supportate.
3. **Recupero e interazione** assembla prove specifiche della richiesta per domande,
  esplorazione e conversazione.
4. La **ricostruzione dell'artefatto** converte un mondo di prove delimitato in un mondo dichiarato
  prodotto per un ricevitore dichiarato.

Le istruzioni del prodotto non filtrano all'indietro nella verità del corpus. Un capitolo, un pubblico, un genere, una mossa retorica o un budget di parole appartengono a un ritiro. Non è un'etichetta intrinseca su un artefatto di origine.

## Topologia a strati

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

## L'adesione non pretende di sapere

Il record di arrivo può indicare che particolari byte hanno raggiunto il sistema attraverso un particolare canale. Non decide silenziosamente chi ha creato l'artefatto, chi appare in esso, quando si è verificato l'oggetto, se il nome di un file è accurato, perché era importante o chi ne possiede il contenuto. Queste sono osservazioni separate con prove e autorità separate.

L'architettura distingue il manufatto originale dalle rappresentazioni da esso derivate. Il testo estratto, le descrizioni, gli incorporamenti, le classificazioni, i riepiloghi e le relazioni possono essere rigenerati o sostituiti. Non sostituiscono la fonte.

## Percorsi interattivi e documentali

Le risposte interattive e la generazione di artefatti condividono prove, provenienza, relazioni tipizzate, incertezza e meccanismi di convalida. Rimangono distinti dallo stesso flusso di lavoro.

Una richiesta interattiva può richiedere una conversazione completa, un ciclo di vita dell'attività, un attraversamento di relazioni ristrette o un chiarimento. Non è necessario costruire un contenitore di libri e comprimere globalmente un albero storico.

La generazione degli artefatti necessita di un prodotto dichiarato, di un destinatario, di un budget e di un piano per l'intero artefatto. Deve visionare la relativa struttura provvisoria prima della potatura e deve rendere conto di ciò che è stato tralasciato.

## Architettura dinamica piuttosto che catena fissa

La catena di montaggio è compilata per il prodotto. Output diversi possono utilizzare specialisti diversi, ordinare gli stessi specialisti in modo diverso o richiedere più istanze di una funzionalità. Il manager utilizza contratti di capacità e prove precedenti piuttosto che solo nomi d'arte codificati.

Gli invarianti universali rimangono stabili su ogni linea: identità della fonte, proprietà, stato epistemico, incertezza, contabilità delle perdite, trasferimenti digitati, osservazione dei costi, verifica indipendente e rollback.

Un modello generale esterno può occupare una stazione tipizzata quando il suo contributo misurato giustifica il trasferimento. Riceve solo il carico utile nell'ambito della richiesta richiesto da quella stazione, non il corpus mantenuto o l'autorità codificata dal piano di controllo più ampio. La sostituzione o la rimozione di quella stazione lascia intatti i dati durevoli e la futura capacità di ricostruzione. La stazione delimitata può contribuire senza ricevere la conoscenza umana, un sistema centralizzato altrimenti si appiattirebbe al valore istituzionale.
