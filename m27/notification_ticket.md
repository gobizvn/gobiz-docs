# Nhận thông báo khi ticket qua Dingtalk đối

**Mục đích**: Ngay cả khi đang không ở trong hệ thống nhưng ticket lại có cập nhật  (bình luận mới, được thêm Người xử lý, Chuyển trạng thái) thì người tạo, người theo dõi ticket, người được gán là Người xử lý ticket rất có nhu cầu nắm được các nội dung này. Vì vậy chức năng này cho phép người dùng nhập số điện thoại để có thể nhận được thông báo của ticket tại ứng dụng Dingtalk nếu có nhu cầu. 

**Bước 1**: Tại màn hình cấu hình cá nhân, người dùng nhập thông tin số điện thoại (trùng với số điện thoại đã đăng ký trên Dingtalk)

<img width="279" alt="Screen Shot 2020-11-14 at 09 50 36" src="https://user-images.githubusercontent.com/73808891/99137660-e246bc80-265e-11eb-9aa1-9c28d9715e57.png">

<img width="876" alt="Screen Shot 2020-11-14 at 09 49 51" src="https://user-images.githubusercontent.com/73808891/99137645-c6dbb180-265e-11eb-992d-515f07488424.png">

**Bước2:** Người dùng truy cập vào **Quản lý dự án**, chọn dự án mà mình muốn nhận thông báo liên quan đến các ticket của dự án đó sau đó bấm biểu tương logo Dingtalk để kết nối tới Dingtalk hoặc bấm **"kết nối tất cả"** để thực hiện kết nối tất cả các dự án đến Dingtalk

<img width="1440" alt="Screen Shot 2020-12-08 at 15 17 32" src="https://user-images.githubusercontent.com/73808891/101459529-f08cad80-396a-11eb-892f-525cf3802196.png">

<img width="912" alt="Screen Shot 2020-12-08 at 15 29 56" src="https://user-images.githubusercontent.com/73808891/101459476-deab0a80-396a-11eb-922d-eb44411529bd.png">

**Bước3:** 

*Các đối tượng nhận được thông báo* 

- Người dùng là người tạo ticket
- Người dùng được gán là "Người xử lý" ticket
- Người dùng bấm theo dõi ticket

<img width="645" alt="Screen Shot 2020-11-14 at 09 55 11" src="https://user-images.githubusercontent.com/73808891/99137938-9cd6bf00-265f-11eb-999e-ff485a9f560e.png">

Lưu ý: Các đối tượng này nếu cũng chính là người thực hiện thao tác chuyển trạng thái/cập nhật người xử lý thì sẽ không nhận thông báo liên quan đến thao tác đó nữa.

*Các trường hợp nhận được thông báo* 

- Ticket có nội dung bình luận mới
- Ticket cập nhật trường "Người xử lý" ticket
- Ticket được chuyển trạng thái

*Các trường hợp không nhận được thông báo* 

- Dự án chưa thực hiện cấu hình kết nối tới Dingtalk --> liên hệ Owner dự án
- Số điện thoại nhập không phải là số điện thoại đã đăng ký trên Dingtalk


