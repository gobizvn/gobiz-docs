**Chức năng**: Hỗ trợ quản lý kho theo dõi được tình trạng/ số lượng kiện định kỳ bằng việc đối soát kiện trong kho vật lý với kiện đang có trên hệ thống nhằm kiểm soát thất lạc, sai lệch

Quản lý kho truy cập màn Kiểm kê từ thanh menu bên trái màn hình

![menu kiểm kê](https://user-images.githubusercontent.com/75357871/101117703-27d12680-361a-11eb-8895-060357d20da8.png)

**I. Kiểm kê kiện** 

**Mục đích**: Hỗ trợ kiểm kê, đối soát và xử lý các kiện trong kho theo mã kiện

**Bước 1**: Quản lý kho lựa chọn kho cần kiểm kê trên danh sách kho mình có quyền phụ trách và lựa chọn loại kiểm kê là "Kiểm kê kiện", sau đó chọn "Tạo kiểm kê" để bắt đầu kiểm kê kho

*Lưu ý: Tùy chọn "Không kiểm kê những kiện đã nằm trong bao" và "Không kiểm kê những kiện lô", tùy theo quy trình vận hành của kho, quản lý kho có thể click chọn hoặc bỏ chọn. Nếu quản lý kho click chọn thì khi quét kiểm kê các kiện trong bao hoặc các kiện vận chuyển lô, các kiện này sẽ được coi là kiện thừa"

![tạo kiểm kê](https://user-images.githubusercontent.com/75357871/101118039-e2f9bf80-361a-11eb-9e22-cdfd9da56b1c.png)

**Bước 2**: Quản lý kho thực hiện quét các kiện đang có trong kho để kiểm kê. Sau khi quét xong các kiện trong kho, quản lý kho thực hiện "Đối soát"

![Đối soát](https://user-images.githubusercontent.com/75357871/101119063-16d5e480-361d-11eb-8e07-e5184ab6ed8f.png)

**Bước 3**: Sau khi quản lý kho thực hiện đối soát, hệ thống tự động thống kê các kiện đã quét theo danh sách kiện thừa, danh sách kiện thiếu và danh sách kiện đúng.

- Danh sách kiện thừa: Là các kiện có trong kho vật lý và được quản lý kho quét kiểm kê, nhưng trên hệ thống kiện này không ở trong kho kiểm kê.

- Danh sách kiện thiếu: Là các kiện không có trong kho vật lý nhưng trên hệ thống kiện đó đang ở trong kho kiểm kê.

- Danh sách kiện đúng: Là các kiện đã được quét kiểm kê, kiện có ở cả kho vật lý và trên hệ thống

Quản lý kho kiểm tra danh sách kiện thừa và kiện thiếu, sau đó thực hiện xử lý danh sách kiện thừa (Đánh dấu "Đã xử lý" hoặc chuyển trạng thái kiện thành "Thất lạc") và danh sách kiện thiếu (đánh dấu "Đã xử lý" hoặc "Nhập kho" để nhập kiện vào kho đang kiểm kê) để hoàn thành đối soát

![đối soát kiểm kê](https://user-images.githubusercontent.com/75357871/101119947-0cb4e580-361f-11eb-9329-56f879af90b2.png)


**II. Kiểm kê nhận hàng**

**Mục đích**: Hỗ trợ kiểm kê, đối soát và xử lý các kiện trong kho dựa theo mã vận đơn

**Bước 1**: Quản lý kho lựa chọn kho cần kiểm kê trên danh sách kho mình có quyền phụ trách và lựa chọn loại kiểm kê là "Kiểm kê nhận hàng", sau đó chọn "Tạo kiểm kê" để bắt đầu kiểm kê kho

![tạo kiểm kê vận đơn](https://user-images.githubusercontent.com/75357871/101120095-57cef880-361f-11eb-967f-30327f7a0d14.png)

**Bước 2**: Quản lý kho thực hiện quét mã vận đơn đang có trong kho để kiểm kê. Sau khi quét xong các mã vận đơn trong kho, quản lý kho thực hiện "Đối soát"

![quét vận đơn](https://user-images.githubusercontent.com/75357871/101120208-9bc1fd80-361f-11eb-86c2-05554cb940ed.png)

**Bước 3**: Sau khi quản lý kho thực hiện đối soát, hệ thống tự động thống kê các mã vận đơn đã quét theo danh sách vận đơn thừa, danh sách vận đơn thiếu và danh sách vận đơn đúng.

- Danh sách vận đơn thừa: Là các mã vận đơn có trong kho vật lý và được quản lý kho quét kiểm kê, nhưng trên hệ thống không có kiện nào được tạo từ mã vận đơn này trong kho kiểm kê.

- Danh sách vận đơn thiếu: Là các mã vận đơn không có trong kho vật lý nhưng trên hệ thống có các kiện trong kho kiểm kê được tạo từ mã vận đơn đó.

- Danh sách vận đơn đúng: Là các mã vận đơn đã được quét kiểm kê và mã vận đơn có trên kho vật lý cũng như đã có kiện tại kho kiểm kê được tạo từ mã vận đơn đó trên hệ thống

Quản lý kho kiểm tra danh sách vận đơn thừa và vận đơn thiếu, sau đó thực hiện xử lý danh sách vận đơn thừa (Đánh dấu "Đã xử lý" hoặc chuyển trạng thái các kiện có trạng thái "Kiện về kho" từ mã vận đơn đó thành "Thất lạc") và danh sách vận đơn thiếu (đánh dấu "Đã xử lý") để hoàn thành đối soát

![đối soát vận đơn](https://user-images.githubusercontent.com/75357871/101120784-163f4d00-3621-11eb-9b55-415b0eb4452d.png)
