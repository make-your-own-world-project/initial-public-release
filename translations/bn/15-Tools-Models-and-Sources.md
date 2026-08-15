> বাংলা: অনুমোদিত ইংরেজি উৎসের মেশিন-সহায়তা অনুবাদ। স্থানীয়-ভাষা সংশোধন স্বাগত জানাই. [ইংরেজি](../../README.md) | [সব ভাষা](../README.md)

# সরঞ্জাম, মডেল, এবং উত্স

![টুল, মডেল, ডেটাসেট, সংস্করণ এবং ভূমিকা একটি নিরীক্ষণযোগ্য উৎস রেজিস্ট্রিতে সংরক্ষিত](../../assets/tool-model-source-index.png)

রক্ষণাবেক্ষণ করা ডেটাসেন্টার লেজার দ্বারা নাম দেওয়া প্রতিটি প্রধান বাহ্যিক সরঞ্জাম বা মডেল এখানে তার অফিসিয়াল পাবলিক প্রকল্প বা বিতরণ পৃষ্ঠার সাথে লিঙ্ক করা হয়েছে। এটি একটি প্রত্যক্ষ-নির্ভরতা এবং মডেল সূচক, উপকরণের একটি ট্রানজিটিভ সফ্টওয়্যার বিল নয়।

স্থিতি কলাম উপাদানটির জন্য রেকর্ড করা সম্পর্ক বর্ণনা করে। একটি অবসরপ্রাপ্ত বা পরিদর্শন করা টুল বর্তমান রানটাইম কোড হিসাবে উপস্থাপিত না করেই জমা থাকে।

একটি পরীক্ষায় নাম দেওয়া একটি বাহ্যিক মডেল একইভাবে রেকর্ডের সিস্টেম নয়। এর ভূমিকা সেই পরীক্ষার জন্য নথিভুক্ত পেলোড এবং অপারেশনের মধ্যে সীমাবদ্ধ। এমনকি যদি প্রাপক সরবরাহকৃত বাইটগুলি ধরে রাখে, বাদ দেওয়া কর্পাস, উত্স, অস্থায়ী ইতিহাস এবং পেলোড-নির্মাণ যন্ত্রপাতি সেই নির্ভরতার বাইরে থাকে।

