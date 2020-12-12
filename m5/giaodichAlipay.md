# KIỂM SOÁT GIAO DỊCH ALIPAY VÀ LỢI NHUẬN MẶC CẢ

## Bước 1: Truy cập để tải về tệp ALIPAY.

  -  Đăng nhập bằng tài khoản taobao https://www.alipay.com/
  
  - Mở link https://consumeprod.alipay.com/record/advanced.htm
  
  - Chọn khoảng thời gian cần xuất/ check
  
  - Chọn thông tin GD chi/ thu để xuất
  
![image](https://user-images.githubusercontent.com/75475064/101973254-47df9600-3c69-11eb-948f-1e4181b722d3.png)

  
**Lưu ý:** Khi bấm xuất file có thể sẽ đòi đăng nhập tiếp, cần đăng nhập vào alipay trên điện thoại sau đó quét mã vào máy tính để đăng nhập xuất

![image](https://user-images.githubusercontent.com/75475064/101973261-647bce00-3c69-11eb-97a9-568638b97a8d.png)

![image](https://user-images.githubusercontent.com/75475064/101973274-7eb5ac00-3c69-11eb-8da4-778b42e08622.png)

![image](https://user-images.githubusercontent.com/75475064/101973288-942ad600-3c69-11eb-9a5e-016937b3c22e.png)

  Nội dung File khi tải về sẽ như sau (Để đọc được file cần tải file lên google docs): 
  
![image](https://user-images.githubusercontent.com/75475064/101973302-a7d63c80-3c69-11eb-90df-4184c2354602.png)

## Bước 2: Upload file giao dịch Alipay lên hệ thống

  Chọn **Kiểm soát mua hàng** > **Danh sách file giao dịch** > **Tải file**

![image](https://user-images.githubusercontent.com/75475064/101973334-e966e780-3c69-11eb-8338-acc877998a04.png)

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
  
 ![image](https://user-images.githubusercontent.com/75475064/101973590-adcd1d00-3c6b-11eb-9300-34dccc096f37.png)
 
  * Màn hình **kiểm soát đơn hàng**: chỉ hiển thị những đơn có trạng thái từ **Đã Mua** trở đi và đơn ở trạng thái **Hủy, Hết hàng** mà có giao dịch nhà cung cấp.

      Hệ thống hỗ trợ nhận biết phân biệt **đơn có vấn đề**:
   
    - Đối với đơn không ở trạng thái **Hủy, Hết hàng**
      
    - **Chưa có giao dịch NCC**: gồm những đơn có trạng thái từ **Đã Mua** trở đi nhưng chưa có giao dịch nhà cung cấp nào
      
    - **Lợi nhuận quá cao**: khi tỉ lệ lợi nhuận đơn được tính tính theo công thức mà vượt quá ngưỡng người dùng **[cấu hình](https://hd.gobiz.vn/m5/cauhinhnangcao)** thì hiển thị cảnh báo này
     
    - **Lợi nhuận âm**: khi giá vốn nhỏ hơn tổng tiền chi cho NCC thì lợi nhuận âm
      
    - **Đối với đơn Hủy, Hết hàng** 
      
    - **Đơn Hủy nhưng có giao dịch thu chi không khớp:** khi đơn có tổng thu khác tổng chi 
      
![image](https://user-images.githubusercontent.com/75475064/101973633-14523b00-3c6c-11eb-8dec-fd489659e788.png)

  * Đánh dấu xử lý đơn có vấn đề: bấm **[Resolve]** hệ thống hiển thị popup để nhập lý do xử lý (lý do không bắt buộc nhập). 

![image](https://user-images.githubusercontent.com/75475064/101973657-30ee7300-3c6c-11eb-9d65-e9407ccc0ec1.png)

![image](https://user-images.githubusercontent.com/75475064/101973667-4368ac80-3c6c-11eb-95e2-d26db7e6b26c.png)

  * Sau khi bấm vào nút **[Resolve]** đơn sẽ được đánh dấu là đơn có vấn đề đã xử lý, thông tin đơn thể hiện ai là **người xử lý** và **thời gian xử lý.**
   
![image](https://user-images.githubusercontent.com/75475064/101973683-68f5b600-3c6c-11eb-9215-ea8cb8642946.png)



