# Cấu hình khác

## 1. Một số mã dịch vụ thường dùng trong bộ cấu hình chính sách

* Gobiz cung cấp một số mã dịch vụ thường dùng trong hệ thống để Quý khách tham khảo thêm trong quá trình sử dụng tính năng **Cấu hình bộ chính sách**

| Mã Dịch Vụ | Tên Dịch vụ |
| :--- | ---: |
| inspection | Kiểm hàng |
| special_packaging | Đóng gỗ riêng |
| standard_packaging | 	Đóng gỗ chung |
| bubble_wrapping | Quấn bọt khí chung |
| private_bubble_wrapping | Quấn bọt khí riêng |
| cargo_insurance | Bảo hiểm hàng hóa |
| direct_delivery | Vận chuyển thẳng |
| normal_shipping | Vận chuyển thường |
| express_shipping | Vận chuyển nhanh |
| eco_shipping | Vận chuyển tiết kiệm |
| ecommerce_shipping | Vận chuyển thương mại điện tử |
| management_fee | Phí quản lý đơn |
| purchasing_fee | Phí mua hàng |
| additional_other | Phụ thu khác |
| packaging_group | Nhóm Dịch vụ đóng hàng |
| shipping_group | Nhóm Dịch vụ chuyển phát |


## 2. Một số công thức tính phí thông dụng

### 2.1. Phí Đóng gỗ & Quấn bọt khí

![Mẫu 1](https://user-images.githubusercontent.com/73226975/157414629-e1af2bde-906b-4ffe-9f4f-897901cf1b13.png)


| DỊCH VỤ | ORDER | KÝ GỬI |
| :--- | ---: | ---: |
| ĐÓNG GỖ | **Scope**: Tính theo đơn | **Scope**: Tính theo đơn |
| | **Công thức tính đơn giá**: totalWeight != null ? (exchangeRate != null ? (totalWeight > 1.00 ? (exchangeRate * (25.00 + ((totalWeight - 1.00).intValue() + 1) * 2.00)) : (exchangeRate * 25.00)) : 0.00) : 0.00 | **Công thức tính đơn giá**: actualWeight != null ? (exchangeRate != null ? (actualWeight > 1.00 ? (exchangeRate * (25.00 + ((actualWeight - 1.00).intValue() + 1) * 2.00)) : (exchangeRate * 25.00)) : 0.00) : 0.00 |
| | **Công thức tính số lượng**: 1 | **Công thức tính số lượng**: 1 |
| 
| 
| 