| টুল বা মডেল | অফিসিয়াল পাবলিক সোর্স | রেকর্ড করা সম্পর্ক | দ্বারা ব্যবহৃত |
|---|---|---|---|
| AMF ARI Roberta OpenVINO মডেল | [উৎস](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | আপস্ট্রিম | amf_ari, argument_relation_classifier |
| ব্লিংফায়ার | [উৎস](https://github.com/microsoft/BlingFire) | আপস্ট্রিম | microplanner, slop_analysis |
| ক্যাডি | [উৎস](https://github.com/caddyserver/caddy) | আপস্ট্রিম | tls |
| দূত | [উৎস](https://github.com/envoyproxy/envoy) | অবসরপ্রাপ্ত পূর্বসূরি (রানটাইম নয়) | রাউটার |
| ফ্যাক্টসিজি | [উৎস](https://github.com/derenlei/FactCG) | আপস্ট্রিম | শব্দার্থিক_পর্যবেক্ষক |
| ফাস্টএপিআই | [উৎস](https://github.com/fastapi/fastapi) | আপস্ট্রিম | কথোপকথন_স্প্লিটার, মিশন_কন্ট্রোল, রাউটার |
| ফাস্টকোরেফ | [উৎস](https://github.com/shon-otmazgin/fastcoref) | আপস্ট্রিম | discourse_preprocessing |
| দ্রুত-পাতিল-হুইস্পার-বড়-v3 | [উৎস](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | আপস্ট্রিম | বক্তৃতা |
| দ্রুত- ফিসফিস | [উৎস](https://github.com/SYSTRAN/faster-whisper) | আপস্ট্রিম | বক্তৃতা |
| গ্রাফভিজ | [উৎস](https://gitlab.com/graphviz/graphviz) | আপস্ট্রিম | মিশন_নিয়ন্ত্রণ |
| IsaNLP RST | [উৎস](https://github.com/tchewik/isanlp_rst) | আপস্ট্রিম | discourse_preprocessing |
| হাঁটু | [উৎস](https://github.com/arvkevi/kneed) | আপস্ট্রিম | collapse_packets |
| LibreChat | [উৎস](https://github.com/danny-avila/LibreChat) | আপস্ট্রিম | চ্যাট |
| মিনিচেক | [উৎস](https://github.com/Liyan06/MiniCheck) | আপস্ট্রিম | শব্দার্থিক_পর্যবেক্ষক |
| মঙ্গোডিবি | [উৎস](https://github.com/mongodb/mongo) | আপস্ট্রিম | mongodb |
| নেটওয়ার্কএক্স | [উৎস](https://github.com/networkx/networkx) | আপস্ট্রিম | গ্রাফ_প্রজেকশন |
| NLTK | [উৎস](https://github.com/nltk/nltk) | আপস্ট্রিম | slop_analysis |
| Node.js | [উৎস](https://github.com/nodejs/node) | আপস্ট্রিম | চ্যাট |
| নামিক এম্বেড টেক্সট | [উৎস](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | আপস্ট্রিম | ollama_embed |
| ওল্লামা | [উৎস](https://github.com/ollama/ollama) | আপস্ট্রিম | ollama, ollama_embed |
| OpenVINO | [উৎস](https://github.com/openvinotoolkit/openvino) | আপস্ট্রিম | amf_ari |
| pgvector | [উৎস](https://github.com/pgvector/pgvector) | আপস্ট্রিম | পোস্টগ্রেস |
| পোস্টগ্রেএসকিউএল | [উৎস](https://github.com/postgres/postgres) | আপস্ট্রিম | পোস্টগ্রেস |
| psutil | [উৎস](https://github.com/giampaolo/psutil) | আপস্ট্রিম | হার্ডওয়্যার_টেলিমেট্রি |
| সাইকোপজি | [উৎস](https://github.com/psycopg/psycopg) | আপস্ট্রিম | মিশন_নিয়ন্ত্রণ |
| Qwen3 | [উৎস](https://github.com/QwenLM/Qwen3) | আপস্ট্রিম | ওল্লামা, ভিএলএলএম |
| spaCy | [উৎস](https://github.com/explosion/spaCy) | আপস্ট্রিম | মাইক্রোপ্ল্যানার, স্লপ_অ্যানালাইসিস, সারফেস_রিয়ালাইজার |
| বক্তৃতা | [উৎস](https://github.com/speaches-ai/speaches) | আপস্ট্রিম | বক্তৃতা |
| stable-diffusion.cpp | [উৎস](https://github.com/leejet/stable-diffusion.cpp) | আপস্ট্রিম | ইমেজ |
| submodlib | [উৎস](https://github.com/decile-team/submodlib) | আপস্ট্রিম | collapse_packets |
| ট্রান্সফরমার | [উৎস](https://github.com/huggingface/transformers) | আপস্ট্রিম | শব্দার্থিক_পর্যবেক্ষক |
| ভিকুঞ্জ | [উৎস](https://github.com/go-vikunja/vikunja) | আপস্ট্রিম | ভিকুঞ্জ |
| ভিএলএলএম | [উৎস](https://github.com/vllm-project/vllm) | আপস্ট্রিম | ভিএলএলএম |
| vLLM শব্দার্থিক রাউটার | [উৎস](https://github.com/vllm-project/semantic-router) | অবসরপ্রাপ্ত পূর্বসূরি / পরিদর্শন বংশ (রানটাইম নয়) | রাউটার |
| জেড-ইমেজ-টার্বো | [উৎস](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | আপস্ট্রিম | ইমেজ |
| জেড-ইমেজ-টার্বো-উইন্ডোজ প্যাকেজিং রেফারেন্স | [উৎস](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | পরিদর্শন করা প্যাকেজিং রেফারেন্স (রানটাইম UI নয়) | ইমেজ |

## বন্টন সীমানা

পাবলিক ডকুমেন্টেশনে কোনো তালিকাভুক্ত প্রকল্পের কোড বা মডেল ওজন নেই। একটি ভবিষ্যত সফ্টওয়্যার বিতরণকে অবশ্যই বিতরণ করা বাইটগুলি থেকে সঠিক সংস্করণ, সংশোধন, হ্যাশ, ট্রানজিটিভ নির্ভরতা, মডেল শর্তাবলী এবং লাইসেন্স পাঠ্য তৈরি করতে হবে। একটি প্রকল্পের লিঙ্ক হল অ্যাট্রিবিউশন এবং ট্রেসেবিলিটি, লাইসেন্স মতামত নয়।
