> Türkçe: Yetkili İngilizce kaynağın makine destekli çevirisi. Ana dildeki düzeltmeler memnuniyetle karşılanır. [İngilizce](../../README.md) | [Tüm diller](../README.md)

# Araçlar, Modeller ve Kaynaklar

![Denetlenebilir bir kaynak kayıt defterinde saklanan araçlar, modeller, veri kümeleri, sürümler ve roller](../../assets/tool-model-source-index.png)

Bakımı yapılan Veri Merkezi defteri tarafından adlandırılan her ana harici araç veya model, burada resmi kamu projesine veya dağıtım sayfasına bağlanır. Bu, geçişli bir yazılım malzeme listesi değil, doğrudan bağımlılık ve model indeksidir.

Durum sütunu, bileşen için kaydedilen ilişkiyi açıklar. Kullanımdan kaldırılan veya incelenen bir araç, geçerli çalışma zamanı kodu olarak sunulmadan kredili olarak kalır.

Bir deneyde adı geçen harici bir model de aynı şekilde kayıt sistemi değildir. Rolü, söz konusu deney için belgelenen yük ve işlemle sınırlıdır. Alıcı sağlanan baytları elinde tutsa bile, ihmal edilen derlem, kaynak, zamansal geçmiş ve yük oluşturma makineleri bu bağımlılığın dışında kalır.

| Araç veya model | Resmi kamu kaynağı | Kaydedilen ilişki | Kullanan |
|---|---|---|---|
| AMF ARI RoBERTa OpenVINO modeli | [kaynak](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | yukarı akış | amf_ari, argüman_ilişki_sınıflandırıcısı |
| BlingAteş | [kaynak](https://github.com/microsoft/BlingFire) | yukarı akış | mikroplanlayıcı, slop_analiz |
| Caddy | [kaynak](https://github.com/caddyserver/caddy) | yukarı akış | TL |
| Elçi | [kaynak](https://github.com/envoyproxy/envoy) | emekli öncül (çalışma zamanı değil) | yönlendirici |
| GerçekCG | [kaynak](https://github.com/derenlei/FactCG) | yukarı akış | semantic_observer |
| FastAPI | [kaynak](https://github.com/fastapi/fastapi) | yukarı akış | konuşma_splitter, görev_kontrol, yönlendirici |
| FastCoref | [kaynak](https://github.com/shon-otmazgin/fastcoref) | yukarı akış | söylem_önişleme |
| daha hızlı-damıtma-fısıltı-büyük-v3 | [kaynak](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | yukarı akış | konuşmalar |
| daha hızlı fısıltı | [kaynak](https://github.com/SYSTRAN/faster-whisper) | yukarı akış | konuşmalar |
| Grafikviz | [kaynak](https://gitlab.com/graphviz/graphviz) | yukarı akış | görev_kontrol |
| IsaNLP RST | [kaynak](https://github.com/tchewik/isanlp_rst) | yukarı akış | söylem_önişleme |
| diz çökmüş | [kaynak](https://github.com/arvkevi/kneed) | yukarı akış | çöküş_paketleri |
| LibreChat | [kaynak](https://github.com/danny-avila/LibreChat) | yukarı akış | sohbet |
| MiniKontrol | [kaynak](https://github.com/Liyan06/MiniCheck) | yukarı akış | semantic_observer |
| MongoDB | [kaynak](https://github.com/mongodb/mongo) | yukarı akış | mongodb |
| AğX | [kaynak](https://github.com/networkx/networkx) | yukarı akış | graph_projection |
| NLTK | [kaynak](https://github.com/nltk/nltk) | yukarı akış | eğim analizi |
| Node.js | [kaynak](https://github.com/nodejs/node) | yukarı akış | sohbet |
| Nomik Gömülü Metin | [kaynak](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | yukarı akış | ollama_embed |
| Ollama | [kaynak](https://github.com/ollama/ollama) | yukarı akış | olma, olma_embed |
| AçıkVINO | [kaynak](https://github.com/openvinotoolkit/openvino) | yukarı akış | amf_ari |
| pgvektör | [kaynak](https://github.com/pgvector/pgvector) | yukarı akış | postgres |
| PostgreSQL | [kaynak](https://github.com/postgres/postgres) | yukarı akış | postgres |
| psutil | [kaynak](https://github.com/giampaolo/psutil) | yukarı akış | donanım_telemetrisi |
| psikopat | [kaynak](https://github.com/psycopg/psycopg) | yukarı akış | görev_kontrol |
| Qwen3 | [kaynak](https://github.com/QwenLM/Qwen3) | yukarı akış | ollama, vllm |
| uzay | [kaynak](https://github.com/explosion/spaCy) | yukarı akış | mikro planlayıcı, eğim_analizi, yüzey_gerçekleştirici |
| Konuşmalar | [kaynak](https://github.com/speaches-ai/speaches) | yukarı akış | konuşmalar |
| stabil-difüzyon.cpp | [kaynak](https://github.com/leejet/stable-diffusion.cpp) | yukarı akış | görüntü |
| alt modlib | [kaynak](https://github.com/decile-team/submodlib) | yukarı akış | çöküş_paketleri |
| Transformatörler | [kaynak](https://github.com/huggingface/transformers) | yukarı akış | semantic_observer |
| Vikunja | [kaynak](https://github.com/go-vikunja/vikunja) | yukarı akış | vikunja |
| vLLM | [kaynak](https://github.com/vllm-project/vllm) | yukarı akış | vllm |
| vLLM Anlamsal Yönlendirici | [kaynak](https://github.com/vllm-project/semantic-router) | emekli öncül / denetlenen soy (çalışma zamanı değil) | yönlendirici |
| Z-Resim-Turbo | [kaynak](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | yukarı akış | görüntü |
| Z-Image-Turbo-Windows paketleme referansı | [kaynak](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | denetlenen paketleme referansı (çalışma zamanı kullanıcı arayüzü değil) | görüntü |

## Dağıtım sınırı

Genel belgeler, listelenen herhangi bir projenin kodunu veya model ağırlığını içermiyor. Gelecekteki bir yazılım dağıtımı, gerçekte dağıtılan baytlardan tam sürümler, revizyonlar, karmalar, geçişli bağımlılıklar, model koşulları ve lisans metinleri oluşturmalıdır. Proje bağlantısı, bir lisans görüşü değil, atıf ve izlenebilirliktir.
