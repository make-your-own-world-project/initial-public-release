> Deutsch: Maschinell unterstützte Übersetzung der maßgeblichen englischen Quelle. Korrekturen in der Muttersprache sind willkommen. [Englisch](../../README.md) | [Alle Sprachen](../README.md)

# Werkzeuge, Modelle und Quellen

![Tools, Modelle, Datensätze, Versionen und Rollen werden in einer überprüfbaren Quellregistrierung gespeichert](../../assets/tool-model-source-index.png)

Jedes wichtige externe Tool oder Modell, das im verwalteten Datacenter-Ledger genannt wird, ist hier mit seiner offiziellen öffentlichen Projekt- oder Vertriebsseite verlinkt. Hierbei handelt es sich um einen direkten Abhängigkeits- und Modellindex, nicht um eine transitive Software-Stückliste.

Die Statusspalte beschreibt die für die Komponente aufgezeichnete Beziehung. Ein ausgemustertes oder überprüftes Tool bleibt gutgeschrieben, ohne dass es als aktueller Laufzeitcode angezeigt wird.

Ein in einem Experiment benanntes externes Modell ist ebenfalls nicht das Aufzeichnungssystem. Seine Rolle beschränkt sich auf die Nutzlast und den für dieses Experiment dokumentierten Betrieb. Selbst wenn der Empfänger die bereitgestellten Bytes behält, bleiben der weggelassene Korpus, die Herkunft, der zeitliche Verlauf und die Maschinen zur Nutzlastkonstruktion außerhalb dieser Abhängigkeit.

| Werkzeug oder Modell | Offizielle öffentliche Quelle | Aufgezeichnete Beziehung | Verwendet von |
|---|---|---|---|
| AMF ARI RoBERTa OpenVINO-Modell | [Quelle](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | stromaufwärts | amf_ari, argument_relation_classifier |
| BlingFire | [Quelle](https://github.com/microsoft/BlingFire) | stromaufwärts | Mikroplaner, slop_analysis |
| Caddie | [Quelle](https://github.com/caddyserver/caddy) | stromaufwärts | TLS |
| Gesandte | [Quelle](https://github.com/envoyproxy/envoy) | im Ruhestand befindlicher Vorgänger (keine Laufzeit) | Router |
| FactCG | [Quelle](https://github.com/derenlei/FactCG) | stromaufwärts | semantic_observer |
| FastAPI | [Quelle](https://github.com/fastapi/fastapi) | stromaufwärts | Konversation_Splitter, Mission_Control, Router |
| FastCoref | [Quelle](https://github.com/shon-otmazgin/fastcoref) | stromaufwärts | discourse_preprocessing |
| schneller-destillieren-flüstern-groß-v3 | [Quelle](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | stromaufwärts | Reden |
| schneller-flüstern | [Quelle](https://github.com/SYSTRAN/faster-whisper) | stromaufwärts | Reden |
| Graphviz | [Quelle](https://gitlab.com/graphviz/graphviz) | stromaufwärts | mission_control |
| IsaNLP RST | [Quelle](https://github.com/tchewik/isanlp_rst) | stromaufwärts | discourse_preprocessing |
| kniete | [Quelle](https://github.com/arvkevi/kneed) | stromaufwärts | collap_packets |
| LibreChat | [Quelle](https://github.com/danny-avila/LibreChat) | stromaufwärts | chatten |
| MiniCheck | [Quelle](https://github.com/Liyan06/MiniCheck) | stromaufwärts | semantic_observer |
| MongoDB | [Quelle](https://github.com/mongodb/mongo) | stromaufwärts | mongodb |
| NetzwerkX | [Quelle](https://github.com/networkx/networkx) | stromaufwärts | graph_projektion |
| NLTK | [Quelle](https://github.com/nltk/nltk) | stromaufwärts | slop_analysis |
| Node.js | [Quelle](https://github.com/nodejs/node) | stromaufwärts | chatten |
| Nomic-Einbettungstext | [Quelle](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | stromaufwärts | ollama_embed |
| Ollama | [Quelle](https://github.com/ollama/ollama) | stromaufwärts | ollama, ollama_embed |
| OpenVINO | [Quelle](https://github.com/openvinotoolkit/openvino) | stromaufwärts | amf_ari |
| pgvector | [Quelle](https://github.com/pgvector/pgvector) | stromaufwärts | postgres |
| PostgreSQL | [Quelle](https://github.com/postgres/postgres) | stromaufwärts | postgres |
| psutil | [Quelle](https://github.com/giampaolo/psutil) | stromaufwärts | hardware_telemetry |
| Psycopg | [Quelle](https://github.com/psycopg/psycopg) | stromaufwärts | mission_control |
| Qwen3 | [Quelle](https://github.com/QwenLM/Qwen3) | stromaufwärts | Ollama, vllm |
| spacig | [Quelle](https://github.com/explosion/spaCy) | stromaufwärts | Mikroplaner, slop_analysis, surface_realizer |
| Reden | [Quelle](https://github.com/speaches-ai/speaches) | stromaufwärts | Reden |
| stabile-diffusion.cpp | [Quelle](https://github.com/leejet/stable-diffusion.cpp) | stromaufwärts | Bild |
| Submodlib | [Quelle](https://github.com/decile-team/submodlib) | stromaufwärts | collap_packets |
| Transformatoren | [Quelle](https://github.com/huggingface/transformers) | stromaufwärts | semantic_observer |
| Vikunja | [Quelle](https://github.com/go-vikunja/vikunja) | stromaufwärts | vikunja |
| vLLM | [Quelle](https://github.com/vllm-project/vllm) | stromaufwärts | vllm |
| vLLM Semantischer Router | [Quelle](https://github.com/vllm-project/semantic-router) | Vorgänger im Ruhestand / überprüfte Abstammung (nicht Laufzeit) | Router |
| Z-Image-Turbo | [Quelle](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | stromaufwärts | Bild |
| Z-Image-Turbo-Windows-Paketreferenz | [Quelle](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | geprüfte Verpackungsreferenz (nicht Laufzeit-UI) | Bild |

## Verbreitungsgrenze

Die öffentliche Dokumentation enthält keine aufgeführten Projektcodes oder Modellgewichte. Eine zukünftige Softwareverteilung muss aus den tatsächlich verteilten Bytes exakte Versionen, Revisionen, Hashes, transitive Abhängigkeiten, Modellbedingungen und Lizenztexte generieren. Bei einem Projektlink handelt es sich um eine Namensnennung und Rückverfolgbarkeit, nicht um eine Lizenzmeinung.
