# SỬ DỤNG YÊU CẦU THANH TOÁN CHO QUY TRÌNH MUA HÀNG
**Mục đích:** Nếu không muốn Giao dịch viên tự thanh toán thì sẽ dùng **Yêu cầu thanh toán**, khi đó quy trình mua hàng sẽ có những thay đổi như sau:

**Bước 1:** Tại màn hình **Chi tiết đơn**

  - Chọn đầy đủ các dịch vụ trên đơn, duyệt dịch vụ bắt buộc duyệt (nếu có).
  
  - Nhập mã hóa đơn gốc cho đơn, phí VCNĐ.
  
  - Chọn đầy đủ Account mua, nhóm ngành hàng (nếu bắt buộc).
  
  - Xác nhận khi thay đổi đơn giá/số lượng.
  
  - Đơn chuyển sang trạng thái **Đã Pai**.

![image](https://user-images.githubusercontent.com/75475064/101896010-e244c880-3bda-11eb-949a-d8d68249b3d3.png)


**Bước 2:** Tại màn hình danh sách các đơn ở trạng thái **Chờ thanh toán** của Taobao

Link: https://buyertrade.taobao.com/trade/itemlist/list_bought_items.htm?spm=a1z02.1.972272805.d4919660.7942782dWHq9NR&action=itemlist/BoughtQueryAction&event_submit_do_query=1&tabCode=waitPay

  * Chọn tích chọn **mã hóa đơn gốc (MHĐG)** của đơn cần thanh toán. Có thể tích chọn all hoặc một vài MHĐG để gửi YCTT cùng lúc
  
    - Click vào nút **[合并付款]**  để thực hiện thanh toán 

![image](https://user-images.githubusercontent.com/75475064/101896148-1ae4a200-3bdb-11eb-9b44-6196d6e378e5.png)

   - Click chọn **thanh toán qua ngân hàng**

![image](https://user-images.githubusercontent.com/75475064/101896346-73b43a80-3bdb-11eb-8468-8e1e61a6375b.png)


  * Công cụ mua hàng sẽ tự động nhận và chuyển YCTT từ site gốc (Taobao)  sang hệ thống KOMODO của bạn với thông báo **Gửi yêu cầu thanh toán thành công**
  
![image](https://user-images.githubusercontent.com/75475064/101896407-8b8bbe80-3bdb-11eb-83ab-dc3ca69315fa.png)

  * YCTT sẽ hiển thị tại danh danh sách ở màn hình Yêu cầu thanh toán với trạng thái là **Chờ thanh toán**

![image](https://user-images.githubusercontent.com/75475064/101896495-ac541400-3bdb-11eb-9d67-10de2bb18fec.png)



  **Lưu ý: Những trường hợp không gửi được yêu cầu thanh toán**

  - Đơn đủ điều kiện để chuyển sang **Đã mua** thì mới tạo được yêu cầu thanh toán(YCTT) : Chọn account mua hàng, nhóm ngành hàng (nếu bắt buộc chọn),
    dịch vụ bắt buộc chọn, duyệt dịch vụ bắt buộc duyệt, xác nhận thay đổi đơn giá/số lượng, phí VCNĐ, mã hóa đơn gốc.
  
  - Nếu YCTT đang ở trạng thái **Chờ Thanh Toán, Đang Thanh Toán, Đã Thanh Toán** thì không cho phép gửi lại YCTT.
  
  - Không thể gửi YCTT khi số tiền của tất cả YCTT trên cùng 1 đơn lớn hơn giá vốn (tiền hàng + phí VCNĐ).
  
  - YCTT ở trạng thái **HỦY** thì không tính vào tổng số tiền thanh toán của đơn.
  
  - Không cho gửi YCTT khi đơn ở trạng thái **HỦY.**
  
  - Đơn có mã hóa đơn gốc không tồn tại trên hệ thống KOMODO.

**Bước 3:** Xử lý Yêu cầu thanh toán

  **Bước 3.1:** Xử lý **Yêu cầu thanh toán đơn hàng thường**
   * Chọn **Đơn hàng** , chọn **Yêu cầu thanh toán**
 
![image](https://user-images.githubusercontent.com/75475064/101896854-313f2d80-3bdc-11eb-85f1-cc0f7263172d.png)

   * YCTT ở trạng thái **Chờ thanh toán** sẽ cho phép nhân viên quỹ **[Tiếp nhận]** hoặc **[Từ chối]**

![image](https://user-images.githubusercontent.com/75475064/101897038-83804e80-3bdc-11eb-97bb-6af685644dfd.png)


   * Nếu chọn **[Tiếp nhận]** thì YCTT sẽ chuyển từ **Chờ thanh toán** sang **Đang thanh toán** và ghi log tên người tiếp nhận.
   
  ![image](https://user-images.githubusercontent.com/75475064/101897286-e540b880-3bdc-11eb-9c72-6504a023afd6.png)

  * YCTT ở trạng thái **Đang thanh toán** sẽ cho phép nhân viên quỹ **[Thanh toán]** hoặc **[Thất bại]**
Sau khi truy cập link thanh toán đơn hàng và xác nhận thanh toán thành công thì YCTT sẽ chuyển từ **Đang thanh toán** sang **Đã thanh toán** và thông báo **Xử lý yêu cầu thanh toán thành công**

![image](https://user-images.githubusercontent.com/75475064/101897442-22a54600-3bdd-11eb-92cc-4d2d2b51c648.png)

   Đồng thời sẽ chuyển sang trạng thái “ Đã mua “ và log Thời gian thanh toán thành công

![image](https://user-images.githubusercontent.com/75475064/101897567-57b19880-3bdd-11eb-8838-6cbec1943473.png)


  **Bước 3.2:** Xử lý yêu cầu thanh toán cho đơn hàng ngoài.
  
   Đơn hàng được đánh dấu là đơn hàng ngoài thì cho phép nhân viên tạo YCTT ngoài cho đơn hàng. 
    
   **Đánh dấu Đơn hàng ngoài**.
   
      - Truy cập màn hình **Chi tiết đơn** và đánh dấu đơn hàng ngoài
      
![image](https://user-images.githubusercontent.com/75475064/101897984-f807bd00-3bdd-11eb-822a-c1b1607bb958.png)

      - Hiển thị cảnh báo và chọn **Xác nhận** 

![image](https://user-images.githubusercontent.com/75475064/101897804-b545e500-3bdd-11eb-8d2d-e27c43fe9992.png)

  * Tạo YCTT từ màn hình **Chi tiết đơn**

![image](https://user-images.githubusercontent.com/75475064/101897934-e4f4ed00-3bdd-11eb-834f-27d8256106c7.png)

  * Nhập đầy đủ thông tin các trường bắt buộc và click Gửi
  
![image](https://user-images.githubusercontent.com/75475064/101898095-21284d80-3bde-11eb-9348-8fd6385405d3.png)

  * Sau khi gửi thành công YCTT đơn hàng ngoài hệ thống sẽ tự động link tới màn hình danh sách YCTT và tự động lọc theo [YCTT đơn hàng ngoài] và chọn tab “Chờ duyệt”.


