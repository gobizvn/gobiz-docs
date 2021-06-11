# Danh sách đơn hàng
- Tại Menu "Đơn hàng" hệ thống hiển thị danh sách đơn hàng sắp xếp theo Ngày tạo từ mới đến cũ, hỗ trợ các bộ lọc và tìm kiếm
- Người dùng có thể lọc bộ lọc và chọn "Xuất file excel" để xuất danh sách các đơn hàng tương ứng theo bộ lọc ra file

![image](https://user-images.githubusercontent.com/73808891/121623991-e58e1380-ca9a-11eb-9d71-73ed415da354.png)


# Tạo mới đơn hàng trong hệ thống

**Bước 1:** Đơn hàng từ hệ thống Fobiz, khi đảm bảo 2 yếu tố sau sẽ tự động đồng bộ sang hệ thống M28
  - Mã vendor trên M28 trùng khớp Mã vendor trên fobiz
  - Mã sku trên M28 đã được cấu hình tại mục "Đồng bộ sản phẩm" để map được với mã fobiz tương ứng.

Ngoài ra hệ thống cũng cho phép user có thể tạo mới đơn hàng trong hệ thống bằng file excel hoặc tạo trên giao diện

1. Import đơn hàng bằng file excel: tại danh sách đơn  hàng, click chọn "Import đơn hàng", kéo file vào vùng tải file lên. Lưu ý: khi xuất danh sách đơn hàng từ Fobiz, người dùng sử dụng button "Export to M28" 
![image](https://user-images.githubusercontent.com/73808891/121623322-ab704200-ca99-11eb-9a6b-8d9994083cc8.png)

2. Tạo đơn hàng trên giao diện: Người dùng click button "Tạo đơn hàng mới" và nhập các thông tin của đơn hàng. Các trường (*) là bắt buộc nhập.

**Bước 2**: Đơn hàng sau khi được tạo trên hệ thống --> hệ thống sẽ tự động chọn Kho xuất hàng dựa theo thông tin Kho và vị trí kho của Vendor còn tồn sản phẩm (Luôn ưu tiên lấy hàng từ kho chính trước). Với đơn hàng tự động chọn được kho xuất sẽ có trạng thái 'Chờ nhập Mã vận đơn". Tồn tạm tính của sản phẩm sẽ được trừ đi ở bước này.

Trường hợp sản phẩm hết hàng hoặc không đủ tồn, hệ thống sẽ dừng ở bước 'Chờ chọn kho xuất" để người dùng cập nhật sau.
![image](https://user-images.githubusercontent.com/73808891/121623588-2d606b00-ca9a-11eb-87c4-61fd29d5aa65.png)

**Bước 3:** Với các đơn ở trạng thái "Chờ nhập mã vận đơn", người dùng click button "Import mã vận đơn" để cập nhật Mã vận đơn cho các đơn hàng (thông tin Mã VĐ lấy từ đơn vị vận chuyển). Tại file excel, người dùng nhập thông tin Mã đơn hàng, Mã vận đơn để hệ thống cập nhật Mã vận đơn cho đơn hàng.
Đơn hàng sau khi có thông tin 'mã vận đơn" sẽ dừng ở trạng thái "Chờ giao hàng".


![image](https://user-images.githubusercontent.com/73808891/111563519-aff2ca80-87ca-11eb-8a9f-ca1321cbc281.png)

**Bước 3:**: Cập nhật trạng thái đơn hàng.

Các đơn hàng khi ở trạng thái "Chờ giao hàng", để cập nhật trạng thái sang "Đang giao hàng", "Đã giao hàng" hoặc "Đã huỷ", người dùng chọn chức năng 
"Import trạng thái".
Lưu ý: với các đơn hàng muốn chuyển sang trạng thái Huỷ cần nhập thông tin tái nhập đơn. Muốn nhập lại sản phẩm vào Vị trí kho và Kho trên đơn hàng hay muốn nhập sang kho trung gian khác, user cần nhập thông tin này theo sheet "tái nhập" trong file excel





