
# HƯỚNG DẪN SỬ DỤNG GO TICKET

## 1. Giới thiệu chung

  Go ticket là phần mềm được ra đời để hỗ trợ cho việc  quản lý, phân công công việc trong tổ chức được vận hành một cách hiệu quả. Dưới góc nhìn của các nhà quản lý, Go ticket là chìa khoá giúp cho việc tổ chức, phân công, quản lý tiến độ của team trở lên minh bạch, công khai và rõ ràng. Dưới góc nhìn cá nhân, Go ticket giúp người dùng tiếp nhận/ đánh giá những nhiệm vụ cần hoàn thành. Điểm nổi bật của Go ticket so với các phần mềm tương tự trên thị trường đó là giao diện đơn giản, dễ dùng, các chức năng đánh đúng trọng tâm nhu cầu của người dùng.
  
## 2. Giao diện chung và các Thanh chức năng

Hệ thống Go ticket gồm 2 thanh Menu:

Menu ngang phía trên để người dùng truy cập vào Quản lý dự án/Tạo mới dự án.

<img width="1440" alt="Screen Shot 2020-11-03 at 10 40 12" src="https://user-images.githubusercontent.com/73808891/97950037-24067600-1dc8-11eb-947f-18d7dbab0883.png">

MEnu dọc để người dùng truy cập vào các chức năng trong 1 dự án. Người dùng sử dụng nút  <img width="82" alt="Screen Shot 2020-11-03 at 11 34 49" src="https://user-images.githubusercontent.com/73808891/97950198-b9096f00-1dc8-11eb-8116-521637356b8e.png">  để xem Menu dọc dạng đầy đủ, và bấm nút **X** để trở về Menu rút gọn.

<img width="241" alt="Screen Shot 2020-11-03 at 11 34 38" src="https://user-images.githubusercontent.com/73808891/97950277-f40ba280-1dc8-11eb-8df9-4e29d3b56d6e.png">

## 3. Đăng nhập và đăng xuất khỏi hệ thống 
### 3.1. Đăng nhập
Để truy cập và sử dụng các chức năng của hệ thống, người dùng cần thực hiện đăng nhập vào hệ thống. Việc thực hiện đăng nhập này được hiểu như một sự định danh, toàn bộ các thao tác trên hệ thống được ghi nhận dưới tài khoản đã đăng nhập.

**Bước 1**: Truy cập vào trình duyệt và đi tới địa chỉ: https://ticket.gobiz.vn/

**Bước 2**: Nhập chính xác **Tên đăng nhập** và **Mật khẩu** đã đăng ký sau đó bấm nút “Sign in" để hệ thống kiểm tra. Trường hợp chưa đăng ký tài khoản, người dùng bấm nút "**Register**" để thực hiện đăng ký tài khoản trước khi đăng nhập vào hệ thống.

<img width="494" alt="Screen Shot 2020-11-03 at 11 40 02" src="https://user-images.githubusercontent.com/73808891/97950470-8ad85f00-1dc9-11eb-81c8-89d89f7b7eff.png">

**Lưu ý**: Trường hợp người dùng được mời vào 1 dự án đã có, hệ thống sẽ gửi email cho người dùng và người dùng tiến hành truy cập vào hệ thống theo đường link được gửi qua email.

<img width="946" alt="Screen Shot 2020-11-03 at 14 47 25" src="https://user-images.githubusercontent.com/73808891/97961111-3fcc4500-1de5-11eb-8897-6374511bfb76.png">

**Các tình huống không đăng nhập thành công:**

- Nhập tên đăng nhập không có trên hệ thống

- Nhập mật khẩu sai

### 3.2 Đăng xuất khỏi hệ thống 

Khi muốn thoát khỏi tài khoản, người dùng thực hiện thao tác chọn nút "Đăng xuất"  ở Thông tin tài khoản và chọn “Đăng xuất” để thoát khỏi tài khoản. Sau khi đăng xuất thành công, hệ thống hiển thị ra màn hình Đăng nhập, sẵn sàng cho người dùng đăng nhập ở các lần tiếp theo. 

