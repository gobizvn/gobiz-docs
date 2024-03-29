# GDV gửi YCTT qua công cụ

**Đơn trước trạng thái ĐÃ MUA:** GDV chuyển trạng thái đơn sang chờ thanh toán \(đảm bảo đủ điều kiện để chuyển sang đã mua\) =&gt; quỹ thanh toán xong, hệ thống tự động chuyển ĐÃ MUA \(không cần duyệt\).

**Đơn sau trạng thái ĐÃ MUA:** Khi GDV gửi YCTT thì YCTT sẽ hiển thị ở tab Chờ duyệt và trưởng nhóm sẽ duyệt YCTT.

**Lưu ý:** Với đơn gửi daifu: Nhập thông tin alipay daifu, không chọn ở phần site gốc đã có

**Bước 1:** **Giao dịch viên truy cập màn hình chi tiết đơn và thực hiện:**

* Chọn đầy đủ các dịch vụ trên đơn
* Điền mã hóa đơn gốc vào đơn hàng
* Chuyển trạng thái đơn sang ĐÃ PAI hoặc CHỜ THANH TOÁN

![Chi ti&#x1EBF;t &#x111;&#x1A1;n](https://user-images.githubusercontent.com/76998374/105937552-64545800-6088-11eb-86c2-ba3869c92f6d.png)

**Lưu ý:** Đơn phải đủ điều kiện chuyển sang ĐÃ MUA thì mới gửi được YCTT:

* Đơn đã chọn tài khoản mua hàng, nhóm ngành hàng, dịch vụ/duyệt dịch vụ, xác nhận thay đổi đơn giá/số lượng, phí VCNĐ TQ, mã hóa đơn gốc
* Nếu giá vốn trên đơn \(tiền hàng + phí VCNĐTQ\) &lt; số tiền gửi YCTT trên site gốc thì không gửi được YCTT
* Nếu mã hóa đơn gốc \(MHĐG\) đã được gửi YCTT thành công và YCTT đang ở trạng thái Chờ thanh toán, Đang xử lý, Thành công thì không gửi lại được YCTT cho MHĐG đó. Chỉ gửi lại được khi YCTT của MHĐG đó ở trạng thái HỦY
* Không thể gửi YCTT khi số tiền của tất cả YCTT trên cùng 1 đơn lớn hơn giá vốn \(tiền hàng + phí VCNĐ\). YCTT ở trạng thái HỦY thì không tính vào tổng số tiền thanh toán của đơn
* Không cho gửi YCTT khi đơn ở trạng thái HỦY

**Bước 2:** **Truy cập site taobao và chọn các đơn chờ thanh toán**

* Link: [https://buyertrade.taobao.com/trade/itemlist/list\_bought\_items.htm?spm=a1z02.1.972272805.d4919660.7942782dWHq9NR&action=itemlist/BoughtQueryAction&event\_submit\_do\_query=1&tabCode=waitPay](https://buyertrade.taobao.com/trade/itemlist/list_bought_items.htm?spm=a1z02.1.972272805.d4919660.7942782dWHq9NR&action=itemlist/BoughtQueryAction&event_submit_do_query=1&tabCode=waitPay)
* Chọn mã đơn cần thanh toán =&gt; Click \[Gửi YCTT gộp\]

![image](https://user-images.githubusercontent.com/76998374/105942275-7a1a4b00-6091-11eb-8f2e-a57dd358e325.png)

**Cơ chế Gửi YCTT:** Người gửi YCTT không cần chọn hình thức thanh toán \(quỹ sẽ quyết định thanh toán bằng hình thức nào\): tích chọn đơn cần thanh toán và thao tác để gửi YCTT, GDV được thêm MHDG ở mọi trạng thái

![G&#x1EED;i YCTT](https://user-images.githubusercontent.com/76998374/105942367-af269d80-6091-11eb-8972-741b999f470d.png)

* Công cụ mua hàng sẽ tự động nhận thông tin và chuyển yêu cầu thanh toán từ site gốc \(Taobao.com\) sang M5 \(hệ thống mua hàng của bạn\). Đồng thời hiển thị thông báo đã gửi yêu cầu thanh toán thành công
* YCTT sau khi gửi thanh công sẽ hiển thị ở trạng thái CHỜ THANH TOÁN \(không cần duyệt\)

**Bước 3:** **Tại màn hình Danh sách yêu cầu thanh toán**

* Nhân viên Quỹ truy cập menu **Đơn hàng** và chọn **Yêu cầu thanh toán**

![Y&#xEA;u c&#x1EA7;u thanh to&#xE1;n](https://user-images.githubusercontent.com/76998374/105938890-b1392e00-608a-11eb-96fd-0d8a2cdcf022.png)

* Xử lý YCTT:
* Tại tab **Chờ thanh toán**, nếu chọn \[Tiếp nhận\] thì hệ thống chuyển YCTT sang Đang thanh toán
* Sau đó truy cập link thanh toán để tiến hành thanh toán đơn hàng

**Duyệt thanh toán đơn hàng thường sau khi bấm đã mua, \(TBP, TN duyệt\)**

Vào trực tiếp theo link hoặc hướng dẫn bên dưới:

[https://mua.nhaphang.com/payment-requests?external\_order=0&i=6&page=1&per\_page=20&status=PENDING](https://mua.nhaphang.com/payment-requests?external_order=0&i=6&page=1&per_page=20&status=PENDING)

Kiểm tra tiền hàng trong đơn hàng để quyết định có duyệt hay không \(yêu cầu kiểm tra tổng tiền trên admin để tránh việc KO không đồng bộ về admin\)

![image](https://user-images.githubusercontent.com/76998374/106359828-95ae7b80-6347-11eb-9d44-5c222ad27cfb.png)

![image](https://user-images.githubusercontent.com/76998374/106359833-a0691080-6347-11eb-9363-af53a20665ce.png)

