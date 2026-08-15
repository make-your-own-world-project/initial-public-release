> فارسی: ترجمه ماشینی منبع معتبر انگلیسی. اصلاحات به زبان مادری پذیرفته می شود. [انگلیسی](../../README.md) | [همه زبان ها](../README.md)

# ابزارها، مدل ها و منابع

![ابزارها، مدل‌ها، مجموعه داده‌ها، نسخه‌ها و نقش‌ها در یک رجیستری منبع قابل بازرسی نگهداری می‌شوند](../../assets/tool-model-source-index.png)

هر ابزار خارجی یا مدل اصلی که توسط دفتر کل Datacenter نگهداری شده نامگذاری شده است، در اینجا به پروژه عمومی یا صفحه توزیع رسمی خود پیوند داده شده است. این یک شاخص وابستگی مستقیم و مدل است، نه یک صورتحساب مواد نرم افزاری گذرا.

ستون وضعیت رابطه ثبت شده برای جزء را توصیف می کند. یک ابزار بازنشسته یا بازرسی شده بدون ارائه به عنوان کد زمان اجرا فعلی اعتبار باقی می ماند.

یک مدل خارجی که در یک آزمایش نامگذاری شده است نیز سیستم ثبت نیست. نقش آن محدود به بار و عملیات مستند شده برای آن آزمایش است. حتی اگر گیرنده بایت‌های ارائه‌شده را حفظ کند، مجموعه حذف‌شده، منشأ، تاریخچه زمانی و ماشین‌آلات ساخت محموله خارج از آن وابستگی باقی می‌مانند.

| ابزار یا مدل | منبع عمومی رسمی | رابطه ثبت شده | استفاده شده توسط |
|---|---|---|---|
| مدل AMF ARI RoBERTa OpenVINO | [منبع](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | بالادست | amf_ari، argument_relation_classifier |
| BlingFire | [منبع](https://github.com/microsoft/BlingFire) | بالادست | microplanner, slop_analysis |
| کدی | [منبع](https://github.com/caddyserver/caddy) | بالادست | tls |
| فرستاده | [منبع](https://github.com/envoyproxy/envoy) | سلف بازنشسته (نه زمان اجرا) | روتر |
| FactCG | [منبع](https://github.com/derenlei/FactCG) | بالادست | ناظر_معنایی |
| FastAPI | [منبع](https://github.com/fastapi/fastapi) | بالادست | گفتگو_شکاف، مأموریت_کنترل، روتر |
| FastCoref | [منبع](https://github.com/shon-otmazgin/fastcoref) | بالادست | گفتمان_پیش پردازش |
| faster-distil-whisper-large-v3 | [منبع](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | بالادست | سخنرانی ها |
| سریعتر زمزمه کن | [منبع](https://github.com/SYSTRAN/faster-whisper) | بالادست | سخنرانی ها |
| گرافویز | [منبع](https://gitlab.com/graphviz/graphviz) | بالادست | ماموریت_کنترل |
| IsaNLP RST | [منبع](https://github.com/tchewik/isanlp_rst) | بالادست | گفتمان_پیش پردازش |
| زانو زد | [منبع](https://github.com/arvkevi/kneed) | بالادست | collapse_packets |
| LibreChat | [منبع](https://github.com/danny-avila/LibreChat) | بالادست | چت کردن |
| مینی چک | [منبع](https://github.com/Liyan06/MiniCheck) | بالادست | ناظر_معنایی |
| MongoDB | [منبع](https://github.com/mongodb/mongo) | بالادست | mongodb |
| NetworkX | [منبع](https://github.com/networkx/networkx) | بالادست | graph_projection |
| NLTK | [منبع](https://github.com/nltk/nltk) | بالادست | slop_analysis |
| Node.js | [منبع](https://github.com/nodejs/node) | بالادست | چت کردن |
| متن جاسازی نامی | [منبع](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | بالادست | ollama_embed |
| اولاما | [منبع](https://github.com/ollama/ollama) | بالادست | olama, olama_embed |
| OpenVINO | [منبع](https://github.com/openvinotoolkit/openvino) | بالادست | amf_ari |
| pgvector | [منبع](https://github.com/pgvector/pgvector) | بالادست | postgres |
| PostgreSQL | [منبع](https://github.com/postgres/postgres) | بالادست | postgres |
| پسوتیل | [منبع](https://github.com/giampaolo/psutil) | بالادست | سخت افزار_تلمتری |
| Psycopg | [منبع](https://github.com/psycopg/psycopg) | بالادست | ماموریت_کنترل |
| Qwen3 | [منبع](https://github.com/QwenLM/Qwen3) | بالادست | اولاما، vllm |
| فضایی | [منبع](https://github.com/explosion/spaCy) | بالادست | microplanner، slop_analysis، surface_realizer |
| سخنرانی ها | [منبع](https://github.com/speaches-ai/speaches) | بالادست | سخنرانی ها |
| stable-diffusion.cpp | [منبع](https://github.com/leejet/stable-diffusion.cpp) | بالادست | تصویر |
| submodlib | [منبع](https://github.com/decile-team/submodlib) | بالادست | collapse_packets |
| ترانسفورماتورها | [منبع](https://github.com/huggingface/transformers) | بالادست | ناظر_معنایی |
| ویکونجا | [منبع](https://github.com/go-vikunja/vikunja) | بالادست | ویکونجا |
| vLLM | [منبع](https://github.com/vllm-project/vllm) | بالادست | vllm |
| روتر معنایی vLLM | [منبع](https://github.com/vllm-project/semantic-router) | سلف بازنشسته / نسب بازرسی شده (نه زمان اجرا) | روتر |
| Z-Image-Turbo | [منبع](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | بالادست | تصویر |
| مرجع بسته بندی Z-Image-Turbo-Windows | [منبع](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | مرجع بسته بندی بازرسی شده (نه رابط کاربری زمان اجرا) | تصویر |

## مرز توزیع

اسناد عمومی شامل هیچ کد پروژه یا وزن مدل لیست شده نیست. یک توزیع نرم‌افزاری آینده باید نسخه‌های دقیق، بازبینی‌ها، هش‌ها، وابستگی‌های گذرا، شرایط مدل و متن‌های مجوز را از بایت‌های توزیع شده واقعی ایجاد کند. پیوند پروژه، انتساب و قابلیت ردیابی است، نه نظر مجوز.
