# Tools, Models, and Sources

![Tools, models, datasets, versions, and roles preserved in an auditable source registry](assets/tool-model-source-index.png)

Every principal external tool or model named by the maintained Datacenter ledger
is linked here to its official public project or distribution page. This is a
direct-dependency and model index, not a transitive software bill of materials.

The status column describes the relationship recorded for the component. A retired
or inspected tool remains credited without being presented as current runtime code.

An external model named in an experiment is likewise not the system of record. Its
role is limited to the payload and operation documented for that experiment. Even if
the recipient retains the supplied bytes, the omitted corpus, provenance, temporal
history, and payload-construction machinery remain outside that dependency.

| Tool or model | Official public source | Recorded relationship | Used by |
|---|---|---|---|
| AMF ARI RoBERTa OpenVINO model | [source](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | upstream | amf_ari, argument_relation_classifier |
| BlingFire | [source](https://github.com/microsoft/BlingFire) | upstream | microplanner, slop_analysis |
| Caddy | [source](https://github.com/caddyserver/caddy) | upstream | tls |
| Envoy | [source](https://github.com/envoyproxy/envoy) | retired predecessor (not runtime) | router |
| FactCG | [source](https://github.com/derenlei/FactCG) | upstream | semantic_observer |
| FastAPI | [source](https://github.com/fastapi/fastapi) | upstream | conversation_splitter, mission_control, router |
| FastCoref | [source](https://github.com/shon-otmazgin/fastcoref) | upstream | discourse_preprocessing |
| faster-distil-whisper-large-v3 | [source](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | upstream | speaches |
| faster-whisper | [source](https://github.com/SYSTRAN/faster-whisper) | upstream | speaches |
| Graphviz | [source](https://gitlab.com/graphviz/graphviz) | upstream | mission_control |
| IsaNLP RST | [source](https://github.com/tchewik/isanlp_rst) | upstream | discourse_preprocessing |
| kneed | [source](https://github.com/arvkevi/kneed) | upstream | collapse_packets |
| LibreChat | [source](https://github.com/danny-avila/LibreChat) | upstream | chat |
| MiniCheck | [source](https://github.com/Liyan06/MiniCheck) | upstream | semantic_observer |
| MongoDB | [source](https://github.com/mongodb/mongo) | upstream | mongodb |
| NetworkX | [source](https://github.com/networkx/networkx) | upstream | graph_projection |
| NLTK | [source](https://github.com/nltk/nltk) | upstream | slop_analysis |
| Node.js | [source](https://github.com/nodejs/node) | upstream | chat |
| Nomic Embed Text | [source](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | upstream | ollama_embed |
| Ollama | [source](https://github.com/ollama/ollama) | upstream | ollama, ollama_embed |
| OpenVINO | [source](https://github.com/openvinotoolkit/openvino) | upstream | amf_ari |
| pgvector | [source](https://github.com/pgvector/pgvector) | upstream | postgres |
| PostgreSQL | [source](https://github.com/postgres/postgres) | upstream | postgres |
| psutil | [source](https://github.com/giampaolo/psutil) | upstream | hardware_telemetry |
| Psycopg | [source](https://github.com/psycopg/psycopg) | upstream | mission_control |
| Qwen3 | [source](https://github.com/QwenLM/Qwen3) | upstream | ollama, vllm |
| spaCy | [source](https://github.com/explosion/spaCy) | upstream | microplanner, slop_analysis, surface_realizer |
| Speaches | [source](https://github.com/speaches-ai/speaches) | upstream | speaches |
| stable-diffusion.cpp | [source](https://github.com/leejet/stable-diffusion.cpp) | upstream | image |
| submodlib | [source](https://github.com/decile-team/submodlib) | upstream | collapse_packets |
| Transformers | [source](https://github.com/huggingface/transformers) | upstream | semantic_observer |
| Vikunja | [source](https://github.com/go-vikunja/vikunja) | upstream | vikunja |
| vLLM | [source](https://github.com/vllm-project/vllm) | upstream | vllm |
| vLLM Semantic Router | [source](https://github.com/vllm-project/semantic-router) | retired predecessor / inspected lineage (not runtime) | router |
| Z-Image-Turbo | [source](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | upstream | image |
| Z-Image-Turbo-Windows packaging reference | [source](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | inspected packaging reference (not runtime UI) | image |

## Distribution boundary

The public documentation does not contain any listed project’s code or model weights.
A future software distribution must generate exact versions, revisions, hashes,
transitive dependencies, model terms, and license texts from the bytes actually
distributed. A project link is attribution and traceability, not a license opinion.
