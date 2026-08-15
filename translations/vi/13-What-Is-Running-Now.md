> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../README.md) | [Tất cả ngôn ngữ](../README.md)

# Những gì đang chạy bây giờ

![Bộ máy cục bộ được tổ chức theo trách nhiệm xung quanh một đường trục được kiểm soát chung](../../assets/public-machinery-catalog.png)

## Cách đọc danh mục này

Danh mục này là bản sao công khai của chế độ xem Trung tâm dữ liệu trong Kiểm soát nhiệm vụ. Nó mô tả mỗi răng cưa đóng góp những gì và những gì sẽ bị mất nếu nó biến mất mà không công bố địa chỉ riêng, bố cục máy, thông tin xác thực, đường dẫn tệp hoặc nhịp hoạt động. Biểu đồ trực tiếp vẫn là nguồn hoạt động chính xác.

Trạng thái thành phần quan trọng. Một công cụ có thể đang hoạt động, được giữ lại dưới dạng hệ thống nguồn, được đánh giá nhưng không được áp dụng hoặc một công cụ tiền nhiệm đã ngừng hoạt động. Sự hiện diện trong danh mục này không cấp quyền cho thành phần nào vượt quá vai trò đã nêu của nó.

Quy tắc đó bao gồm khả năng biên giới bên ngoài. Khi được sử dụng, nó chiếm một trạm giới hạn và nhận tải trọng được xây dựng có mục đích thay vì quyền truy cập không hạn chế vào kho dữ liệu được duy trì. Tải trọng hỗ trợ hoạt động đã khai báo nhưng bỏ qua trạng thái bền vững cần thiết để xây dựng lại hệ thống rộng hơn hoặc thực hiện rút tiền một cách độc lập trong tương lai. Trạm nhận công việc chứ không phải lưu giữ hồ sơ con người mà từ đó một tổ chức tập trung có thể thu được giá trị lâu dài.

## Đường vào và xung quanh hệ thống

### Bộ não robot (LibreChat)


