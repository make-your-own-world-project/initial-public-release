> 简体中文: 权威英文源的机器辅助翻译。欢迎母语更正。 [英语](../../README.md) | [所有语言](../README.md)

# 工具、模型和来源

![保存在可审计源注册表中的工具、模型、数据集、版本和角色](../../assets/tool-model-source-index.png)

由维护的数据中心分类账命名的每个主要外部工具或模型都在此处链接到其官方公共项目或分发页面。这是直接依赖项和模型索引，而不是可传递的软件物料清单。

状态列描述了为组件记录的关系。已退役或已检查的工具仍保留在贷方中，而不显示为当前运行时代码。

实验中命名的外部模型同样不是记录系统。它的作用仅限于该实验记录的有效负载和操作。即使接收者保留了所提供的字节，省略的语料库、出处、时间历史和有效负载构造机制仍然不属于该依赖性。

| 工具或模型 | 官方公开来源 | 记录关系 | 使用者 |
|---|---|---|---|
| AMF ARI RoBERTa OpenVINO 模型 | [来源](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | 上游 | amf_ari，参数关系分类器 |
| 布林火 | [来源](https://github.com/microsoft/BlingFire) | 上游 | 微观规划师，slop_analysis |
| 球童 | [来源](https://github.com/caddyserver/caddy) | 上游 | tls |
| 使者 | [来源](https://github.com/envoyproxy/envoy) | 退休的前任（不是运行时） | 路由器 |
| 事实CG | [来源](https://github.com/derenlei/FactCG) | 上游 | 语义观察者 |
| 快速API | [来源](https://github.com/fastapi/fastapi) | 上游 | 对话分配器、任务控制、路由器 |
| 快速核心 | [来源](https://github.com/shon-otmazgin/fastcoref) | 上游 | 话语预处理 |
| 更快-蒸馏-耳语-大-v3 | [来源](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | 上游 | 演讲 |
| 更快的耳语 | [来源](https://github.com/SYSTRAN/faster-whisper) | 上游 | 演讲 |
| 图形可视化 | [来源](https://gitlab.com/graphviz/graphviz) | 上游 | 任务控制中心 |
| IsaNLP RST | [来源](https://github.com/tchewik/isanlp_rst) | 上游 | 话语预处理 |
| 跪下 | [来源](https://github.com/arvkevi/kneed) | 上游 | 折叠数据包 |
| 自由聊天 | [来源](https://github.com/danny-avila/LibreChat) | 上游 | 聊天 |
| 迷你检查 | [来源](https://github.com/Liyan06/MiniCheck) | 上游 | 语义观察者 |
| MongoDB | [来源](https://github.com/mongodb/mongo) | 上游 | 蒙古数据库 |
| 网络X | [来源](https://github.com/networkx/networkx) | 上游 | 图投影 |
| NLTK | [来源](https://github.com/nltk/nltk) | 上游 | 坡度分析 |
| Node.js | [来源](https://github.com/nodejs/node) | 上游 | 聊天 |
| 规则嵌入文本 | [来源](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | 上游 | llama_嵌入 |
| 奥拉玛 | [来源](https://github.com/ollama/ollama) | 上游 | llama, llama_embed |
| 开放VINO | [来源](https://github.com/openvinotoolkit/openvino) | 上游 | amf_ari |
| PG向量 | [来源](https://github.com/pgvector/pgvector) | 上游 | postgres |
| PostgreSQL | [来源](https://github.com/postgres/postgres) | 上游 | postgres |
| 普苏蒂尔 | [来源](https://github.com/giampaolo/psutil) | 上游 | 硬件遥测 |
| 精神病学 | [来源](https://github.com/psycopg/psycopg) | 上游 | 任务控制中心 |
| Q文3 | [来源](https://github.com/QwenLM/Qwen3) | 上游 | 乌拉马 |
| 斯帕西 | [来源](https://github.com/explosion/spaCy) | 上游 | 微规划器、slop_analysis、surface_realizer |
| 演讲 | [来源](https://github.com/speaches-ai/speaches) | 上游 | 演讲 |
| 稳定扩散.cpp | [来源](https://github.com/leejet/stable-diffusion.cpp) | 上游 | 图像 |
| 子模块库 | [来源](https://github.com/decile-team/submodlib) | 上游 | 折叠数据包 |
| 变形金刚 | [来源](https://github.com/huggingface/transformers) | 上游 | 语义观察者 |
| 维昆贾 | [来源](https://github.com/go-vikunja/vikunja) | 上游 | 维昆贾 |
| 法学硕士 | [来源](https://github.com/vllm-project/vllm) | 上游 | 弗洛姆 |
| vLLM 语义路由器 | [来源](https://github.com/vllm-project/semantic-router) | 退休前任/检查血统（不是运行时） | 路由器 |
| Z-图像-Turbo | [来源](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | 上游 | 图像 |
| Z-Image-Turbo-Windows 打包参考 | [来源](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | 检查包装参考（不是运行时 UI） | 图像 |

## 分布边界

公共文档不包含任何列出的项目的代码或模型权重。未来的软件分发必须根据实际分发的字节生成准确的版本、修订版、哈希值、传递依赖项、模型术语和许可证文本。项目链接是归属和可追溯性，而不是许可意见。