## 4. Tình huống sử dụng: Tạo 1 dự án mới trên hệ thống 

**_Cách 1: Tạo mới dự án từ Menu_**

**Bước 1**: Người dùng bấm vào biểu tượng tại menu ngang, chọn "Tạo mới dự án"

<img width="263" alt="Screen Shot 2020-11-03 at 11 43 05" src="https://user-images.githubusercontent.com/73808891/97950548-cffc9100-1dc9-11eb-89be-93b7412b86fc.png">

**Bước 2**: Hệ thống hiển thị giao diện cho phép người dùng nhập các thông tin của dự án, trong đó 2 trường thông tin "**Tên dự án**" và "**Loại dự án**" là bắt buộc nhập. Dự án được tạo mới sẽ hiển thị trong mục "**Quản lý dự án**"

<img width="686" alt="Screen Shot 2020-11-03 at 11 46 02" src="https://user-images.githubusercontent.com/73808891/97950666-3ed9ea00-1dca-11eb-9ef2-9476307199e8.png">

**_Cách 2: Tạo mới dự án khi đang ở màn hình Quản lý dự án_**

Trường hợp người dùng đang ở màn hình Quản lý dự án, người dùng cũng có thể tạo mới dự án bằng cách bấm vào nút "**tạo mới dự án**". Người dùng nhập các thông tin cần tạo như đã mô tả ở Cách 1.

**Các tình huống tạo dự án thất bại:**

- Không nhập các trường thông tin có dấu * (bắt buộc nhập)

- Ảnh đại diện không phải định dạng ảnh, dung lượng quá 5MB

## 5. Tình huống sử dụng: Xem danh sách dự án trên hệ thống

**Bước 1**: Người dùng bấm vào biểu tượng tại menu ngang, chọn "**Quản lý dự án**"

<img width="263" alt="Screen Shot 2020-11-03 at 11 43 05" src="https://user-images.githubusercontent.com/73808891/97950548-cffc9100-1dc9-11eb-89be-93b7412b86fc.png">

**Bước 2**: Tại mục Quản lý dự án, hệ thống mặc định hiển thị danh sách "**Dự án của tôi**" - Các dự án mà người dùng đang là thành viên của dự án. Hệ thống mặc định sắp xếp theo thời gian người dùng được thêm là thành viên của dự án. Người dùng có thể tự sắp xếp lại danh sách bằng cách kéo thả các bản ghi theo thứ tự mình mong muốn. 

<img width="1436" alt="Screen Shot 2020-11-03 at 13 50 28" src="https://user-images.githubusercontent.com/73808891/97956580-99c80d00-1ddb-11eb-9735-e407acb86fb9.png">


Ngi ra người dùng cũng có thể xem Danh sách dự án Public (những dự án cho phép người dùng không là thành viên vẫn có quyền xem với vai trò của Khách) bằng cách bấm chọn sang **Dự án Public**

<img width="783" alt="Screen Shot 2020-11-03 at 13 53 20" src="https://user-images.githubusercontent.com/73808891/97956724-02af8500-1ddc-11eb-81a9-f3ef0617ec23.png">

## 6. Tình huống sử dụng: Thêm thành viên cho dự án

**Bước 1**: Tại **Quản lý dự án**, chọn Project muốn truy cập. Tại Meu dọc, truy cập **Quản lý thành viên**

<img width="239" alt="Screen Shot 2020-11-03 at 14 26 39" src="https://user-images.githubusercontent.com/73808891/97959688-76ed2700-1de2-11eb-92ac-9eac6f4cbdfb.png">

**Bước 2**: Hệ thống hiển thị ra Danh sách các thành viên hiện tại của dự án. Cho phép mời thêm thành viên cho dự án bằng cách nhập Email. Hệ thống sẽ gửi thư mời tới email được nhập.  

<img width="1197" alt="Screen Shot 2020-11-03 at 14 28 21" src="https://user-images.githubusercontent.com/73808891/97961104-3cd15480-1de5-11eb-89b0-4b63f5754f30.png">



