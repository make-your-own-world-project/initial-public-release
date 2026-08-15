> Tiếng Việt: Bản dịch có sự hỗ trợ của máy từ nguồn tiếng Anh có thẩm quyền. Việc chỉnh sửa bằng ngôn ngữ bản địa đều được chào đón. [Tiếng Anh](../../README.md) | [Tất cả ngôn ngữ](../README.md)

# Ngôn ngữ được chia sẻ

![Các khái niệm định kỳ về kiến ​​trúc được sắp xếp xung quanh một kho lưu trữ cục bộ nguyên vẹn](../../assets/architecture-glossary.png)

**Thành phần**: Bất kỳ sản phẩm đầu vào hoặc sản phẩm được tạo ra nào được bảo tồn.

**Ký gửi**: Một hiện vật được đưa vào kho văn bản có thẩm quyền. Sự tồn tại của nó có giá trị ngay cả khi chưa biết lý do hay mối quan hệ nào.

**Rút tiền**: Một sản phẩm được truy xuất hoặc tạo ra có giới hạn được tạo ra từ các khoản tiền gửi được chọn và các quan sát dẫn xuất. Nó không bao giờ thay thế nguồn của nó.

**Biểu diễn**: Một chế độ xem phái sinh chẳng hạn như văn bản được trích xuất, mô tả phương tiện, nhúng, đơn vị ngữ nghĩa hoặc phân loại.

**Sự kiện quan sát**: Bằng chứng cho thấy quan điểm, phản ứng, câu hỏi hoặc báo cáo đã xảy ra. Nó khác biệt với sự thật của bất kỳ mệnh đề nào bên trong nó.

**Vai trò nhận thức**: Trạng thái của nội dung dưới dạng quan sát, khẳng định, diễn giải, giả thuyết, ẩn dụ, cảm giác, câu hỏi, kế hoạch, thất bại, sửa chữa, trích dẫn hoặc chưa biết.

**Bản đồ thời gian**: Lớp quan hệ được phiên bản phía trên kho văn bản, bao gồm lịch sử quan sát, tính hợp lệ và phiên thay thế.

**Ma trận ý nghĩa cá nhân**: Một phép chiếu đa chiều, trong phạm vi yêu cầu về những đóng góp và sự không chắc chắn có ý nghĩa ràng buộc nguồn. Đó không phải là một hình mẫu cá tính.

**Đi bộ ngược**: Đi từ mục tiêu có nhiều ngữ cảnh tới bằng chứng liên quan trước đó mà không chỉ định cấu trúc sản phẩm cuối cùng.

**Tái tạo chuyển tiếp**: Đảo ngược trên cùng một biểu đồ đã chọn để giải thích hành trình theo thứ tự mà con người có thể giải mã được.

**Thu gọn**: Phân vùng mất mát rõ ràng, dành riêng cho sản phẩm của các nhánh biểu đồ đã chọn theo các công việc ngữ nghĩa và tu từ.

**Cog hoặc chuyên gia**: Thành phần giới hạn có đầu vào, đầu ra, giới hạn, chi phí và quyền được khai báo.

**Dây chuyền lắp ráp**: Sự sắp xếp dành riêng cho sản phẩm của các chuyên gia được sử dụng để thực hiện rút tiền.

**Bàn giao**: Tải trọng đã đánh máy và chuyển giao trách nhiệm giữa các chuyên gia.

**Mô hình làm việc nhỏ gọn**: Bằng chứng di động, lý luận, yêu cầu sản phẩm và bộ điều khiển mở rộng được tập hợp cho một đầu ra. Nó không phải là một mô hình chung được đào tạo.

**Sổ cái khối lượng công việc**: Bản ghi kiểm tra về những gì từng giai đoạn đã nhận được, tạo ra, bỏ sót, chi phí và đóng góp.

**Giao thức con người**: Ranh giới hai chiều để điều chỉnh cấu trúc do máy tổ chức cho phù hợp với trạng thái giao tiếp cụ thể của con người mà không yêu cầu quyền truy cập vào hoạt động triển khai nội bộ của người đó.

**Dệt**: Quỹ đạo được đo lường và sự cân bằng của các chức năng phân phối trên một sản phẩm.

**Độ kín**: Tham số tỷ lệ hoặc mật độ được áp dụng cho kiểu dệt mà không xác định lại công việc phân phối của nó.

**Căn cứ**: Yêu cầu rằng đóng góp được tạo ra vẫn có thể truy nguyên được bằng chứng được ủy quyền hoặc được phân loại rõ ràng là diễn giải, không chắc chắn hoặc vắng mặt.

**Cổng biên nhận**: Xác minh độc lập yêu cầu giữ lại các bất biến cho các byte tạo tác chính xác. Chỉ riêng việc thoát khỏi quy trình không phải là sự chấp nhận.

**Sự thay thế**: Một quan sát sau này thay thế cách diễn giải trước đó để sử dụng sau này mà không xóa trạng thái lịch sử trước đó.

**Chủ quyền cá nhân**: Ranh giới quyền sở hữu và quyền hạn xung quanh trải nghiệm, danh tính, sự chú ý, biểu hiện và khả năng xác định ý nghĩa của một người.

**Đóng góp bên ngoài có giới hạn**: Chuyển giao được ủy quyền, theo yêu cầu cụ thể trong đó chuyên gia bên ngoài chỉ nhận được tải trọng cần thiết cho một hoạt động đã khai báo. Tải trọng có thể hữu ích nhưng vẫn không đủ để tái tạo lại kho dữ liệu được duy trì, nguồn gốc, lịch sử thời gian, ý nghĩa cá nhân hoặc máy móc tạo ra các khoản rút tiền trong tương lai. Ranh giới này ngăn cản sự đóng góp hạn hẹp trở thành việc khai thác và giảm thiểu mang tính hủy diệt kiến ​​thức của con người thành giá trị thể chế.