**Trách nhiệm.** Cung cấp cửa sổ trò chuyện trực tiếp với con người có thể thay thế được. Nó mang theo các yêu cầu và phản hồi trong khi bộ nhớ lâu bền, khả năng truy xuất, lý luận và xác minh vẫn được duy trì trong các dịch vụ bên dưới nó.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[LibreChat](https://github.com/danny-avila/LibreChat),[Node.js](https://github.com/nodejs/node)

### Bộ chia cuộc hội thoại


**Trách nhiệm.** Thông báo khi cuộc trò chuyện chuyển thành hai chủ đề và đề nghị gửi riêng chủ đề đã hoàn thành.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[API nhanh](https://github.com/fastapi/fastapi)

### Kiểm soát nhiệm vụ


**Trách nhiệm.** Cửa sổ trên máy: cái gì đang chạy, cái gì cần chú ý và cái gì nó đang làm ngay bây giờ. Tại ranh giới xuất bản này, trang trạng thái của nó báo cáo tất cả các hệ thống được giám sát đang hoạt động trên cài đặt cục bộ.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Trạng thái hoạt động báo cáo trạng thái dịch vụ; các hiện vật và biên nhận được chấp nhận thiết lập các ranh giới thực thi và bằng chứng ngữ nghĩa riêng biệt.

**Các công cụ công cộng chính.**[API nhanh](https://github.com/fastapi/fastapi),[Đồ họa](https://gitlab.com/graphviz/graphviz),[Tâm lý học](https://github.com/psycopg/psycopg)

### Bộ định tuyến ngữ nghĩa


**Trách nhiệm.** Định tuyến các yêu cầu có giới hạn đến công cụ cục bộ thích hợp và yêu cầu ủy quyền rõ ràng trước khi sử dụng suy luận bên ngoài. Khả năng đắt tiền chỉ được chọn khi yêu cầu chứng minh được chi phí đo được của nó.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[API nhanh](https://github.com/fastapi/fastapi). Envoy và Bộ định tuyến ngữ nghĩa vLLM vẫn được ghi nhận trong chỉ mục nguồn dưới dạng các phiên bản tiền nhiệm đã được kiểm tra hoặc đã ngừng hoạt động, chứ không phải các phần phụ thuộc thời gian chạy hiện tại.

### Hoàn thành lịch sử đại lý


**Trách nhiệm.** Lưu giữ các luồng sự kiện của nhân viên được sắp xếp, hoàn chỉnh làm bằng chứng tương tác, bao gồm lượt của con người, lượt trợ lý, công cụ, lỗi và sửa chữa. Lịch sử ghi lại những gì đã xảy ra; họ không biến các tuyên bố của đại lý thành sự thật đã được xác minh.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ cung cấp những gì nguồn và xuất xứ của nó xác lập; giải thích xuôi dòng vẫn riêng biệt.

### Tài liệu dự án


**Trách nhiệm.** Lưu giữ thiết kế riêng, bằng chứng và hồ sơ dự án giải thích lý do nền tảng tồn tại và kiến ​​trúc của nó đã thay đổi như thế nào. Các sản phẩm công khai sử dụng các dẫn xuất đã được đánh giá thay vì tiết lộ vị trí tài liệu riêng tư.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ cung cấp những gì nguồn và xuất xứ của nó xác lập; giải thích xuôi dòng vẫn riêng biệt.

### Vikunja


**Trách nhiệm.** Duy trì hệ thống tác vụ bên ngoài dưới dạng nguồn sở hữu độc lập có trước nền tảng. Tích hợp có thể đọc bằng chứng nhiệm vụ được ủy quyền mà không cần đưa hệ thống nhiệm vụ vào kho dữ liệu hoặc thay đổi vòng đời của nó.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ cung cấp những gì nguồn và xuất xứ của nó xác lập; giải thích xuôi dòng vẫn riêng biệt.

**Các công cụ công cộng chính.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Bảo quản và thu hồi

### Tiếp thu kiến ​​thức


**Trách nhiệm.** Cách mọi thứ diễn ra. Thả một tài liệu, một bản xuất, một chồng ghi chú và nó sẽ được đưa đến một nơi nào đó có thể tìm thấy thay vì không có nơi nào.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### MongoDB


**Trách nhiệm.** Tự mình tổ chức các cuộc trò chuyện như đã nói.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Tính sẵn có và tính toàn vẹn là cần thiết; dữ liệu được lưu trữ không tự giải thích hoặc xác minh.

**Các công cụ công cộng chính.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Trách nhiệm.** Lưu giữ các hồ sơ dự án có cấu trúc bền vững, trạng thái dẫn xuất và các chỉ mục tìm kiếm nhằm tồn tại lâu hơn các dịch vụ ứng dụng có thể thay thế. Các hồ sơ được lưu trữ giữ lại thẩm quyền và nguồn gốc riêng biệt thay vì trở thành một bộ nhớ không phân biệt.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Tính sẵn có và tính toàn vẹn là cần thiết; dữ liệu được lưu trữ không tự giải thích hoặc xác minh.

**Các công cụ công cộng chính.**[PostgreSQL](https://github.com/postgres/postgres),[pgvector](https://github.com/pgvector/pgvector)

## Lý luận và tái thiết

### Trình phân loại quan hệ đối số

đã ghim AMF_ARI Phân loại CPU OpenVINO suy luận, xung đột, diễn đạt lại hoặc không có quan hệ

**Trách nhiệm.** Phân loại mối quan hệ giữa hai mệnh đề được cung cấp; nó không tạo ra mệnh đề hoặc suy ra động cơ cá nhân. Ví dụ: phân biệt một phát biểu hỗ trợ một phát biểu khác với một phát biểu mâu thuẫn với nó hoặc không trả về mối quan hệ nào được hỗ trợ.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[Mô hình AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Hiện vật của con người


**Trách nhiệm.** Xác định các sản phẩm hướng tới con người mà dây chuyền lắp ráp có thể tạo ra. Mỗi sản phẩm đều có bộ tiếp nhận, mục đích, cấu trúc, chính sách bằng chứng và hợp đồng giao hàng riêng thay vì chia sẻ một bản phác thảo chung.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Tiếp đất + Xác nhận giao hàng

cổng nhận độc lập qua kiểm tra độ trung thực, xuất xứ, mất mát, phát minh, dệt và hiểu

**Trách nhiệm.** Kiểm tra độc lập xem hiện vật có duy trì ý nghĩa được hỗ trợ và đáp ứng hợp đồng giao hàng đã khai báo trước khi phát hành hay không. Ví dụ: từ chối một đoạn văn có thể đọc được phát minh ra một kết luận và từ chối riêng một tài liệu có căn cứ có cấu trúc không thể sử dụng được cho người đọc mục tiêu của nó.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Độ phân giải đối tượng

trạng thái người nhận, điều kiện tiên quyết, đăng ký và mức độ liên quan

**Trách nhiệm.** Mô tả những gì người nhận mong muốn biết, cần và chấp nhận trong khi vẫn giữ các giả định rõ ràng. Ví dụ: yêu cầu chủ nhà hướng dẫn giải thích độ pH trước khi sử dụng các từ viết tắt quen thuộc với kỹ thuật viên hồ bơi.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Thu gọn toàn bộ cây + Gói

phân vùng, lựa chọn, lợi nhuận và tổn thất bị ràng buộc bởi container

**Trách nhiệm.** Chọn và cân bằng những gì có thể phù hợp với hiện vật được yêu cầu trong khi ghi lại những gì đã bị bỏ qua và giữ nguyên hình dạng có ý nghĩa của cây. Ví dụ: giữ mỗi nhánh chính được trình bày trong một bài viết 1.000 từ thay vì để nhánh nguồn lớn nhất tiêu tốn toàn bộ ngân sách.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[submodlib](https://github.com/decile-team/submodlib),[quỳ gối](https://github.com/arvkevi/kneed)

### Mô hình làm việc nhỏ gọn

Nhà cung cấp dịch vụ có phạm vi yêu cầu di động dành cho các đơn vị, mối quan hệ, quỹ đạo, khối nguồn, kế hoạch, tay cầm và sổ cái chuyển giao đã chọn

**Trách nhiệm.** Đóng gói các sự kiện, mối quan hệ, trình tự thời gian, sự không chắc chắn, lỗi và nguồn xử lý đã chọn vào một bối cảnh cụ thể của công việc di động. Ví dụ: cung cấp cho người chỉnh sửa chuỗi bảo trì nhóm và lý do tại sao các bước của nó kết nối mà không tải toàn bộ kho văn bản hoặc bỏ liên kết.

**Phải bảo tồn.** source_spans; quan hệ_ids; niên đại; sự không chắc chắn; thất bại; thay thế; ẩn số

**Hình dạng tài nguyên.** CPU và RAM tỷ lệ thuận với lựa chọn giới hạn; không có GPU hoặc cho thuê

**Ranh giới.** chất lượng được giới hạn bởi mối quan hệ thượng nguồn và phạm vi bảo hiểm trạng thái tiền gửi

### Cơ khí giao hàng

điều khiển đăng ký, chế độ, cấu hình dệt, nhịp độ, mật độ và deslop

**Trách nhiệm.** Cung cấp các giới hạn phân phối được đo lường, chẳng hạn như tốc độ, mật độ, đăng ký và quỹ đạo dệt cho sản phẩm và đối tượng này. Ví dụ: đưa ra lời giải thích cho trẻ với các gói ngắn hơn và kiểu lặp lại khác với báo cáo kỹ thuật mà không làm thay đổi các sự kiện cơ bản.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Tiền xử lý diễn ngôn

các lát cắt giới hạn chính xác, các ứng cử viên tham chiếu FastCoref và các liên kết toán hạng RST isanlp được thuê

**Trách nhiệm.** Xác định các đối tượng tham chiếu ứng cử viên và các khoảng diễn ngôn trước khi phân loại lý luận trong khi vẫn duy trì tọa độ nguồn chính xác. Ví dụ: liên kết 'it' với ứng cử viên bơm được đặt tên và hiển thị hai mệnh đề được nối với nhau bằng quan hệ diễn ngôn nhân quả.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Tái thiết chuyển tiếp toàn bộ hiện vật

điều kiện tiên quyết, tài liệu tham khảo, chất kết dính nhân quả, tiến triển, giới thiệu và kết luận

**Trách nhiệm.** Xây dựng lại tài liệu đã chọn theo thứ tự người đọc, khôi phục các điều kiện tiên quyết, tài liệu tham khảo, liên kết nhân quả, diễn biến và phần kết trung thực. Ví dụ: giới thiệu mục tiêu trước khi thực hiện và kết thúc một câu hỏi chưa được giải quyết khi chưa có kết luận.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Biểu đồ Tại sao và Phép chiếu phụ thuộc

quan điểm xác định của các cạnh đồ thị được phân loại không thể đưa ra các tuyên bố lý luận mới

**Trách nhiệm.** Chuyển các cạnh quan hệ được chấp nhận thành phần phụ thuộc có thể kiểm tra và các chế độ xem tại sao mà không cần thêm diễn giải. Ví dụ: chỉ ra rằng kết luận B phụ thuộc vào tiền đề A vì cạnh được phân loại chính xác đó tồn tại.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[MạngX](https://github.com/networkx/networkx)

### Câu trả lời tương tác có căn cứ


**Trách nhiệm.** Trả lại câu trả lời mang tính trò chuyện kèm theo lý do, nguồn gốc, sự không chắc chắn và đường dẫn mở rộng có liên quan. Đường dẫn câu trả lời có thể đi qua các cuộc hội thoại hoàn chỉnh và vòng đời bằng chứng mà không giả vờ là một quá trình tạo tài liệu.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Cầu giao thức con người

mã hóa hướng tới người nhận của tải trọng được hỗ trợ cố định

**Trách nhiệm.** Chuyển đổi tải trọng cố định, được hỗ trợ thành dạng mà người dùng dự định có thể làm theo, sử dụng hợp đồng sản phẩm và mẫu phân phối được đo lường; nó không thể thay đổi bằng chứng. Ví dụ: biến chuỗi lý luận có cơ sở tương tự thành một email ngắn gọn hoặc một hướng dẫn theo giai đoạn bằng cách thay đổi cấu trúc phân phối chứ không phải kết luận.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Hội ngữ cảnh tương tác


**Trách nhiệm.** Xây dựng bằng chứng có giới hạn và biểu đồ lý luận cho câu hỏi hiện tại, lưu giữ trình tự thời gian, các chỉnh sửa, lỗi, nhận dạng nguồn và ủy quyền. Nó cung cấp ngữ cảnh cho câu trả lời mà không làm phẳng kho ngữ liệu thành các đoạn tìm kiếm.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Gia nhập không mất dữ liệu


**Trách nhiệm.** Chấp nhận byte gốc và sự kiện gốc trước khi diễn giải, chỉ ghi lại các sự kiện đến được quan sát. Các mô tả, dấu thời gian được suy ra từ nội dung, danh tính và mối quan hệ vẫn là các quan sát được phiên bản riêng biệt.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Bằng chứng chính


**Trách nhiệm.** Giữ các khoản tiền gửi có thẩm quyền mà các đại diện và sản phẩm sau này phải có khả năng truy ngược lại. Sự tồn tại của chúng vẫn có chỗ đứng ngay cả khi hệ thống chưa thể giải thích được ý nghĩa hoặc mối quan hệ của chúng.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Cây tạm thời hoàn chỉnh

bằng chứng đầy đủ trước khi cắt tỉa, sự phụ thuộc, sự thay thế và cấu trúc thất bại

**Trách nhiệm.** Giữ cây ứng viên hoàn chỉnh trong phạm vi yêu cầu, bao gồm các lựa chọn thay thế, lỗi, ẩn số và chế độ xem thay thế, để việc thu gọn có thể xem nó sẽ mất những gì. Ví dụ: giữ lại cả phương pháp xử lý thất bại và phương pháp điều chỉnh sau đó trước khi chọn tài liệu làm hướng dẫn.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Đồ thị lý luận

trình tự thời gian, mối quan hệ được đánh máy, vòng đời yêu cầu bồi thường, lỗi và sự không chắc chắn

**Trách nhiệm.** Duy trì bản đồ trong phạm vi yêu cầu về các mệnh đề, trình tự thời gian, nỗ lực, kết quả, xung đột, sự phụ thuộc và sự không chắc chắn. Ví dụ: kết nối một phương pháp điều trị thất bại với phương pháp điều chỉnh thay thế nó mà không xóa cả hai trạng thái.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Yêu cầu + Hợp đồng tạo tác

mục đích, người nhận, vùng chứa, kênh, ngân sách và tính xác thực

**Trách nhiệm.** Cố định mục đích, người tiếp nhận, sản phẩm, kênh, ngân sách và tiêu chuẩn sự thật để mọi bánh răng phía dưới đều giải quyết được cùng một công việc. Ví dụ: phân biệt lời giải thích dài 500 từ dành cho người đọc với báo cáo sự cố kỹ thuật trước khi bắt đầu lựa chọn bằng chứng.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Mở rộng ngược

thu thập về phía sau mà không cắt tỉa; đo lường sự đóng góp cận biên

**Trách nhiệm.** Đi từ yêu cầu hoặc bằng chứng sau này đến các hồ sơ liên quan trước đó và thu thập toàn bộ hành trình của ứng viên trước khi bất kỳ điều gì bị loại bỏ. Ví dụ: theo dõi câu hỏi về tảo hiện tại thông qua các bản ghi pH, kích thước bể bơi, bảo trì và bối cảnh sử dụng trước đó.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Các bước tu từ được gõ

công việc ngữ nghĩa và sự phụ thuộc, không bao giờ tiêu đề chuỗi con

**Trách nhiệm.** Chỉ định cho mỗi đơn vị được chọn một công việc giao tiếp và sự phụ thuộc dựa trên hợp đồng sản phẩm chứ không phải từ tiêu đề phù hợp. Ví dụ: đánh dấu bằng chứng là hỗ trợ cho tuyên bố và thất bại khi thiết lập quá trình khôi phục thay vì gọi cả hai là 'nền'.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Tái thiết ngữ nghĩa

thực thể, mệnh đề, tình tiết, nỗ lực, kết quả và câu hỏi

**Trách nhiệm.** Chuyển đổi các quan sát nguồn thành các đối tượng ngữ nghĩa được phân bổ mà không quyết định tầm quan trọng hoặc cách trình bày cuối cùng của chúng. Ví dụ: trình bày cách khắc phục được đề xuất, nỗ lực, thất bại và câu hỏi còn lại dưới dạng các bản ghi được liên kết riêng biệt.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Phiên bản đại diện


**Trách nhiệm.** bản ghi, cấu trúc, văn bản, OCR, bố cục và chế độ xem phái sinh

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Tại sao nó quan trọng

động lực, mối quan tâm, hậu quả và mức độ phù hợp hiện tại

**Trách nhiệm.** Mang theo bằng chứng trực tiếp và rõ ràng về lý do tại sao lại đầu tư sự chú ý, không nêu lý do không được chứng minh. Ví dụ: cho rằng nhiệm vụ bảo trì quan trọng vì nó bảo vệ những người sử dụng thiết bị dùng chung khi hồ sơ hỗ trợ nó, thay vì đoán động cơ đó chỉ từ một câu hỏi kỹ thuật.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Lý luận + Công cụ tạo tác

tái thiết cổng nhận, thu gọn, Giao thức con người và kết xuất Markdown nguyên tử

**Trách nhiệm.** Điều phối đường dẫn tái thiết và hiển thị có giới hạn cũng như hiển thị biên nhận của từng giai đoạn; nó không thay thế sự phán xét của chuyên gia. Ví dụ: thực hiện yêu cầu soạn thảo thông qua lựa chọn, lập kế hoạch, hiện thực hóa, xác thực và ghi nguyên tử.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Trình quản lý lắp ráp + năng lực

lùi các trường bắt buộc, định giá các điều kiện tiên quyết, chọn các chuyên gia trung thực, đặt hàng các đợt phụ thuộc và bỏ qua công việc có giá trị bằng 0

**Trách nhiệm.** Chọn chuyên gia nào là cần thiết, họ thực hiện theo trình tự nào và công việc nào không mang lại giá trị gì; nó không thực hiện công việc của họ. Ví dụ: lên lịch thực hiện quan hệ trước khi thực hiện câu và bỏ qua bước phong cách không có sẵn mà không đóng góp gì cần thiết.

**Phải bảo tồn.** must_preserve_fields; field_lineage; rõ ràng_không có sẵn

**Hình dạng tài nguyên.** CPU; bộ nhớ thấp; không có GPU hoặc cho thuê

**Ranh giới.** Quan sát chi phí và giá trị cho thấy các quyết định nhưng không bao giờ xác định tầm quan trọng của con người

### Bộ điều chỉnh ngân sách nhà cung cấp nguyên tử

đo lường các nguồn không thể phân chia, chất kết dính và các chất mang mối quan hệ trước khi hiện thực hóa và phân phối lại ngân sách toàn bộ sản phẩm cố định theo phần chính xác

**Trách nhiệm.** Kiểm tra xem các sự kiện không thể chia nhỏ và các nhà cung cấp mối quan hệ có thể phù hợp với từng phần hay không, sau đó chỉ di chuyển phần dự phòng có sẵn trong khi vẫn bảo toàn tổng ngân sách tài liệu. Ví dụ: phóng to phần thủ tục 90 từ có chứa hướng dẫn nguyên tử 120 từ bắt buộc bằng cách mượn các từ không sử dụng từ phần khác.

**Phải bảo tồn.** Whole_artifact_budget; bắt buộc_hùng biện_jobs; nguồn_authority; đồ thị

**Hình dạng tài nguyên.** CPU; thời gian chạy gần như bằng không; ngăn chặn công việc lãng phí của GPU/mô hình/trình xác minh Giai đoạn 8

**Ranh giới.** không thể nén một mệnh đề không thể chia được; không thành công nếu tất cả các hãng vận chuyển được yêu cầu vượt quá ngân sách sản phẩm đã khai báo

### Trình quản lý liên kết lại nguồn-ràng buộc

chỉ di chuyển một nhánh hoàn toàn biệt lập khi công việc sản phẩm được giao của nó không tương thích và một đích được chứng minh là tương thích

**Trách nhiệm.** Chuyển một nhánh bằng chứng hoàn chỉnh, biệt lập sang một bộ phận mà công việc của họ có thể sử dụng nó một cách hợp pháp, đồng thời từ chối các động thái mơ hồ hoặc có liên quan. Ví dụ: gán lại ghi chú khôi phục độc lập từ quá trình thiết lập đến khắc phục sự cố mà không sao chép ghi chú đó ở cả hai phần.

**Phải bảo tồn.** Branch_identity; nguồn_spans; quan hệ_ids; cận biên_gain_ledger

**Hình dạng tài nguyên.** CPU; độ trễ thấp; không có GPU hoặc cho thuê

**Ranh giới.** từ chối các động thái mang tính liên quan, không rõ ràng, một phần hoặc vượt quá công suất

### Trình thực hiện mối quan hệ trên toàn tài liệu

biến các cạnh lý luận cùng mặt cắt và mặt cắt ngang được chấp nhận thành ngôn ngữ liên kết nhỏ gọn, có thể chơi lại độc lập mà không lặp lại cả hai toán hạng

**Trách nhiệm.** Biến các quan hệ biểu đồ được chấp nhận thành ngôn ngữ liên kết ngắn gọn trong khi vẫn giữ hướng, toán hạng và các nhịp nguồn có thể phát lại một cách độc lập. Ví dụ: coi A-nguyên nhân-B là cầu nối nhân quả có giới hạn thay vì in A và B là các sự kiện liền kề không liên quan.

**Phải bảo tồn.** quan hệ_hướng; toán hạng_identity; chính xác_carrier_spans; nguồn_spans; phần_dòng dõi

**Hình dạng tài nguyên.** CPU; thời gian chạy gần như bằng không; không có GPU hoặc cho thuê

**Ranh giới.** chỉ hiện thực hóa các loại quan hệ được chấp nhận rõ ràng; cầu nhỏ gọn bảo tồn bản sắc cạnh gõ nhưng vẫn được diễn đạt một cách máy móc; các cạnh cùng sóng mang, mơ hồ, ẩn và không xác định vẫn hiển thị trong biểu đồ nhưng không được xác nhận là văn xuôi

### Công cụ tri thức


**Trách nhiệm.** Điều phối việc gia nhập, biểu diễn dẫn xuất, tìm kiếm, xuất xứ và các công việc lâu dài mà không hợp nhất các trách nhiệm đó thành một trạng thái chân lý. Nó hiển thị các giao diện được hỗ trợ cho người tiêu dùng trong khi bằng chứng chính vẫn có thể giải quyết được một cách độc lập.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Điều khoản đã nhập / Công cụ lập kế hoạch vi mô câu

chỉ định các nhà cung cấp dịch vụ liên quan đến nguồn cho các công việc tu từ được đánh máy và biên soạn các sơ đồ mệnh đề, câu và đoạn văn

**Trách nhiệm.** Chia ý nghĩa và các mối quan hệ đã được phê duyệt thành các công việc mệnh đề, câu và đoạn văn trong khi vẫn giữ nguyên ràng buộc nguồn của chúng; nó không phát minh ra từ ngữ hoặc tuyên bố. Ví dụ: lập kế hoạch cho một mệnh đề nguyên nhân, theo sau là hậu quả và sự chuyển tiếp của nó đối với bộ thực hiện bề mặt.

**Phải bảo tồn.** ngữ nghĩa_unit_ids; quan hệ_ids; nguồn_forms

**Hình dạng tài nguyên.** CPU; độ trễ thấp; không có GPU hoặc cho thuê

**Ranh giới.** không phát minh ra một mệnh đề còn thiếu hoặc sửa chữa một mối quan hệ chưa được phân loại

**Các công cụ công cộng chính.**[spaCy](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire)

### Người quản lý hợp đồng sản phẩm

chuyển đổi thể loại, người nhận, mục đích, kênh, tính xác thực, sự chú ý và ngân sách thành các lĩnh vực sản phẩm bắt buộc và tác phẩm hùng biện

**Trách nhiệm.** Biến yêu cầu thành một danh sách kiểm tra cụ thể cho thành phẩm mà không cần chọn bằng chứng hay viết ra. Ví dụ: đối với hướng dẫn sử dụng, yêu cầu các điều kiện tiên quyết, các hành động được yêu cầu, hướng dẫn khôi phục và kết thúc trước khi bất kỳ trình soạn thảo nào bắt đầu.

**Phải bảo tồn.** khai_mục đích; người nhận; tính xác thực; kênh

**Hình dạng tài nguyên.** CPU; thời gian chạy gần như bằng không; không có GPU hoặc cho thuê

**Ranh giới.** không suy ra ý nghĩa nguồn hoặc chọn dữ kiện

### Công cụ thực hiện bề mặt hợp đồng

áp dụng các phép biến đổi ngữ pháp, hình thái, kiểu chữ, phối cảnh và định kiểu giới hạn cho các đơn vị phân phối

**Trách nhiệm.** Áp dụng ngữ pháp, hình thái, kiểu chữ và phối cảnh được phép cho một kế hoạch đã được phê duyệt; nó không thể quyết định ý nghĩa mới. Ví dụ: biến kế hoạch mệnh lệnh đánh máy thành hướng dẫn ngữ pháp mà không cần thêm tuyên bố an toàn chưa từng được cung cấp.

**Phải bảo tồn.** Claim_authority; source_and_relation_binds; hùng biện_job

**Hình dạng tài nguyên.** CPU; biên tập viên ứng cử viên tùy chọn có thể sử dụng hợp đồng thuê GPU hiện có nhưng không có thẩm quyền

**Ranh giới.** ngữ pháp khép kín là trung thực nhưng có thể vẫn cứng nhắc về mặt văn phong

**Các công cụ công cộng chính.**[spaCy](https://github.com/explosion/spaCy)

## Quản lý, xác minh và vận hành

### Amf Ari


**Trách nhiệm.** Chạy trình phân loại quan hệ đối số được ghim trên các cặp mệnh đề được cung cấp và trả về các nỗ lực hỗ trợ, xung đột, diễn đạt lại hoặc không liên quan được ghi điểm. Nó không tạo ra các đề xuất, suy luận động cơ hoặc chứng nhận nhãn hiệu riêng của mình.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[OpenVINO](https://github.com/openvinotoolkit/openvino),[Mô hình AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Trình lập chỉ mục trò chuyện


**Trách nhiệm.** Lưu giữ các cuộc trò chuyện trong bản ghi dài thay vì để chúng trong cửa sổ trò chuyện.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Trình lập chỉ mục tệp


**Trách nhiệm.** Khám phá các tệp đủ điều kiện và gửi công việc lập chỉ mục có giới hạn, bảo toàn xuất xứ. Nó không được coi ngày tháng, tên tệp hoặc văn bản được trích xuất của hệ thống tệp là thời gian, danh tính hoặc động cơ tạo có thẩm quyền.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Đo từ xa phần cứng


**Trách nhiệm.** Ghi lại lịch sử tình trạng máy được giới hạn để có thể so sánh các lỗi hỏng hóc với nguồn điện, nhiệt độ, bộ nhớ và trạng thái máy gia tốc. Mô tả công khai bỏ qua nhịp lấy mẫu riêng và bố cục máy.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[psutil](https://github.com/giampaolo/psutil)

### Hình ảnh


**Trách nhiệm.** Sản xuất hình ảnh cục bộ để khái niệm trực quan không cần phải vượt qua ranh giới suy luận bên ngoài. Việc tạo hình ảnh vẫn tách biệt với thẩm quyền chứng cứ và sự cho phép xuất bản.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[ổn định-khuếch tán.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Hình ảnh-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Tham khảo bao bì Z-Image-Turbo-Windows](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Trách nhiệm.** Tâm trí nặng trĩu. Chậm hơn và lớn hơn, dành cho những câu hỏi thực sự cần suy nghĩ nhiều hơn tốc độ.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### nhúng Ollama


**Trách nhiệm.** Làm cho bài viết có thể tìm kiếm được theo ý nghĩa thay vì theo từ chính xác.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[Ollama](https://github.com/ollama/ollama),[Văn bản nhúng danh nghĩa](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Cho thuê điện


**Trách nhiệm.** Cho phép máy chạy không tải và hoạt động hoàn toàn để thực hiện công việc thực tế.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Trình đổi tên cuộc trò chuyện


**Trách nhiệm.** Đặt tên các cuộc hội thoại có ý nghĩa gì đó để bạn có thể tìm thấy danh sách thay vì một bức tường gồm các câu đầu tiên.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Người quan sát ngữ nghĩa


**Trách nhiệm.** Kiểm tra xem câu trả lời có được hỗ trợ bởi tài liệu mà nó tuyên bố xuất phát hay không.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[Máy biến áp](https://github.com/huggingface/transformers),[Kiểm tra nhỏ](https://github.com/Liyan06/MiniCheck),[Sự thậtCG](https://github.com/derenlei/FactCG)

### Phân tích độ dốc


**Trách nhiệm.** Lưu giữ hồ sơ về việc mỗi tâm trí thất bại như thế nào và liệu điều đó đang trở nên tốt hơn hay tồi tệ hơn.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[spaCy](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Bài phát biểu


**Trách nhiệm.** Chuyển lời nói thành văn bản, vì vậy nói chuyện là một cách viết ra mọi thứ.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[Bài phát biểu](https://github.com/speaches-ai/speaches),[thì thầm nhanh hơn](https://github.com/SYSTRAN/faster-whisper),[nhanh hơn-chưng cất-thì thầm-lớn-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Dịch vụ nhiệm vụ


**Trách nhiệm.** Đọc hồ sơ nhiệm vụ được ủy quyền làm bằng chứng về công việc đã lên kế hoạch mà không chuyển chúng thành lời nhắc, động cơ được suy luận hoặc sự thật trong kho tài liệu.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### vLLM


**Trách nhiệm.** Tâm trí hàng ngày. Nhanh chóng, luôn được tải, trả lời hầu hết mọi thứ.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

**Các công cụ công cộng chính.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Công việc giai đoạn bền vững

lô giới hạn, điểm kiểm tra, hủy bỏ, tiếp tục và lỗi một phần

**Trách nhiệm.** Chạy các giai đoạn tạo tác dài dưới dạng các công việc giới hạn có thể tiếp tục với trạng thái đầu cuối trung thực thay vì buộc chúng vào một yêu cầu trình duyệt. Ví dụ: tiếp tục sau khi điểm kiểm tra thăng hạng đã được xác minh thay vì lặp lại bước lý luận đắt tiền sau khi bị gián đoạn.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Thực thi + Trình quản lý tệp kê khai

chạy bộ điều hợp được chỉ định và ghi lại phương thức vật lý, điểm cuối, bản sửa đổi mô hình, hàm băm, cạnh cuộc gọi, thời gian, số lần thử và cách xử lý

**Trách nhiệm.** Chạy từng chuyên gia được chỉ định và ghi lại những gì được thực hiện về mặt vật lý, cùng với thông tin đầu vào, danh tính, thời gian, số lần thử và kết quả. Ví dụ: chứng minh rằng trình phân loại AMF được ghim đã xử lý Giai đoạn 2 thay vì tin cậy vào nhãn kê khai chỉ nói rằng nó đã xử lý.

**Phải bảo toàn.** input_hash; adapter_identity; trạng thái thất bại

**Hình dạng tài nguyên.** Điều phối viên CPU; đại biểu GPU chỉ làm việc thông qua chủ sở hữu hợp đồng thuê đã khai báo

**Ranh giới.** ghi lại việc thực hiện; không thể chứng nhận sự thành công của chính mình

### Trọng tài cho thuê GPU


**Trách nhiệm.** Điều phối việc bàn giao tư vấn giữa các khối lượng công việc tăng tốc do nền tảng quản lý mà không làm lộ danh tính thiết bị vật lý hoặc chiếm trước công việc đang thực hiện.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Điều phối viên cư trú quyền lực

**Trách nhiệm.** Duy trì một mô hình trạng thái HOẠT ĐỘNG, WARM, IDLE và KHÔNG BAO GIỜ trên các cơ chế cư trú và sức mạnh nền tảng phân tán.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

### Sổ cái tải trọng dự kiến/được quan sát

liên kết từng trách nhiệm của răng cưa với các trường được quan sát, tính sẵn sàng, thiếu sót, giá trị, chi phí, thời gian, số lần thử lại và yêu cầu sửa chữa

**Trách nhiệm.** So sánh những gì mỗi bánh răng dự kiến ​​sẽ đóng góp với những gì nó thực sự mang lại, bao gồm chi phí và những đầu vào còn thiếu. Ví dụ: phơi bày rằng phân tích mối quan hệ đã chạy trong 40 giây nhưng không cung cấp đường liên kết hữu dụng nào cho trình soạn thảo.

**Phải bảo tồn.** handoff_identity; tiêu hóa; thiếu_fields; cơ sở chi phí

**Hình dạng tài nguyên.** CPU; gần bằng 0 so với lý luận và xác minh

**Boundary.** thời gian của phần di động không thay thế thời gian của giai đoạn/mô hình vật lý trong tệp kê khai thực thi

### Giám đốc chất lượng nhận thức sản phẩm

kiểm tra sự hoàn thiện của thuật hùng biện, lý luận liên kết, khả năng đọc, kiểu chữ, sự trùng lặp, sự chú ý, ngân sách, sự đan xen, sự trượt và các hành động thực thi cho sản phẩm được yêu cầu

**Trách nhiệm.** Đánh giá xem sản phẩm cụ thể này có hoạt động phù hợp với người đọc và mục đích đã tuyên bố trên các trục chất lượng riêng biệt hay không, sau đó xác định giai đoạn sửa chữa có trách nhiệm. Ví dụ: một cuốn sổ tay có thể thiếu hướng dẫn phục hồi ngay cả khi mọi câu đều đúng ngữ pháp và có căn cứ.

**Phải bảo tồn.** cá nhân_axis_results; bị từ chối_candidate_evidence

**Hình dạng tài nguyên.** CPU cộng với trình xác minh giới hạn/giải nén HTTP; trong lịch sử chia sẻ Giai đoạn 8 lớn nhất

**Ranh giới.** trục thể loại phải được đo lường và lập phiên bản; một điểm chất lượng không rõ ràng bị cấm

### Quản lý Biên lai + Khuyến mãi

tính toán lại các bất biến một cách độc lập và chỉ cho phép quảng bá và tạo tác nguyên tử từ biên nhận PASS

**Trách nhiệm.** Xác minh gói một cách độc lập và chỉ viết tạo phẩm sau mỗi lần vượt qua bất biến bắt buộc. Ví dụ: từ chối quảng cáo khi trình kết xuất báo cáo thành công nhưng việc nhận nó không thể tạo lại ràng buộc nguồn.

**Phải bảo tồn.** failed_results; những điều chưa biết; phát hành_nhận dạng; rollback_boundary

**Hình dạng tài nguyên.** CPU và I/O; không có GPU hoặc cho thuê

**Boundary.** tính xác thực của tệp kê khai cuối cùng phụ thuộc vào liên kết bản phát hành/cấu hình bất biến đã được xem xét

### Xuất xứ + Kiểm soát tổn thất

nhận dạng nguồn, trạng thái nhận thức, suy luận, phát minh và các nhánh bị từ chối

**Trách nhiệm.** Giữ mọi tuyên bố gắn liền với ai hoặc cái gì đã cung cấp nó, khi nào nó được áp dụng và liệu nó có được quan sát, suy luận, thay thế, bị từ chối hay không xác định. Ví dụ: giữ nguyên sự diễn giải lại sau này mà không ghi đè niềm tin trước đó đã thực sự hướng dẫn một hành động.

**Phải bảo toàn.** Nhận dạng chính xác biểu đồ, nguồn gốc mối quan hệ và ranh giới thành phần đã khai báo.

**Hình dạng tài nguyên.** Quá trình triển khai trực tiếp ghi lại việc sử dụng CPU, bộ nhớ, bộ nhớ, bộ tăng tốc và hoạt động cho thuê thực tế; danh mục công khai này không tiết lộ vị trí đặt máy.

**Ranh giới.** Chỉ có thể thực hiện trách nhiệm biểu đồ đã khai báo và không thể sửa chữa bằng chứng ngược dòng bị thiếu hoặc không được hỗ trợ.

## Các thành phần khai báo bổ sung

### Cổng Web an toàn

Cung cấp quyền truy cập từ xa được xác thực từ các khách hàng được phê duyệt mà không để lộ trực tiếp các dịch vụ nền tảng riêng tư ra Internet công cộng.

### Giám sát nền tảng

Khởi động các dịch vụ theo thứ tự phụ thuộc, theo dõi tình trạng của chúng và thực hiện các hành động khởi động lại có giới hạn. Lỗi của nó sẽ loại bỏ sự giám sát phối hợp mà không xác định lại trạng thái của các dịch vụ vẫn đang chạy.

## Ranh giới đầy đủ

Danh mục này bao gồm các thành phần logic hoạt động trong biểu đồ kiến ​​trúc được duy trì, không phải mọi gói bắc cầu được cài đặt trong mỗi thời gian chạy. Bản phát hành phần mềm trong tương lai yêu cầu danh mục tài liệu phần mềm chính xác và gói giấy phép được tạo từ các byte cụ thể đang được phân phối.
