
**Bước 1:** **KSCLDV kiểm tra thông tin giao dịch alipay**

Từ menu **Kiểm soát mua hàng**, nhân viên KSCLDV chọn mục **Kiểm soát giao dịch** để truy cập vào trang **Danh sách giao dịch alipay**

![Kiểm soát giao dịch](https://user-images.githubusercontent.com/76998374/105815675-e0e22a80-5fe5-11eb-9b4c-17c2f1c8d918.png)

Sau khi kế toán upload file giao dịch alipay thành công lên hệ thống thì tất cả giao dịch sẽ hiển thị ở màn hình danh sách giao dịch alipay.

Mỗi giao dịch alipay bao gồm các thông tin: 

- Tài khoản giao dịch

- Mã giao dịch

- Số tiền giao dịch

- Thời gian GD

- Mã đơn hàng

- Loại GD

- Nhà cung cấp

- Mã GD nhà cung cấp

- Thời gian tạo trên hệ thống

- Thời gian xử lý

- File CSV

- Giao dịch liên quan

- Tài khoản liên quan

![Danh sách giao dịch alipay](https://user-images.githubusercontent.com/76998374/105813563-9d39f180-5fe2-11eb-849e-6a3367210dab.png)

**Bước 2** **Thêm/xóa MHĐG khỏi giao dịch**

Tại trang danh sách giao dịch alipay, KSCLDV có thể thêm/xóa MHĐG trên giao dịch.

- Nếu nhập MHĐG tồn tại trên đơn thì giao dịch sẽ map với đơn và giao dịch alipay hiển thị ở chi tiết đơn 

- Nếu nhập MHĐG không tồn tại trên đơn thì giao dịch chưa khớp được đơn và không hiển thị ở chi tiết đơn

**Thêm MHĐG vào giao dịch** 

![Thêm MHĐG vào GD](https://user-images.githubusercontent.com/76998374/105818085-09b7ef00-5fe9-11eb-87ab-46ec04e39e44.png)

**Xóa MHĐG khỏi GD:** Click vào icon bút chì bên cạnh MHĐG, sau đó chọn xóa trên MHĐG cần xóa

![Xóa MHĐG](https://user-images.githubusercontent.com/76998374/105818481-9367bc80-5fe9-11eb-87e3-e24a8792f215.png)

![Xóa MHĐG khỏi GD](https://user-images.githubusercontent.com/76998374/105818670-c5791e80-5fe9-11eb-97d0-da2d35edf952.png)























Bước 2: Kế toán Upload file giao dịch Alipay lên hệ thống

  Chọn **Kiểm soát mua hàng** > **Danh sách file giao dịch** > **Tải file**
  File alipay được chia thành 03 loại: 
  - Alipay thường
  - Alipay Global
  - Alipay Mbill
 Kế toán cần upload đúng loại giao dịch alipay tương ứng với 3 nút tải file
 
![Tải file alipay](https://user-images.githubusercontent.com/76998374/104807781-1895e900-5814-11eb-85b5-2a771eca5334.png)


![image](https://user-images.githubusercontent.com/75475064/101973355-0e5b5a80-3c6a-11eb-9cbc-3ecb5c48b031.png)

## Bước 3: Kiểm soát giao dịch bất thường

  * Khi kế toán upload **file csv** thành công, các giao dịch alipay hiển thị ở màn hình **Danh sách giao dịch alipay**

![image](https://user-images.githubusercontent.com/75475064/101973379-39de4500-3c6a-11eb-9e26-a7789ddac3c7.png)

  * Sau khi upload file csv, những giao dịch được đánh dấu là **giao dịch bất thường chưa xử lý** là những giao dịch trong file Alipay có các lý do bất thường: 
  
    - Giao dịch không khớp được MHĐG
    
    - Giao dịch có MHĐG nhưng không thấy trên hệ thống
    
    - Giao dịch chi thanh toán hộ chưa khớp giao dịch liên quan
      
    - Giao dịch chi thanh toán hộ có số tiền không khớp
    
    - Khác
    
    
  * **Resolve/Unresolve** giao dịch bất thường
  
   Với những giao dịch được đánh dấu là **bất thường chưa xử lý** thì có thể **resolve/unresolve** giao dịch ở màn hình **danh sách** và
    màn hình **chi tiết giao dịch.**
    
![image](https://user-images.githubusercontent.com/75475064/101973388-4fec0580-3c6a-11eb-8537-949927f93041.png)

   Sau khi **resolve** giao dịch thì giao dịch trở thành **giao dịch bất thường đã xử lý**    
    
![image](https://user-images.githubusercontent.com/75475064/101973448-ce48a780-3c6a-11eb-88c6-0641d0b9a6b4.png)

   Cho phép **unresolve** giao dịch bất thường đã xử lý nếu có quyền **unresolve**. Khi **unresolve** sẽ có cảnh báo xác nhận
    
![image](https://user-images.githubusercontent.com/75475064/101973435-b709ba00-3c6a-11eb-8032-3b396571c266.png)

  * Thêm **mã hóa đơn gốc** vào giao dịch: Mã hóa đơn gốc nhập vào cho giao dịch nếu có đơn hàng có **mã đơn gốc** đó thì giao dịch
  sẽ hiển thị thông tin đơn này, và giao dịch sẽ được đánh dấu là **bất thường đã xử lý**.
  
![image](https://user-images.githubusercontent.com/75475064/101973464-ecaea300-3c6a-11eb-9047-35e3d0015d89.png)

![image](https://user-images.githubusercontent.com/75475064/101973549-6ba3db80-3c6b-11eb-8bb8-a6403f3d67aa.png)

## Bước 4: Kiểm soát lợi nhuận mặc cả 

  * **Mục đích:** Để xác định được doanh số mặc cả cho giao dịch viên, hệ thống tính toán dựa trên giao dịch NCC được map về đơn và thể hiện trên danh sách kiểm soát giao dịch nhà cung cấp để phát hiện được các **trường hợp sai phạm** :

      - Với đơn ở trạng thái không phải **Hủy, Hết hàng.**
    
      - **Tổng tiền Alipay** (không phải trạng thái **Hủy, Hết Hàng**) được tính bằng tổng alipay (chi-thu).
    
      - **Lợi nhuận mặc cả** (không phải trạng thái **Hủy, Hết hàng**) được tính bằng tổng giá vốn (tiền hàng + vận chuyển nội địa) - tổng giao dịch alipay chi (chi - thu).
    
      - **Tỉ lệ lợi nhuận** (không phải trạng thái **Hủy, Hết hàng**) được tính bằng lợi nhuận/giá vốn.
    
      - Với đơn ở trạng thái **Hủy, Hết hàng.**
    
      - Khi tính **lợi nhuận mặc cả** trên đơn **Hủy/Hết** hàng thì = tổng giao dịch alipay (thu - chi); tuy nhiên khi xuất doanh số cho mua hàng thì không bao gồm những đơn này; 
    
      - **Tỉ lệ lợi nhuận** = lợi nhuận/giá vốn.

  * Từ menu **Kiểm soát mua hàng**, chọn **Kiểm soát đơn hàng** 
  
![image](https://user-images.githubusercontent.com/75475064/104264521-6205d180-54be-11eb-9b25-3cc4de781bd5.png)
 
  * Màn hình **kiểm soát đơn hàng**: chỉ hiển thị những đơn có trạng thái từ **Đã Mua** trở đi và đơn ở trạng thái **Hủy, Hết hàng** mà có giao dịch nhà cung cấp.

      Hệ thống hỗ trợ nhận biết phân biệt **đơn có vấn đề**:
   
    - Đối với đơn không ở trạng thái **Hủy, Hết hàng**
      
    - **Chưa có giao dịch NCC**: gồm những đơn có trạng thái từ **Đã Mua** trở đi nhưng chưa có giao dịch nhà cung cấp nào
      
    - **Lợi nhuận quá cao**: khi tỉ lệ lợi nhuận đơn được tính tính theo công thức mà vượt quá ngưỡng người dùng **[cấu hình](https://hd.gobiz.vn/m5/cauhinhnangcao)** thì hiển thị cảnh báo này
     
    - **Lợi nhuận âm**: khi giá vốn nhỏ hơn tổng tiền chi cho NCC thì lợi nhuận âm
      
    - **Đối với đơn Hủy, Hết hàng** 
      
    - **Đơn Hủy nhưng có giao dịch thu chi không khớp:** khi đơn có tổng thu khác tổng chi 
      
![image](https://user-images.githubusercontent.com/75475064/104264257-e015a880-54bd-11eb-8b1f-349b2dda3755.png)

  * Đánh dấu xử lý đơn có vấn đề: bấm **[Resolve]** hệ thống hiển thị popup để nhập lý do xử lý (lý do không bắt buộc nhập). 

![image](https://user-images.githubusercontent.com/75475064/104264662-a42f1300-54be-11eb-98c6-bcb25b99c2c3.png)

![image](https://user-images.githubusercontent.com/75475064/101973667-4368ac80-3c6c-11eb-95e2-d26db7e6b26c.png)

  * Sau khi bấm vào nút **[Resolve]** đơn sẽ được đánh dấu là đơn có vấn đề đã xử lý, thông tin đơn thể hiện ai là **người xử lý** và **thời gian xử lý.**
   
![image](https://user-images.githubusercontent.com/75475064/104264395-21a65380-54be-11eb-9fa1-bba41acfe7a4.png)



