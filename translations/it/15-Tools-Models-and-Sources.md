> Italiano: Traduzione assistita da macchina dell'autorevole fonte inglese. Sono gradite correzioni nella lingua madre. [Inglese](../../README.md) | [Tutte le lingue](../README.md)

# Strumenti, modelli e fonti

![Strumenti, modelli, set di dati, versioni e ruoli conservati in un registro di origine controllabile](../../assets/tool-model-source-index.png)

Ogni principale strumento o modello esterno nominato dal registro mantenuto del Datacenter è collegato qui al suo progetto pubblico ufficiale o alla pagina di distribuzione. Si tratta di un indice di dipendenza diretta e di modello, non di una distinta base transitiva del software.

La colonna stato descrive la relazione registrata per il componente. Uno strumento ritirato o ispezionato rimane accreditato senza essere presentato come codice runtime corrente.

Allo stesso modo, un modello esterno nominato in un esperimento non è il sistema di registrazione. Il suo ruolo è limitato al carico utile e all'operazione documentata per quell'esperimento. Anche se il destinatario conserva i byte forniti, il corpus, la provenienza, la storia temporale e il meccanismo di costruzione del carico utile rimangono al di fuori di tale dipendenza.

| Strumento o modello | Fonte pubblica ufficiale | Relazione registrata | Usato da |
|---|---|---|---|
| Modello AMF ARI RoBERTa OpenVINO | [fonte](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | a monte | amf_ari, argomento_relazione_classificatore |
| Fuoco scintillante | [fonte](https://github.com/microsoft/BlingFire) | a monte | microplanner, slop_analysis |
| Caddy | [fonte](https://github.com/caddyserver/caddy) | a monte | tls |
| Inviato | [fonte](https://github.com/envoyproxy/envoy) | predecessore ritirato (non runtime) | router |
| FattoCG | [fonte](https://github.com/derenlei/FactCG) | a monte | osservatore_semantico |
| API veloce | [fonte](https://github.com/fastapi/fastapi) | a monte | conversazione_splitter, missione_controllo, router |
| FastCoref | [fonte](https://github.com/shon-otmazgin/fastcoref) | a monte | discorso_preelaborazione |
| distillazione-veloce-whisper-large-v3 | [fonte](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | a monte | discorsi |
| sussurro più veloce | [fonte](https://github.com/SYSTRAN/faster-whisper) | a monte | discorsi |
| Graphviz | [fonte](https://gitlab.com/graphviz/graphviz) | a monte | mission_control |
| IsaNLP RST | [fonte](https://github.com/tchewik/isanlp_rst) | a monte | discorso_preelaborazione |
| inginocchiato | [fonte](https://github.com/arvkevi/kneed) | a monte | collasso_pacchetti |
| LibreChat | [fonte](https://github.com/danny-avila/LibreChat) | a monte | chiacchierata |
| MiniCheck | [fonte](https://github.com/Liyan06/MiniCheck) | a monte | osservatore_semantico |
| MongoDB | [fonte](https://github.com/mongodb/mongo) | a monte | mongodb |
| ReteX | [fonte](https://github.com/networkx/networkx) | a monte | grafico_proiezione |
| NLTK | [fonte](https://github.com/nltk/nltk) | a monte | slop_analysis |
| Node.js | [fonte](https://github.com/nodejs/node) | a monte | chiacchierata |
| Testo incorporato nomico | [fonte](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | a monte | ollama_embed |
| Ollama | [fonte](https://github.com/ollama/ollama) | a monte | ollama, ollama_embed |
| ApriVINO | [fonte](https://github.com/openvinotoolkit/openvino) | a monte | amf_ari |
| pgvettore | [fonte](https://github.com/pgvector/pgvector) | a monte | postgres |
| PostgreSQL | [fonte](https://github.com/postgres/postgres) | a monte | postgres |
| psutil | [fonte](https://github.com/giampaolo/psutil) | a monte | hardware_telemetria |
| Psicopg | [fonte](https://github.com/psycopg/psycopg) | a monte | mission_control |
| Qwen3 | [fonte](https://github.com/QwenLM/Qwen3) | a monte | ollama, vllm |
| SPAZIOSO | [fonte](https://github.com/explosion/spaCy) | a monte | microplanner, slop_analysis, surface_realizer |
| Discorsi | [fonte](https://github.com/speaches-ai/speaches) | a monte | discorsi |
| diffusione-stabile.cpp | [fonte](https://github.com/leejet/stable-diffusion.cpp) | a monte | immagine |
| submodlib | [fonte](https://github.com/decile-team/submodlib) | a monte | collasso_pacchetti |
| Trasformatori | [fonte](https://github.com/huggingface/transformers) | a monte | osservatore_semantico |
| Vikunja | [fonte](https://github.com/go-vikunja/vikunja) | a monte | vikunja |
| vLLM | [fonte](https://github.com/vllm-project/vllm) | a monte | vllm |
| Router semantico vLLM | [fonte](https://github.com/vllm-project/semantic-router) | predecessore ritirato/lignaggio ispezionato (non runtime) | router |
| Z-Immagine-Turbo | [fonte](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | a monte | immagine |
| Riferimento alla confezione Z-Image-Turbo-Windows | [fonte](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | riferimento al pacchetto ispezionato (non interfaccia utente runtime) | immagine |

## Confine di distribuzione

La documentazione pubblica non contiene alcun codice di progetto elencato o pesi di modello. Una futura distribuzione del software deve generare versioni esatte, revisioni, hash, dipendenze transitive, termini del modello e testi di licenza dai byte effettivamente distribuiti. Un collegamento al progetto è attribuzione e tracciabilità, non un parere di licenza.
