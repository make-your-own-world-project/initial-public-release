> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../README.md) | [Alle Sprachen](../README.md)

# Wie das System zusammenhält

![Die erhaltenen Aufzeichnungen unterstützen austauschbare Spezialisten und eine inspizierbare Kontrollebene](../../assets/core-architecture-layers.png)

## Trennung der Verantwortlichkeiten

Die Plattform trennt vier Konzerne, die kooperieren, ohne zueinander zu werden:

1. **Konservierung** bewahrt Originalbeweise und beobachtete Herkunft.
2. **Verstehen** fügt versionierte semantische Objekte, Beziehungen, zeitliche Zustände hinzu,
  und unterstützte Interpretationen.
3. **Abruf und Interaktion** stellt anforderungsspezifische Beweise für Fragen zusammen,
  Erkundung und Gespräch.
4. **Artefaktrekonstruktion** wandelt eine begrenzte Beweiswelt in eine deklarierte um
  Produkt für einen deklarierten Empfänger.

Produktanweisungen dringen nicht in die Korpuswahrheit ein. Ein Kapitel, eine Zielgruppe, ein Genre, eine rhetorische Bewegung oder ein Wortbudget gehören zu einem Rückzug. Es handelt sich nicht um eine intrinsische Kennzeichnung eines Quellartefakts.

## Schichttopologie

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

## Der Beitritt gibt nicht vor, es zu wissen

Der Ankunftsdatensatz kann angeben, dass bestimmte Bytes das System über einen bestimmten Kanal erreicht haben. Es entscheidet nicht stillschweigend, wer das Artefakt erstellt hat, wer darin vorkommt, wann sein Thema vorkam, ob ein Dateiname korrekt ist, warum er wichtig ist oder wem der Inhalt gehört. Das sind separate Beobachtungen mit separaten Beweisen und Autorität.

Die Architektur unterscheidet das Originalartefakt von davon abgeleiteten Darstellungen. Extrahierte Texte, Beschreibungen, Einbettungen, Klassifizierungen, Zusammenfassungen und Beziehungen können neu generiert oder ersetzt werden. Sie ersetzen nicht die Quelle.

## Interaktive und Dokumentpfade

Interaktive Antworten und Artefaktgenerierung teilen Beweise, Herkunft, typisierte Beziehungen, Unsicherheit und Validierungsmechanismen. Sie bleiben vom gleichen Arbeitsablauf getrennt.

Eine interaktive Anfrage erfordert möglicherweise ein vollständiges Gespräch, einen Aufgabenlebenszyklus, einen engen Beziehungsdurchlauf oder eine Klarstellung. Es ist nicht erforderlich, einen Buchcontainer zu erstellen und einen historischen Baum global zu reduzieren.

Für die Artefaktgenerierung ist ein deklariertes Produkt, ein Empfänger, ein Budget und ein Plan für das gesamte Artefakt erforderlich. Es muss vor dem Beschneiden die relevante provisorische Struktur sehen und berücksichtigen, was ausgelassen wurde.

## Dynamische Architektur statt einer festen Kette

Die Montagelinie wird für das Produkt zusammengestellt. Unterschiedliche Ausgaben können unterschiedliche Spezialisten verwenden, dieselben Spezialisten unterschiedlich anordnen oder mehrere Instanzen einer Fähigkeit erfordern. Der Manager verwendet Fähigkeitsverträge und vorherige Beweise und nicht nur fest codierte Künstlernamen.

Universelle Invarianten bleiben in allen Bereichen stabil: Quellenidentität, Eigentum, epistemischer Zustand, Unsicherheit, Verlustrechnung, typisierte Übergaben, Kostenbeobachtung, unabhängige Verifizierung und Rollback.

Ein externes allgemeines Modell kann eine typisierte Station belegen, wenn sein gemessener Beitrag die Übergabe rechtfertigt. Es empfängt nur die von dieser Station benötigte anforderungsbezogene Nutzlast, nicht den verwalteten Korpus oder die von der umfassenderen Steuerungsebene codierte Autorität. Durch das Ersetzen oder Entfernen dieser Station bleiben die dauerhafte Aufzeichnung und die zukünftige Rekonstruktionsfähigkeit erhalten. Die begrenzte Station kann einen Beitrag leisten, ohne das menschliche Wissen zu erhalten, das ein zentralisiertes System sonst zu institutionellem Wert verflachen würde.
