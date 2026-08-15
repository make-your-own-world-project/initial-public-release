> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../README.md) | [Tất cả ngôn ngữ](../README.md)

# Cách hệ thống hoạt động cùng nhau

![Hồ sơ được bảo quản hỗ trợ các chuyên gia có thể thay thế và mặt phẳng điều khiển có thể kiểm tra được](../../assets/core-architecture-layers.png)

## Tách biệt trách nhiệm

Nền tảng tách biệt bốn mối quan tâm hợp tác mà không trở thành nhau:

1. **Bảo quản** giữ lại bằng chứng gốc và xuất xứ được quan sát.
2. **Hiểu** thêm các đối tượng ngữ nghĩa được phiên bản, các mối quan hệ, trạng thái thời gian,
  và các giải thích được hỗ trợ.
3. **Truy xuất và tương tác** tập hợp bằng chứng theo yêu cầu cụ thể cho các câu hỏi,
  tìm tòi, trò chuyện.
4. **Tái tạo hiện vật** chuyển đổi một thế giới bằng chứng có giới hạn thành một thế giới được tuyên bố
  sản phẩm cho một người nhận được khai báo.

Hướng dẫn về sản phẩm không bị rò rỉ ngược vào sự thật của kho văn bản. Một chương, khán giả, thể loại, động thái tu từ hoặc ngân sách từ thuộc về một lần rút lui. Nó không phải là một nhãn nội tại trên một tạo phẩm nguồn.

## Cấu trúc liên kết lớp

```text
PRIMARY EVIDENCE
  immutable artifacts, interaction events, source identity, observed arrival
        |
        v
VERSIONED REPRESENTATIONS
  extracted text, media observations, chunks, entities, embeddings, locators
        |
        v
SEMANTIC AND TEMPORAL MAPS
  propositions, discourse links, argument edges, chronology, supersession,
  uncertainty, open attachment points, Personal Meaning Matrix contributions
        |
        +---------------------------+
        |                           |
        v                           v
INTERACTIVE CONTEXT             ARTIFACT CONTRACT
  request-scoped traversal        receiver, purpose, form, budget, evidence rules
        |                           |
        |                           v
        |                       REVERSE EXPANSION
        |                           |
        |                       WHOLE-TREE COLLAPSE
        |                           |
        |                       FORWARD RECONSTRUCTION
        |                           |
        +----------------------> HUMAN PROTOCOL + WEAVE
                                    |
                                INDEPENDENT GATES
                                    |
                              RECEIPT-GATED PRODUCT
```

## Gia nhập không giả vờ biết

Bản ghi đến có thể cho biết các byte cụ thể đã đến hệ thống thông qua một kênh cụ thể. Nó không âm thầm quyết định ai đã tạo ra hiện vật, ai xuất hiện trong đó, chủ đề của nó xuất hiện khi nào, liệu tên tệp có chính xác hay không, tại sao nó lại quan trọng hoặc ai sở hữu nội dung của nó. Đó là những quan sát riêng biệt với bằng chứng và thẩm quyền riêng biệt.

Kiến trúc phân biệt tạo tác ban đầu với các biểu diễn bắt nguồn từ nó. Văn bản được trích xuất, mô tả, phần nhúng, phân loại, tóm tắt và mối quan hệ có thể được tạo lại hoặc thay thế. Họ không thay thế nguồn.

## Đường dẫn tương tác và tài liệu

Câu trả lời tương tác và tạo tác chia sẻ bằng chứng, nguồn gốc, mối quan hệ đã đánh máy, tính không chắc chắn và cơ chế xác nhận. Chúng vẫn khác biệt với cùng một quy trình làm việc.

Một yêu cầu tương tác có thể cần một cuộc trò chuyện hoàn chỉnh, vòng đời nhiệm vụ, duyệt qua mối quan hệ hẹp hoặc làm rõ. Nó không cần phải xây dựng một thùng chứa sách và thu gọn một cây lịch sử trên toàn cầu.

Việc tạo tạo tác cần có sản phẩm, người nhận, ngân sách và kế hoạch toàn bộ tạo tác được khai báo. Nó phải xem cấu trúc tạm thời có liên quan trước khi cắt tỉa và phải tính đến những gì còn sót lại.

## Kiến trúc động chứ không phải là một chuỗi cố định

Dây chuyền lắp ráp được biên soạn cho sản phẩm. Các đầu ra khác nhau có thể sử dụng các chuyên gia khác nhau, sắp xếp các chuyên gia giống nhau theo cách khác nhau hoặc yêu cầu nhiều phiên bản của một khả năng. Người quản lý sử dụng các hợp đồng năng lực và bằng chứng trước đó thay vì chỉ sử dụng nghệ danh được mã hóa cứng.

Các bất biến phổ quát vẫn ổn định trên mọi dòng: nhận dạng nguồn, quyền sở hữu, trạng thái nhận thức, tính không chắc chắn, tính toán tổn thất, chuyển giao đã nhập, quan sát chi phí, xác minh độc lập và khôi phục.

Một mô hình chung bên ngoài có thể chiếm một trạm được đánh máy khi sự đóng góp được đo lường của nó phù hợp với việc chuyển giao. Nó chỉ nhận được tải trọng trong phạm vi yêu cầu mà trạm đó yêu cầu, không nhận được kho dữ liệu được duy trì hoặc quyền hạn được mã hóa bởi mặt phẳng điều khiển rộng hơn. Việc thay thế hoặc loại bỏ trạm đó sẽ giữ nguyên bản ghi lâu dài và khả năng tái thiết trong tương lai. Trạm giới hạn có thể đóng góp mà không cần nhận được kiến ​​thức của con người, nếu không thì một hệ thống tập trung sẽ trở thành giá trị thể chế.
