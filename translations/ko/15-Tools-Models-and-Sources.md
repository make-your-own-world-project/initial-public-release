> 한국어: 권위 있는 영어 소스의 기계 지원 번역입니다. 모국어 수정을 환영합니다. [영어](../../README.md) | [모든 언어](../README.md)

# 도구, 모델 및 소스

![감사 가능한 소스 레지스트리에 보존된 도구, 모델, 데이터 세트, 버전 및 역할](../../assets/tool-model-source-index.png)

유지 관리되는 Datacenter 원장에 의해 명명된 모든 주요 외부 도구 또는 모델은 여기에서 공식 공개 프로젝트 또는 배포 페이지에 연결됩니다. 이는 전이적 소프트웨어 BOM이 아닌 직접 종속성 및 모델 인덱스입니다.

상태 열은 구성 요소에 대해 기록된 관계를 설명합니다. 폐기되거나 검사된 도구는 현재 런타임 코드로 표시되지 않고 크레딧을 유지합니다.

실험에서 명명된 외부 모델도 마찬가지로 기록 시스템이 아닙니다. 그 역할은 해당 실험에 대해 문서화된 페이로드 및 작업으로 제한됩니다. 수신자가 제공된 바이트를 유지하더라도 생략된 말뭉치, 출처, 임시 기록 및 페이로드 구성 기계는 해당 종속성 외부에 남아 있습니다.

| 도구 또는 모델 | 공식 공개 소스 | 기록된 관계 | 사용처 |
|---|---|---|---|
| AMF ARI RoBERTa OpenVINO 모델 | [원천](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | 상류 | amf_ari, 인수_관계_분류자 |
| 블링파이어 | [원천](https://github.com/microsoft/BlingFire) | 상류 | 마이크로플래너, slop_analytic |
| 캐디 | [원천](https://github.com/caddyserver/caddy) | 상류 | tls |
| 사절 | [원천](https://github.com/envoyproxy/envoy) | 폐기된 선행 작업(런타임 아님) | 라우터 |
| FactCG | [원천](https://github.com/derenlei/FactCG) | 상류 | semantic_observer |
| FastAPI | [원천](https://github.com/fastapi/fastapi) | 상류 | 대화 분배기, 임무 제어, 라우터 |
| FastCoref | [원천](https://github.com/shon-otmazgin/fastcoref) | 상류 | 담론_전처리 |
| 빠른 증류 속삭임 대형 v3 | [원천](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | 상류 | 연설 |
| 더 빠른 속삭임 | [원천](https://github.com/SYSTRAN/faster-whisper) | 상류 | 연설 |
| 그래프비즈 | [원천](https://gitlab.com/graphviz/graphviz) | 상류 | 임무_통제 |
| IsaNLP RST | [원천](https://github.com/tchewik/isanlp_rst) | 상류 | 담론_전처리 |
| 무릎을 꿇은 | [원천](https://github.com/arvkevi/kneed) | 상류 | 붕괴_패킷 |
| 리브레챗 | [원천](https://github.com/danny-avila/LibreChat) | 상류 | 채팅 |
| 미니체크 | [원천](https://github.com/Liyan06/MiniCheck) | 상류 | semantic_observer |
| 몽고DB | [원천](https://github.com/mongodb/mongo) | 상류 | 몽고디비 |
| 네트워크X | [원천](https://github.com/networkx/networkx) | 상류 | 그래프_투영 |
| NLTK | [원천](https://github.com/nltk/nltk) | 상류 | 슬롭_분석 |
| Node.js | [원천](https://github.com/nodejs/node) | 상류 | 채팅 |
| 노믹 삽입 텍스트 | [원천](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | 상류 | ollama_embed |
| 올라마 | [원천](https://github.com/ollama/ollama) | 상류 | 올라마, ollama_embed |
| 오픈비노 | [원천](https://github.com/openvinotoolkit/openvino) | 상류 | amf_ari |
| pg벡터 | [원천](https://github.com/pgvector/pgvector) | 상류 | 포스트그레스 |
| 포스트그레SQL | [원천](https://github.com/postgres/postgres) | 상류 | 포스트그레스 |
| psutil | [원천](https://github.com/giampaolo/psutil) | 상류 | 하드웨어_원격 측정 |
| 사이코패스 | [원천](https://github.com/psycopg/psycopg) | 상류 | 임무_통제 |
| Qwen3 | [원천](https://github.com/QwenLM/Qwen3) | 상류 | 올라마, vllm |
| 스파시 | [원천](https://github.com/explosion/spaCy) | 상류 | 마이크로플래너, slop_analytic, 표면_현실화기 |
| 연설 | [원천](https://github.com/speaches-ai/speaches) | 상류 | 연설 |
| 안정-확산.cpp | [원천](https://github.com/leejet/stable-diffusion.cpp) | 상류 | 영상 |
| 하위 모드립 | [원천](https://github.com/decile-team/submodlib) | 상류 | 붕괴_패킷 |
| 트랜스포머 | [원천](https://github.com/huggingface/transformers) | 상류 | semantic_observer |
| 비쿠냐 | [원천](https://github.com/go-vikunja/vikunja) | 상류 | 비쿤자 |
| vLLM | [원천](https://github.com/vllm-project/vllm) | 상류 | vllm |
| vLLM 시맨틱 라우터 | [원천](https://github.com/vllm-project/semantic-router) | 만료된 전임자/검사된 계보(런타임 아님) | 라우터 |
| Z-이미지-터보 | [원천](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | 상류 | 영상 |
| Z-Image-Turbo-Windows 패키징 참조 | [원천](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | 검사된 패키징 참조(런타임 UI 아님) | 영상 |

## 유통경계

공개 문서에는 나열된 프로젝트의 코드 또는 모델 가중치가 포함되어 있지 않습니다. 향후 소프트웨어 배포에서는 실제로 배포된 바이트에서 정확한 버전, 개정, 해시, 전이적 종속성, 모델 조건 및 라이센스 텍스트를 생성해야 합니다. 프로젝트 링크는 라이선스 의견이 아니라 귀속 및 추적 가능성입니다.
