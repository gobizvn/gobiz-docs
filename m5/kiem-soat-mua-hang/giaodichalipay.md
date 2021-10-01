# Kiểm soát giao dịch alipay

**Bước 1:** **KSCLDV kiểm tra thông tin giao dịch alipay**

Từ menu **Kiểm soát mua hàng**, nhân viên KSCLDV chọn mục **Kiểm soát giao dịch** để truy cập vào trang **Danh sách giao dịch alipay**

![Ki&#x1EC3;m so&#xE1;t giao d&#x1ECB;ch](https://user-images.githubusercontent.com/76998374/105815675-e0e22a80-5fe5-11eb-9b4c-17c2f1c8d918.png)

Sau khi kế toán upload file giao dịch alipay thành công lên hệ thống thì tất cả giao dịch sẽ hiển thị ở màn hình danh sách giao dịch alipay.

Mỗi giao dịch alipay bao gồm các thông tin:

* Tài khoản giao dịch
* Mã giao dịch
* Số tiền giao dịch
* Thời gian GD
* Mã đơn hàng
* Loại GD
* Nhà cung cấp
* Mã GD nhà cung cấp
* Thời gian tạo trên hệ thống
* Thời gian xử lý
* File CSV
* Giao dịch liên quan
* Tài khoản liên quan

![Danh s&#xE1;ch giao d&#x1ECB;ch alipay](https://user-images.githubusercontent.com/76998374/105813563-9d39f180-5fe2-11eb-849e-6a3367210dab.png)

**Bước 2** **Thêm/xóa MHĐG khỏi giao dịch**

Tại trang danh sách giao dịch alipay, KSCLDV có thể thêm/xóa MHĐG trên giao dịch.

* Nếu nhập MHĐG tồn tại trên đơn thì giao dịch sẽ map với đơn và giao dịch alipay hiển thị ở chi tiết đơn
* Nếu nhập MHĐG không tồn tại trên đơn thì giao dịch chưa khớp được đơn và không hiển thị ở chi tiết đơn

**Thêm MHĐG vào giao dịch**

![Th&#xEA;m MH&#x110;G v&#xE0;o GD](https://user-images.githubusercontent.com/76998374/105818085-09b7ef00-5fe9-11eb-87ab-46ec04e39e44.png)

**Xóa MHĐG khỏi GD:** Click vào icon bút chì bên cạnh MHĐG, sau đó chọn xóa trên MHĐG cần xóa

![X&#xF3;a MH&#x110;G](https://user-images.githubusercontent.com/76998374/105818481-9367bc80-5fe9-11eb-87e3-e24a8792f215.png)

![X&#xF3;a MH&#x110;G kh&#x1ECF;i GD](https://user-images.githubusercontent.com/76998374/105818670-c5791e80-5fe9-11eb-97d0-da2d35edf952.png)

**Bước 3:** **Kiểm soát giao dịch bất thường**

Các giao dịch được đánh dấu bất thường bao gồm:

* Giao dịch khớp được MHĐG
* Giao dịch có MHĐG nhưng không thấy trên hệ thống
* Giao dịch chi thanh toán hộ chưa khớp giao dịch liên quan
* Giao dịch chi thanh toán hộ có số tiền không khớp
* Khác \(các trường hợp bất thường khác không bao gồm các TH kể trên\)

**Resolve giao dịch bất thường**

Với những giao dịch bất thường chưa xử lý thì có thể đánh dấu là Resolved \(đã xử lý\) với lý do đánh dấu là bắt buộc nhập.

Có 2 màn hình để thực hiện Resolve giao dịch đó là: Màn hình danh sách giao dịch và chi tiết giao dịch alipay.

Tại danh sách giao dịch alipay, nhân viên click vào nút \[Resolve\] bên cạnh cảnh báo bất thường của giao dịch.

![Resolve giao d&#x1ECB;ch](https://user-images.githubusercontent.com/76998374/105819641-0291e080-5feb-11eb-8c6c-6c741e7aadc4.png)

Nhập lý do đánh dấu giao dịch đã xử lý và click chọn \[Resolve\] để đánh dấu là đã xử lý giao dịch bất thường

![&#x110;&#xE1;nh d&#x1EA5;u &#x111;&#xE3; x&#x1EED; l&#xFD; GD b&#x1EA5;t th&#x1B0;&#x1EDD;ng](https://user-images.githubusercontent.com/76998374/105819724-20f7dc00-5feb-11eb-9ea2-d1b765712927.png)

Hiển thị thông báo Resolve giao dịch thành công và giao dịch được đánh dấu là đã xử lý

![Resolve giao d&#x1ECB;ch](https://user-images.githubusercontent.com/76998374/105819871-5bfa0f80-5feb-11eb-8d48-de4bf3f2084c.png)

**Unresolve giao dịch**

Với những giao dịch bất thường đã xử lý thì được phép Unrelove giao dịch bằng cách click vào nút \[Unresolve\] trên GD được đánh dấu là đã xử lý

![Unresolve GD](https://user-images.githubusercontent.com/76998374/105820269-efcbdb80-5feb-11eb-9cb8-83597e015c39.png)

Khi click vào nút \[Unresolve\] sẽ có thông báo confirm. Nếu chọn \[OK\] thì giao dịch sẽ Unresolve thành công và giao dịch trở thành GD bất thường chưa xử lý

![Confirm Unresolve GD](https://user-images.githubusercontent.com/76998374/105820565-49cca100-5fec-11eb-8f14-5b006a688dc3.png)

**Bước 4:** **Xem chi tiết giao dịch alipay**

Từ trang danh sách GD alipay, nhân viên truy cập trang chi tiết giao dịch bằng cách click vào icon bên cạnh mã giao dịch

![Chi ti&#x1EBF;t giao d&#x1ECB;ch](https://user-images.githubusercontent.com/76998374/105820835-a8921a80-5fec-11eb-8982-ba49396258e4.png)

![Chi ti&#x1EBF;t giao d&#x1ECB;ch](https://user-images.githubusercontent.com/76998374/105821052-f9097800-5fec-11eb-84bd-9fb7171f5649.png)

Chi tiết giao dịch hiển thị đầy đủ các thông tin của giao dịch. Ngoài ra,còn có thêm thông tin:

* Log hành động GD
* Cho phép ghi chú trên GD
* Download file alipay chứa GD

![Chi ti&#x1EBF;t GD](https://user-images.githubusercontent.com/76998374/105821740-c318c380-5fed-11eb-9b02-433fb5c2dfe5.png)

