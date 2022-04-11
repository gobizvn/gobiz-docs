# Giao hàng 

## 1. Khách tạo yêu cầu giao hàng

### 1.1. Danh sách yêu cầu giao
- Hàng về Việt Nam, khách chủ động tạo yêu cầu giao hàng, nhân viên kho truy cập **Menu** => **Yêu cầu giao** => **Danh sách yêu cầu giao**

![Menu](https://user-images.githubusercontent.com/73226975/162739814-02012d9e-8279-4953-a0f4-1206a9ff0c6d.png)

**Danh sách yêu cầu giao gồm các thông tin:**
- Bộ lọc, tìm kiếm thông tin yêu cầu giao
- Phần danh sách có 4 tab:
- Mới
- Đang xử lý
- Đã xử lý
- Huỷ

![DS yêu cầu giao](https://user-images.githubusercontent.com/73226975/162741682-b5d50c2a-a31e-495b-957d-3a825d76e2d0.png)

- Danh sách phiếu xuất tại tab **Mới** sẽ hiển thị theo mốc thời gian Cũ -> Mới. Các yêu cầu giao quá hạn xử lý sẽ chuyển sang màu đỏ.

![DS yêu cầu giao](https://user-images.githubusercontent.com/73226975/162742114-46e03299-9e89-4db7-be70-3ddbcd415b97.png)

(1) - Xem chi tiết mã yêu cầu giao

(2) - Tạo phiếu xuất hàng cho khách

(3) - Chuyển trạng thái **Đã xử lý** hoặc **Hủy** yêu cầu giao

![Tạo phiếu xuất](https://user-images.githubusercontent.com/73226975/162743365-c4b48b4f-5cf7-4ffe-8e7e-5ad3b1c04c6a.png)

### 1.2. Tạo phiếu xuất từ danh sách yêu cầu giao

- Tại màn hình Danh sách yêu cầu giao mới, Quý khách lựa chọn xử lý **Tạo phiếu xuất** cho từng mã yêu cầu giao khác nhau.

![Tạo phiếu](https://user-images.githubusercontent.com/73226975/162748754-17af417e-95d7-4eec-a463-0a4496c15a0b.png)

- Hệ thống sẽ chuyển hướng sang giao diện **Tạo phiếu xuất hàng**

Bước 1: Chọn kho và đối tượng **khách hàng** để tạo phiếu xuất

Bước 2: Chọn Kiện/Bao để thêm vào phiếu xuất cho đối tượng đã chọn

Bước 3: Quét mã vạch kiện hàng/bao hàng 

![Tạo phiếu](https://user-images.githubusercontent.com/73226975/162750083-6d5ca260-2c79-48a8-b8fb-46ea65036601.png)

Bước 4: ấn **Lưu** sẽ tiến hành tạo ra phiếu xuất. Nếu ấn **Tạo mới** sẽ quay lại màn hình chọn khách hàng để tạo phiếu

![Quét mã kiện](https://user-images.githubusercontent.com/73226975/162760575-469845a8-7edc-40dd-b164-d5e333c96df7.png)

Bước 5: Kiểm tra thông tin trước khi xuất phiếu

![Phiếu xuất](https://user-images.githubusercontent.com/73226975/162761016-a6575d67-35db-4a42-9d5d-75828e5c232b.png)

![Phiếu xuất](https://user-images.githubusercontent.com/73226975/162761182-be9141cd-0a4b-4561-9b7d-ba26856e8d67.png)

Bước 6: In phiếu xuất, đính kèm hàng hóa khi giao tới khách

![Phiếu xuất](https://user-images.githubusercontent.com/73226975/162761260-f6d5ed90-c183-4166-bf72-2eacb565a71a.png)

![Phiếu xuất](https://user-images.githubusercontent.com/73226975/162761723-ddf0f8a4-9530-4ff6-89a6-c9582224896c.png)

### 1.3. Chức năng liên quan

### Các khách đang yêu cầu giao hàng (YCG) 
- Danh sách các mã yêu cầu giao hàng chưa được xử lý

### Thông tin khách hàng của phiếu xuất bao gồm
1. Tên khách hàng
2. Số dư ví của khách
3. Thông tin người nhận (mặc định sẽ là tên khách hàng)
4. Phí vận chuyển giao hàng nội địa Việt Nam
5. Phần âm tài chính: chính là số dư của khách < 0đ
6. COD: là giao hàng rồi mới thu tiền. Công thức tính phí COD trên phiếu xuất = Tiền phí vận chuyển nội địa VN + Phần âm tài chính
**Ví dụ:** 
Phí vận chuyển: 30.000đ
Phần âm tài chính: -100.000đ. 
Công thức tính COD = 30.000 + 100.000 = 130.000đ
7. Đối tác vận chuyển: Quý khách có thể lựa chọn gửi hàng thông qua các đối tác giao hàng nội địa tại VN như GHTK, GHN, Snappy...

8. Kích thước kiện hàng: Dài x rộng x Cao

10. Ghi chú thêm khi giao hàng

11. Số điện thoại & Địa chỉ người nhận: Tính năng chỉ áp dụng cho trường hợp nếu thông tin người nhận khác với thông tin mặc định trên hệ thống.
### Danh sách có thể giao
- Danh sách các kiện hàng hiện tại đang nằm trong kho 

### Danh sách sẵn sàng giao
- Khi nhân viên kho quét mã vạch tại **Bước 3**, những kiện vừa được quét sẽ không còn xuất hiện tại mục **Danh sách có thể giao** và chuyển sang mục **Danh sách sẵn sàng giao**

## 2. Kho tạo phiếu xuất hàng
- Quý khách truy cập **Menu** => **Xuất kho** => **Tạo phiếu xuất khách hàng**

![Menu](https://user-images.githubusercontent.com/73226975/162762909-32eb5a12-10ab-4279-812d-04157b049066.png)

- Bước 1: Chọn kho và đối tượng **khách hàng** để tạo phiếu xuất

- Bước 2: Chọn Kiện/Bao để thêm vào phiếu xuất cho đối tượng đã chọn

- Bước 3: Nhập mã khách hàng, Username hoặc tên khách hàng

![Phiếu xuất](https://user-images.githubusercontent.com/73226975/162763650-6a82521f-45a6-403f-93f9-f5b69405b6d8.png)

- Các bước còn lại thao tác tương tự như hướng dẫn tại mục [1.2. Tạo phiếu xuất từ danh sách yêu cầu giao](https://hd.gobiz.vn/m6/hang-thuong/van-hanh-kho-phan-phoi/m6_yeucaugiao#1.2.-tao-phieu-xuat-tu-danh-sach-yeu-cau-giao)
