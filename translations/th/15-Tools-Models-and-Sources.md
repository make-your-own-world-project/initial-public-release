> ไทย: การแปลต้นฉบับภาษาอังกฤษที่เชื่อถือได้โดยใช้เครื่องช่วย ยินดีต้อนรับการแก้ไขภาษาพื้นเมือง [ภาษาอังกฤษ](../../README.md) | [ทุกภาษา](../README.md)

# เครื่องมือ โมเดล และแหล่งที่มา

![เครื่องมือ โมเดล ชุดข้อมูล เวอร์ชัน และบทบาทที่เก็บรักษาไว้ในรีจีสทรีต้นทางที่ตรวจสอบได้](../../assets/tool-model-source-index.png)

เครื่องมือหรือโมเดลภายนอกหลักทุกรายการที่ได้รับการตั้งชื่อโดยบัญชีแยกประเภท Datacenter ที่ได้รับการดูแลจะเชื่อมโยงที่นี่ไปยังโครงการสาธารณะหรือหน้าการเผยแพร่อย่างเป็นทางการ นี่เป็นดัชนีการพึ่งพาโดยตรงและแบบจำลอง ไม่ใช่รายการวัสดุซอฟต์แวร์สกรรมกริยา

คอลัมน์สถานะอธิบายความสัมพันธ์ที่บันทึกไว้สำหรับส่วนประกอบ เครื่องมือที่เลิกใช้หรือตรวจสอบแล้วยังคงได้รับเครดิตโดยไม่ต้องแสดงเป็นโค้ดรันไทม์ปัจจุบัน

แบบจำลองภายนอกที่มีชื่อในการทดลองก็ไม่ใช่ระบบบันทึกเช่นกัน บทบาทของมันถูกจำกัดอยู่ที่น้ำหนักบรรทุกและการดำเนินการที่บันทึกไว้สำหรับการทดลองนั้น แม้ว่าผู้รับจะเก็บไบต์ที่ให้มาไว้ แต่คลังข้อมูลที่ละเว้น ที่มา ประวัติชั่วคราว และกลไกการสร้างเพย์โหลดจะยังคงอยู่นอกการอ้างอิงนั้น