## 7. Tình huống sử dụng: Xem danh sách các ticket của dự án

**Bước 1**: Tại màn hình Quản lý dự án, người dùng bấm chọn vào Logo/Tên dự án mà mình muốn truy cập.
**Bước 2**: Hệ thống điều hướng đến màn hình Danh sách ticket của dự án 

- Tại đây hệ thống hỗ trợ các bộ lọc để người dùng có thể tìm kiếm các ticket 1 cách nhanh chóng. Bấm "**Tìm kiếm**" để hệ thống tìm kiếm theo bộ lọc mà người dùng đã thiết lập và "**Huỷ bỏ**" để xoá bộ lọc.

<img width="1304" alt="Screen Shot 2020-11-03 at 13 59 15" src="https://user-images.githubusercontent.com/73808891/97957063-cd576700-1ddc-11eb-8d6e-3dac3ae39077.png">


- Hệ thống cũng hỗ trợ lọc sẵn các ticket theo Trạng thái và mục Ticket của tôi cho phép xem các ticket mà người dùng là người tạo ticket.

<img width="241" alt="Screen Shot 2020-11-03 at 14 01 26" src="https://user-images.githubusercontent.com/73808891/97957307-625a6000-1ddd-11eb-94e9-6664dfe0ed55.png">

- Người dùng có thể sắp xếp lại các cột trong danh sách bằng cách bấm vào biểu tượng <img width="40" alt="Screen Shot 2020-11-03 at 14 06 43" src="https://user-images.githubusercontent.com/73808891/97957456-d09f2280-1ddd-11eb-9c57-0b53cf0636f2.png">

## 8. Tình huống sử dụng: Tạo mới ticket của dự án

**Bước 1**: Tại màn hình **Danh sách ticket**, người dùng bấm chọn nút "**Thêm mới ticket**" 

<img width="1313" alt="Screen Shot 2020-11-03 at 14 16 03" src="https://user-images.githubusercontent.com/73808891/97958119-2d4f0d00-1ddf-11eb-852c-8c2eb505c82f.png">

**Bước 2**: Hệ thống hiển thị giao diện để người dùng nhập các thông tin cần thiết để tạo ticket. Yêu cầu bắt buộc nhập **Tiêu đề** và **Loại ticket**

<img width="651" alt="Screen Shot 2020-11-03 at 14 17 03" src="https://user-images.githubusercontent.com/73808891/97958231-5f606f00-1ddf-11eb-8c96-57a1d47a882a.png">

**Bước 3**: Người dùng nhập các thông tin của ticket, bấm  "**Thêm mới**" để tạo thêm 1 ticket. Ticket được tạo mới sẽ hiển thị trong Danh sách ticket theo thứ tự Mới trước cũ sau. Bấm "**Huỷ bỏ**" để xoá các dữ liệu đã nhập. Bấm X để tắt màn hình tạo mới ticket.

**Các tình huống tạo mới ticket thất bại:**

- Không nhập các trường thông tin có dấu * (bắt buộc nhập)

- Đính kèm file quá dung lượng

## 9. Tình huống sử dụng: Xem chi tiết ticket và cập nhật ticket

**Bước 1**: Tại màn hình **Danh sách ticket**, người dùng bấm tiêu đề của từng bản ghi để xem chi tiết ticket. 

<img width="1061" alt="Screen Shot 2020-11-03 at 15 10 28" src="https://user-images.githubusercontent.com/73808891/97961938-bf0e4880-1de6-11eb-8cea-75d6901d4b0c.png">

**Bước2:** Hệ thống hiển thị ra chi tiết ticket. Cho phép người dùng cập nhật các trường thông tin của ticket bằng cách bấm vào dòng muốn cập nhật, nhập nội dung --> enter

Các trường thông tin cố định hệ  không cho phép cập nhật: Mã ticket, Người tạo, Ngày tạo 

<img width="584" alt="Screen Shot 2020-11-03 at 15 14 13" src="https://user-images.githubusercontent.com/73808891/97962263-55426e80-1de7-11eb-95e3-1da0fd744e8e.png">

