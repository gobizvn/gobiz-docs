# KHIẾU NẠI NGƯỜI BÁN
## Bước 1:Tạo khiếu nại người bán 
(Hệ thống cho phép tạo KNNB cho đơn từ trạng thái **Đã Mua** trở đi và đơn ở trạng thái **Hủy** hoặc **Hết Hàng**) 

**Lưu ý**:
     - Người dùng có thể cài đặt **Tạo khiếu nại người bán tự động** với đơn trong mục **[Cấu hình](https://hd.gobiz.vn/m5/cauhinhnangcao)** đối với đơn lâu chưa phát hàng, lâu chưa nhận hàng, đã nhận hàng nhưng chưa có kiện.   
     - 
Có thể bấm nút **Tạo khiếu nại người bán**(KNNB) từ:

  - Màn hình **Chi tiết đơn**
  
![image](https://user-images.githubusercontent.com/75475064/104262053-5c59bd00-54b9-11eb-80ec-689900976c6d.png)

  - Màn hình **Quản lý đơn hàng**
  
![image](https://user-images.githubusercontent.com/75475064/101886935-caffde00-3bce-11eb-925b-53af342e652a.png)

  - Màn hình **Kiểm soát giao dịch Nhà cung cấp**

![image](https://user-images.githubusercontent.com/75475064/101887064-f4b90500-3bce-11eb-9f88-03e7bbece1a9.png)

  - Màn hình **Danh sách khiếu nại người bán**
  
![image](https://user-images.githubusercontent.com/75475064/101886822-9c820300-3bce-11eb-8d2c-648fccec3eb8.png)



## Bước 2: Điền trường thông tin bắt buộc
  
  Điền những trường thông tin bắt buộc và chọn **[Thực hiện]**
  
  **Lưu ý:** Chỉ được tạo một lần đối với KNNB có cùng lý do và ở trạng thái **Đang xử lý**
 
 ![image](https://user-images.githubusercontent.com/75475064/101887687-ca1b7c00-3bcf-11eb-9588-fef7da1f58d4.png)



## Bước 3: Xử lý khiếu nại người bán

  * Sau khi điền đầy đủ thông tin và bấm **Thực hiện**, hệ thống sẽ tự chuyển hướng sang màn **Chi tiết khiếu nại người bán** 
  
  * Hoặc người dùng vào **Danh sách khiếu nại người bán** > chọn mục **Chưa tiếp nhận** > chọn **Chi tiết** để xem chi tiết khiếu nại

![image](https://user-images.githubusercontent.com/75475064/101887975-2bdbe600-3bd0-11eb-95d1-c98316a14c2d.png)

![image](https://user-images.githubusercontent.com/75475064/101981188-9b6bd700-3c9d-11eb-89ef-a8a9cdb3df22.png)

  * Chọn **Tiếp nhận** > KNNB sẽ chuyển trạng thái sang **Đang xử lý**
 
![image](https://user-images.githubusercontent.com/75475064/101892134-96435500-3bd5-11eb-9df7-eb2d4d6173eb.png)

  * Chọn **Thành công** > Nhập số tiền đòi được >  KNNB sẽ chuyển trạng thái sang **Thành công**

![image](https://user-images.githubusercontent.com/75475064/101892342-d86c9680-3bd5-11eb-8dc8-ba7a78158eea.png)

![image](https://user-images.githubusercontent.com/75475064/101892600-2d101180-3bd6-11eb-8187-1afe0db9d5ec.png)

  * Chọn **Thất bại** > Nhập lý do khiếu nại thất bại > KNNB chuyển sang trạng thái **Thất  bại**

![image](https://user-images.githubusercontent.com/75475064/101892442-f89c5580-3bd5-11eb-96b8-8f08299dd06b.png)

![image](https://user-images.githubusercontent.com/75475064/101892826-73fe0700-3bd6-11eb-86ec-bc1759b680b0.png)

  * Có thể gia hạn thêm cho **Hạn xử lý KNNB** và nhập lý do

![image](https://user-images.githubusercontent.com/75475064/101891908-419fda00-3bd5-11eb-8e51-c832c99b876b.png)

![image](https://user-images.githubusercontent.com/75475064/101891959-53817d00-3bd5-11eb-8dc9-83b37f2562f9.png)



## Bước 4: Nhập mã giao dịch alipay hoàn vào KNNB

  * Tại màn hình **Chi tiết KNNB**, cho phép nhập **Mã giao dịch Alipay** hoàn tương ứng với KNNB này hoặc có thể chọn trong danh sách giao dịch hoàn có sẵn trên hệ thống.
  
![image](https://user-images.githubusercontent.com/75475064/101893038-c17a7400-3bd6-11eb-83b3-6b6e9e84e86c.png)

![image](https://user-images.githubusercontent.com/75475064/101893149-ec64c800-3bd6-11eb-9db2-883216aeefcd.png)

  * Đánh dấu KNNB có **tài chính hợp lệ** khi: 
  
     Tổng số tiền hoàn trên giao dịch = số tiền hoàn trên KNNB
    
     Không có mã giao dịch nào chưa có giao dịch alipay tương ứng trên hệ thống
    
     Không có mã giao dịch nào là giao dịch của đơn khác, không phải đơn của KNNB này
    
![image](https://user-images.githubusercontent.com/75475064/102747515-fe8ef500-4392-11eb-967d-d4b9f4883d92.png)
 
  * Ngoài ra, với các trường hợp sau thì KNNB **luôn luôn được đánh dấu là có tài chính hợp lệ** 
   
     KNNB chuyển sang thành công với số tiền đòi được > 0¥    
    
     KNNB chưa có số tiền đòi được và có thể có hoặc chưa có giao dịch alipay

  * Đánh dấu KNNB có **tài chính không hợp lệ** khi:
  
     KNNB được đánh dấu là "tài chính không hợp lệ" khi số tiền đòi được trên KNNB không khớp với số tiền hoàn lại từ alipay
    
     KNNB được đánh dấu là "tài chính không hợp lệ" khi số tiền đòi được trên KNNB khớp với số tiền hoàn lại từ alipay nhưng tồn tại mã giao dịch alipay không có trên hệ thống
    
![image](https://user-images.githubusercontent.com/75475064/102748041-09965500-4394-11eb-9862-7725b4192158.png)

  * **Lưu ý:** Hệ thống cho phép chuyển KNNB sang trạng thái thành công khi KNNB có số tiền đòi được > 0¥ và KNNB có thể có hoặc chưa có giao dịch alipay
  
    - Một giao dịch chỉ được map cho 1 KNNB
    
    - Có thể nhập mã giao dịch Alipay đã tồn tại hoặc chưa tồn tại trên hệ thống
    
    - Chỉ chấp nhận giao dịch hoàn (có số tiền là cộng)

### Lấy thông tin khiếu nại người bán từ việc đồng bộ mã khiếu nại site gốc
Tại màn hình chi tiết KNNB, nếu KNNB có mã khiếu nại trên site gốc thì khi thực hiện đồng bộ thông tin sẽ lấy được các thông tin của KNNB. Khi hover vào mã khiếu nại sẽ hiển thị các thông tin lấy được bao gồm:
- Mã khiếu nại site gốc
- Thời gian gia hạn khiếu nại
- Trạng thái khiếu nại 
- Mã vận đơn trả hàng
- Mã hóa đơn gốc
- Số tiền

![Đồng bộ KNNB](https://user-images.githubusercontent.com/76998374/104545995-d4f97e80-565d-11eb-87f5-4868ec1af481.png)

![Thông tin lấy được từ mã KN site gốc](https://user-images.githubusercontent.com/76998374/104546329-839dbf00-565e-11eb-90b6-f6e008543fd2.png)




