> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../README.md) | [Alle Sprachen](../README.md)

# Was gerade läuft

![Die lokale Maschinerie ist nach Verantwortung um ein gemeinsam kontrolliertes Rückgrat herum organisiert](../../assets/public-machinery-catalog.png)

## So lesen Sie diesen Katalog

Der Katalog ist das öffentliche Gegenstück zur Datacenter-Ansicht in Mission Control. Es beschreibt, was jedes Rädchen beiträgt und was verloren gehen würde, wenn es verschwinden würde, ohne private Adressen, Maschinenlayout, Anmeldeinformationen, Dateipfade oder Betriebsrhythmen zu veröffentlichen. Das Live-Diagramm bleibt die operative Quelle der Wahrheit.

Der Komponentenstatus ist wichtig. Ein Tool kann aktiv sein, als Quellsystem beibehalten, evaluiert, aber nicht übernommen werden oder ein veralteter Vorgänger sein. Durch die Präsenz in diesem Katalog wird einer Komponente keine Autorität gewährt, die über ihre angegebene Rolle hinausgeht.

Diese Regel umfasst die Außengrenzenfähigkeit. Bei Verwendung belegt es eine begrenzte Station und erhält eine speziell angefertigte Nutzlast statt uneingeschränkten Zugriff auf den gewarteten Korpus. Die Nutzlast unterstützt den deklarierten Vorgang, lässt jedoch den dauerhaften Zustand aus, der für die Rekonstruktion des Gesamtsystems oder die unabhängige Erzeugung zukünftiger Abhebungen erforderlich ist. Die Station erhält Arbeit, nicht die Verwaltung der menschlichen Daten, aus denen eine zentralisierte Institution dauerhaften Wert ziehen könnte.

## Wege in und um das System

### Robotergehirn (LibreChat)


