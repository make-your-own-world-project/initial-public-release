> Українська: Машинний переклад авторитетного англійського джерела. Виправлення рідною мовою вітаються. [англійська](../../README.md) | [Всі мови](../README.md)

# Інструменти, моделі та джерела

![Інструменти, моделі, набори даних, версії та ролі зберігаються в вихідному реєстрі, який можна перевірити](../../assets/tool-model-source-index.png)

Кожен основний зовнішній інструмент або модель, названі в обліковій книзі центру обробки даних, пов’язані тут із офіційним загальнодоступним проектом або сторінкою розповсюдження. Це індекс прямої залежності та моделі, а не перехідний список матеріалів програмного забезпечення.

Стовпець статусу описує зв’язок, записаний для компонента. Вилучений або перевірений інструмент залишається зарахованим без представлення як поточний код виконання.

Зовнішня модель, названа в експерименті, також не є системою запису. Його роль обмежена корисним навантаженням і операціями, задокументованими для цього експерименту. Навіть якщо одержувач зберігає надані байти, пропущений корпус, походження, часова історія та механізм створення корисного навантаження залишаються поза цією залежністю.

| Інструмент або модель | Офіційне публічне джерело | Записані відносини | Використовується |
|---|---|---|---|
| Модель AMF ARI RoBERTa OpenVINO | [джерело](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | вище за течією | amf_ari, аргумент_відношення_класифікатор |
| BlingFire | [джерело](https://github.com/microsoft/BlingFire) | вище за течією | мікропланувальник, slop_analysis |
| Кедді | [джерело](https://github.com/caddyserver/caddy) | вище за течією | tls |
| Посланець | [джерело](https://github.com/envoyproxy/envoy) | знятий попередник (не час виконання) | маршрутизатор |
| FactCG | [джерело](https://github.com/derenlei/FactCG) | вище за течією | semantic_observer |
| FastAPI | [джерело](https://github.com/fastapi/fastapi) | вище за течією | розгалужувач_розмов, керування місією, маршрутизатор |
| FastCoref | [джерело](https://github.com/shon-otmazgin/fastcoref) | вище за течією | попередня обробка дискурсу |
| faster-distil-whisper-large-v3 | [джерело](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | вище за течією | виступи |
| швидше-пошепки | [джерело](https://github.com/SYSTRAN/faster-whisper) | вище за течією | виступи |
| Graphviz | [джерело](https://gitlab.com/graphviz/graphviz) | вище за течією | mission_control |
| IsaNLP RST | [джерело](https://github.com/tchewik/isanlp_rst) | вище за течією | попередня обробка дискурсу |
| коліна | [джерело](https://github.com/arvkevi/kneed) | вище за течією | collapse_packets |
| LibreChat | [джерело](https://github.com/danny-avila/LibreChat) | вище за течією | чат |
| MiniCheck | [джерело](https://github.com/Liyan06/MiniCheck) | вище за течією | semantic_observer |
| MongoDB | [джерело](https://github.com/mongodb/mongo) | вище за течією | mongodb |
| NetworkX | [джерело](https://github.com/networkx/networkx) | вище за течією | граф_проекція |
| NLTK | [джерело](https://github.com/nltk/nltk) | вище за течією | slop_analysis |
| Node.js | [джерело](https://github.com/nodejs/node) | вище за течією | чат |
| Nomic Embed Text | [джерело](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | вище за течією | ollama_embed |
| Оллама | [джерело](https://github.com/ollama/ollama) | вище за течією | ollama, ollama_embed |
| OpenVINO | [джерело](https://github.com/openvinotoolkit/openvino) | вище за течією | amf_ari |
| pgvector | [джерело](https://github.com/pgvector/pgvector) | вище за течією | postgres |
| PostgreSQL | [джерело](https://github.com/postgres/postgres) | вище за течією | postgres |
| psutil | [джерело](https://github.com/giampaolo/psutil) | вище за течією | апаратна_телеметрія |
| Psycopg | [джерело](https://github.com/psycopg/psycopg) | вище за течією | mission_control |
| Qwen3 | [джерело](https://github.com/QwenLM/Qwen3) | вище за течією | ollama, vllm |
| spaCy | [джерело](https://github.com/explosion/spaCy) | вище за течією | мікропланувальник, slop_analysis, surface_realizer |
| Виступи | [джерело](https://github.com/speaches-ai/speaches) | вище за течією | виступи |
| stable-diffusion.cpp | [джерело](https://github.com/leejet/stable-diffusion.cpp) | вище за течією | зображення |
| submodlib | [джерело](https://github.com/decile-team/submodlib) | вище за течією | collapse_packets |
| Трансформери | [джерело](https://github.com/huggingface/transformers) | вище за течією | semantic_observer |
| Вікунья | [джерело](https://github.com/go-vikunja/vikunja) | вище за течією | вікунджа |
| vLLM | [джерело](https://github.com/vllm-project/vllm) | вище за течією | vllm |
| Семантичний маршрутизатор vLLM | [джерело](https://github.com/vllm-project/semantic-router) | вилучений попередник/перевірене походження (не час виконання) | маршрутизатор |
| Z-Image-Turbo | [джерело](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | вище за течією | зображення |
| Посилання на упаковку Z-Image-Turbo-Windows | [джерело](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | посилання на перевірену упаковку (не інтерфейс користувача під час виконання) | зображення |

## Межа поширення

Загальнодоступна документація не містить коду проекту чи ваги моделі. Майбутнє розповсюдження програмного забезпечення має генерувати точні версії, редакції, хеші, транзитивні залежності, умови моделі та тексти ліцензій із фактично розповсюджених байтів. Посилання на проект: це посилання на авторство та відстеження, а не думка про ліцензію.
