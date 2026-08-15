> Français: Traduction assistée par machine de la source anglaise faisant autorité. Native-language corrections are welcome. [Anglais](../../README.md) | [Toutes les langues](../README.md)

# Outils, modèles et sources

![Outils, modèles, ensembles de données, versions et rôles conservés dans un registre source auditable](../../assets/tool-model-source-index.png)

Chaque principal outil ou modèle externe nommé par le grand livre du Datacenter maintenu est lié ici à son projet public officiel ou à sa page de distribution. Il s'agit d'un index de modèle et de dépendance directe, et non d'une nomenclature logicielle transitive.

La colonne d'état décrit la relation enregistrée pour le composant. Un outil retiré ou inspecté reste crédité sans être présenté comme code d'exécution actuel.

Un modèle externe nommé dans une expérience n’est pas non plus le système d’enregistrement. Son rôle se limite à la charge utile et au fonctionnement documentés pour cette expérience. Même si le destinataire conserve les octets fournis, le corpus omis, la provenance, l'historique temporel et la machinerie de construction de charge utile restent en dehors de cette dépendance.

| Outil ou modèle | Source publique officielle | Relation enregistrée | Utilisé par |
|---|---|---|---|
| Modèle AMF ARI RoBERTa OpenVINO | [source](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | en amont | amf_ari, argument_relation_classifier |
| BlingFire | [source](https://github.com/microsoft/BlingFire) | en amont | microplanificateur, slop_analysis |
| Caddie | [source](https://github.com/caddyserver/caddy) | en amont | tls |
| Envoyé | [source](https://github.com/envoyproxy/envoy) | prédécesseur retiré (pas d'exécution) | routeur |
| FactCG | [source](https://github.com/derenlei/FactCG) | en amont | observateur_sémantique |
| API rapide | [source](https://github.com/fastapi/fastapi) | en amont | conversation_splitter, mission_control, routeur |
| FastCoref | [source](https://github.com/shon-otmazgin/fastcoref) | en amont | discours_prétraitement |
| distillation-plus rapide-chuchotée-large-v3 | [source](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | en amont | discours |
| murmurer plus vite | [source](https://github.com/SYSTRAN/faster-whisper) | en amont | discours |
| Visualisation graphique | [source](https://gitlab.com/graphviz/graphviz) | en amont | mission_control |
| IsaNLP RST | [source](https://github.com/tchewik/isanlp_rst) | en amont | discours_prétraitement |
| à genoux | [source](https://github.com/arvkevi/kneed) | en amont | réduire_paquets |
| LibreChat | [source](https://github.com/danny-avila/LibreChat) | en amont | chat |
| MiniVérification | [source](https://github.com/Liyan06/MiniCheck) | en amont | observateur_sémantique |
| MongoDB | [source](https://github.com/mongodb/mongo) | en amont | mongodb |
| RéseauX | [source](https://github.com/networkx/networkx) | en amont | graphique_projection |
| NLTK | [source](https://github.com/nltk/nltk) | en amont | slop_analyse |
| Noeud.js | [source](https://github.com/nodejs/node) | en amont | chat |
| Texte intégré nomique | [source](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | en amont | ollama_embed |
| Ollama | [source](https://github.com/ollama/ollama) | en amont | ollama, ollama_embed |
| OuvrirVINO | [source](https://github.com/openvinotoolkit/openvino) | en amont | amf_ari |
| pgvecteur | [source](https://github.com/pgvector/pgvector) | en amont | postgres |
| PostgreSQL | [source](https://github.com/postgres/postgres) | en amont | postgres |
| psutil | [source](https://github.com/giampaolo/psutil) | en amont | matériel_télémétrie |
| Psycopg | [source](https://github.com/psycopg/psycopg) | en amont | mission_control |
| Qwen3 | [source](https://github.com/QwenLM/Qwen3) | en amont | ollama, vllm |
| SpaCy | [source](https://github.com/explosion/spaCy) | en amont | microplanificateur, slop_analysis, surface_realizer |
| Discours | [source](https://github.com/speaches-ai/speaches) | en amont | discours |
| stable-diffusion.cpp | [source](https://github.com/leejet/stable-diffusion.cpp) | en amont | image |
| sous-modlib | [source](https://github.com/decile-team/submodlib) | en amont | réduire_paquets |
| Transformateurs | [source](https://github.com/huggingface/transformers) | en amont | observateur_sémantique |
| Vikunja | [source](https://github.com/go-vikunja/vikunja) | en amont | vikunja |
| vLLM | [source](https://github.com/vllm-project/vllm) | en amont | vllm |
| Routeur sémantique vLLM | [source](https://github.com/vllm-project/semantic-router) | prédécesseur à la retraite / lignée inspectée (pas d'exécution) | routeur |
| Z-Image-Turbo | [source](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | en amont | image |
| Référence d'emballage Z-Image-Turbo-Windows | [source](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | référence d'emballage inspecté (pas d'interface utilisateur d'exécution) | image |

## Limite de distribution

La documentation publique ne contient aucun code de projet répertorié ni aucun poids de modèle. Une future distribution de logiciels doit générer des versions exactes, des révisions, des hachages, des dépendances transitives, des termes de modèle et des textes de licence à partir des octets réellement distribués. Un lien de projet est une attribution et une traçabilité, pas un avis de licence.
