> Polski: Wspomagane maszynowo tłumaczenie wiarygodnego źródła w języku angielskim. Mile widziane poprawki w języku ojczystym. [angielski](../../README.md) | [Wszystkie języki](../README.md)

# Narzędzia, modele i źródła

![Narzędzia, modele, zbiory danych, wersje i role zachowane w możliwym do audytu rejestrze źródłowym](../../assets/tool-model-source-index.png)

Każde główne zewnętrzne narzędzie lub model wymienione w prowadzonej księdze Datacenter jest tutaj połączone z jego oficjalnym publicznym projektem lub stroną dystrybucyjną. Jest to indeks bezpośrednich zależności i modeli, a nie przechodnie zestawienie materiałów oprogramowania.

Kolumna stanu opisuje relację zarejestrowaną dla komponentu. Wycofane lub sprawdzone narzędzie pozostaje uznane bez przedstawiania go jako bieżącego kodu wykonawczego.

Model zewnętrzny wymieniony w eksperymencie również nie jest systemem zapisu. Jego rola ogranicza się do ładunku i działania udokumentowanego dla tego eksperymentu. Nawet jeśli odbiorca zachowa dostarczone bajty, pominięty korpus, pochodzenie, historia czasowa i maszyny do budowy ładunku pozostają poza tą zależnością.

| Narzędzie lub model | Oficjalne źródło publiczne | Nagrana relacja | Używany przez |
|---|---|---|---|
| Model AMF ARI RoBERTa OpenVINO | [źródło](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | pod prąd | amf_ari, argument_relation_classifier |
| BlingFire | [źródło](https://github.com/microsoft/BlingFire) | pod prąd | mikroplanista, slop_analytics |
| Nosiciel kijów golfowych | [źródło](https://github.com/caddyserver/caddy) | pod prąd | tls |
| Wysłannik | [źródło](https://github.com/envoyproxy/envoy) | emerytowany poprzednik (nie środowisko wykonawcze) | routera |
| FaktCG | [źródło](https://github.com/derenlei/FactCG) | pod prąd | semantyczny_obserwator |
| FastAPI | [źródło](https://github.com/fastapi/fastapi) | pod prąd | rozdzielacz_rozmowy, kontrola_misji, router |
| FastCoref | [źródło](https://github.com/shon-otmazgin/fastcoref) | pod prąd | wstępne przetwarzanie dyskursu |
| szybsza destylacja-szept-duży-v3 | [źródło](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | pod prąd | przemawia |
| szybciej-szeptem | [źródło](https://github.com/SYSTRAN/faster-whisper) | pod prąd | przemawia |
| Grafwiz | [źródło](https://gitlab.com/graphviz/graphviz) | pod prąd | kontrola_misji |
| IsaNLP RST | [źródło](https://github.com/tchewik/isanlp_rst) | pod prąd | wstępne przetwarzanie dyskursu |
| kolanem | [źródło](https://github.com/arvkevi/kneed) | pod prąd | zwiń_pakiety |
| LibreChat | [źródło](https://github.com/danny-avila/LibreChat) | pod prąd | pogawędzić |
| Miniczek | [źródło](https://github.com/Liyan06/MiniCheck) | pod prąd | semantyczny_obserwator |
| MongoDB | [źródło](https://github.com/mongodb/mongo) | pod prąd | mongodb |
| SiećX | [źródło](https://github.com/networkx/networkx) | pod prąd | wykres_projekcja |
| NLTK | [źródło](https://github.com/nltk/nltk) | pod prąd | analiza_slopu |
| Node.js | [źródło](https://github.com/nodejs/node) | pod prąd | pogawędzić |
| Tekst osadzania Nomic | [źródło](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | pod prąd | ollama_embed |
| Ollama | [źródło](https://github.com/ollama/ollama) | pod prąd | ollama, ollama_embed |
| OtwórzVINO | [źródło](https://github.com/openvinotoolkit/openvino) | pod prąd | amf_ari |
| pgwektor | [źródło](https://github.com/pgvector/pgvector) | pod prąd | postgres |
| PostgreSQL | [źródło](https://github.com/postgres/postgres) | pod prąd | postgres |
| psutil | [źródło](https://github.com/giampaolo/psutil) | pod prąd | sprzęt_telemetria |
| Psychopatyk | [źródło](https://github.com/psycopg/psycopg) | pod prąd | kontrola_misji |
| Qwen3 | [źródło](https://github.com/QwenLM/Qwen3) | pod prąd | ollama, vllm |
| spaCy | [źródło](https://github.com/explosion/spaCy) | pod prąd | mikroplanista, analiza_slopu, realizacja_powierzchni |
| Przemawia | [źródło](https://github.com/speaches-ai/speaches) | pod prąd | przemawia |
| stable-diffusion.cpp | [źródło](https://github.com/leejet/stable-diffusion.cpp) | pod prąd | obraz |
| submodlib | [źródło](https://github.com/decile-team/submodlib) | pod prąd | zwiń_pakiety |
| Transformatory | [źródło](https://github.com/huggingface/transformers) | pod prąd | semantyczny_obserwator |
| Vikunja | [źródło](https://github.com/go-vikunja/vikunja) | pod prąd | vikunja |
| vLLM | [źródło](https://github.com/vllm-project/vllm) | pod prąd | vllm |
| Router semantyczny vLLM | [źródło](https://github.com/vllm-project/semantic-router) | emerytowany poprzednik / sprawdzony rodowód (nie czas wykonania) | routera |
| Z-Image-Turbo | [źródło](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | pod prąd | obraz |
| Odniesienie do opakowania Z-Image-Turbo-Windows | [źródło](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | sprawdzone odniesienie do opakowania (nie interfejs użytkownika środowiska wykonawczego) | obraz |

## Granica dystrybucji

Dokumentacja publiczna nie zawiera żadnego wymienionego kodu projektu ani wag modeli. Przyszła dystrybucja oprogramowania musi generować dokładne wersje, poprawki, skróty, zależności przechodnie, warunki modelu i teksty licencji z faktycznie dystrybuowanych bajtów. Link do projektu to przypisanie i identyfikowalność, a nie opinia licencyjna.
