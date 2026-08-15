> Bahasa Indonesia: Terjemahan dengan bantuan mesin dari sumber bahasa Inggris resmi. Koreksi dalam bahasa asli dipersilakan. [Bahasa inggris](../../README.md) | [Semua bahasa](../README.md)

# Alat, Model, dan Sumber

![Alat, model, himpunan data, versi, dan peran disimpan dalam registri sumber yang dapat diaudit](../../assets/tool-model-source-index.png)

Setiap alat atau model eksternal utama yang diberi nama oleh buku besar Pusat Data yang dikelola ditautkan di sini ke proyek publik resmi atau halaman distribusinya. Ini adalah ketergantungan langsung dan indeks model, bukan bill of material perangkat lunak transitif.

Kolom status menjelaskan hubungan yang direkam untuk komponen. Alat yang dihentikan atau diperiksa tetap dikreditkan tanpa disajikan sebagai kode runtime saat ini.

Model eksternal yang disebutkan dalam eksperimen juga bukan sistem pencatatan. Perannya terbatas pada muatan dan operasi yang didokumentasikan untuk eksperimen tersebut. Sekalipun penerima tetap menyimpan byte yang disediakan, korpus, asal, riwayat temporal, dan mesin konstruksi muatan yang dihilangkan tetap berada di luar ketergantungan tersebut.

| Alat atau model | Sumber publik resmi | Hubungan yang direkam | Digunakan oleh |
|---|---|---|---|
| Model AMF ARI RoBERTa OpenVINO | [sumber](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | hulu | amf_ari, argument_relation_classifier |
| Bling Api | [sumber](https://github.com/microsoft/BlingFire) | hulu | perencana mikro, slop_analisis |
| Caddy | [sumber](https://github.com/caddyserver/caddy) | hulu | tl |
| Utusan | [sumber](https://github.com/envoyproxy/envoy) | pendahulunya yang sudah pensiun (bukan runtime) | router |
| FaktaCG | [sumber](https://github.com/derenlei/FactCG) | hulu | semantik_pengamat |
| API Cepat | [sumber](https://github.com/fastapi/fastapi) | hulu | percakapan_splitter, kontrol_misi, router |
| FastCoref | [sumber](https://github.com/shon-otmazgin/fastcoref) | hulu | wacana_pemrosesan awal |
| lebih cepat-distilasi-bisikan-besar-v3 | [sumber](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | hulu | pidato |
| bisikan lebih cepat | [sumber](https://github.com/SYSTRAN/faster-whisper) | hulu | pidato |
| Grafikviz | [sumber](https://gitlab.com/graphviz/graphviz) | hulu | misi_kontrol |
| IsaNLP Pertama | [sumber](https://github.com/tchewik/isanlp_rst) | hulu | wacana_pemrosesan awal |
| berlutut | [sumber](https://github.com/arvkevi/kneed) | hulu | runtuh_paket |
| Obrolan Libre | [sumber](https://github.com/danny-avila/LibreChat) | hulu | mengobrol |
| Periksa Mini | [sumber](https://github.com/Liyan06/MiniCheck) | hulu | semantik_pengamat |
| MongoDB | [sumber](https://github.com/mongodb/mongo) | hulu | mongodb |
| JaringanX | [sumber](https://github.com/networkx/networkx) | hulu | grafik_proyeksi |
| NLTK | [sumber](https://github.com/nltk/nltk) | hulu | analisis_slop |
| Node.js | [sumber](https://github.com/nodejs/node) | hulu | mengobrol |
| Teks Sematan Nomik | [sumber](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | hulu | ollama_embed |
| Ollama | [sumber](https://github.com/ollama/ollama) | hulu | ollama, ollama_embed |
| BukaVINO | [sumber](https://github.com/openvinotoolkit/openvino) | hulu | amf_ari |
| vektor pg | [sumber](https://github.com/pgvector/pgvector) | hulu | postgres |
| PostgreSQL | [sumber](https://github.com/postgres/postgres) | hulu | postgres |
| psutil | [sumber](https://github.com/giampaolo/psutil) | hulu | perangkat keras_telemetri |
| Psikopg | [sumber](https://github.com/psycopg/psycopg) | hulu | misi_kontrol |
| Qwen3 | [sumber](https://github.com/QwenLM/Qwen3) | hulu | oke, vllm |
| spaCy | [sumber](https://github.com/explosion/spaCy) | hulu | mikroplanner, slop_analisis, permukaan_realizer |
| Pidato | [sumber](https://github.com/speaches-ai/speaches) | hulu | pidato |
| stable-diffusion.cpp | [sumber](https://github.com/leejet/stable-diffusion.cpp) | hulu | gambar |
| submodlib | [sumber](https://github.com/decile-team/submodlib) | hulu | runtuh_paket |
| transformator | [sumber](https://github.com/huggingface/transformers) | hulu | semantik_pengamat |
| Vikunja | [sumber](https://github.com/go-vikunja/vikunja) | hulu | vikunja |
| vLLM | [sumber](https://github.com/vllm-project/vllm) | hulu | vllm |
| vLLM Router Semantik | [sumber](https://github.com/vllm-project/semantic-router) | pensiunan pendahulunya / garis keturunan yang diperiksa (bukan runtime) | router |
| Z-Gambar-Turbo | [sumber](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | hulu | gambar |
| Referensi pengemasan Z-Image-Turbo-Windows | [sumber](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | referensi kemasan yang diperiksa (bukan UI runtime) | gambar |

## Batas distribusi

Dokumentasi publik tidak berisi kode proyek atau bobot model apa pun yang terdaftar. Distribusi perangkat lunak di masa depan harus menghasilkan versi, revisi, hash, ketergantungan transitif, persyaratan model, dan teks lisensi yang tepat dari byte yang sebenarnya didistribusikan. Tautan proyek adalah atribusi dan ketertelusuran, bukan opini lisensi.