**Verantwortung.** Stellen Sie das austauschbare, dem Menschen zugewandte Gesprächsfenster bereit. Es überträgt Anfragen und Antworten, während dauerhaftes Gedächtnis, Abruf, Argumentation und Überprüfung in den darunter liegenden Diensten verbleiben.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[LibreChat](https://github.com/danny-avila/LibreChat),[Node.js](https://github.com/nodejs/node)

### Gesprächsteiler


**Verantwortung.** Bemerkt, wenn ein Chat in zwei Themen umgewandelt wurde, und bietet an, das fertige Thema separat abzulegen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[FastAPI](https://github.com/fastapi/fastapi)

### Missionskontrolle


**Verantwortung.** Das Fenster zur Maschine: Was läuft, was Aufmerksamkeit erfordert und was sie gerade tut. An dieser Veröffentlichungsgrenze meldet die Statusseite alle überwachten Systeme, die in der lokalen Installation betriebsbereit sind.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Betriebsstatus meldet Dienststatus; Akzeptierte Artefakte und Belege legen die Grenzen der getrennten Ausführung und semantischen Beweise fest.

**Wichtigste öffentliche Tools.**[FastAPI](https://github.com/fastapi/fastapi),[Graphviz](https://gitlab.com/graphviz/graphviz),[Psycopg](https://github.com/psycopg/psycopg)

### Semantischer Router


**Verantwortung.** Leiten Sie begrenzte Anforderungen an die entsprechende lokale Engine weiter und erfordern Sie eine explizite Autorisierung, bevor Sie externe Rückschlüsse verwenden. Eine teure Funktion wird nur dann ausgewählt, wenn die Anforderung die gemessenen Kosten rechtfertigt.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[FastAPI](https://github.com/fastapi/fastapi). Envoy und vLLM Semantic Router bleiben im Quellindex als überprüfte oder zurückgezogene Vorgänger aufgeführt, nicht als aktuelle Laufzeitabhängigkeiten.

### Vollständige Agentenhistorien


**Verantwortung.** Bewahren Sie vollständige, geordnete Agenten-Ereignisströme als Interaktionsbeweis auf, einschließlich menschlicher Abläufe, Assistentenabläufe, Tools, Fehler und Korrekturen. Die Geschichten dokumentieren, was passiert ist; Sie verwandeln Agentenaussagen nicht in verifizierte Fakten.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Liefert nur das, was seine Quelle und Herkunft begründen; Die nachgelagerte Interpretation bleibt getrennt.

### Projektdokumente


**Verantwortung.** Bewahren Sie die privaten Entwurfs-, Beweis- und Projektaufzeichnungen auf, die erklären, warum die Plattform existiert und wie sich ihre Architektur verändert hat. Öffentliche Produkte nutzen überprüfte Derivate, anstatt den Speicherort privater Dokumente offenzulegen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Liefert nur das, was seine Quelle und Herkunft begründen; Die nachgelagerte Interpretation bleibt getrennt.

### Vikunja


**Verantwortung.** Bewahren Sie das externe Aufgabensystem als unabhängige Quelle, die älter ist als die Plattform. Durch die Integration können autorisierte Aufgabennachweise gelesen werden, ohne das Aufgabensystem in den Korpus zu integrieren oder seinen Lebenszyklus zu ändern.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Liefert nur das, was seine Quelle und Herkunft begründen; Die nachgelagerte Interpretation bleibt getrennt.

**Wichtigste öffentliche Tools.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Bewahren und Wiederfinden

### Wissensaufnahme


**Verantwortung.** Die Art und Weise, wie Dinge hineinkommen. Lassen Sie ein Dokument fallen, einen Export, einen Stapel Notizen, und es landet an einem auffindbaren Ort und nicht irgendwo.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### MongoDB


**Verantwortung.** Führt die Gespräche selbst, wie es hieß.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Verfügbarkeit und Integrität sind notwendig; gespeicherte Daten interpretieren oder verifizieren sich nicht.

**Wichtigste öffentliche Tools.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Verantwortung.** Halten Sie dauerhaft strukturierte Projektdatensätze, abgeleitete Status- und Suchindizes, die austauschbare Anwendungsdienste überdauern sollen. Gespeicherte Aufzeichnungen behalten ihre eindeutige Autorität und Herkunft und werden nicht zu einer undifferenzierten Erinnerung.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Verfügbarkeit und Integrität sind notwendig; gespeicherte Daten interpretieren oder verifizieren sich nicht.

**Wichtigste öffentliche Tools.**[PostgreSQL](https://github.com/postgres/postgres),[pgvector](https://github.com/pgvector/pgvector)

## Begründung und Rekonstruktion

### Klassifikator für Argumentbeziehungen

Angeheftete AMF_ARI OpenVINO-CPU-Klassifizierung von Schlussfolgerung, Konflikt, Umformulierung oder keine Beziehung

**Verantwortung.** Klassifizieren Sie die Beziehung zwischen zwei bereitgestellten Vorschlägen. Es werden weder Aussagen gemacht noch Rückschlüsse auf persönliche Motive gezogen. Beispiel: Unterscheiden Sie eine Aussage, die eine andere unterstützt, von einer, die ihr widerspricht, oder geben Sie keine unterstützte Beziehung zurück.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[AMF ARI RoBERTa OpenVINO-Modell](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Menschliche Artefakte


**Verantwortung.** Definieren Sie die Produkte für den Menschen, die am Fließband hergestellt werden können. Jedes Produkt verfügt über einen eigenen Empfänger, Zweck, eine eigene Struktur, eine eigene Beweisrichtlinie und einen eigenen Liefervertrag, anstatt eine allgemeine Gliederung zu teilen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Erdung + Liefervalidierung

Unabhängiges Empfangstor für Treue-, Herkunfts-, Verlust-, Erfindungs-, Web- und Verständnisprüfungen

**Verantwortung.** Überprüfen Sie vor der Veröffentlichung unabhängig, ob das Artefakt die unterstützte Bedeutung beibehält und seinen erklärten Liefervertrag erfüllt. Beispiel: Lehnen Sie einen lesbaren Absatz ab, der eine Schlussfolgerung erfindet, und lehnen Sie separat ein begründetes Dokument ab, dessen Struktur für den Zielleser unbrauchbar ist.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Zielgruppenauflösung

Empfängerstatus, Voraussetzungen, Register und Relevanz

**Verantwortung.** Beschreiben Sie, was der beabsichtigte Empfänger wissen, brauchen und tolerieren sollte, und halten Sie dabei die Annahmen explizit. Beispiel: Fordern Sie einen Leitfaden für Hausbesitzer auf, um den pH-Wert zu erklären, bevor Sie Abkürzungen verwenden, mit denen ein Pooltechniker vertraut ist.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Zusammenbruch des gesamten Baums + Pakete

Containerbeschränkte Partition, Auswahl, Gewinne und Verluste

**Verantwortung.** Wählen und balancieren Sie aus, was zum gewünschten Artefakt passt, während Sie gleichzeitig aufzeichnen, was weggelassen wurde, und die sinnvolle Form des Baums beibehalten. Beispiel: Lassen Sie jeden Hauptzweig in einem Artikel mit 1.000 Wörtern vertreten, anstatt zuzulassen, dass der größte Quellzweig das gesamte Budget verschlingt.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[Submodlib](https://github.com/decile-team/submodlib),[kniete](https://github.com/arvkevi/kneed)

### Kompaktes Arbeitsmodell

tragbarer, anforderungsbezogener Träger für ausgewählte Einheiten, Beziehungen, Trajektorien, Quellblöcke, Pläne, Handles und Übergabebücher

**Verantwortung.** Packen Sie die ausgewählten Fakten, Beziehungen, Chronologie, Unsicherheiten, Fehler und Quellcodes in einen tragbaren, auftragsspezifischen Kontext. Beispiel: Geben Sie dem Editor die Pool-Wartungskette und warum ihre Schritte miteinander verbunden sind, ohne den gesamten Korpus zu laden oder die Links zu löschen.

**Muss erhalten bleiben.** source_spans; relation_ids; Chronologie; Unsicherheit; Misserfolge; Ersetzung; Unbekannte

**Ressourcenform.** CPU und RAM proportional zur begrenzten Auswahl; Keine GPU oder Leasing

**Grenze.** Die Qualität wird durch die Upstream-Beziehung und die Einlagen-Staat-Abdeckung begrenzt

### Liefermechaniker

Register, Modi, Webprofile, Tempo, Dichte und Deslop-Steuerung

**Verantwortung.** Geben Sie für dieses Produkt und diese Zielgruppe gemessene Lieferbeschränkungen an, z. B. Geschwindigkeit, Dichte, Register und Webbahn. Beispiel: Geben Sie einer Erklärung für Kinder kürzere Pakete und ein anderes Wiederholungsmuster als einem technischen Bericht, ohne die zugrunde liegenden Fakten zu ändern.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Diskursvorverarbeitung

exakt begrenzte Slices, FastCoref-Referenzkandidaten und geleaste isanlp-RST-Operandenverknüpfungen

**Verantwortung.** Identifizieren Sie Kandidatenreferenten und Diskursspannen, bevor Sie eine Klassifizierung begründen, und behalten Sie dabei die genauen Quellkoordinaten bei. Beispiel: Verknüpfen Sie „it“ mit dem genannten Pumpenkandidaten und legen Sie die beiden durch eine kausale Diskursbeziehung verbundenen Klauseln offen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Vorwärtsrekonstruktion des gesamten Artefakts

Voraussetzungen, Referenten, Kausalzusammenhang, Fortschritt, Einleitung und Schluss

**Verantwortung.** Bauen Sie das ausgewählte Material in der Leserreihenfolge neu auf und stellen Sie dabei Voraussetzungen, Referenzen, kausale Zusammenhänge, Fortschritt und ein ehrliches Ende wieder her. Beispiel: Stellen Sie das Ziel vor dem Verfahren vor und schließen Sie mit einer ungelösten Frage, wenn keine Schlussfolgerung vorliegt.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Diagramm Warum und Abhängigkeitsprojektion

deterministische Sichtweise klassifizierter Graphkanten, die keine neuen Argumentationsansprüche einführen kann

**Verantwortung.** Übersetzen Sie akzeptierte Beziehungskanten in überprüfbare Abhängigkeiten und Warum-Ansichten, ohne Interpretation hinzuzufügen. Beispiel: Zeigen Sie, dass Schlussfolgerung B von Prämisse A abhängt, weil genau diese klassifizierte Kante existiert.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[NetzwerkX](https://github.com/networkx/networkx)

### Bodenständige interaktive Antwort


**Verantwortung.** Geben Sie eine Konversationsantwort mit der relevanten Begründung, Herkunft, Unsicherheit und Erweiterungspfaden zurück. Der Antwortpfad kann vollständige Konversationen und Beweislebenszyklen durchlaufen, ohne vorzutäuschen, dass es sich um einen Dokumentgenerierungslauf handelt.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Menschliche Protokollbrücke

empfängerorientierte Kodierung der fest unterstützten Nutzlast

**Verantwortung.** Konvertieren Sie eine feste, unterstützte Nutzlast in eine Form, der die vorgesehene Person folgen kann, indem Sie den Produktvertrag und das gemessene Liefermuster verwenden; es kann die Beweise nicht ändern. Beispiel: Verwandeln Sie dieselbe fundierte Argumentationskette in eine prägnante E-Mail oder einen inszenierten Leitfaden, indem Sie die Lieferstruktur und nicht die Schlussfolgerungen ändern.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Interaktive Kontextassemblierung


**Verantwortung.** Erstellen Sie ein begrenztes Beweis- und Argumentationsdiagramm für die aktuelle Frage und bewahren Sie dabei Chronologie, Korrekturen, Fehler, Quellenidentität und Autorisierung. Es liefert Kontext zur Antwort, ohne den Korpus in Suchausschnitte zu reduzieren.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Verlustfreier Beitritt


**Verantwortung.** Lassen Sie Originalbytes und native Ereignisse vor der Interpretation zu und zeichnen Sie nur beobachtete Ankunftsfakten auf. Aus Inhalten, Identitäten und Beziehungen abgeleitete Beschreibungen, Zeitstempel bleiben separate versionierte Beobachtungen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Primärer Beweis


**Verantwortung.** Halten Sie die maßgeblichen Einlagen, auf die spätere Darstellungen und Produkte zurückgeführt werden können. Ihre Existenz hat auch dann Bestand, wenn das System ihre Bedeutung oder Beziehung noch nicht erklären kann.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Vollständiger provisorischer Baum

Vollständige Evidenz, Abhängigkeit, Alternative und Fehlerstruktur vor der Bereinigung

**Verantwortung.** Bewahren Sie den gesamten Kandidatenbaum im Anforderungsbereich auf, einschließlich Alternativen, Fehlern, Unbekannten und ersetzten Ansichten, damit Sie beim Zusammenklappen sehen können, was verloren gehen würde. Beispiel: Behalten Sie sowohl eine fehlgeschlagene Behandlung als auch die spätere Korrektur bei, bevor Sie Material für eine Schablone auswählen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Argumentationsdiagramm

Chronologie, typisierte Beziehungen, Anspruchslebenszyklen, Ausfälle und Unsicherheit

**Verantwortung.** Pflegen Sie die anfragebezogene Karte von Vorschlägen, Chronologie, Versuchen, Ergebnissen, Konflikten, Abhängigkeiten und Unsicherheiten. Beispiel: Verknüpfen Sie eine fehlgeschlagene Behandlung mit der Korrektur, die sie ersetzt hat, ohne einen der Zustände zu löschen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Anfrage + Artefaktvertrag

Zweck, Empfänger, Container, Kanal, Budget und Wahrhaftigkeit

**Verantwortung.** Fixieren Sie den Zweck, den Empfänger, das Produkt, den Kanal, das Budget und den Wahrheitsstandard, sodass jedes nachgelagerte Rädchen die gleiche Aufgabe löst. Beispiel: Unterscheiden Sie eine allgemeine 500-Wörter-Erklärung von einem technischen Vorfallbericht, bevor mit der Beweisauswahl begonnen wird.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Umgekehrte Erweiterung

rückwärts sammeln, ohne zu beschneiden; Grenzbeitrag messen

**Verantwortung.** Gehen Sie von der Anfrage oder späteren Beweisen zu früheren zugehörigen Datensätzen und erfassen Sie die gesamte Kandidatenreise, bevor etwas verworfen wird. Beispiel: Verfolgen Sie eine aktuelle Algenfrage durch vorherige Aufzeichnungen zu pH-Wert, Poolgröße, Wartung und Nutzungskontext.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Typisierte rhetorische Bewegungen

semantische Jobs und Abhängigkeiten, niemals Überschriften-Teilzeichenfolgen

**Verantwortung.** Weisen Sie jeder ausgewählten Einheit eine kommunikative Aufgabe und Abhängigkeit zu, die auf dem Produktvertrag und nicht auf einem passenden Überschriftenwort basiert. Beispiel: Kennzeichnen Sie Beweise als Untermauerung eines Anspruchs und einen Fehler als Begründung für eine Wiederherstellung, anstatt beide als „Hintergrund“ zu bezeichnen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Semantische Rekonstruktion

Entitäten, Vorschläge, Episoden, Versuche, Ergebnisse und Fragen

**Verantwortung.** Wandeln Sie Quellbeobachtungen in zugeschriebene semantische Objekte um, ohne über deren endgültige Bedeutung oder Präsentation zu entscheiden. Beispiel: Stellen Sie einen Lösungsvorschlag, den Versuch, seinen Fehlschlag und die verbleibende Frage als separate verknüpfte Datensätze dar.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Versionierte Darstellungen


**Verantwortung.** Transkripte, Struktur, Text, OCR, Layout und abgeleitete Ansichten

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Warum es wichtig war

zugeschriebene Motivation, Besorgnis, Konsequenz und aktuelle Relevanz

**Verantwortung.** Geben Sie direkte und explizit zugeschriebene Beweise dafür an, warum Aufmerksamkeit investiert wurde, und lassen Sie nicht unterstützte Gründe unbekannt. Beispiel: Stellen Sie sicher, dass eine Wartungsaufgabe wichtig ist, weil sie Personen schützt, die gemeinsam genutzte Geräte verwenden, wenn die Aufzeichnungen dies unterstützen, anstatt dieses Motiv allein aufgrund einer technischen Frage zu erraten.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Argumentation + Artefakt-Engine

Empfangsgesteuerte Rekonstruktion, Kollaps, Human Protocol und atomares Markdown-Rendering

**Verantwortung.** Koordinieren Sie den begrenzten Rekonstruktions- und Rendering-Pfad und legen Sie den Empfang jeder Stufe offen. es ersetzt nicht die fachmännische Beurteilung. Beispiel: Durchführen einer Erstellungsanforderung durch Auswahl, Planung, Umsetzung, Validierung und atomares Schreiben.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Montage- und Fähigkeitsmanager

Durchläuft erforderliche Felder rückwärts, bewertet Voraussetzungen, wählt echte Spezialisten aus, ordnet Abhängigkeitswellen an und überspringt Nullwertarbeit

**Verantwortung.** Wählen Sie, welche Spezialisten benötigt werden, in welcher Reihenfolge sie ausgeführt werden und welche Arbeit keinen Mehrwert bringt; es erfüllt seine Aufgaben nicht. Beispiel: Planen Sie die Relationsrealisierung vor der Satzrealisierung und überspringen Sie einen nicht verfügbaren stilistischen Durchgang, der nichts Erforderliches beiträgt.

**Muss erhalten bleiben.** must_preserve_fields; field_lineage; explizite_Unverfügbarkeit

**Ressourcenform.** CPU; geringer Speicher; Keine GPU oder Leasing

**Grenze.** Kosten- und Wertbeobachtungen legen Entscheidungen offen, definieren jedoch niemals die menschliche Bedeutung

### Atomic Carrier Budget Reconciler

Misst unteilbare Quell-, Leim- und Relationsträger vor der Realisierung und verteilt das festgelegte Gesamtproduktbudget um echte Abschnittslücke

**Verantwortung.** Prüfen Sie, ob unteilbare Fakten und Beziehungsträger in jeden Abschnitt passen, und verschieben Sie dann nur die verfügbare Lücke unter Beibehaltung des gesamten Dokumentbudgets. Beispiel: Vergrößern Sie einen Prozedurabschnitt mit 90 Wörtern, der eine erforderliche atomare Anweisung mit 120 Wörtern enthält, indem Sie nicht verwendete Wörter aus einem anderen Abschnitt entlehnen.

**Muss erhalten bleiben.** Whole_artifact_budget; erforderliche_rhetorische_jobs; source_authority; graph_shape

**Ressourcenform.** CPU; Laufzeit nahe Null; verhindert verschwendete GPU-/Modell-/Verifiziererarbeit der Stufe 8

**Grenze.** kann einen unteilbaren Satz nicht komprimieren; schlägt fehl, wenn alle erforderlichen Träger das angegebene Produktbudget überschreiten

### Quellgebundener Rebinding-Manager

Verschiebt nur einen vollständig isolierten Zweig, wenn der zugewiesene Produktauftrag inkompatibel ist und ein Ziel nachweislich kompatibel ist

**Verantwortung.** Verschieben Sie einen vollständigen, isolierten Beweiszweig in den einen Abschnitt, dessen Job ihn rechtmäßig verwenden kann, und lehnen Sie mehrdeutige oder beziehungsbezogene Verschiebungen ab. Beispiel: Weisen Sie einen eigenständigen Wiederherstellungshinweis vom Setup zur Fehlerbehebung zu, ohne ihn in beiden Abschnitten zu duplizieren.

**Muss erhalten bleiben.** branch_identity; source_spans; relation_ids; marginal_gain_ledger

**Ressourcenform.** CPU; geringe Latenz; Keine GPU oder Leasing

**Grenze.** lehnt beziehungstragende, mehrdeutige, teilweise oder Überkapazitätsbewegungen ab

### Dokumentweiter Beziehungsrealisierer

wandelt akzeptierte Argumentationskanten gleichen Abschnitts und Querschnitts in eine kompakte, unabhängig abspielbare Verbindungssprache um, ohne beide Operanden zu wiederholen

**Verantwortung.** Verwandeln Sie akzeptierte Diagrammbeziehungen in eine kurze Verbindungssprache, während Richtung, Operanden und Quellbereiche unabhängig voneinander wiederholbar bleiben. Beispiel: Realisieren Sie A-Ursachen-B als begrenzte Kausalbrücke, anstatt A und B als unabhängige benachbarte Fakten auszugeben.

**Muss erhalten bleiben.** relation_direction; operand_identity; Exact_Carrier_Spans; source_spans; section_lineage

**Ressourcenform.** CPU; Laufzeit nahe Null; Keine GPU oder Leasing

**Boundary.** realisiert nur explizit akzeptierte Beziehungsarten; kompakte Brücken bewahren die typisierte Kantenidentität, bleiben aber mechanisch formuliert; Kanten mit demselben Träger, mehrdeutige, implizite und unbekannte Kanten bleiben im Diagramm sichtbar, werden jedoch nicht als Prosa bestätigt

### Wissensmaschine


**Verantwortung.** Koordinieren Sie Zugriff, abgeleitete Darstellungen, Suche, Herkunft und dauerhafte Aufgaben, ohne diese Verantwortlichkeiten in einem Wahrheitszustand zusammenzuführen. Es stellt den Verbrauchern unterstützte Schnittstellen zur Verfügung, während primäre Beweise unabhängig adressierbar bleiben.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Mikroplaner für typisierte Klauseln/Sätze

weist getippten rhetorischen Aufgaben quellengebundene Träger zu und erstellt Satz-, Satz- und Absatzpläne

**Verantwortung.** Teilen Sie genehmigte Bedeutungen und Beziehungen in Klausel-, Satz- und Absatzjobs auf und bewahren Sie dabei ihre Quellbindungen. es erfindet keine Formulierungen oder Ansprüche. Beispiel: Planen Sie eine Ursachenklausel, gefolgt von ihrer Konsequenz und ihrem Übergang für den Oberflächenrealisierer.

**Muss erhalten bleiben.** semantic_unit_ids; relation_ids; source_forms

**Ressourcenform.** CPU; geringe Latenz; Keine GPU oder Leasing

**Boundary.** erfindet keinen fehlenden Satz und repariert keine nicht klassifizierte Beziehung

**Wichtigste öffentliche Tools.**[spacig](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire)

### Produktvertragsmanager

wandelt Genre, Empfänger, Zweck, Kanal, Wahrhaftigkeit, Aufmerksamkeit und Budget in erforderliche Produktfelder und rhetorische Arbeit um

**Verantwortung.** Verwandeln Sie die Anfrage in eine konkrete Checkliste für das fertige Produkt, ohne Beweise auszuwählen oder diese zu schreiben. Beispiel: Für ein Benutzerhandbuch sind Voraussetzungen, angeordnete Aktionen, Wiederherstellungsanweisungen und ein Schließen erforderlich, bevor ein Editor gestartet wird.

**Muss erhalten bleiben.** deklarierter_zweck; Empfänger; Richtigkeit; Kanal

**Ressourcenform.** CPU; Laufzeit nahe Null; Keine GPU oder Leasing

**Grenze.** leitet keine Quellenbedeutung ab und wählt keine Fakten aus

### Contract Surface Realizer

wendet begrenzte Grammatik, Morphologie, Typografie, Perspektive und typisierte Transformationen auf Liefereinheiten an

**Verantwortung.** Wenden Sie Grammatik, Morphologie, Typografie und zulässige Perspektive auf einen bereits genehmigten Plan an; es kann nicht über eine neue Bedeutung entscheiden. Beispiel: Verwandeln Sie einen getippten Imperativplan in eine Grammatikanweisung, ohne einen Sicherheitsanspruch hinzuzufügen, der nie angegeben wurde.

**Muss erhalten bleiben.** Claim_authority; source_and_relation_bindings; rhetorischer_job

**Ressourcenform.** CPU; Der optionale Editor-Kandidat kann einen vorhandenen GPU-Leasing nutzen, hat aber keine Berechtigung

**Grenze.** Die geschlossene Grammatik ist originalgetreu, kann aber stilistisch steif bleiben

**Wichtigste öffentliche Tools.**[spacig](https://github.com/explosion/spaCy)

## Verwaltung, Überprüfung und Betrieb

### Amf Ari


**Verantwortung.** Führen Sie den angehefteten Argument-Beziehungs-Klassifikator über bereitgestellte Satzpaare aus und geben Sie bewertete Unterstützungs-, Konflikt-, Umformulierungs- oder Nicht-Beziehungsversuche zurück. Es erstellt keine Aussagen, leitet keine Motive ab und bestätigt auch nicht seine eigenen Etiketten.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[OpenVINO](https://github.com/openvinotoolkit/openvino),[AMF ARI RoBERTa OpenVINO-Modell](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Chat-Indexer


**Verantwortung.** Behält Gespräche im Langzeitprotokoll, anstatt sie im Chatfenster zu belassen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Dateiindexer


**Verantwortung.** Entdecken Sie geeignete Dateien und reichen Sie begrenzte, herkunftserhaltende Indexierungsarbeiten ein. Dateisystemdaten, Dateinamen oder extrahierter Text dürfen nicht als maßgebliche Erstellungszeit, Identität oder Motiv betrachtet werden.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Hardware-Telemetrie


**Verantwortung.** Zeichnen Sie einen begrenzten Maschinenzustandsverlauf auf, damit Ausfälle mit Leistung, Temperatur, Speicher und Beschleunigerstatus verglichen werden können. In der öffentlichen Beschreibung wird der private Probenahmerhythmus und das Maschinenlayout weggelassen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[psutil](https://github.com/giampaolo/psutil)

### Bild


**Verantwortung.** Erstellen Sie Bilder lokal, damit ein visuelles Konzept keine externen Schlussfolgerungsgrenzen überschreiten muss. Die Bilderzeugung bleibt getrennt von der Beweisbehörde und der Veröffentlichungserlaubnis.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[stabile-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Image-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Z-Image-Turbo-Windows-Paketreferenz](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Verantwortung.** Der schwere Geist. Langsamer und größer, für Fragen gedacht, die wirklich mehr Nachdenken als Geschwindigkeit erfordern.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Ollama Embed


**Verantwortung.** Ermöglicht die Suche nach Texten nach Bedeutung und nicht nach genauen Wörtern.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[Ollama](https://github.com/ollama/ollama),[Nomic-Einbettungstext](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Stromleasing


**Verantwortung.** Lässt die Maschine leise im Leerlauf laufen und für die eigentliche Arbeit voll aufgeweckt werden.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Konversations-Retitler


**Verantwortung.** Gibt Konversationen Namen, die etwas bedeuten, sodass die Liste auffindbar ist und nicht eine Wand aus ersten Sätzen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Semantischer Beobachter


**Verantwortung.** Überprüft, ob eine Antwort durch das Material gestützt wird, aus dem sie angeblich stammt.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[Transformatoren](https://github.com/huggingface/transformers),[MiniCheck](https://github.com/Liyan06/MiniCheck),[FactCG](https://github.com/derenlei/FactCG)

### Slop-Analyse


**Verantwortung.** Hält Aufzeichnungen darüber, wie jeder Geist versagt und ob sich dies verbessert oder verschlechtert.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[spacig](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Reden


**Verantwortung.** Verwandelt Sprache in Text, also ist Sprechen eine Möglichkeit, Dinge aufzuschreiben.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[Reden](https://github.com/speaches-ai/speaches),[schneller-flüstern](https://github.com/SYSTRAN/faster-whisper),[schneller-destillieren-flüstern-groß-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Aufgabendienst


**Verantwortung.** Lesen Sie autorisierte Aufgabenaufzeichnungen als Beweis für geplante Arbeiten, ohne sie in Erinnerungen, abgeleitete Motive oder Korpuswahrheiten umzuwandeln.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### vLLM


**Verantwortung.** Der alltägliche Geist. Schnell, immer geladen, beantwortet fast alles.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

**Wichtigste öffentliche Tools.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Dauerhafte Bühnenjobs

Begrenzte Stapel, Prüfpunkte, Abbruch, Wiederaufnahme und Teilfehler

**Verantwortung.** Führen Sie lange Artefaktphasen als fortsetzbare begrenzte Jobs mit wahrheitsgetreuen Endzuständen aus, anstatt sie an eine Browseranforderung zu binden. Beispiel: Nach einem verifizierten Beförderungskontrollpunkt fortfahren, anstatt nach einer Unterbrechung einen teuren Argumentationsdurchgang zu wiederholen.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Ausführungs- und Manifestmanager

führt den zugewiesenen Adapter aus und zeichnet physische Methode, Endpunkt, Modellrevision, Hashes, Aufrufkanten, Timing, Wiederholungsversuche und Disposition auf

**Verantwortung.** Führen Sie jeden zugewiesenen Spezialisten aus und zeichnen Sie auf, was physisch ausgeführt wurde, mit seinen Eingaben, Identität, Zeitpunkt, Wiederholungsversuchen und Ergebnis. Beispiel: Zeigen Sie, dass der angeheftete AMF-Klassifikator Stufe 2 verarbeitet hat, anstatt einem Manifestetikett zu vertrauen, das lediglich besagt, dass dies der Fall war.

**Muss erhalten bleiben.** input_hashes; adapter_identity; Fehlerstatus

**Ressourcenform.** CPU-Koordinator; Delegierte die GPU-Arbeit nur über deklarierte Lease-Eigentümer

**Boundary.** zeichnet die Ausführung auf; kann seinen eigenen Erfolg nicht bescheinigen

### GPU-Leasing-Schiedsverfahren


**Verantwortung.** Koordinieren Sie Beratungsübergaben zwischen plattformverwalteten Beschleuniger-Workloads, ohne die physische Geräteidentität preiszugeben oder bereits laufende Arbeiten zu verhindern.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Koordinator der Stromresidenz

**Verantwortung.** Behalten Sie ein ACTIVE-, WARM-, IDLE- und NEVER-Zustandsmodell für alle verteilten Plattformleistungs- und Residenzmechanismen bei.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

### Erwartetes/beobachtetes Nutzlast-Ledger

verbindet jede Zahnradverantwortung mit ihren beobachteten Feldern, Bereitschaft, Auslassungen, Wert, Kosten, Timing, Wiederholungsversuchen und Reparaturanforderung

**Verantwortung.** Vergleichen Sie den erwarteten Beitrag jedes Rädchens mit dem, was es tatsächlich geleistet hat, einschließlich Kosten und fehlender Eingaben. Beispiel: Stellen Sie fest, dass die Beziehungsanalyse 40 Sekunden lang lief, dem Editor jedoch keine nutzbare Verbindungskante lieferte.

**Muss erhalten bleiben.** handoff_identity; verdaut; fehlende_Felder; Kostenbasis

**Ressourcenform.** CPU; nahe Null im Verhältnis zu Argumentation und Verifizierung

**Grenze.** Das Timing des tragbaren Abschnitts ersetzt nicht das Timing der physischen Phase/des Modells im Ausführungsmanifest

### Produktbewusster Qualitätsmanager

prüft rhetorische Vollständigkeit, konnektive Argumentation, Lesbarkeit, Typografie, Duplizierung, Aufmerksamkeit, Budget, Webart, Slop und ausführbare Aktionen für das angeforderte Produkt

**Verantwortung.** Bewerten Sie, ob dieses spezifische Produkt für den angegebenen Leser und Zweck über verschiedene Qualitätsachsen hinweg funktioniert, und identifizieren Sie dann die verantwortliche Reparaturstufe. Beispiel: In einem Handbuch kann es vorkommen, dass Anleitungen zur Wiederherstellung fehlen, selbst wenn jeder Satz grammatikalisch und fundiert ist.

**Muss erhalten bleiben.** individual_axis_results; abgelehnter_Kandidat_Beweis

**Ressourcenform.** CPU plus begrenzter Prüfer/Deslop HTTP; Historisch gesehen der größte Stage-8-Anteil

**Grenze.** Genreachsen müssen gemessen und versioniert werden; Eine undurchsichtige Qualitätsbewertung ist verboten

### Empfangs- und Werbemanager

Berechnet unabhängig Invarianten neu und ermöglicht die Förderung und das Schreiben atomarer Artefakte nur aus einer PASS-Quittung

**Verantwortung.** Überprüfen Sie das Bundle unabhängig und schreiben Sie das Artefakt erst nach jedem erforderlichen Invariantendurchlauf. Beispiel: Verweigern Sie die Heraufstufung, wenn der Renderer einen Erfolg meldet, sein Empfang jedoch eine Quellbindung nicht reproduzieren kann.

**Muss erhalten bleiben.** fail_results; Unbekannte; release_identity; rollback_boundary

**Ressourcenform.** CPU und E/A; Keine GPU oder Leasing

**Grenze.** Die Manifestauthentizität hängt letztendlich von der überprüften unveränderlichen Release-/Konfigurationsbindung ab

### Provenienz + Verlustkontrolle

Quellenidentität, epistemischer Zustand, Schlussfolgerung, Erfindung und abgelehnte Zweige

**Verantwortung.** Halten Sie jede Aussage daran fest, wer oder was sie bereitgestellt hat, wann sie angewendet wurde und ob sie beobachtet, abgeleitet, ersetzt, abgelehnt oder unbekannt war. Beispiel: Bewahren Sie eine spätere Neuinterpretation auf, ohne die frühere Überzeugung zu überschreiben, die tatsächlich eine Handlung geleitet hat.

**Muss erhalten bleiben.** Exakte Diagrammidentität, Beziehungsherkunft und deklarierte Komponentengrenze.

**Ressourcenform.** Die Live-Bereitstellung zeichnet die tatsächliche CPU-, Arbeitsspeicher-, Speicher-, Beschleuniger- und Lease-Nutzung auf; In diesem öffentlichen Katalog wird die Maschinenplatzierung nicht offengelegt.

**Grenze.** Kann nur seine erklärte Diagrammverantwortung erfüllen und kann fehlende oder nicht unterstützte Upstream-Beweise nicht reparieren.

## Zusätzlich deklarierte Komponenten

### Sicheres Web-Gateway

Bietet authentifizierten Fernzugriff von zugelassenen Clients, ohne private Plattformdienste direkt dem öffentlichen Internet auszusetzen.

### Plattform-Supervisor

Startet Dienste in Abhängigkeitsreihenfolge, überwacht ihren Zustand und führt begrenzte Neustartaktionen aus. Durch seinen Ausfall wird die koordinierte Überwachung aufgehoben, ohne dass der Status der weiterhin ausgeführten Dienste neu definiert wird.

## Vollständigkeitsgrenze

Der Katalog deckt aktive logische Komponenten im verwalteten Architekturdiagramm ab, nicht jedes transitive Paket, das von jeder Laufzeit installiert wird. Eine zukünftige Softwareversion erfordert eine genaue Software-Stückliste und ein Lizenzpaket, das aus den spezifischen zu verteilenden Bytes generiert wird.
