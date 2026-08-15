> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../README.md) | [Tất cả ngôn ngữ](../README.md)

# Cái gì là thật và cái gì còn lại

![Ý tưởng, thử nghiệm, thất bại và khả năng được xác minh vượt qua các cổng triển khai riêng biệt](../../assets/evidence-implementation-gates.png)

## Lớp bằng chứng

Mô hình bằng chứng giữ cho một số lớp khác biệt:

- **bằng chứng chính:** hiện vật nguồn được bảo tồn và các sự kiện tương tác;
- **bằng chứng dẫn xuất:** văn bản được trích xuất, đơn vị ngữ nghĩa, mối quan hệ, phân loại,
  quan sát thời gian và các biểu diễn phiên bản khác;
- **bằng chứng thực thi:** biểu hiện, quan sát cuộc gọi, chi phí, nhận dạng mô hình và
  kết quả giai đoạn;
- **bằng chứng chấp nhận:** các bất biến độc lập, biên lai, gói được quảng cáo và
  băm đầu ra chính xác;
- **mục đích thiết kế:** kiến ​​trúc và hành vi theo kế hoạch chưa được chứng minh trong quá trình thực thi;
- **tuyên bố lịch sử:** nội dung mà bản phát hành hoặc thử nghiệm trước đó đã báo cáo về chính nó.

Việc vượt qua bài kiểm tra chỉ là bằng chứng cho phần vỏ mà nó thực hiện. Tài liệu phát hành không phải là bằng chứng cho thấy thời gian chạy hiện tại vẫn khớp với nó. Thư viện đã cài đặt không phải là khả năng được triển khai.

## Cơ sở đã triển khai

Việc thực hiện đã thể hiện được những căn cứ ràng buộc sau:

- bảo quản nguồn theo địa chỉ nội dung và xử lý bằng chứng theo định hướng bổ sung;
- các tạo phẩm, biểu diễn, bộ định vị và sự kiện nguồn riêng biệt;
- các sự kiện hội thoại theo trình tự và tác nhân;
- xử lý trước diễn ngôn và cốt lõi với các lát nguồn giới hạn;
- phân loại quan hệ đối số với các khoảng nguồn chính xác và các lần thử được giữ lại;
- một biểu đồ mệnh đề và quan hệ được đánh máy;
- phép chiếu phụ thuộc xác định;
- đóng góp vào Ma trận Ý nghĩa Cá nhân trong phạm vi yêu cầu với sự không chắc chắn và
  cờ bảo vệ;
- lựa chọn lùi và các đối tượng phát lại chuyển tiếp cùng đồ thị trong các thử nghiệm giới hạn;
- phân bổ đơn vị ngữ nghĩa thuộc sở hữu toàn cầu và lập kế hoạch tạo tác xen kẽ;
- sàn kết xuất được nối đất và so sánh ứng viên tùy chọn;
- khuyến mãi có kiểm soát độc lập;
- công việc tạo tác bền bỉ và một người xem lý trí;
- ranh giới xuất bản tài liệu công cộng với các bản phát hành có địa chỉ nội dung.

Những tuyên bố này mô tả các ranh giới thành phần đã được chứng minh chứ không phải tuyên bố rằng toàn bộ tầm nhìn đã hoàn thiện.

Sự so sánh được chứng minh cũng ghi lại ranh giới răng cưa bên ngoài. Một mô hình biên giới đã nhận được tải trọng được chuẩn bị sẵn, theo yêu cầu cụ thể và đóng góp một kết xuất bóng bẩy hơn mà không nhận được kho dữ liệu được duy trì hoặc trở thành cơ quan phát hành. Bằng chứng ủng hộ giao dịch bị ràng buộc đó; nó không thiết lập những gì bất kỳ nhà cung cấp nào giữ lại bên ngoài đường dẫn tạo tác đã được thử nghiệm, đây vẫn là một câu hỏi về quyền riêng tư và hợp đồng riêng biệt. Nó chứng minh rằng sự đóng góp hữu ích không yêu cầu chuyển hồ sơ con người để giảm thiểu tác hại thành giá trị thuộc sở hữu của nhà cung cấp.

## Quy mô nền tảng được cài đặt

Kiểm kê hệ thống tệp giới hạn của cây ứng dụng đã cài đặt đếm được khoảng 566.000 tệp và 218 GiB. Nội dung mô hình chiếm khoảng 172 GiB, phần phụ thuộc và thời gian chạy ngôn ngữ chiếm 25 GiB, trạng thái dữ liệu và các nội dung khác chiếm 20 GiB và nguồn triển khai chiếm khoảng 184 MiB. Kiểm kê gặp phải một số mục không thể đọc được hoặc thay đổi, vì vậy đây là những ước tính quy mô hoạt động chứ không phải là hóa đơn nguyên vật liệu phần mềm.

