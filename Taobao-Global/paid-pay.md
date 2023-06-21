# 2.1 Xử lý đơn 

**Mục đích:** Chức năng này cho phép quản lý tập trung tất cả các đơn hàng, hỗ trợ các bộ lọc để tìm kiếm đơn một cách dễ dàng, xem chi tiết thông tin đơn hàng và cập nhật các thông tin liên quan đến đơn.

**Giao dịch viên(GDV) tiến hành xử lý đơn hàng như sau:**

**Bước 1:** GDV click vào Đơn hàng cần xử lý

![Danh sách đơn đang mua](https://github.com/gobizvn/gobiz-docs/assets/135328227/f1c4b866-eb5b-4d9b-b733-167b0d1a01e0)

**Bước 2:** GDV cập nhật các trường thông tin của đơn hàng
GDV cập nhật thông tin như: tài khoản mua hàng Taobao Global đã kết nối, điều chỉnh tỷ lệ đặt cọc, chỉnh sửa giá,…

![Thông tin chi tiết đơn](https://github.com/gobizvn/gobiz-docs/assets/135328227/4dbee03f-065b-4094-b135-d85abb922286)

**Bước 3:** Đặt đơn

-	GDV click Tạo đơn Taobao Global để tự động đặt đơn trên tài khoản Taobao Global
  
![Tạo đơn Taobao Global](https://github.com/gobizvn/gobiz-docs/assets/135328227/f85b22e0-0de7-462c-b1bb-d1120f88c800)

- Tiếp đó hệ thống sẽ hiển thị thông báo **Tạo đơn hàng thành công**.

![Tạo đơn thành công](https://github.com/gobizvn/gobiz-docs/assets/135328227/f18f406a-76f5-4d61-89c9-ec71dab74e40)

**Bước 4:** GDV click Đã Pai để chuyển trạng thái cho đơn hàng

![Đã Pai](https://github.com/gobizvn/gobiz-docs/assets/121548042/f56f390a-efaa-4fae-b452-1eb99dbe51be)

- Sau khi chuyển Đã pai hệ thống sẽ tự động cập nhật mã hoá đơn gốc, phí vận chuyển nội địa, trường hợp đơn hàng miễn phí nội địa hệ thống sẽ để trống mục này GDV sẽ tự click chọn miễn phí.
- GDV cập nhật các thông tin còn lại như: nhóm ngành hàng(nếu có) và dịch vụ.

![Pai hàng thành công](https://github.com/gobizvn/gobiz-docs/assets/121548042/d128eab5-d39c-4d06-9081-2a1e8dc5bca3)

- Khi GDV ấn Tạo đơn TBDN nếu đơn hàng có sản phẩm hết hàng hoặc thiếu hàng thì khi GD hệ thống sẽ hiển thị thông báo, GDV click vào Cập nhật số lượng theo site gốc, sau đó GDV có thể tiếp tục Tạo đơn TBDN như thông thường.

![Cập nhật số lượng](https://github.com/gobizvn/gobiz-docs/assets/121548042/ad6ceb04-6084-46f3-8e39-505c90f33d9a)

# 2.2 Tìm kiếm đơn hàng và liên hệ với nhà cung cấp trên Taobao Global

## 2.2.1.	Tìm kiếm đơn hàng trên Taobao Global

- Tìm kiếm bằng Mã đơn hàng taobao **淘宝订单编号**

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/02fa5152-b6c8-40b4-822c-52df9662186d)

- Giao dịch viên tìm bằng Mã đơn Taobao Global **采购单**

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/7f01d309-51d8-49bf-8d58-ccff47d70c3a)


Các bước Tìm kiếm bằng Mã đơn Taobao Global **采购单** cũng tương tự như tìm kiếm bằng Mã đơn hàng taobao **淘宝订单编号**, Giao dịch viên chỉ cần thay Mã đơn hàng taobao **淘宝订单编号** bằng Mã đơn Tobao Global **采购单**

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/7b64500f-8b3a-4d14-a418-91f49e753361)

## 2.2.2.	Liên hệ với nhà cung cấp

- GDV click vào biểu tượng chat **联系商家**， ngay lập tức sẽ hiện ra cửa sổ chat web để GDV trao đổi với Nhà cung cấp
**Lưu ý:** Phần mở chat vui lòng liên hệ DVKH Gobiz để được hỗ trợ.
  
![](https://github.com/gobizvn/gobiz-docs/assets/135328227/2909896b-9429-4bcb-95f1-c2d3d69f3b15)

## 2.3.	Thanh toán
### 2.3.1. Thanh toán bằng gửi YCTT trực tiếp trên đơn (áp dụng khi gửi 1 đơn riêng lẻ)
**Bước 1:** Trước khi gửi YCTT GDV kiểm tra lại thông tin đơn hàng như phí vận chuyển nội địa,  mã hoá đơn, số tiền trên đơn phải lớn số tiền thực thanh toán, dịch vụ,…
**Lưu ý:** Mã hoá đơn trên đơn hàng phải đúng với mã hoá đơn site gốc trên Taobao Global mới có thể gửi được YCTT.
Sau khi kiểm tra xong GDV click vào Tạo YCTT đơn Taobao Global

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/09216041-8e69-42cd-b2d6-3dfadc1d9934)

**Bước 2:** GDV click tiếp Tạo YCTT đơn Taobao Global để hoàn tất YCTT, sau đó hệ thống sẽ hiển thị thông báo *Tạo YCTT thành công*. Đơn hàng sẽ tự động chuyển trạng thái từ **Đã pai** sang **Đã mua**, GDV có thể F5 lại trang để kiểm tra.

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/98b6a8be-7c08-4f1e-8857-aa97bbf347e4)

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/466bd394-ffa9-473f-b50d-ea88c04fa91c)

**Bước 3:** GDV tiến hành kiểm tra lại đơn hàng trên Taobao Global, nếu đơn hàng hiển thị trạng thái 待发货 tức là đơn hàng đã được thanh toán thành công.

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/00c79d8b-aea7-447f-bb16-3fe22282b846)

### 2.3.2. Thanh toán gộp nhiều đơn trên Danh sách đơn đang mua
**Bước 1:** Tại trang Danh sách đơn đang mua mục Đã pai, GDV chọn các đơn hàng cần gửi thanh toán gộp. (Tối đa được chọn 10 đơn)

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/2af1278d-e205-4e2d-b9fc-4c73ee926938)

**Bước 2:** GDV click chọn Tạo YCTT đơn Taobao Global.

**Bước 3:** GDV click tiếp Tạo YCTT đơn Taobao Global để hoàn tất gửi YCTT, sau đó hệ thống sẽ hiển thị thông báo *Tạo YCTT thành công* và tự động chuyển trạng thái sang **Đã mua**.

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/7f72b9af-f9e1-4d80-af8f-02b44941ad3d)

![](https://github.com/gobizvn/gobiz-docs/assets/135328227/e30184ac-e733-4796-ba68-47cb9a23a16d)

**Lưu ý:** sau khi gửi YCTT thành công GDV bỏ tích các đơn đã chọn mới có thể gửi thanh toán gộp được các đơn sau.

**Bước 4:** GDV tiến hành kiểm tra lại đơn hàng trên Taobao Global, nếu đơn hàng hiển thị trạng thái **待发货** tức là đơn hàng đã được thanh toán thành công.













  

  

















  




 







===========================================================

✅ Gobiz - Phần mềm Quản lý nhập hàng & Logistics cho các đơn vị đa quốc gia.

📌 Đăng ký dùng thử: https://bit.ly/gobiz-tuvan

📞 Hotline: 0388.432.436

🌐 Website: https://gobiz.vn/
