> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../README.md) | [Tất cả ngôn ngữ](../README.md)

# Công cụ, mô hình và nguồn

![Các công cụ, mô hình, bộ dữ liệu, phiên bản và vai trò được lưu giữ trong sổ đăng ký nguồn có thể kiểm tra](../../assets/tool-model-source-index.png)

Mọi công cụ hoặc mô hình chính bên ngoài được đặt tên theo sổ cái Trung tâm dữ liệu được duy trì đều được liên kết ở đây với trang phân phối hoặc dự án công cộng chính thức của nó. Đây là chỉ mục mô hình và phụ thuộc trực tiếp, không phải là hóa đơn vật liệu phần mềm bắc cầu.

Cột trạng thái mô tả mối quan hệ được ghi lại cho thành phần. Công cụ đã ngừng hoạt động hoặc đã được kiểm tra vẫn được ghi có mà không được trình bày dưới dạng mã thời gian chạy hiện tại.

Một mô hình bên ngoài được đặt tên trong một thử nghiệm cũng không phải là hệ thống hồ sơ. Vai trò của nó được giới hạn ở tải trọng và hoạt động được ghi lại cho thử nghiệm đó. Ngay cả khi người nhận giữ lại các byte đã cung cấp, kho dữ liệu bị bỏ qua, nguồn gốc, lịch sử thời gian và máy móc xây dựng tải trọng vẫn nằm ngoài sự phụ thuộc đó.

| Công cụ hoặc mô hình | Nguồn công cộng chính thức | Mối quan hệ được ghi lại | Được sử dụng bởi |
|---|---|---|---|
| Mô hình AMF ARI RoBERTa OpenVINO | [nguồn](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8) | ngược dòng | amf_ari, đối số_relation_classifier |
| BlingFire | [nguồn](https://github.com/microsoft/BlingFire) | ngược dòng | người lập kế hoạch vi mô, slop_analysis |
| caddie | [nguồn](https://github.com/caddyserver/caddy) | ngược dòng | tls |
| sứ giả | [nguồn](https://github.com/envoyproxy/envoy) | người tiền nhiệm đã nghỉ hưu (không phải thời gian chạy) | bộ định tuyến |
| Sự thậtCG | [nguồn](https://github.com/derenlei/FactCG) | ngược dòng | ngữ nghĩa_observer |
| API nhanh | [nguồn](https://github.com/fastapi/fastapi) | ngược dòng | cuộc trò chuyện_splitter, nhiệm vụ_control, bộ định tuyến |
| FastCoref | [nguồn](https://github.com/shon-otmazgin/fastcoref) | ngược dòng | diễn ngôn_tiền xử lý |
| nhanh hơn-chưng cất-thì thầm-lớn-v3 | [nguồn](https://huggingface.co/Systran/faster-distil-whisper-large-v3) | ngược dòng | bài giảng |
| thì thầm nhanh hơn | [nguồn](https://github.com/SYSTRAN/faster-whisper) | ngược dòng | bài giảng |
| Đồ họa | [nguồn](https://gitlab.com/graphviz/graphviz) | ngược dòng | nhiệm vụ_điều khiển |
| IsaNLP RST | [nguồn](https://github.com/tchewik/isanlp_rst) | ngược dòng | diễn ngôn_tiền xử lý |
| quỳ gối | [nguồn](https://github.com/arvkevi/kneed) | ngược dòng | thu gọn_gói |
| LibreChat | [nguồn](https://github.com/danny-avila/LibreChat) | ngược dòng | trò chuyện |
| Kiểm tra nhỏ | [nguồn](https://github.com/Liyan06/MiniCheck) | ngược dòng | ngữ nghĩa_observer |
| MongoDB | [nguồn](https://github.com/mongodb/mongo) | ngược dòng | mongodb |
| MạngX | [nguồn](https://github.com/networkx/networkx) | ngược dòng | đồ thị_chiếu |
| NLTK | [nguồn](https://github.com/nltk/nltk) | ngược dòng | phân tích dốc |
| Node.js | [nguồn](https://github.com/nodejs/node) | ngược dòng | trò chuyện |
| Văn bản nhúng danh nghĩa | [nguồn](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) | ngược dòng | ollama_embed |
| Ollama | [nguồn](https://github.com/ollama/ollama) | ngược dòng | ollama, ollama_embed |
| OpenVINO | [nguồn](https://github.com/openvinotoolkit/openvino) | ngược dòng | amf_ari |
| pgvector | [nguồn](https://github.com/pgvector/pgvector) | ngược dòng | postgres |
| PostgreSQL | [nguồn](https://github.com/postgres/postgres) | ngược dòng | postgres |
| psutil | [nguồn](https://github.com/giampaolo/psutil) | ngược dòng | phần cứng_từ xa |
| Tâm lý học | [nguồn](https://github.com/psycopg/psycopg) | ngược dòng | nhiệm vụ_điều khiển |
| Qwen3 | [nguồn](https://github.com/QwenLM/Qwen3) | ngược dòng | olma, vllm |
| spaCy | [nguồn](https://github.com/explosion/spaCy) | ngược dòng | công cụ lập kế hoạch vi mô, slop_analysis, surface_realizer |
| Bài phát biểu | [nguồn](https://github.com/speaches-ai/speaches) | ngược dòng | bài giảng |
| ổn định-khuếch tán.cpp | [nguồn](https://github.com/leejet/stable-diffusion.cpp) | ngược dòng | hình ảnh |
| submodlib | [nguồn](https://github.com/decile-team/submodlib) | ngược dòng | thu gọn_gói |
| Máy biến áp | [nguồn](https://github.com/huggingface/transformers) | ngược dòng | ngữ nghĩa_observer |
| Vikunja | [nguồn](https://github.com/go-vikunja/vikunja) | ngược dòng | vikunja |
| vLLM | [nguồn](https://github.com/vllm-project/vllm) | ngược dòng | vllm |
| Bộ định tuyến ngữ nghĩa vLLM | [nguồn](https://github.com/vllm-project/semantic-router) | người tiền nhiệm đã nghỉ hưu/dòng dõi được kiểm tra (không phải thời gian chạy) | bộ định tuyến |
| Z-Hình ảnh-Turbo | [nguồn](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo) | ngược dòng | hình ảnh |
| Tham khảo bao bì Z-Image-Turbo-Windows | [nguồn](https://github.com/airesearch-official/Z-Image-Turbo-Windows) | tham chiếu bao bì được kiểm tra (không phải giao diện người dùng thời gian chạy) | hình ảnh |

## Ranh giới phân bố

Tài liệu công khai không chứa bất kỳ trọng lượng mô hình hoặc mã dự án nào được liệt kê. Bản phân phối phần mềm trong tương lai phải tạo ra các phiên bản, bản sửa đổi, hàm băm, phần phụ thuộc bắc cầu, điều khoản mô hình và văn bản giấy phép chính xác từ các byte được phân phối thực sự. Liên kết dự án là sự ghi nhận và truy xuất nguồn gốc, không phải là ý kiến ​​cấp phép.
