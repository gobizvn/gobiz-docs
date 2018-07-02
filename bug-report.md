# Làm thế nào để report bug

## Quy định chung về việc report bug trên Taiga

Một bug trên Taiga sẽ được log với các thông tin như sau:

### 1. Tiêu đề bug

Sẽ có dạng Bug: (Môi_trường) Mô tả ngắn về bug

Ví dụ:

- Bug: (Production) Danh sách đơn thiếu cột trạng thái
- Bug: (Dev 1) Không nhập được tên contact là Hoàng Hoàng
- Bug: (Dev 2) Lỗi khi nhập số điện thoại đầu +84

**Lưu ý: không có khoảng trắng giữa chữ Bug và dấu :**

### 2. Nội dung bug

Nội dung bug sẽ bao gồm 3 nội dung như sau:

- **2.1. Các bước để tái hiện bug:** nếu để trống, mặc định hiểu là thao tác theo như kịch bản (scenario) thông thường là luôn bị lỗi không có step đặc thù nào
- **2.2. Kết quả (Results):** kết quả của việc thao tác, tối ưu nhất là có sử dụng hình ảnh chụp màn hình
- **2.3. Kết quả mong muốn (Expected):** kết quả mong muốn, để đối lập với kết quả nhận được, và dev hiểu sẽ phải làm gì hoặc có thể phản biện nếu có

## Bug trong quá trình phát triển

Trong quá trình phát triển, khi test một user-story nếu phát hiện ra bug, người phát hiện bug sẽ report trên Taiga với định dạng như trên. Gobinet sẽ có nhiệm vụ thông báo bug lên trên kênh Dingtalk của team.

## Bug Production

Tạo bug ngoài sprint để xử lý (đang xây dựng quy trình)