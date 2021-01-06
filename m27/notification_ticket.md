# Nhận thông báo liên quan ticket qua Dingtalk/chatbot Dingtalk

**Mục đích**: Ngay cả khi đang không ở trong hệ thống nhưng ticket lại có cập nhật  (bình luận mới, được thêm Người xử lý, Chuyển trạng thái) thì người tạo, người theo dõi ticket, người được gán là Người xử lý ticket rất có nhu cầu nắm được các nội dung này. Vì vậy chức năng này cho phép người dùng thực hiện kết nối dự án với Dingtalk để nhận thông báo tại Dingtalk và Chatbot Dingtalk

**Bước 1:** Tại Menu ngang người dùng truy cập Cấu hình cá nhận và nhập thông tin Số điện thoại, yêu cầu số điện thoại này phải trùng với số điện thoại đăng ký trên Dingtalk

<img width="246" alt="Screen Shot 2020-12-08 at 16 14 59" src="https://user-images.githubusercontent.com/73808891/101463890-968ee680-3970-11eb-98e9-f8a3954882c5.png">

<img width="885" alt="Screen Shot 2020-12-08 at 16 15 18" src="https://user-images.githubusercontent.com/73808891/101463899-97c01380-3970-11eb-932e-bc936bd47c4a.png">

**Bước 2:** Người dùng truy cập vào **Quản lý dự án**, chọn dự án mà mình muốn nhận thông báo đó sau đó bấm biểu tương logo Dingtalk để kết nối tới talk theo từng dự án. Hoặc bấm **"Kết nối tất cả"** để kết nối toàn bộ các dự án hiện tại với Dingtalk

<img width="972" alt="Screen Shot 2020-12-08 at 16 17 40" src="https://user-images.githubusercontent.com/73808891/101464261-01402200-3971-11eb-9166-7e85a4c9e08d.png">


*Các đối tượng nhận được thông báo* 

- Người dùng là người tạo ticket
- Người dùng được gán là "Người xử lý" ticket
- Người dùng bấm theo dõi ticket


Lưu ý: Các đối tượng này nếu cũng chính là người thực hiện thao tác chuyển trạng thái/cập nhật người xử lý thì sẽ không nhận thông báo liên quan đến thao tác đó nữa.
Tuỳ theo Owner của dự án Cấu hình kết nối Dingtalk hay Chatbot Dingtalk mà user sẽ nhận được thông báo qua phương tiện tương ứng

*Các trường hợp nhận được thông báo* 

- Ticket có nội dung bình luận mới
- Ticket cập nhật trường "Người xử lý" ticket
- Ticket được chuyển trạng thái

*Các trường hợp không nhận được thông báo* 

- Dự án chưa thực hiện cấu hình kết nối tới Dingtalk --> liên hệ Owner dự án
- Số điện thoại trong Cấu hình cá nhân không phải số điện thoại đã đăng ký trên Dingtalk --> liên hệ Owner dự án



