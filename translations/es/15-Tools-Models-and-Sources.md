> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../README.md) | [Todos los idiomas](../README.md)

# Herramientas, modelos y fuentes

![Herramientas, modelos, conjuntos de datos, versiones y roles conservados en un registro de origen auditable](../../assets/tool-model-source-index.png)

Cada herramienta o modelo externo principal nombrado por el libro mayor del centro de datos mantenido está vinculado aquí a su proyecto público oficial o página de distribución. Este es un índice de modelo y dependencia directa, no una lista de materiales de software transitivo.

La columna de estado describe la relación registrada para el componente. Una herramienta retirada o inspeccionada permanece acreditada sin presentarse como código de ejecución actual.

Un modelo externo nombrado en un experimento tampoco es el sistema de registro. Su función se limita a la carga útil y la operación documentada para ese experimento. Incluso si el destinatario retiene los bytes suministrados, el corpus, la procedencia, la historia temporal y la maquinaria de construcción de la carga útil omitidos permanecen fuera de esa dependencia.

| Herramienta o modelo | Fuente pública oficial | relación grabada | Utilizado por |
|---|---|---|---|
| Modelo AMF ARI RoBERTa OpenVINO | [fuente](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | río arriba | amf_ari, clasificador_relación_argumento |
| BlingFuego | [fuente](https://github.com/microsoft/BlingFire) | río arriba | microplanificador, análisis de pendiente |
| Caddie | [fuente](https://github.com/caddyserver/caddy) | río arriba | tls |
| Enviado | [fuente](https://github.com/envoyproxy/envoy) | predecesor retirado (no tiempo de ejecución) | enrutador |
| HechoCG | [fuente](https://github.com/derenlei/FactCG) | río arriba | observador_semántico |
| API rápida | [fuente](https://github.com/fastapi/fastapi) | río arriba | divisor_conversación, control_misión, enrutador |
| FastCoref | [fuente](https://github.com/shon-otmazgin/fastcoref) | río arriba | preprocesamiento_del discurso |
| destilado-más rápido-susurro-grande-v3 | [fuente](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | río arriba | discursos |
| susurro más rápido | [fuente](https://github.com/SYSTRAN/faster-whisper) | río arriba | discursos |
| Grafiz | [fuente](https://gitlab.com/graphviz/graphviz) | río arriba | control_misión |
| IsaNLP RST | [fuente](https://github.com/tchewik/isanlp_rst) | río arriba | preprocesamiento_del discurso |
| arrodillado | [fuente](https://github.com/arvkevi/kneed) | río arriba | colapso_paquetes |
| LibreChat | [fuente](https://github.com/danny-avila/LibreChat) | río arriba | charlar |
| minicheque | [fuente](https://github.com/Liyan06/MiniCheck) | río arriba | observador_semántico |
| MongoDB | [fuente](https://github.com/mongodb/mongo) | río arriba | mongodb |
| RedX | [fuente](https://github.com/networkx/networkx) | río arriba | proyección_grafo |
| NLTK | [fuente](https://github.com/nltk/nltk) | río arriba | análisis_deslizamiento |
| Nodo.js | [fuente](https://github.com/nodejs/node) | río arriba | charlar |
| Texto incrustado nómico | [fuente](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | río arriba | ollama_embed |
| Ollama | [fuente](https://github.com/ollama/ollama) | río arriba | ollama, ollama_embed |
| AbiertoVINO | [fuente](https://github.com/openvinotoolkit/openvino) | río arriba | amf_ari |
| pgvector | [fuente](https://github.com/pgvector/pgvector) | río arriba | postgres |
| PostgreSQL | [fuente](https://github.com/postgres/postgres) | río arriba | postgres |
| psutil | [fuente](https://github.com/giampaolo/psutil) | río arriba | telemetría_hardware |
| psicópata | [fuente](https://github.com/psycopg/psycopg) | río arriba | control_misión |
| Qwen3 | [fuente](https://github.com/QwenLM/Qwen3) | río arriba | ollama, vllm |
| espacio | [fuente](https://github.com/explosion/spaCy) | río arriba | microplanificador, análisis de pendiente, realizador de superficie |
| discursos | [fuente](https://github.com/speaches-ai/speaches) | río arriba | discursos |
| difusión-estable.cpp | [fuente](https://github.com/leejet/stable-diffusion.cpp) | río arriba | imagen |
| submodlib | [fuente](https://github.com/decile-team/submodlib) | río arriba | colapso_paquetes |
| Transformadores | [fuente](https://github.com/huggingface/transformers) | río arriba | observador_semántico |
| Vikunja | [fuente](https://github.com/go-vikunja/vikunja) | río arriba | vikunja |
| vllm | [fuente](https://github.com/vllm-project/vllm) | río arriba | vllm |
| Enrutador semántico vLLM | [fuente](https://github.com/vllm-project/semantic-router) | predecesor retirado/linaje inspeccionado (no tiempo de ejecución) | enrutador |
| Z-Imagen-Turbo | [fuente](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | río arriba | imagen |
| Referencia de empaquetado de Z-Image-Turbo-Windows | [fuente](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | referencia de embalaje inspeccionado (no interfaz de usuario en tiempo de ejecución) | imagen |

## Límite de distribución

La documentación pública no contiene ningún código de proyecto ni pesos de modelo enumerados. Una futura distribución de software debe generar versiones, revisiones, hashes, dependencias transitivas, términos modelo y textos de licencia exactos a partir de los bytes realmente distribuidos. Un vínculo de proyecto es atribución y trazabilidad, no una opinión de licencia.
