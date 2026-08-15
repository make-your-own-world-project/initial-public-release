> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../README.md) | [Todos os idiomas](../README.md)

# Ferramentas, modelos e fontes

![Ferramentas, modelos, conjuntos de dados, versões e funções preservadas em um registro de origem auditável](../../assets/tool-model-source-index.png)

Cada ferramenta ou modelo externo principal nomeado pelo livro-razão do Datacenter mantido está vinculado aqui ao seu projeto público oficial ou página de distribuição. Este é um índice de modelo e dependência direta, não uma lista de materiais de software transitiva.

A coluna de status descreve o relacionamento registrado para o componente. Uma ferramenta descontinuada ou inspecionada permanece creditada sem ser apresentada como código de tempo de execução atual.

Da mesma forma, um modelo externo nomeado em um experimento não é o sistema de registro. Sua função é limitada à carga útil e à operação documentada para esse experimento. Mesmo que o destinatário retenha os bytes fornecidos, o corpus, a proveniência, a história temporal e o maquinário de construção de carga omitidos permanecem fora dessa dependência.

| Ferramenta ou modelo | Fonte pública oficial | Relacionamento gravado | Usado por |
|---|---|---|---|
| Modelo AMF ARI RoBERTa OpenVINO | [fonte](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | rio acima | amf_ari, argumento_relação_classificador |
| BlingFire | [fonte](https://github.com/microsoft/BlingFire) | rio acima | microplanejador, slop_análise |
| Caddie | [fonte](https://github.com/caddyserver/caddy) | rio acima | tls |
| Enviado | [fonte](https://github.com/envoyproxy/envoy) | antecessor aposentado (não em tempo de execução) | roteador |
| FatoCG | [fonte](https://github.com/derenlei/FactCG) | rio acima | observador_semântico |
| API rápida | [fonte](https://github.com/fastapi/fastapi) | rio acima | conversa_splitter, controle de missão, roteador |
| FastCoref | [fonte](https://github.com/shon-otmazgin/fastcoref) | rio acima | discurso_pré-processamento |
| mais rápido-destilar-sussurro-grande-v3 | [fonte](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | rio acima | discursos |
| sussurro mais rápido | [fonte](https://github.com/SYSTRAN/faster-whisper) | rio acima | discursos |
| Gráficoviz | [fonte](https://gitlab.com/graphviz/graphviz) | rio acima | missão_controle |
| IsaNLP RST | [fonte](https://github.com/tchewik/isanlp_rst) | rio acima | discurso_pré-processamento |
| joelhada | [fonte](https://github.com/arvkevi/kneed) | rio acima | recolher_pacotes |
| Chat Livre | [fonte](https://github.com/danny-avila/LibreChat) | rio acima | bater papo |
| MiniCheck | [fonte](https://github.com/Liyan06/MiniCheck) | rio acima | observador_semântico |
| MongoDB | [fonte](https://github.com/mongodb/mongo) | rio acima | mongodb |
| RedeX | [fonte](https://github.com/networkx/networkx) | rio acima | projeção_gráfica |
| NLTK | [fonte](https://github.com/nltk/nltk) | rio acima | slop_análise |
| Node.js | [fonte](https://github.com/nodejs/node) | rio acima | bater papo |
| Texto incorporado Nômico | [fonte](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | rio acima | ollama_embed |
| Ollama | [fonte](https://github.com/ollama/ollama) | rio acima | ollama, ollama_embed |
| OpenVINO | [fonte](https://github.com/openvinotoolkit/openvino) | rio acima | amf_ari |
| vetor pg | [fonte](https://github.com/pgvector/pgvector) | rio acima | postgres |
| PostgreSQL | [fonte](https://github.com/postgres/postgres) | rio acima | postgres |
| psutil | [fonte](https://github.com/giampaolo/psutil) | rio acima | hardware_telemetria |
| Psicopg | [fonte](https://github.com/psycopg/psycopg) | rio acima | missão_controle |
| Qwen3 | [fonte](https://github.com/QwenLM/Qwen3) | rio acima | ollama, vllm |
| spaCy | [fonte](https://github.com/explosion/spaCy) | rio acima | microplanejador, análise de slop, superfície_realizer |
| Discursos | [fonte](https://github.com/speaches-ai/speaches) | rio acima | discursos |
| difusão estável.cpp | [fonte](https://github.com/leejet/stable-diffusion.cpp) | rio acima | imagem |
| submodlib | [fonte](https://github.com/decile-team/submodlib) | rio acima | recolher_pacotes |
| Transformadores | [fonte](https://github.com/huggingface/transformers) | rio acima | observador_semântico |
| Vikunja | [fonte](https://github.com/go-vikunja/vikunja) | rio acima | Vikunja |
| vLLM | [fonte](https://github.com/vllm-project/vllm) | rio acima | vllm |
| Roteador Semântico vLLM | [fonte](https://github.com/vllm-project/semantic-router) | antecessor aposentado/linhagem inspecionada (não em tempo de execução) | roteador |
| Z-Imagem-Turbo | [fonte](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | rio acima | imagem |
| Referência de embalagem Z-Image-Turbo-Windows | [fonte](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | referência de embalagem inspecionada (não UI de tempo de execução) | imagem |

## Limite de distribuição

A documentação pública não contém nenhum código de projeto listado ou pesos de modelo. Uma futura distribuição de software deve gerar versões exatas, revisões, hashes, dependências transitivas, termos de modelo e textos de licença a partir dos bytes realmente distribuídos. Um link de projeto é atribuição e rastreabilidade, não uma opinião de licença.
