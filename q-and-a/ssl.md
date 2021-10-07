# Another Ploblem


{% embed url="https://youtu.be/ipUyti7lPaw" caption="" %}

## Các lỗi chứng chỉ bảo mật Google Chrome hay gặp

* Kết nối không đáng tin cậy \(This connection is untrusted\)
* Lỗi kết nối và lỗi giao thức SSL \(SSL connection Error or SSL Protocol Error\)
* Kết nối của bạn không phải là kết nối riêng tư hoặc không an toàn \(Your connection is not private or secure\)
* Bảo mật chứng chỉ của máy chủ không hợp lệ \(The server’s certificate security is not yet valid\)
* Chứng chỉ an toàn của web không tin cậy \(The sites security certificate is not trusted\)
* Chứng chỉ của máy chủ không đáng tin cậy \(Server’s certificate is not trusted\)
* Đây có khả năng không phải là trang web bạn đang tìm kiếm \(This is probably not the site you are looking for\).

Các dạng lỗi kết nối SSL trên chỉ là một số lỗi trong rất nhiều lỗi SSL khác mà người dùng có thể gặp phải. Quý khách có thể tham khảo 1 số cách khắc phục sau:

## 1. Thêm chứng chỉ trên máy tính

### Bước 1: Download file import

* Quý khách truy cập vào link [https://letsencrypt.org/certs/isrgrootx1.pem](https://letsencrypt.org/certs/isrgrootx1.pem) để download file vào thư mục lưu trữ trên máy tính.
* File driver dự phòng nếu Quý khách không thể truy cập vào link trên: [https://bit.ly/3zWzPPJ](https://bit.ly/3zWzPPJ)

![Download](https://user-images.githubusercontent.com/73226975/135574024-02b993c6-03bd-47f9-b3a6-f152fc90584f.png)

### Bước 2: Vào Start Menu

* Quý khách gõ vào ô tìm kiếm **mmc.exe**, sau đó ấn **Enter**

![MMC](https://user-images.githubusercontent.com/73226975/135575282-b8db95c1-9529-4323-941c-1a8946831bf3.png)

### Bước 3: chọn **Menu File**

![File](https://user-images.githubusercontent.com/73226975/135575387-0c5bac89-e754-4413-bdf0-40a424663926.png)

* Chọn **Add/remove Snap-in**

![Add/remove](https://user-images.githubusercontent.com/73226975/135575553-65ead00a-71f6-4007-a1fe-a26b30bed3c7.png)

### Bước 4: Chọn **Certificates**

* Chọn **Add** =&gt; **My user account** =&gt; Click **Finish**

![Certificates](https://user-images.githubusercontent.com/73226975/135575741-f7eb220d-dee4-4943-8aeb-db79188cda3d.png)

![Add](https://user-images.githubusercontent.com/73226975/135575845-5b2314e1-b7a2-45d6-91bc-36a54c364e9b.png)

* Click **OK**
* 
![User account](https://user-images.githubusercontent.com/73226975/135575741-f7eb220d-dee4-4943-8aeb-db79188cda3d.png)


* Quý khách click vào button **Certificates** =&gt; Click chuột phải vào **Personal**, chọn **All Tasks** =&gt; **Import**

![Personal](https://user-images.githubusercontent.com/73226975/135576291-47947ff4-77fb-4a15-aa64-daa654213ca8.png)

* Chọn **Next**

![image](https://user-images.githubusercontent.com/73226975/135578126-8480484a-99b8-4319-be76-cdf6ac9d72d3.png)

* Chọn file **pem** tại thư mục đã download ở [Bước 1](https://hd.gobiz.vn/q-and-a/ssl#buoc-1-download-file-import)

![image](https://user-images.githubusercontent.com/73226975/135578288-84653059-e35d-4472-9a92-6aad86565f7e.png)

* Tiếp tục chọn **Next** cho tới hết các bước, Quý khách ấn **OK** để kết thúc quá trình chỉnh sửa.

![Next](https://user-images.githubusercontent.com/73226975/135578312-4b5614da-fdec-43c0-bd89-e457828456f5.png)

![Next](https://user-images.githubusercontent.com/73226975/135578431-56d78ccc-aa38-4758-b90f-d781d5eadebc.png)

![Finish](https://user-images.githubusercontent.com/73226975/135583095-f13f380d-13da-4e38-ab75-c0b7a0de0cf9.png)

![OK](https://user-images.githubusercontent.com/73226975/135582876-c5d712b0-c819-4c01-9b0c-0b4414fb148c.png)

### Bước 5: Trusted Root Certification Authorities

* Quý khách thao tác tương tự như các bước vừa làm với mục **Personal**

![image](https://user-images.githubusercontent.com/73226975/136367202-ec8a963a-3b8f-4264-81a5-fd2bc51f7b69.png)


## 2. Thêm chứng chỉ trên trình duyệt

### Bước 1: Mở cài đặt trình duyệt

![image](https://user-images.githubusercontent.com/73226975/136367918-d422b0a7-d133-437d-abd0-c0e2ffa9b23a.png)

### Bước 2: Chọn Bảo mật và quyền riêng tư

![image](https://user-images.githubusercontent.com/73226975/136367776-98e93fd0-824c-4c6f-8e01-ef86cb34a3d1.png)

(1) - Bảo mật và quyền riêng tư
(2) - Bật luôn sử dụng kết nối an toàn
(3) - Truy cập vào mục Quản lý chứng chỉ


## 2. Xoá lịch sử trình duyệt web

* Nếu sau khi thao tác chỉnh sửa bằng cách import file vẫn không hiệu quả, Quý khách có thể xóa tất cả dữ liệu duyệt web \(bộ nhớ cache, cookie, dữ liệu ứng dụng được lưu trữ, v.v…\).
* Sau đó khởi động lại trình duyệt hoặc máy tính và truy cập lại nhé.

