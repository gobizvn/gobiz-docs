**Mục đích:** Hỗ trợ tính toán doanh số cho giao dịch viên (GDV) và giúp phát hiện được các trường hợp sai phạm liên quan đến giao dịch nhà cung cấp

**Bước 1:** Giao dịch viên truy cập trang **Kiểm soát đơn hàng** từ menu bên trái màn hình.

![Kiểm soát đơn hàng](https://user-images.githubusercontent.com/76998374/105332814-976d9600-5c07-11eb-8968-d4975eb224fa.png)

**Bước 2:** Sau khi upload file alipay thành công, các giao dịch sẽ map về đơn dựa trên mã hóa đơn gốc. Giao dịch viên kiểm tra được lợi nhuận mặc cả trên đơn tại trang **Kiểm soát giao dịch nhà cung cấp**

![Kiểm soát giao dịch nhà cung cấp](https://user-images.githubusercontent.com/76998374/105333497-617ce180-5c08-11eb-94ba-57917abb870b.png)

**Công thức tính lợi nhuận mặc cả đơn dựa trên giao dịch nhà cung cấp:**

**Đơn ở trạng thái HỦY/HẾT HÀNG:**


Lợi nhuận mặc cả =  tổng giao dịch alipay (thu - chi)


**Đơn ở trạng thái **khác** HỦY/HẾT HÀNG:**


Lợi nhuận mặc cả =  (tiền hàng + vận chuyển nội địa) - tổng giao dịch alipay chi (chi - thu)

![Lợi nhuận mặc cả](https://user-images.githubusercontent.com/76998374/105334752-d1d83280-5c09-11eb-83a6-27b8e725c645.png)


**Bước 3:** Xác định các vấn đề của đơn

- Chưa có giao dịch NCC: gồm những đơn có trạng thái từ Đã Mua trở đi nhưng chưa có giao dịch nhà cung cấp nào

- Lợi nhuận quá cao: khi tỉ lệ lợi nhuận đơn được tính tính theo công thức mà vượt quá ngưỡng người dùng cấu hình thì hiển thị cảnh báo này

- Lợi nhuận âm: khi giá vốn nhỏ hơn tổng tiền chi cho NCC thì lợi nhuận âm

- Đơn Hủy nhưng có giao dịch thu chi không khớp: khi đơn ở trạng thái Hủy/Hết hàng nhưng có (tổng thu - chi) khác 0


![Các vấn đề của đơn](https://user-images.githubusercontent.com/76998374/105335820-187a5c80-5c0b-11eb-9956-17416eeec57c.png)

**Bước 4** Xử lý đơn có vấn đề

Trên từng đơn nếu có vấn đề sẽ hiển thị cảnh báo đỏ như **Bước 3**, để xử lý các vấn đề của đơn thì giao dịch viên click chọn vào nút **Resolve** 

![Resolve đơn có vấn đề](https://user-images.githubusercontent.com/76998374/105336468-dbfb3080-5c0b-11eb-9fc1-ff81b9b53aaf.png)

Khi giao dịch viên click vào nút **Resolve** sẽ hiển thị popup để nhập lý do đánh dấu đã xử lý đơn có vấn đề. Trường lý do này không bắt buộc nhập

![Nhập lý do resolve](https://user-images.githubusercontent.com/76998374/105336866-4dd37a00-5c0c-11eb-9e69-5fcbcb99ab82.png)

Sau khi resolve đơn có vấn đề thành công sẽ ghi nhận log bao gồm các thông tin: Người xử lý, thời gian xử lý, lý do (nếu có)

![Nhập lý do resolve](https://user-images.githubusercontent.com/76998374/105336866-4dd37a00-5c0c-11eb-9e69-5fcbcb99ab82.png)