| เครื่องมือหรือรุ่น | แหล่งที่มาสาธารณะอย่างเป็นทางการ | ความสัมพันธ์ที่บันทึกไว้ | ใช้โดย |
|---|---|---|---|
| AMF ARI RoBERTa รุ่น OpenVINO | [แหล่งที่มา](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | ต้นน้ำ | amf_ari, argument_relation_classifier |
| บลิงไฟร์ | [แหล่งที่มา](https://github.com/microsoft/BlingFire) | ต้นน้ำ | นักวางแผนไมโคร, slop_analysis |
| แคดดี้ | [แหล่งที่มา](https://github.com/caddyserver/caddy) | ต้นน้ำ | ไม่เป็นไร |
| ทูต | [แหล่งที่มา](https://github.com/envoyproxy/envoy) | บรรพบุรุษที่เลิกใช้แล้ว (ไม่ใช่รันไทม์) | เราเตอร์ |
| FactCG | [แหล่งที่มา](https://github.com/derenlei/FactCG) | ต้นน้ำ | semantic_observer |
| FastAPI | [แหล่งที่มา](https://github.com/fastapi/fastapi) | ต้นน้ำ | Conversation_splitter, mission_control, เราเตอร์ |
| FastCoref | [แหล่งที่มา](https://github.com/shon-otmazgin/fastcoref) | ต้นน้ำ | discourse_การประมวลผลล่วงหน้า |
| เร็วกว่า-กลั่น-กระซิบ-ขนาดใหญ่-v3 | [แหล่งที่มา](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | ต้นน้ำ | สุนทรพจน์ |
| เร็วขึ้นกระซิบ | [แหล่งที่มา](https://github.com/SYSTRAN/faster-whisper) | ต้นน้ำ | สุนทรพจน์ |
| กราฟวิซ | [แหล่งที่มา](https://gitlab.com/graphviz/graphviz) | ต้นน้ำ | ภารกิจ_การควบคุม |
| ไอเอสแอลพี อาร์เอสที | [แหล่งที่มา](https://github.com/tchewik/isanlp_rst) | ต้นน้ำ | discourse_การประมวลผลล่วงหน้า |
| คุกเข่า | [แหล่งที่มา](https://github.com/arvkevi/kneed) | ต้นน้ำ | ยุบ_แพ็กเก็ต |
| LibreChat | [แหล่งที่มา](https://github.com/danny-avila/LibreChat) | ต้นน้ำ | แชท |
| มินิเช็ค | [แหล่งที่มา](https://github.com/Liyan06/MiniCheck) | ต้นน้ำ | semantic_observer |
| MongoDB | [แหล่งที่มา](https://github.com/mongodb/mongo) | ต้นน้ำ | mongodb |
| เน็ตเวิร์กเอ็กซ์ | [แหล่งที่มา](https://github.com/networkx/networkx) | ต้นน้ำ | กราฟ_การฉายภาพ |
| เอ็นแอลทีเค | [แหล่งที่มา](https://github.com/nltk/nltk) | ต้นน้ำ | slop_analysis |
| โหนด js | [แหล่งที่มา](https://github.com/nodejs/node) | ต้นน้ำ | แชท |
| ข้อความฝัง Nomic | [แหล่งที่มา](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | ต้นน้ำ | ollama_embed |
| โอลามา | [แหล่งที่มา](https://github.com/ollama/ollama) | ต้นน้ำ | โอลามา, ollama_embed |
| OpenVINO | [แหล่งที่มา](https://github.com/openvinotoolkit/openvino) | ต้นน้ำ | amf_ari |
| pgvector | [แหล่งที่มา](https://github.com/pgvector/pgvector) | ต้นน้ำ | โพสต์เกรส |
| PostgreSQL | [แหล่งที่มา](https://github.com/postgres/postgres) | ต้นน้ำ | โพสต์เกรส |
| psutil | [แหล่งที่มา](https://github.com/giampaolo/psutil) | ต้นน้ำ | hardware_telemetry |
| ไซคอปจ์ | [แหล่งที่มา](https://github.com/psycopg/psycopg) | ต้นน้ำ | ภารกิจ_การควบคุม |
| คิวเวน3 | [แหล่งที่มา](https://github.com/QwenLM/Qwen3) | ต้นน้ำ | โอลามา, วีแอลเอ็ม |
| สปาซี | [แหล่งที่มา](https://github.com/explosion/spaCy) | ต้นน้ำ | ไมโครแพลนเนอร์, slop_analysis, surface_realizer |
| สุนทรพจน์ | [แหล่งที่มา](https://github.com/speaches-ai/speaches) | ต้นน้ำ | สุนทรพจน์ |
| เสถียร-diffusion.cpp | [แหล่งที่มา](https://github.com/leejet/stable-diffusion.cpp) | ต้นน้ำ | ภาพ |
| ซับมอดลิบ | [แหล่งที่มา](https://github.com/decile-team/submodlib) | ต้นน้ำ | ยุบ_แพ็กเก็ต |
| หม้อแปลงไฟฟ้า | [แหล่งที่มา](https://github.com/huggingface/transformers) | ต้นน้ำ | semantic_observer |
| วิคุนจา | [แหล่งที่มา](https://github.com/go-vikunja/vikunja) | ต้นน้ำ | วิคุนจา |
| วีแอลแอลเอ็ม | [แหล่งที่มา](https://github.com/vllm-project/vllm) | ต้นน้ำ | vllm |
| vLLM เราเตอร์ความหมาย | [แหล่งที่มา](https://github.com/vllm-project/semantic-router) | บรรพบุรุษที่เกษียณแล้ว / เชื้อสายที่ได้รับการตรวจสอบ (ไม่ใช่รันไทม์) | เราเตอร์ |
| Z-Image-Turbo | [แหล่งที่มา](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | ต้นน้ำ | ภาพ |
| ข้อมูลอ้างอิงบรรจุภัณฑ์ Z-Image-Turbo-Windows | [แหล่งที่มา](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | ตรวจสอบการอ้างอิงบรรจุภัณฑ์ (ไม่ใช่ UI รันไทม์) | ภาพ |

## ขอบเขตการกระจาย

เอกสารสาธารณะไม่มีรหัสของโครงการหรือน้ำหนักโมเดลที่ระบุไว้ การแจกจ่ายซอฟต์แวร์ในอนาคตจะต้องสร้างเวอร์ชัน การแก้ไข แฮช การขึ้นต่อกันแบบสกรรมกริยา ข้อกำหนดของโมเดล และข้อความสิทธิ์การใช้งานที่แน่นอนจากไบต์ที่เผยแพร่จริง ลิงก์โปรเจ็กต์คือการระบุแหล่งที่มาและความสามารถในการตรวจสอบย้อนกลับ ไม่ใช่ความเห็นเกี่ยวกับใบอนุญาต
