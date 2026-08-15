> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../README.md) | [Tất cả ngôn ngữ](../README.md)

# Giữ lý luận có thể kiểm tra được

![Các chuyên gia độc lập truy tìm các lối suy luận được chấp nhận và bị bác bỏ để tìm ra bằng chứng chính xác](../../assets/reasoning-engine-inspectable-path.png)

## Lý luận có thể kiểm tra

Công cụ lý luận là một chuỗi các chuyên gia bị chặn và các phép chiếu xác định. Mục đích của nó là xây dựng một biểu đồ mệnh đề và quan hệ có thể kiểm tra được từ bằng chứng nguồn chính xác. Đây không phải là lời nhắc hoàn thành chung chung được yêu cầu để suy ra toàn bộ tài liệu.

```text
EXACT EVIDENCE ITEMS AND SOURCE SPANS
        |
DISCOURSE AND REFERENCE PREPROCESSING
        |
PROPOSITION AND RELATION CANDIDATES
        |
ARGUMENT RELATION CLASSIFICATION
        |
TYPED PROVENANCE GRAPH
        |
DETERMINISTIC DEPENDENCY AND WHY PROJECTION
        |
PRODUCT-SPECIFIC SELECTION AND RECONSTRUCTION
        |
INDEPENDENT VERIFIER AND RECEIPT
```

## Tiền xử lý ngôn ngữ

Bằng chứng được chia thành các phần có giới hạn, không có khoảng trống gắn liền với các danh tính nguồn bất biến và các ký tự bù trừ. Phân tích coreference đề xuất chuỗi tham chiếu. Phân tích lý thuyết cấu trúc tu từ đề xuất cấu trúc diễn ngôn và các cặp toán hạng. Các cấu trúc quá khổ hoặc không bị ràng buộc vẫn rõ ràng thay vì bị cắt bớt hoặc ánh xạ âm thầm tới cụm từ khớp đầu tiên.

Những công cụ này bộc lộ cấu trúc ngôn ngữ. Họ không tự mình thiết lập động cơ cá nhân hoặc lập luận lẽ thật.

## Phân loại quan hệ đối số

Các cặp mệnh đề bắt nguồn từ diễn ngôn được phân loại thành một kho lưu trữ quan hệ nhỏ, bao gồm hỗ trợ, xung đột, tương đương hoặc không có quan hệ chính thống. Mọi nỗ lực đều giữ lại toán hạng, phân phối điểm, nhận dạng mô hình và cách sắp xếp. Kết quả dưới ngưỡng vẫn hiển thị và không tạo ra cạnh.

Các mối quan hệ được chấp nhận trở thành các cạnh của biểu đồ có hướng với các khoảng nguồn và nhận dạng phương thức chính xác. Liên kết nguồn không rõ ràng không đóng được.

## Phép chiếu đồ thị

Chế độ xem phụ thuộc và “tại sao” là một phép chiếu xác định của các cạnh đã được phân loại. Nó có thể bộc lộ chuỗi hỗ trợ hoặc xung đột ở dạng dễ sử dụng hơn. Nó có thể không phát minh ra những lý do, mối quan tâm hoặc hậu quả mới và cho rằng một chuyên gia đã tìm ra chúng.

Biểu đồ có thể được xuất thông qua các cấu trúc trao đổi đối số đã được thiết lập, nhưng biểu diễn trao đổi không phải là kho lưu trữ chân lý thứ hai và không yêu cầu mô hình hoặc bộ tăng tốc.

## Ranh giới tài nguyên

Phân tích cú pháp tham chiếu và diễn ngôn có thể sử dụng công suất tăng tốc được thuê vì các mô hình đó được tải cho các công việc tiền xử lý có giới hạn. Phân loại đối số được thiết kế để chạy qua một đường dẫn suy luận chuyên môn nhỏ gọn. Phép chiếu đồ thị, lựa chọn, giải quyết ràng buộc, kiểm tra xuất xứ và xác minh biên nhận là những công việc thông thường của CPU.

Thiết kế tránh giữ mọi cư dân mô hình và cấm bắt đầu nhân công trùng lặp để trốn tránh cơ chế cho thuê chung.

## Những gì người xác minh chứng minh và không chứng minh

Trình xác minh có thể chứng minh rằng các thành phần bắt buộc đã chạy, các nhịp chính xác vẫn tồn tại, phép chiếu biểu đồ có thể tái tạo, các liên kết sản phẩm nhất quán và các byte được quảng cáo khớp với gói được chấp nhận. Nó có thể từ chối các bảng kê khai bịa đặt, văn xuôi không được hỗ trợ, hướng đi sai, các dự phòng ẩn và các khả năng còn thiếu trong chính sách của nó.

Tính đúng đắn về cấu trúc không tự động chứng minh rằng mọi nhãn quan hệ đều phù hợp với đánh giá của chuyên gia con người. Đánh giá chất lượng mối quan hệ yêu cầu các ví dụ được dán nhãn độc lập và phân tích độ chính xác, thu hồi, định hướng và hiệu chuẩn. Cổng chất lượng ngữ nghĩa đó vẫn là một trách nhiệm riêng biệt.

Ranh giới này cũng ngăn cản mô hình bên ngoài hạ nguồn trở thành cơ quan lý luận. Nó có thể nhận được các mệnh đề được hỗ trợ và các mối quan hệ được định loại cho một nhiệm vụ thực hiện có giới hạn, trong khi bằng chứng, nỗ lực, biểu đồ và tiêu chí chấp nhận vẫn có sẵn độc lập. Sự trôi chảy không nắm giữ lý do khiến tải trọng trở nên hữu ích.
