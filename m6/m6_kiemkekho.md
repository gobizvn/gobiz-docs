**Chức năng**: Hỗ trợ quản lý kho theo dõi được tình trạng/ số lượng kiện định kỳ nhằm kiểm soát thất lạc, sai lệch,... bằng việc đối soát kiện trong kho vật lý với kiện đang có trên hệ thống 

Quản lý kho truy cập màn Kiểm kê từ thanh menu bên trái màn hình

![menu kiểm kê](https://user-images.githubusercontent.com/75357871/101117703-27d12680-361a-11eb-8895-060357d20da8.png)

**I. Kiểm kê kiện** 

**Mục đích**: Quét kiểm kê các kiện trong kho bằng mã kiện sau đó thực hiện đối soát để thống kê được số lượng kiện thừa/ kiện thiếu trong kho.

**Bước 1**: Quản lý kho lựa chọn kho cần kiểm kê trên danh sách kho mình có quyền phụ trách và lựa chọn loại kiểm kê là "Kiểm kê kiện", sau đó chọn "Tạo kiểm kê" để bắt đầu kiểm kê kho

*Lưu ý: Tùy chọn "Không kiểm kê những kiện đã nằm trong bao" và "Không kiểm kê những kiện dùng dịch vụ", tùy theo quy trình vận hành của kho, quản lý kho có thể click chọn hoặc bỏ chọn. 

*Nếu quản lý kho click chọn "Không kiểm kê những kiện đã nằm trong bao", thì với các kiện trong bao có kho vật lý và kho trên hệ thống đều đang ở kho kiểm kê:*

*+ Quét kiện vào kiểm kê: Kiện được quét hiển thị ở danh sách kiện thừa*

*+ Không quét kiện vào kiểm kê: Các kiện trong bao không hiển thị ở danh sách kiện thừa, không hiển thị ở danh sách kiện thiếu*

*Nếu quản lý kho không click chọn "Không kiểm kê những kiện đã nằm trong bao", thì với các kiện trong bao có kho vật lý và kho trên hệ thống đều đang ở kho kiểm kê:*

*+ Quét kiện vào kiểm kê: Kiện được quét hiển thị ở danh sách kiện đúng*

*+ Không quét kiện vào kiểm kê: Các kiện trong bao thuộc kho kiểm kê sẽ hiển thị ở danh sách kiện thiếu*

*Nếu quản lý kho click chọn "Không kiểm kê những kiện dùng dịch vụ" và chọn một hoặc nhiều dịch vụ không kiểm kê, khi kiểm kê, hệ thống kiểm tra dịch vụ của kiện và dịch vụ không kiểm kê như sau:*

*+ Quét mã kiện mà dịch vụ trên kiện đó chứa dịch vụ không kiểm kê: Kiện được quét hiển thị ở danh sách kiện thừa*

*+ Quét mã kiện mà dịch vụ trên kiện không chứa dịch vụ không kiểm kê: Kiện được quét hiển thị ở danh sách kiện đúng*

*+ Không quét mã kiện mà dịch vụ trên kiện đó chứa dịch vụ không kiểm kê: Kiện không hiển thị ở danh sách kiện thừa, không hiển thị ở danh sách kiện thiếu*

*+ Không quét mã kiện mà dịch vụ trên kiện không chứa dịch vụ không kiểm kê: Kiện hiển thị ở danh sách kiện thiếu*

*Nếu quản lý kho không click chọn "Không kiểm kê những kiện dùng dịch vụ" thì khi kiểm kê kiện trong kho không quan tâm đến kiện dùng dịch vụ gì, kiện được quét sẽ ở danh sách kiện đúng, kiện không được quét sẽ ở danh sách kiện thiếu*

![tạo kiểm kê](https://user-images.githubusercontent.com/75357871/101118039-e2f9bf80-361a-11eb-9e22-cdfd9da56b1c.png)

**Bước 2**: Quản lý kho thực hiện quét các kiện đang có trong kho để kiểm kê. Sau khi quét xong các kiện trong kho, quản lý kho thực hiện "Đối soát"

![Đối soát](https://user-images.githubusercontent.com/75357871/101119063-16d5e480-361d-11eb-8e07-e5184ab6ed8f.png)

**Bước 3**: Sau khi quản lý kho thực hiện đối soát, hệ thống tự động thống kê các kiện đã quét theo danh sách kiện thừa, danh sách kiện thiếu và danh sách kiện đúng.

- Danh sách kiện thừa: Là các kiện có trong kho vật lý và được quản lý kho quét kiểm kê, nhưng trên hệ thống kiện này không ở trong kho kiểm kê.

- Danh sách kiện thiếu: Là các kiện không có trong kho vật lý nhưng trên hệ thống kiện đó đang ở trong kho kiểm kê.

- Danh sách kiện đúng: Là các kiện đã được quét kiểm kê, kiện có ở cả kho vật lý và trên hệ thống

Quản lý kho kiểm tra danh sách kiện thừa và kiện thiếu, sau đó thực hiện xử lý danh sách kiện thiếu/ kiện thừa như sau:

- Click "Đã xử lý" kiện thiếu: Khi đã tìm thấy kiện tại kho hoặc kiện đã được tìm thấy tại kho khác và có phương án xử lý với kiện

- Xử lý Thất lạc với kiện thiếu: Khi không tìm thấy kiện

- Xử lý Nhập kho kiện thừa: Nhập kiện thừa vào kho hiện tại

- Click "Đã xử lý" kiện thừa: Có phương án xử lý khác với kiện thừa (VD: chuyển về kho đúng của kiện, lưu kho...) và nhập lý do xử lý

![đối soát kiểm kê](https://user-images.githubusercontent.com/75357871/101119947-0cb4e580-361f-11eb-9329-56f879af90b2.png)


**II. Kiểm kê nhận hàng**

**Mục đích**: Hỗ trợ kiểm kê, đối soát và xử lý các kiện trong kho dựa theo mã vận đơn

**Bước 1**: Quản lý kho lựa chọn kho cần kiểm kê trên danh sách kho mình có quyền phụ trách và lựa chọn loại kiểm kê là "Kiểm kê nhận hàng", sau đó chọn "Tạo kiểm kê" để bắt đầu kiểm kê kho

![tạo kiểm kê vận đơn](https://user-images.githubusercontent.com/75357871/101120095-57cef880-361f-11eb-967f-30327f7a0d14.png)

**Bước 2**: Quản lý kho thực hiện quét mã vận đơn đang có trong kho để kiểm kê. Sau khi quét xong các mã vận đơn trong kho, quản lý kho thực hiện "Đối soát"

![quét vận đơn](https://user-images.githubusercontent.com/75357871/101120208-9bc1fd80-361f-11eb-86c2-05554cb940ed.png)

**Bước 3**: Sau khi quản lý kho thực hiện đối soát, hệ thống tự động thống kê các mã vận đơn đã quét theo danh sách vận đơn thừa, danh sách vận đơn thiếu và danh sách vận đơn đúng. Hệ thống hiển thị mã vận đơn và danh sách kiện được tạo từ mã vận đơn đó.

- Danh sách vận đơn thừa: Là các mã vận đơn có trong kho vật lý và được quản lý kho quét kiểm kê, nhưng trên hệ thống không có kiện nào được tạo từ mã vận đơn này trong kho kiểm kê.

- Danh sách vận đơn thiếu: Là các mã vận đơn không có trong kho vật lý nhưng trên hệ thống có các kiện trong kho kiểm kê được tạo từ mã vận đơn đó.

- Danh sách vận đơn đúng: Là các mã vận đơn đã được quét kiểm kê và mã vận đơn có trên kho vật lý cũng như đã có kiện tại kho kiểm kê được tạo từ mã vận đơn đó trên hệ thống

Quản lý kho kiểm tra danh sách vận đơn thừa và vận đơn thiếu, sau đó thực hiện xử lý danh sách vận đơn thiếu/ kiện thừa như sau:

- Click "Đã xử lý" vận đơn thiếu: Khi đã tìm thấy kiện của mã vận đơn tại kho hoặc kiện đã được tìm thấy tại kho khác và có phương án xử lý với kiện

- Xử lý Thất lạc với vận đơn thiếu: Khi không tìm thấy kiện của mã vận đơn đó

- Xử lý Nhập kho vận đơn thừa: Nhập kiện thừa thuộc mã vận đơn đó vào kho hiện tại

- Click "Đã xử lý" vận đơn thừa: Có phương án xử lý khác với kiện thừa của mã vận đơn đó như: chuyển về kho đúng của kiện, lưu kho...

![đối soát vận đơn](https://user-images.githubusercontent.com/75357871/101120784-163f4d00-3621-11eb-9b55-415b0eb4452d.png)
