> Română: Traducere asistată automat a sursei autorizate în limba engleză. Corecțiile în limba maternă sunt binevenite. [engleză](../../README.md) | [Toate limbile](../README.md)

# Instrumente, modele și surse

![Instrumente, modele, seturi de date, versiuni și roluri păstrate într-un registru sursă auditabil](../../assets/tool-model-source-index.png)

Fiecare instrument sau model extern principal numit de registrul Datacenter întreținut este legat aici la proiectul public oficial sau la pagina de distribuție. Acesta este un index de dependență directă și model, nu o listă de materiale software tranzitivă.

Coloana de stare descrie relația înregistrată pentru componentă. Un instrument retras sau inspectat rămâne creditat fără a fi prezentat ca cod de rulare curent.

Un model extern numit într-un experiment nu este, de asemenea, sistemul de înregistrare. Rolul său este limitat la sarcina utilă și la funcționarea documentate pentru acel experiment. Chiar dacă destinatarul păstrează octeții furnizați, corpus omis, proveniența, istoricul temporal și mașina de construcție a sarcinii utile rămân în afara acestei dependențe.

| Instrument sau model | Sursă publică oficială | Relație înregistrată | Folosit de |
|---|---|---|---|
| AMF ARI Roberta OpenVINO model | [sursă](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | în amonte | amf_ari, argument_relation_classifier |
| BlingFire | [sursă](https://github.com/microsoft/BlingFire) | în amonte | microplanner, slop_analysis |
| Caddy | [sursă](https://github.com/caddyserver/caddy) | în amonte | tls |
| Trimis | [sursă](https://github.com/envoyproxy/envoy) | predecesor retras (nu runtime) | router |
| FactCG | [sursă](https://github.com/derenlei/FactCG) | în amonte | observator_semantic |
| FastAPI | [sursă](https://github.com/fastapi/fastapi) | în amonte | conversation_splitter, mission_control, router |
| FastCoref | [sursă](https://github.com/shon-otmazgin/fastcoref) | în amonte | discurs_preprocesare |
| mai rapid-distilează-whisper-large-v3 | [sursă](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | în amonte | discursuri |
| mai repede-şoaptă | [sursă](https://github.com/SYSTRAN/faster-whisper) | în amonte | discursuri |
| Graphviz | [sursă](https://gitlab.com/graphviz/graphviz) | în amonte | misiune_control |
| IsaNLP RST | [sursă](https://github.com/tchewik/isanlp_rst) | în amonte | discurs_preprocesare |
| îngenunchează | [sursă](https://github.com/arvkevi/kneed) | în amonte | collapse_packets |
| LibreChat | [sursă](https://github.com/danny-avila/LibreChat) | în amonte | chat |
| MiniCheck | [sursă](https://github.com/Liyan06/MiniCheck) | în amonte | observator_semantic |
| MongoDB | [sursă](https://github.com/mongodb/mongo) | în amonte | mongodb |
| NetworkX | [sursă](https://github.com/networkx/networkx) | în amonte | proiecție_grafică |
| NLTK | [sursă](https://github.com/nltk/nltk) | în amonte | slop_analysis |
| Node.js | [sursă](https://github.com/nodejs/node) | în amonte | chat |
| Nomic Embed Text | [sursă](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | în amonte | ollama_embed |
| Ollama | [sursă](https://github.com/ollama/ollama) | în amonte | ollama, ollama_embed |
| OpenVINO | [sursă](https://github.com/openvinotoolkit/openvino) | în amonte | amf_ari |
| pgvector | [sursă](https://github.com/pgvector/pgvector) | în amonte | postgres |
| PostgreSQL | [sursă](https://github.com/postgres/postgres) | în amonte | postgres |
| psutil | [sursă](https://github.com/giampaolo/psutil) | în amonte | telemetrie_hardware |
| Psychopg | [sursă](https://github.com/psycopg/psycopg) | în amonte | misiune_control |
| Qwen3 | [sursă](https://github.com/QwenLM/Qwen3) | în amonte | ollama, vllm |
| spațios | [sursă](https://github.com/explosion/spaCy) | în amonte | microplanner, slop_analysis, surface_realizer |
| Discursuri | [sursă](https://github.com/speaches-ai/speaches) | în amonte | discursuri |
| stabil-difuzie.cpp | [sursă](https://github.com/leejet/stable-diffusion.cpp) | în amonte | imagine |
| submodlib | [sursă](https://github.com/decile-team/submodlib) | în amonte | collapse_packets |
| Transformatoare | [sursă](https://github.com/huggingface/transformers) | în amonte | observator_semantic |
| Vikunja | [sursă](https://github.com/go-vikunja/vikunja) | în amonte | vikunja |
| vLLM | [sursă](https://github.com/vllm-project/vllm) | în amonte | vllm |
| Router semantic vLLM | [sursă](https://github.com/vllm-project/semantic-router) | predecesor retras / descendență inspectată (nu timpul de execuție) | router |
| Z-Imagine-Turbo | [sursă](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | în amonte | imagine |
| Referință de ambalare Z-Image-Turbo-Windows | [sursă](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | referință de ambalare inspectată (nu interfața de rulare) | imagine |

## Limita de distribuție

Documentația publică nu conține codul proiectului sau greutățile modelului enumerate. O viitoare distribuție de software trebuie să genereze versiuni exacte, revizuiri, hashuri, dependențe tranzitive, termeni de model și texte de licență din octeții distribuiți efectiv. O legătură de proiect este atribuirea și trasabilitatea, nu o opinie de licență.
