> Magyar: A hiteles angol forrás gépi fordítása. Anyanyelvi javításokat szívesen fogadunk. [angol](../../README.md) | [Minden nyelv](../README.md)

# Eszközök, modellek és források

![Eszközök, modellek, adatkészletek, verziók és szerepkörök egy auditálható forrásnyilvántartásban tárolva](../../assets/tool-model-source-index.png)

A karbantartott Datacenter főkönyv által megnevezett minden fő külső eszköz vagy modell itt kapcsolódik a hivatalos nyilvános projekthez vagy terjesztési oldalhoz. Ez egy közvetlen függőségi és modellindex, nem pedig egy tranzitív szoftveres anyagjegyzék.

Az állapotoszlop az összetevőhöz rögzített kapcsolatot írja le. A megszüntetett vagy ellenőrzött eszköz jóváírásra kerül anélkül, hogy aktuális futási kódként jelenne meg.

A kísérletben megnevezett külső modell szintén nem a rekordrendszer. Szerepe az adott kísérlethez dokumentált hasznos teherre és műveletre korlátozódik. Még ha a címzett megtartja is a szolgáltatott bájtokat, a kihagyott korpusz, származás, időtörténet és hasznos teherépítő gépezet kívül marad ezen a függőségen.

| Szerszám vagy modell | Hivatalos nyilvános forrás | Rögzített kapcsolat | által használt |
|---|---|---|---|
| AMF ARI RoBERTa OpenVINO modell | [forrás](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | felfelé | amf_ari, argumentum_relation_classifier |
| BlingFire | [forrás](https://github.com/microsoft/BlingFire) | felfelé | mikrotervező, slop_analysis |
| Labdaszedő | [forrás](https://github.com/caddyserver/caddy) | felfelé | tls |
| Követ | [forrás](https://github.com/envoyproxy/envoy) | nyugdíjas előd (nem futásidejű) | router |
| FactCG | [forrás](https://github.com/derenlei/FactCG) | felfelé | szemantikai_megfigyelő |
| FastAPI | [forrás](https://github.com/fastapi/fastapi) | felfelé | beszélgetés_elosztó, mission_control, router |
| FastCoref | [forrás](https://github.com/shon-otmazgin/fastcoref) | felfelé | discourse_preprocessing |
| gyorsabb-desztil-súg-nagy-v3 | [forrás](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | felfelé | beszédeket |
| gyorsabb-suttog | [forrás](https://github.com/SYSTRAN/faster-whisper) | felfelé | beszédeket |
| Graphviz | [forrás](https://gitlab.com/graphviz/graphviz) | felfelé | mission_control |
| IsaNLP RST | [forrás](https://github.com/tchewik/isanlp_rst) | felfelé | discourse_preprocessing |
| letérdelt | [forrás](https://github.com/arvkevi/kneed) | felfelé | collapse_packets |
| LibreChat | [forrás](https://github.com/danny-avila/LibreChat) | felfelé | csevegés |
| MiniCheck | [forrás](https://github.com/Liyan06/MiniCheck) | felfelé | szemantikai_megfigyelő |
| MongoDB | [forrás](https://github.com/mongodb/mongo) | felfelé | mongodb |
| NetworkX | [forrás](https://github.com/networkx/networkx) | felfelé | graph_projection |
| NLTK | [forrás](https://github.com/nltk/nltk) | felfelé | slop_analízis |
| Node.js | [forrás](https://github.com/nodejs/node) | felfelé | csevegés |
| Névleges szöveg beágyazása | [forrás](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | felfelé | ollama_embed |
| Ollama | [forrás](https://github.com/ollama/ollama) | felfelé | ollama, ollama_embed |
| OpenVINO | [forrás](https://github.com/openvinotoolkit/openvino) | felfelé | amf_ari |
| pgvector | [forrás](https://github.com/pgvector/pgvector) | felfelé | postgres |
| PostgreSQL | [forrás](https://github.com/postgres/postgres) | felfelé | postgres |
| psutil | [forrás](https://github.com/giampaolo/psutil) | felfelé | hardver_telemetria |
| Psycopg | [forrás](https://github.com/psycopg/psycopg) | felfelé | mission_control |
| Qwen3 | [forrás](https://github.com/QwenLM/Qwen3) | felfelé | ollama, vllm |
| borsos | [forrás](https://github.com/explosion/spaCy) | felfelé | mikrotervező, slop_analízis, felületmegvalósító |
| Beszédek | [forrás](https://github.com/speaches-ai/speaches) | felfelé | beszédeket |
| stabil diffúzió.cpp | [forrás](https://github.com/leejet/stable-diffusion.cpp) | felfelé | kép |
| submodlib | [forrás](https://github.com/decile-team/submodlib) | felfelé | collapse_packets |
| Transzformátorok | [forrás](https://github.com/huggingface/transformers) | felfelé | szemantikai_megfigyelő |
| Vikunja | [forrás](https://github.com/go-vikunja/vikunja) | felfelé | vikunja |
| vLLM | [forrás](https://github.com/vllm-project/vllm) | felfelé | vllm |
| vLLM szemantikus útválasztó | [forrás](https://github.com/vllm-project/semantic-router) | nyugdíjazott előd / ellenőrzött származás (nem futásidejű) | router |
| Z-Image-Turbo | [forrás](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | felfelé | kép |
| Z-Image-Turbo-Windows csomagolási hivatkozás | [forrás](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | ellenőrzött csomagolási hivatkozás (nem futásidejű felhasználói felület) | kép |

## Elterjedési határ

A nyilvános dokumentáció nem tartalmazza a projekt felsorolt ​​kódját vagy modellsúlyát. Egy jövőbeli szoftverterjesztésnek pontos verziókat, változatokat, kivonatokat, tranzitív függőségeket, modellfeltételeket és licencszövegeket kell generálnia a ténylegesen terjesztett bájtokból. A projekt linkje hozzárendelés és nyomon követhetőség, nem licenc vélemény.
