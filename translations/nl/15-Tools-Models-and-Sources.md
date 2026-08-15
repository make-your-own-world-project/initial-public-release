> Nederlands: Machineondersteunde vertaling van de gezaghebbende Engelse bron. Correcties in de moedertaal zijn welkom. [Engels](../../README.md) | [Alle talen](../README.md)

# Hulpmiddelen, modellen en bronnen

![Tools, modellen, datasets, versies en rollen bewaard in een controleerbaar bronregister](../../assets/tool-model-source-index.png)

Elk belangrijk extern hulpmiddel of model dat in het onderhouden Datacenter-grootboek wordt genoemd, is hier gelinkt naar de officiële openbare project- of distributiepagina. Dit is een directe afhankelijkheids- en modelindex, geen transitieve softwarestuklijst.

De statuskolom beschrijft de relatie die voor het onderdeel is vastgelegd. Een buiten gebruik gestelde of geïnspecteerde tool blijft gecrediteerd zonder te worden gepresenteerd als huidige runtimecode.

Een extern model dat in een experiment wordt genoemd, is eveneens niet het registratiesysteem. Zijn rol is beperkt tot de payload en de werking die voor dat experiment zijn gedocumenteerd. Zelfs als de ontvanger de aangeleverde bytes behoudt, blijven het weggelaten corpus, de herkomst, de tijdelijke geschiedenis en de machines voor de constructie van de nuttige lading buiten die afhankelijkheid.

| Gereedschap of model | Officiële publieke bron | Opgenomen relatie | Gebruikt door |
|---|---|---|---|
| AMF ARI RoBERTa OpenVINO-model | [bron](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | stroomopwaarts | amf_ari, argument_relation_classifier |
| BlingVuur | [bron](https://github.com/microsoft/BlingFire) | stroomopwaarts | microplanner, slop_analyse |
| Caddy | [bron](https://github.com/caddyserver/caddy) | stroomopwaarts | tl |
| Gezant | [bron](https://github.com/envoyproxy/envoy) | gepensioneerde voorganger (niet runtime) | router |
| FeitCG | [bron](https://github.com/derenlei/FactCG) | stroomopwaarts | semantische_waarnemer |
| SnelleAPI | [bron](https://github.com/fastapi/fastapi) | stroomopwaarts | conversation_splitter, mission_control, router |
| SnelCoref | [bron](https://github.com/shon-otmazgin/fastcoref) | stroomopwaarts | discours_voorverwerking |
| sneller-destilleren-fluisteren-groot-v3 | [bron](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | stroomopwaarts | toespraken |
| sneller-gefluister | [bron](https://github.com/SYSTRAN/faster-whisper) | stroomopwaarts | toespraken |
| Grafviz | [bron](https://gitlab.com/graphviz/graphviz) | stroomopwaarts | missie_controle |
| IsaNLP RST | [bron](https://github.com/tchewik/isanlp_rst) | stroomopwaarts | discours_voorverwerking |
| knielde | [bron](https://github.com/arvkevi/kneed) | stroomopwaarts | samenvouwen_pakketten |
| LibreChat | [bron](https://github.com/danny-avila/LibreChat) | stroomopwaarts | chatten |
| MiniCheck | [bron](https://github.com/Liyan06/MiniCheck) | stroomopwaarts | semantische_waarnemer |
| MongoDB | [bron](https://github.com/mongodb/mongo) | stroomopwaarts | Mongodb |
| NetwerkX | [bron](https://github.com/networkx/networkx) | stroomopwaarts | grafiek_projectie |
| NLTK | [bron](https://github.com/nltk/nltk) | stroomopwaarts | slop_analyse |
| Knooppunt.js | [bron](https://github.com/nodejs/node) | stroomopwaarts | chatten |
| Nomic-tekst insluiten | [bron](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | stroomopwaarts | ollama_embed |
| Ollama | [bron](https://github.com/ollama/ollama) | stroomopwaarts | ollama, ollama_embed |
| OpenVINO | [bron](https://github.com/openvinotoolkit/openvino) | stroomopwaarts | amf_ari |
| vector | [bron](https://github.com/pgvector/pgvector) | stroomopwaarts | postgres |
| PostgreSQL | [bron](https://github.com/postgres/postgres) | stroomopwaarts | postgres |
| psutil | [bron](https://github.com/giampaolo/psutil) | stroomopwaarts | hardware_telemetrie |
| Psycopg | [bron](https://github.com/psycopg/psycopg) | stroomopwaarts | missie_controle |
| Qwen3 | [bron](https://github.com/QwenLM/Qwen3) | stroomopwaarts | ollama, vllm |
| spaCy | [bron](https://github.com/explosion/spaCy) | stroomopwaarts | microplanner, slop_analyse, oppervlakte_realizer |
| Toespraken | [bron](https://github.com/speaches-ai/speaches) | stroomopwaarts | toespraken |
| stabiele diffusie.cpp | [bron](https://github.com/leejet/stable-diffusion.cpp) | stroomopwaarts | afbeelding |
| submodlib | [bron](https://github.com/decile-team/submodlib) | stroomopwaarts | samenvouwen_pakketten |
| Transformatoren | [bron](https://github.com/huggingface/transformers) | stroomopwaarts | semantische_waarnemer |
| Vikunja | [bron](https://github.com/go-vikunja/vikunja) | stroomopwaarts | vikunja |
| vLLM | [bron](https://github.com/vllm-project/vllm) | stroomopwaarts | vllm |
| vLLM semantische router | [bron](https://github.com/vllm-project/semantic-router) | gepensioneerde voorganger / geïnspecteerde lijn (geen runtime) | router |
| Z-Image-Turbo | [bron](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | stroomopwaarts | afbeelding |
| Z-Image-Turbo-Windows-verpakkingsreferentie | [bron](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | geïnspecteerde verpakkingsreferentie (niet runtime-UI) | afbeelding |

## Verspreidingsgrens

De openbare documentatie bevat geen vermelde projectcode of modelgewichten. Een toekomstige softwaredistributie moet exacte versies, revisies, hashes, transitieve afhankelijkheden, modelvoorwaarden en licentieteksten genereren uit de daadwerkelijk gedistribueerde bytes. Een projectlink is attributie en traceerbaarheid, geen licentieadvies.
