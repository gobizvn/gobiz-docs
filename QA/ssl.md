

# Cách khắc phục lỗi chứng chỉ bảo mật

## Các lỗi chứng chỉ bảo mật Google Chrome hay gặp 

- Kết nối không đáng tin cậy (This connection is untrusted)

- Lỗi kết nối và lỗi giao thức SSL (SSL connection Error or SSL Protocol Error)

- Kết nối của bạn không phải là kết nối riêng tư hoặc không an toàn (Your connection is not private or secure)

-  Bảo mật chứng chỉ của máy chủ không hợp lệ (The server’s certificate security is not yet valid)

- Chứng chỉ an toàn của web không tin cậy (The sites security certificate is not trusted)

- Chứng chỉ của máy chủ không đáng tin cậy (Server’s certificate is not trusted) 

- Đây có khả năng không phải là trang web bạn đang tìm kiếm (This is probably not the site you are looking for).

Các dạng lỗi kết nối SSL trên chỉ là một số lỗi trong rất nhiều lỗi SSL khác mà người dùng có thể gặp phải. 

## Thêm chứng chỉ

### Bước 1: Download file import

- Quý khách truy cập vào link https://letsencrypt.org/certs/isrgrootx1.pem để download file vào thư mục lưu trữ trên máy tính.

- File driver dự phòng nếu Quý khách không thể truy cập vào link trên: https://bit.ly/3zWzPPJ

![Download](https://user-images.githubusercontent.com/73226975/135574024-02b993c6-03bd-47f9-b3a6-f152fc90584f.png)

### Bước 2: Vào Start Menu

- Quý khách gõ vào ô tìm kiếm **mmc.exe**, sau đó ấn **Enter**

![MMC](https://user-images.githubusercontent.com/73226975/135575282-b8db95c1-9529-4323-941c-1a8946831bf3.png)

- Quý khách chọn **Menu File**

![File](https://user-images.githubusercontent.com/73226975/135575387-0c5bac89-e754-4413-bdf0-40a424663926.png)

- Chọn **Add/remove Snap-in**

![Add/remove](https://user-images.githubusercontent.com/73226975/135575553-65ead00a-71f6-4007-a1fe-a26b30bed3c7.png)

- Chọn **Certificates** => **Add** => Chọn **My user account** => **Finish**


![Certificates](https://user-images.githubusercontent.com/73226975/135575741-f7eb220d-dee4-4943-8aeb-db79188cda3d.png)

![Add](https://user-images.githubusercontent.com/73226975/135575845-5b2314e1-b7a2-45d6-91bc-36a54c364e9b.png)

![User account](https://user-images.githubusercontent.com/73226975/135575741-f7eb220d-dee4-4943-8aeb-db79188cda3d.png)

- Click **OK**

![OK](https://user-images.githubusercontent.com/73226975/135575993-cc16a3e9-ee02-4213-b68e-89a92183a9f3.png)

- Quý khách click vào button **Certificates** => Click chuột phải vào **Personal**, chọn **All Tasks** => **Import**

![Personal](https://user-images.githubusercontent.com/73226975/135576291-47947ff4-77fb-4a15-aa64-daa654213ca8.png)


- Chọn **Next**

![image](https://user-images.githubusercontent.com/73226975/135578126-8480484a-99b8-4319-be76-cdf6ac9d72d3.png)

- Chọn file **pem** tại thư mục đã download ở [Bước 1](https://hd.gobiz.vn/q-and-a/ssl#buoc-1-download-file-import)

![image](https://user-images.githubusercontent.com/73226975/135578288-84653059-e35d-4472-9a92-6aad86565f7e.png)

- Chọn **Next** cho tới hết các bước, Quý khách ấn **OK** để kết thúc quá trình cài đặt

![image](https://user-images.githubusercontent.com/73226975/135578312-4b5614da-fdec-43c0-bd89-e457828456f5.png)


![image](https://user-images.githubusercontent.com/73226975/135578431-56d78ccc-aa38-4758-b90f-d781d5eadebc.png)


![image](https://user-images.githubusercontent.com/73226975/135582876-c5d712b0-c819-4c01-9b0c-0b4414fb148c.png)


![image](https://user-images.githubusercontent.com/73226975/135583095-f13f380d-13da-4e38-ab75-c0b7a0de0cf9.png)


![image](https://user-images.githubusercontent.com/73226975/135582876-c5d712b0-c819-4c01-9b0c-0b4414fb148c.png)

![image](https://user-images.githubusercontent.com/73226975/135578431-56d78ccc-aa38-4758-b90f-d781d5eadebc.png)