Sự bất đối xứng là bằng chứng có chủ ý về kiến ​​trúc. Mã nguồn là một phần nhỏ của dấu chân được cài đặt; trọng lượng mô hình và thời gian chạy có thể tái sử dụng chiếm ưu thế. Do đó, mặt phẳng điều khiển theo dõi giá trị, quyền hạn và chi phí vận hành của từng chuyên gia thay vì coi kích thước cài đặt là khả năng. Bản phát hành mã có thể phân phối trong tương lai cần có kho lưu trữ phụ thuộc dành riêng cho tạo phẩm, phiên bản chính xác, giấy phép, hàm băm và ranh giới bản dựng có thể tái tạo.

## Bài học kỹ thuật được bảo tồn bởi thiết kế

Sự phát triển đã tạo ra một số bài học kỹ thuật bền vững:

- nhắc mô hình chung để mô phỏng một chuyên gia còn thiếu;
- coi việc thoát khỏi quy trình hoặc bảng kê khai tự báo cáo là bằng chứng về năng lực;
- điều hành diễn ngôn sau khi phân loại ngữ nghĩa và sao chép công việc chuyên môn;
- chỉ định lần xuất hiện trích dẫn lặp lại đầu tiên làm xuất xứ;
- cho phép một mục bằng chứng toàn bộ hồ sơ làm cho thành phần không thể xác minh được;
- coi các mối quan hệ không được chấp nhận là lỗi đường ống;
- nhầm lẫn giữa phép chiếu đồ thị xác định với một chuyên gia được thực hiện riêng biệt;
- khớp với một cấu hình dệt trong khi tạo ra văn xuôi không được hỗ trợ hoặc không thể đọc được;
- gỡ lỗi bằng cách chạy toàn bộ kho văn bản khi các trường hợp vừa và nhỏ bộc lộ lỗi;
- điều chỉnh một sản phẩm theo cách có thể làm thoái lui một sản phẩm khác.

Kiến trúc công cộng giữ lại những chỉnh sửa này vì chúng giải thích mục đích của các ràng buộc hiện tại và làm cho việc sàng lọc trong tương lai trở nên đáng tin cậy hơn.

## Cơ hội phát triển hiện tại

Một số khả năng chính vẫn chưa đầy đủ hoặc cần có bằng chứng rộng hơn:

- nhãn quan hệ cần đánh giá chất lượng chuyên gia độc lập, không chỉ cấu trúc
  xác nhận;
- liên kết tạm thời ký gửi chéo và phân bổ lại cần tiếp tục thử nghiệm ở mức lớn hơn
  ranh giới nguồn hỗn hợp;
- trình điều khiển cá nhân cấp cao phải không được phổ biến cho đến khi có bằng chứng ràng buộc về nguồn và
  hành vi của ống kính biện minh cho chúng;
- các loại sản phẩm khác nhau cần dây chuyền lắp ráp được hiệu chuẩn, bảo vệ hồi quy;
- Phản hồi về Giao thức của Con người cần bằng chứng về kết quả theo chiều dọc;
- cơ chế tượng hình và tường thuật yêu cầu đánh giá nhận thức về sản phẩm trước khi
  quyền được cấp;
- tài liệu công khai đầy đủ yêu cầu tiếp tục xem xét biên tập như hồ sơ riêng tư
  phát triển.

## Thang xác thực

Tiến trình phát triển từ nhỏ đến lớn:

1. lược đồ thuần túy và đồ đạc bất biến;
2. ví dụ ngữ nghĩa ngắn với cấu trúc liên kết đã biết;
3. lát nguồn thực nhỏ;
4. lát cắt định dạng hỗn hợp và thời gian hỗn hợp trung bình;
5. ranh giới khả năng mở rộng lớn hơn sau khi vượt qua các cấp độ trước đó;
6. so sánh do con người tạo ra và do hệ thống tạo ra dưới cùng một bằng chứng,
  người nhận, hình thức và ngân sách.

Việc so sánh chẩn đoán liệu tổn thất có đến từ việc lựa chọn biểu đồ, phân bổ tầm quan trọng, phát lại chuyển tiếp, hiện thực hóa hay khả năng đọc cuối cùng hay không thay vì gán mọi lỗi cho “chất lượng mô hình” chung chung.
