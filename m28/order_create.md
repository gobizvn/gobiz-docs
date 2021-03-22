# Tạo mới đơn hàng trong hệ thống

**Bước 1:** Để tạo mới đơn hàng trong hệ thống, hệ thống hỗ trợ người dùng 2 cách tạo mới bao gồm:  tạo mới bằng giao diện trên hệ thống và nhập file excel. Người dùng nhập các thông tin của đơn hàng

![image](https://user-images.githubusercontent.com/73808891/111562306-8e90df00-87c8-11eb-9331-89c27e2272e9.png)


**Bước 2:** Chọn kho xuất cho đơn

Đơn hàng sau khi được tạo sẽ ở trạng thái **Chờ chọn kho xuất**, người dùng Click vào đơn hàng - Tab Thông tin cho xuất chọn thông tin Kho, Vị trí kho theo Seller, Số lượng xuất hàng. Sau khi hoàn thành việc nhập thông tin, bấm "Xác nhận kho xuất". Đơn hàng chuyển sang trạng thái **Chờ đóng gói**

![image](https://user-images.githubusercontent.com/73808891/111563519-aff2ca80-87ca-11eb-8a9f-ca1321cbc281.png)

**Bước 3:**: Đóng gói kiện cho đơn hàng 

Người dùng thực hiện đóng gói kiện hàng bằng cách click vào "Đóng gói và chọn ĐVVC" và nhập các thông tin đóng gói

![image](https://user-images.githubusercontent.com/73808891/111563650-ecbec180-87ca-11eb-8d76-f99557eb24cb.png)

![image](https://user-images.githubusercontent.com/73808891/111565025-488a4a00-87cd-11eb-96db-3775c541f379.png)

**Bước 4:**: Nhập thông tin kho Đích cho kiện

Kiện được đóng gói sẽ có trạng thái "Khởi tạo: Người dùng truy cập hệ thống M6: để theo dõi quá trình kiện được đóng bao và vận chuyển của kiện và bao
- Link truy cập hệ thống M6: 
Thị trường Thái Lan: ubox_th.logistics.mygobiz.net
Thị trường Indonesia: ubox_id.logistics.mygobiz.net
Thị trường Philippines: ubox_ph.logistics.mygobiz.net

- Truy cập Menu "Kiện hàng - Danh sách kiện hàng", Click vào Mã kiện cần cập nhật --> "Sửa kiện" --> cập nhật **Kho đích** cho kiện

![image](https://user-images.githubusercontent.com/73808891/111741256-c5462280-88b8-11eb-995b-cd182b4cb03c.png)

**Bước 5**: Đóng bao

Người dùng truy cập Menu Bao hàng - Tạo bao hàng, nhập các thông tin của bao, lưu và đóng bao
![image](https://user-images.githubusercontent.com/73808891/111724490-ed715980-8897-11eb-88fe-244a18928ac0.png)

**Bước 6:** Quét kiện vào bao

Sau khi tạo bao, người dùng quét kiện vào Bao bằng cách nhập mã kiện --> enter và nhập cân nặng kiện trên giao diện

![image](https://user-images.githubusercontent.com/73808891/111744192-68993680-88bd-11eb-88d4-1109bcf9681e.png)

**Bước 7:** Quét kiện nhập vào Kho xuất

Người dùng quét kiện nhập kho xuất để xác nhận kiện đang ở trong Kho xuất bằng cách truy cập Menu Vận hành - Quét mã vạch, chọn hành động "Nhập", chọn kho là kho xuất, nhập mã kiện và Enter. Sau khi quét trạng thái kiện sẽ được cập nhật thành Kiện về kho

![image](https://user-images.githubusercontent.com/73808891/111745679-89628b80-88bf-11eb-992e-6552ebdee92b.png)

![image](https://user-images.githubusercontent.com/73808891/111745910-dd6d7000-88bf-11eb-8263-51fb33cee4bd.png)

**Bước 8:** Quét bao xuất khỏi kho xuất (khi bao rời kho xuất và bắt đầu VCQT)

Khi muốn xuất bao khỏi kho Xuất để vận chuyển quốc tế, người dùng thực hiện thao tác Quét mã vạch, chọn hành động "Xuất", cho kho là kho xuất, nhập mã bao và Enter. Lúc này kiện sẽ được cập nhật trạng thái là Đang vận chuyển quốc tế

**Bước 9:** Quét kiện nhập vào kho đích (khi bao đến kho Đích)

Thời điểm kiện đến kho đích, người dùng thực hiện việc quét mã vạch nhập vào kho đích (tương tự bước 7,8), trạng thái của kiện chuyển sang "Chờ giao"
![image](https://user-images.githubusercontent.com/73808891/111751001-85863780-88c6-11eb-9fea-4a3a87e5a47e.png)

**Bước 10:** Quét kiện xuất khỏi kho đích (khi kiện xuất kho đích để thực hiện giao hàng đến tay người nhận)

Thời điểm kiện xuất khỏi kho đích người dùng thực hiện việc quét mã vạch xuất khỏi vào kho đích, trạng thái kiện chuyển sang "Đang giao".

**Bước 11:** Cập nhật trạng thái kiện sang "Đã nhận" khi kiện đã giao thành công cho người nhận

Click "Sửa kiện" tại bản ghi kiện hàng muốn cập nhật
Chọn Trạng thái --> "Đã nhận"
![image](https://user-images.githubusercontent.com/73808891/111932040-25bea500-8aef-11eb-8662-c1b39ebd24af.png)

**Lưu ý:** Các trạng thái của kiện trên M6 sẽ được hiển thị tương ứng trên hệ thống Quản lý kho.

# Danh sách đơn hàng
- Tại Menu "Đơn hàng" hệ thống hiển thị danh sách đơn hàng sắp xếp theo Ngày tạo từ mới đến cũ, hỗ trợ các bộ lọc và tìm kiếm
- Người dùng có thể lọc bộ lọc và chọn "Xuất file excel" để xuất danh sách các đơn hàng tương ứng theo bộ lọc ra file
![image](https://user-images.githubusercontent.com/73808891/111932241-9b2a7580-8aef-11eb-94ac-73b3a5cd799e.png)



