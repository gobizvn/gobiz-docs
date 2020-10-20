# Change Logs

## [1.12.0] - 18:00 ngày 14/10/2020

### Chức năng mới
- Thêm luồng đề nghị thay đổi mã hóa đơn gốc, giúp nhân viên ngay cả khi đơn đã mua mà không có quyền thay đổi vẫn có thể gửi đề nghị xét duyệt thay đổi mã hóa đơn gốc cho quản lý/kiểm soát (#874)
 
### Cập nhật cải tiến
- Bổ sung bộ lọc tìm KNNB theo số tiền thực đòi (#2603)
- Bổ sung bộ lọc theo tính chất TMĐT/Dễ vỡ trên danh sách đơn (#2604)
- Bổ sung các cột thông tin vào báo cáo doanh số (#2610)
- Một số cải tiến về performance (#2659) (#2238)
- Một số cải tiến nhỏ khác (#2636) (#2722)
- Cập nhật logic để nhận giao dịch alipay trùng mã trên cùng 1 file (#2552)
- Công cụ hỗ trợ mua hàng:
    - bổ sung gửi YCTT theo từng đơn (#2618)
    - cải tiến performance của nút Autopai (#2616) (#2617)

## [1.11.0] - 18:00 ngày 01/10/2020

### Chức năng mới

- Cho phép lấy thông tin KNNB từ các hệ thống taobao, tmall, 1688 (#2510) (#2509)
- Cấu hình chế độ duyệt tự động với các lý do mua chậm (#2322)
- Cho phép tự động khớp giao dịch alipay vào KNNB (#2513)

### Cập nhật cải tiến

- Một số cải tiến về hệ thống nhập liệu thông tin sản phẩm (#2554)
- Bổ sung dịch đơn vị tính tiếng Việt với 1 số trường hợp trước đó lỗi (#2614)
- Fix lỗi biểu tượng nguồn hàng hiển thị không chính xác (#2635)
- Cải thiện performance hệ thống

## [1.10.0] - Ngày 25/09/2020

### Cập nhật cải tiến
- Fix lỗi cấu hình số đơn tối đa nhận & bổ sung cho phép điều chỉnh trạng thái được phép nhận đơn tiếp (#2221)
- Fix một loạt các lỗi nhỏ và cải tiến liên quan đến việc nhập thông tin hải quan (#2367) (#2518)
- Hiển thị tài khoản mua hàng tương ứng nếu ghép được tài khoản alipay khi ĐNTT (#2553)
- Khi thay mã KNNB site gốc, sẽ loại bỏ thông tin KNNB site gốc cũ (#2545)
- Tự động dịch đối với một số thông tin hải quan (#2471)
- Ẩn những đơn không có lý do mua chậm tại giao diện quản lý hiện tại (#2291) 
