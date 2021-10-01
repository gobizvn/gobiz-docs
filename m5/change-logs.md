# Changelog

## \[1.21.0\] - 17/06/2021

### Chức năng mới

* Cho phép đánh dấu mã quản lý sản phẩm trên từng sản phẩm \(\#2998\)

### Cập nhật

* Thêm cột ID đơn khi xuất file CSV giao dịch alipay \(\#2967\)

## \[1.20.0\] - 01/06/2021

### Chức năng mới

* Cho phép bỏ phần dịch tên sản phẩm và đơn vị tính sản phẩm \(\#2968\)
* Cho phép cảnh báo khi đơn có một số tính chất đặc biệt \(\#3007\)

### Cập nhật

* Khi sửa thông tin khai quan, phần log ghi rõ thông tin thay đổi \(sửa thành gì\) \(\#2975\)

## \[1.19.0\] - 27/05/2021

### Chức năng mới

* Cho phép đánh dấu tính chất đơn hàng \(\#2971\)
* Cho phép cấu hình kho nhận trong db \(\#2972\)
* Cho phép hiển thị cảnh báo khi thay đổi tính chất đơn, dịch vụ làm thay đổi kho nhận \(\#2974\)

## \[1.18.0\] - 26/04/2021

### Chức năng mới

* Cho phép tìm kiếm những file alipay đang xử lý \(\#2946\)
* Hiển thị trực tiếp link download công cụ hỗ trợ mua hàng để cài đặt \(\#2948\)
* Bổ sung cột thông tin: nội dung xử lý, người xử lý, thời gian xử lý ở file kiểm soát đơn \(\#2949\)
* Thêm các bộ lọc: người xử lý và thời gian xử lý ở danh sách kiểm soát đơn \(\#2949\)

### Cập nhật

* Giao dịch hoàn lấy thông tin thời gian ở cột C trong file alipay \(\#2944\)
* Cho phép chặn không cho map giao dịch hoàn có thời gian giao dịch trước thời gian mua của đơn \(\#2943\)
* Điều chỉnh giao diện quản lý đơn và phân đơn \(\#2947\)

## \[1.17.0\] - 09/04/2021

### Chức năng mới

* Cho phép nhập mã hs code cho sản phẩm và đơn hàng, chuẩn bị sẵn sàng dữ liệu khai báo hải quan
* Cho phép đồng bộ giao dịch thanh toán hộ hàng loạt \(\#2940\)

### Cập nhật cải tiến

* Thay text "Đủ điều kiện vận chuyển TMĐT" để phân biệt với dịch vụ "Vận chuyển TMĐT" \(nếu có\) \(\#2939\)
* Thêm các cột thông tin trạng thái đơn, thời gian hết hàng \(nếu có\), tỷ giá khi xuất danh sách kiểm soát đơn \(\#2941\)

## \[1.16.0\] - 30/11/2020

### Chức năng mới

* Thêm quyền xem thông tin đơn mới, theo đó sẽ không xem được đơn chờ mua \(chưa tiếp nhận\), hạn chế nhân viên xem đơn chưa tiếp nhận \(\#2749\)
* Cho phép viết lưu ý choh YCTT ngay khi tạo YCTT \(\#2791\)
* API hỗ trợ việc tạo KNNB từ các module khác \(\#2792\)
* Thêm kiện liên quan đến KNNB để chuẩn bị cho việc xử lý đối trả \(\#2793\)
* Hỗ trợ kiểm tra điều kiện xuất khẩu trên 1688 với tài khoản doanh nghiệp \(\#2814\)
* Báo cáo hiệu suất, tốc độ mua hàng \(\#2757\)

### Cập nhật cải tiến

* Khi xuất YCTT ghi thêm chi tiết đơn hàng thuộc web/agency nào \(\#2724\)
* Tách biệt quyền thanh toán đơn hàng thường và quyền thanh toán đơn hàng ngoài \(\#2724\)
* Gợi ý: cái/đôi/bộ khi chưa dịch được đơn vị tính \(\#2724\)
* Khi xuất YCTT tách dòng theo từng mã HĐG \(\#2744\)
* Cho phép cấu hình khi điền đủ thông tin mới tính là đã khai quan xong \(\#2743\)
* Đơn chờ thanh toán sẽ quay về trạng thái "Đã pai" nếu như YCTT bị hủy \(\#2745\)
* Thêm bộ lọc "nhà cung cấp" tại danh sách giao dịch Alipay \(\#2789\)
* Fix lỗi không hiển thị nguồn hàng ở bộ lọc đơn hàng \(\#2789\)
* Hiển thị thêm username tại khối comment trên đơn \(\#2789\)
* Một số lỗi nhỏ khác \(\#2789\)

## \[1.15.0\] - 03/11/2020

### Chức năng mới

* Cho phép ghi chú cho YCTT \(\#2754\)
* Hỗ trợ YCTT đặt cọc cho đơn cần đặt cọc \(\#2755\)

### Cập nhật cải tiến

* Cho phép nhận diện đơn hàng ngoài từ hệ thống đặt hàng \(\#2752\)
* Hiển thị đầy đủ tên thanh toán viên \(\#2742\)
* Fix lỗi hiển thị sai thanh timeline của đơn hàng khi đơn hàng có chuyển ngược trạng thái \(\#2742\)
* Fix lỗi giao diện khi mã khiếu nại site gốc quá dài \(\#2742\)
* Khi thay đổi đơn giá và số lượng tự động add comment ở sản phẩm \(\#2742\)

## \[1.13.0\] - 03/11/2020

### Chức năng mới

* Cho phép chọn tài khoản ngân hàng cho cả YCTT thường \(\#2699\)

### Cập nhật cải tiến

* Tách quyền duyệt YCTT thường và duyệt YCTT sửa đổi trên đơn \(\#2699\)
* Fix một số lỗi nhỏ \(\#2680\)
* Tối ưu performance \(\#2371\) \(\#2238\)

## \[1.12.0\] - 14/10/2020

### Chức năng mới

* Thêm luồng đề nghị thay đổi mã hóa đơn gốc, giúp nhân viên ngay cả khi đơn đã mua mà không có quyền thay đổi vẫn có thể gửi đề nghị xét duyệt thay đổi mã hóa đơn gốc cho quản lý/kiểm soát \(\#874\)

### Cập nhật cải tiến

* Bổ sung bộ lọc tìm KNNB theo số tiền thực đòi \(\#2603\)
* Bổ sung bộ lọc theo tính chất TMĐT/Dễ vỡ trên danh sách đơn \(\#2604\)
* Bổ sung các cột thông tin vào báo cáo doanh số \(\#2610\)
* Một số cải tiến về performance \(\#2659\) \(\#2238\)
* Một số cải tiến nhỏ khác \(\#2636\) \(\#2722\)
* Cập nhật logic để nhận giao dịch alipay trùng mã trên cùng 1 file \(\#2552\)
* Công cụ hỗ trợ mua hàng:
  * bổ sung gửi YCTT theo từng đơn \(\#2618\)
  * cải tiến performance của nút Autopai \(\#2616\) \(\#2617\)

## \[1.11.0\] - 01/10/2020

### Chức năng mới

* Cho phép lấy thông tin KNNB từ các hệ thống taobao, tmall, 1688 \(\#2510\) \(\#2509\)
* Cấu hình chế độ duyệt tự động với các lý do mua chậm \(\#2322\)
* Cho phép tự động khớp giao dịch alipay vào KNNB \(\#2513\)

### Cập nhật cải tiến

* Một số cải tiến về hệ thống nhập liệu thông tin sản phẩm \(\#2554\)
* Bổ sung dịch đơn vị tính tiếng Việt với 1 số trường hợp trước đó lỗi \(\#2614\)
* Fix lỗi biểu tượng nguồn hàng hiển thị không chính xác \(\#2635\)
* Cải thiện performance hệ thống

## \[1.10.0\] - 25/09/2020

### Cập nhật cải tiến

* Fix lỗi cấu hình số đơn tối đa nhận & bổ sung cho phép điều chỉnh trạng thái được phép nhận đơn tiếp \(\#2221\)
* Fix một loạt các lỗi nhỏ và cải tiến liên quan đến việc nhập thông tin hải quan \(\#2367\) \(\#2518\)
* Hiển thị tài khoản mua hàng tương ứng nếu ghép được tài khoản alipay khi ĐNTT \(\#2553\)
* Khi thay mã KNNB site gốc, sẽ loại bỏ thông tin KNNB site gốc cũ \(\#2545\)
* Tự động dịch đối với một số thông tin hải quan \(\#2471\)
* Ẩn những đơn không có lý do mua chậm tại giao diện quản lý hiện tại \(\#2291\) 

## \[1.09.0\] - 19/09/2020

### Chức năng mới

* Cho phép lấy thông tin KNNB trên site gốc \(\#2236\)
* Hỗ trợ nhiều đơn vị tiền tệ khác nhau cho các nguồn hàng khác nhau, cho phép nhập mã hóa đơn gốc/mã vận đơn có ký tự alphabet \(cấu hình\) \(\#2467\)

### Cập nhật cải tiến

* Update logic map giao dịch hoàn theo các ký tự đầu mã giao dịch \(\#2463\)
* Hỗ trợ dịch tự động một số từ tiếng Trung \(\#2471\) 

## \[1.8.0\] - 08/09/2020

### Chức năng mới

* Bổ sung các trạng thái đơn hàng sau Đã mua để có thể tìm kiếm được \(\#2188\)
* Tự động nhận diện tài khoản thanh toán khi thanh toán YCTT \(\#2304\)
* Ẩn thông báo yêu cầu xác nh   ận thay đổi số lượng/đơn giá khi khách hàng đã xác nhận \(\#2311\)
* Hiển thị mã KNNB trên site gốc & cho phép link trực tiếp tới KNNB \(\#2312\)

### Cập nhật cải tiến

* Một loạt cải tiến khác liên quan đến việc nhập dữ liệu khai báo hải quan \(đã deploy\)

## \[1.7.0\] - 01/09/2020

### Chức năng mới

* Hiển thị danh sách KNDV trên chi tiết KNNB \(\#1879\)
* Cho phép tạo YCTT lại cho đơn ở trạng thái Đã mua nếu còn mã HĐG chưa thanh toán \(\#2051\)
* Hỗ trợ hiển thị thao tác cuối với KNNB trên KNDV \(\#2182\)
* Tự động đóng KNNB thiếu hàng khi đã nhận đủ hàng \(\#2187\)
* Xác định giao dịch alipay chi cho tài khoản mua hàng nào dựa trên MHĐG & thông tin trên file \(\#2222\)

### Cập nhật cải tiến

* Hiển thị loại file giao dịch alipay trên danh sách file \(\#2231\)
* Sửa bộ lọc thời gian để không bị miss mất phút 23:59 của ngày \(\#2149\)
* Tại chi tiết KNNB khi click vào mã đơn mở giao diện admin \(\#2149\)
* Các bộ lọc thời gian cho phép lọc thời gian dài trên 1 tháng \(vẫn hạn chế khi xuất file\) \(\#2149\)
* Danh sách đơn kiểm soát GDNCC: 
  * click mã đơn mở giao diện admin
  * bổ sung các bộ lọc theo thời gian Hủy, Hết hàng, 
  * tìm kiếm theo mã HĐG
  * hiển thị mã HĐG
  * thay đổi cấu trúc hiển thị cho gọn
  * bổ sung cột mã HĐG trong file xuất

## \[1.6.0\] - 21/08/2020

### Chức năng mới

* Cho phép chọn lý do mua chậm cho đơn đối với đơn YCTT không qua công cụ \(\#2031\)
* Cho phép sử dụng thông tin username, mã đơn ở địa chỉ kho nhận hàng \(\#2024\)
* Cho phép upload file giao dịch alipay mbill \(\#2147\)

### Cập nhật cải tiến

* Ẩn các giao dịch không tham gia vào quá trình tính tài chính đơn trên chi tiết đơn, bao gồm cả trên các hệ thống M2 \(\#2088\)
* Cập nhật logic phân tích giao dịch \(\#2148\)

## \[1.5.0\]

### Chức năng mới

* Hỗ trợ cảnh báo số tiền thanh toán không khớp với YCTT trên công cụ mua hàng \(\#1993\)
* Thêm trạng thái đơn "Chờ thanh toán" để đánh dấu đơn chỉ còn chờ thanh toán \(\#2054\)
* Thêm chức năng sửa thông tin khai báo hải quan của sản phẩm \(\#2089\)

## \[1.4.0\]

### Chức năng mới

* Cho phép chọn tài khoản thực hiện thanh toán của YCTT \(\#1996\)
* Cảnh báo trên YCTT khi tài khoản mua hàng không đúng với thông tin trên đơn \(\#2052\)
* Lấy thông tin đơn vị tính khi sử dụng công cụ hỗ trợ mua hàng \(\#2135\)

## \[1.3.0\]

### Chức năng mới

* Cho phép xuất dữ liệu YCTT \(\#1995\)
* Cho phép ghi chú trên YCTT \(\#2000\)

### Cập nhật cải tiến

* Cải tiến & nâng cấp khả năng tạo YCTT thông qua công cụ hỗ trợ mua hàng \(\#1994\)
* Cho phép sửa số tiền thực thanh toán trên YCTT \(\#1997\)
* Hiển thị mã YCTT \(\#2029\)

## \[1.2.0\]

### Chức năng mới

* Hiển thị log chi tiết cho YCTT \(\#1999\)
* Hiển thị YCTT đã tạo cho GDV để theo dõi được các YCTT do mình tạo \(\#2002\)

## \[1.1.0\]

### Chức năng mới

* Cho phép người dùng tự cấu hình thay đổi thông tin các web mình có trong hệ thống \(\#1594\)

### Cập nhật cải tiến

* Cải thiện performance hệ thống \(\#1933\) \(\#1920\)
* Thêm thông tin khi xuất dữ liệu theo dõi đơn \(\#1991\)
* Một loạt cải tiến nhỏ liên quan YCTT \(\#1992\)
* Một số lỗi lặt vặt khác \(\#1913\)

## \[1.0.0\] - 19/06/2020

### Chức năng mới

* Thể hiện các sản phẩm thừa/thiếu trên KNNB \(chỉ áp dụng khi được kiểm số lượng thực nhận\) \(\#1599\)
* Khi đơn hàng chuyển trạng thái nhưng không có kiện hàng thì hệ thống sẽ tự động tạo KNNB \(chỉ áp dụng cho hệ thống Gobiz\) \(\#1779\)

### Cập nhật cải tiến

* Bổ sung thông tin nhân viên mua hàng trên giao diện kiểm soát đơn \(\#1857\)
* Giao dịch chi thanh toán hộ tự động đánh dấu đã xử lý nếu đã map hết các giao dịch liên quan và tổng giá trị giao dịch đã khớp \(\#1860\)
* Có chức năng fix link 1688 trong trường hợp link bị hết hạn \(\#1861\)
* Cho phép tìm kiếm theo tài khoản giao dịch trên danh sách file upload alipay \(\#1862\)
* Fix logic sai của giao dịch nhờ thanh toán hộ và nhờ hoàn thanh toán hộ \(\#1927\) 

## \[0.29.0\]

### Chức năng mới

* Cho phép click để chat Aliwang với shop trực tiếp từ màn hình chi tiết đơn \(\#1710\)

### Cập nhật cải tiến

* Nâng cấp chức năng điền mã giao dịch trên KNNB, cho phép đánh dấu KNNB đã hoàn thành tài chính \(map đủ giao dịch tương ứng với số tiền hoàn\) \(\#1110\)
* Khi tạo KNNB từ danh sách đơn hàng, thể hiện được đơn vừa được tạo KNNB để đánh dấu cho người tạo KN \(\#1784\)
* Thay đổi lại giao diện chi tiết KNNB \(\#1776\)

## \[0.28.0\]

### Chức năng mới

* Cho phép điền mã giao dịch trên KNNB, tìm kiếm những KNNB chưa điền đủ giao dịch hoặc tổng giao dịch chưa khớp số tiền hoàn \(chưa nên áp dụng vận hành do vẫn còn chức năng cần lên kèm\) \(\#1817\)
* Cho phép đánh dấu đơn hàng Dễ Vỡ \(để phục vụ kiểm soát và cảnh báo trên các hệ thống khác sau này, hiện tại chưa có tác dụng thực tế\) \(\#1781\)

### Cập nhật cải tiến

* Cải tiến trải nghiệm trang quản lý đơn \(\#1787\)

## \[0.27.0\]

### Chức năng mới

* Khi có tích hợp Caresoft, có thể click vào số điện thoại để gọi Caresoft luôn \(\#1602\)
* Cảnh báo những đơn có comment mới của khách \(\#1774\)

### Cập nhật cải tiến

* Fix các vấn đề liên quan cấu hình kho nhận hàng \(\#1777\)
* Tự động đóng KNNB lâu chưa phát hàng khi đơn đã nhận được hàng \(\#1819\)
* Chuẩn bị dữ liệu lợi nhuận mặc cả để sau có thể xuất dữ liệu tổng hợp doanh số \(\#1668\)

## \[0.26.0\]

### Chức năng mới

* Cải thiện hệ thống báo cáo doanh số cho nhân viên mua hàng, đồng thời cho phép nhân viên mua hàng tự xem thống kê doanh số của mình \(\#666\)
* Cho phép bật/tắt việc tạo YCTT để sử dụng quy trình thanh toán qua ngân hàng với cả đơn hàng thường khi cần thiết \(\#1322\)
* Hiển thị các mốc trạng thái của đơn trên đơn hàng \(\#1561\)

### Cập nhật cải tiến

* Cải tiến performance tại danh sách đơn \(\#1465\)
* Fix lỗi không truy cập được danh sách đơn trên thiết bị di động \(\#1773\)
* Fix lỗi không hiển thị thông báo đơn chờ khách xác nhận trên danh sách đơn \(\#1786\)
* Cập nhật thông tin sản phẩm gốc khi autopai, cải thiện dữ liệu sản phẩm phục vụ các mục đích sau này \(\#1808\)

## \[0.25.0\]

### Chức năng mới

* Hệ thống tự tạo KNNB phát hàng thiếu \(\#1557\)
* Cho phép nhân viên đánh dấu NCC xấu để lưu ý cho những lần mua sau \(\#1560\)
* Phân biệt rõ ràng các kho nhận hàng đang được sử dụng và ngừng sử dụng nếu có nhiều kho nhận \(\#1562\)
* Thêm loại giao dịch Alipay: giao dịch Hủy, phân biệt loại giao dịch này và không tính vào trên đơn \(\#1574\)

## Cập nhật cải tiến

* Bổ sung lý do KNNB: đơn chưa hoàn tiền \(\#1573\)
* Bổ sung bộ lọc theo nhân viên mua hàng khi đồng bộ thông tin đơn \(\#1595\)
* Bổ sung bộ lọc giá trị đơn theo Tệ và cho phép sắp xếp theo giá trị đơn \(\#1667\)

## \[0.24.0\] - 18:00 ngày /04/2020

### Chức năng mới

* Tách các cấu hình liên quan giao dịch Alipay thành quyền mới, cho phép phân quyền độc lập với cấu hình hệ thống \(\#1321\)
* Hệ thống tự động tạo KNNB lâu chưa phát hàng, lâu chưa nhận hàng tự động khi đơn sau một khoảng thời gian quy định mà chưa có mã vận đơn, có mã vận đơn mà chưa chuyển trạng thái nhận hàng tại kho \(\#1485\)
* Cảnh báo hàng dễ vỡ theo các từ khóa liên quan trên các web nguồn hàng khi autopai, giúp có thể cân nhắc dịch vụ đóng gỗ \(\#1547\) 

## \[0.23.0\] - 18:00 ngày 10/04/2020

### Chức năng mới

* Tách cấu hình chung hệ thống và cấu hình mua hàng & nhận đơn, cho phép phân quyền khác nhau đối với 2 chức năng này \(\#1319\) \(\#1320\) 

### Cập nhật cải tiến

* Thay đổi giao diện hệ thống KNNB \(\#309\)
* Cho phép gia hạn KNNB mà không cần tiếp nhận \(\#1546\)
* Một số chỉnh sửa trên giao diện danh sách đơn và chi tiết đơn \(\#1579\) \(\#1614\)
* Fix một số lỗi nhỏ của hệ thống liên quan danh sách đơn và phân tích giao dịch Alipay \(\#1518\)

## \[0.22.0\] - 18:00 ngày 18/03/2020

### Chức năng mới

* Cho phép có nội dung ghi chú đối với từng hệ thống web đại lý nếu có sử dụng nhiều hệ thống đại lý \(\#1531\)
* Triển khai giao diện chi tiết đơn mới, giao diện này sử dụng bằng cách truy cập thông qua giao diện danh sách đơn mới \(\#1102\)

### Cập nhật cải tiến

* Thời hạn mặc định của yêu cầu KNNB là ngày hôm sau thay vì ngày hiện tại \(\#1484\)
* Trên danh sách đơn: \(\#1526\)
  * cho phép tìm kiếm thời gian chính xác đến giờ phút
  * cho phép tìm kiếm theo nhiều trạng thái đơn cùng lúc, và cho phép tìm kiếm cả các trạng thái sau đã mua
  * đơn quá hạn mua trở thành một bộ lọc nhanh thay vì trạng thái
  * bổ sung các bộ lọc nhanh: đơn lâu chưa phát hàng \(chưa có mã vận đơn\), đơn lâu chưa nhận hàng \(có mã vận đơn nhưng chưa có hàng\)
  * hiển thị ghi chú đơn ở khu vực comment của khách trên đơn
* Fix một số lỗi giao diện khác

## \[0.21.0\] - 18:00 ngày 11/03/2020

### Chức năng mới

* đối với đơn hàng ngoài cho phép tạo mã đơn gốc ngẫu nhiên \(\#1348\)
* khi đánh dấu đơn hàng ngoài sẽ tự động tăng tỉ lệ đặt cọc lên 100% \(\#1417\)

### Cập nhật cải tiến

* nâng cấp giao diện quản lý nhóm ngành hàng \(\#964\)
* nâng cấp khả năng phát hiện sai lệch sản phẩm trên đơn đã mua và đơn trên hệ thống thông qua việc check logic số lượng sản phẩm tương đối \(\#1091\)
* thêm bộ lọc nhanh đơn lâu chưa phát hàng khi đồng bộ thông tin đơn\(\#1307\)
* bổ sung thêm các quyền liên quan đến YCTT \(\#1347\)
* không tự động xóa mã hóa đơn gốc khi Hủy đơn nữa \(\#1361\)
* cho phép cấu hình lý do mua hàng chậm \(\#1050\)
* sửa một số lỗi và cải tiến nhỏ khác \(\#1424\)

## \[0.20.0\] - 18:00 ngày 25/02/2020

Cập nhật công cụ mua hàng lên Chrome Store phiên bản 0.6.1, cài đặt tại đây: [https://chrome.google.com/webstore/detail/c%C3%B4ng-c%E1%BB%A5-mua-h%C3%A0ng-gobiz/fmknmegefdocamdggpdlcnippgjfelmn](https://chrome.google.com/webstore/detail/c%C3%B4ng-c%E1%BB%A5-mua-h%C3%A0ng-gobiz/fmknmegefdocamdggpdlcnippgjfelmn)

### Chức năng mới

* Cho phép upload file đánh dấu xử lý hàng loạt giao dịch
* Đối với đơn hàng ngoài, cho phép gửi YCTT với thông tin chuyển khoản - và luồng xử lý khác với đơn hàng thường: cần được duyệt trước khi thanh toán
* GDV khi tự mua đơn cũng có thể kiểm tra điều kiện mua hàng thông qua những nút thanh toán tương ứng \(khi cài đặt công cụ mua hàng bản mới nhất sẽ có thêm nút\)
* Giao diện danh sách đơn, đơn đang mua thử nghiệm phiên bản mới
* Mở rộng link YCTT đối với ngân hàng Kiến Thiết Trung Quốc

### Cập nhật cải tiến

* Cải thiện performance giao diện kiểm soát đơn hàng
* Khi upload file khớp mã hóa đơn gốc sẽ không bắt buộc nhập account mua
* Hiển thị tổng tiền giao dịch liên quan/giao dịch
* Cho phép tạo KNNB với đơn ở trạng thái Hủy
* Chuyển việc log lý do mua chậm thành log nội bộ
* Cho phép quét mã giao dịch liên quan của nhiều giao dịch thanh toán hộ cùng lúc
* Bổ sung các logic cho yêu cầu thanh toán:
* không cho hủy đơn khi đơn đang có yêu cầu thanh toán  
* phân quyền hủy đối với những đơn đã có yêu cầu thanh toán
* không cho xóa mã hóa đơn gốc đã có yêu cầu thanh toán
* Fix một số lỗi liên quan YCTT
* Fix lỗi không mở được một số chức năng dù đã được phân quyền 

## \[0.19.0\] - 18:00 ngày 20/12/2019

### Chức năng mới

* Gộp công cụ lấy mã vận đơn tự động vào công cụ autopai, Quý khách có thể chỉ cần cài một công cụ mua hàng là sử dụng được hết các tiện ích của Go Purchasing.

  Hiện tại do công cụ mua hàng chưa được lên Web Store, Quý khách có thể tải bản cài đặt thủ công tại đây.

* Bổ sung chức năng trên công cụ mua hàng: Gửi yêu cầu thanh toán, khi gửi yêu cầu thanh toán hệ thống sẽ kiểm tra giá trị đơn hàng và giá trị hóa đơn gốc để đảm bảo thông tin đơn chính xác
* Quản lý yêu cầu thanh toán: \(\#701-\#707\)
  * danh sách các yêu cầu thanh toán
  * nhận yêu cầu để thực hiện thanh toán
  * đánh dấu yêu cầu thanh toán thành công/thất bại
* Cho phép upload trực tiếp file zip danh sách giao dịch Alipay tải về từ alipay thay vì phải giải nén để upload file CSV \(\#880\)
* Tự động nhận viện tài khoản alipay thông qua nội dung file thay vì phải đặt tên file đúng \(\#881\)
* Thêm thông số file giao dịch alipay chứa giao dịch từ ngày nào đến ngày nào trên danh sách file tải lên và cho phép tìm kiếm. Chức năng chỉ áp dụng cho các file tải sau khi triển khai phiên bản mới. \(\#882\)
* Chức năng quản lý token \(dành cho tài khoản doanh nghiệp 1688\) \(\#507\)
* Công cụ hỗ trợ việc tự động lấy mã giao dịch nhờ thanh toán hộ \(\#721\)
* Cho phép cấu hình loại giao dịch sẽ tính trên đơn \(\#1044\)
* Hỗ trợ dùng file excel để map mã hóa đơn gốc cho một loạt giao dịch

### Cập nhật cải tiến

* Bổ sung icon cho biết giao dịch đã được sửa mã hóa đơn gốc chứ không phải hệ thống tự động nhận diện \(\#977\)
* Sửa lỗi không hủy được đơn khi đơn có mã hóa đơn gốc được điền ở một đơn khác \(\#977\)
* Giới hạn số lượng mã hóa đơn gốc được điền ở giao dịch hoàn thanh toán thường \(\#1042\)
* Cho phép mở mã hóa đơn gốc từ mã hóa đơn gốc ở KNNB \(\#1047\)
* Trên giao diện công cụ lấy thông tin đơn, khi click vào mã đơn mở tab mới thay vì dùng tab cũ \(\#1048\)
* Cho phép tải nhiều ảnh lên cùng lúc ở khối comment trên KNNB \(\#1049\)
* Cho phép đổi lý do KNNB \(\#927\)
* Hỗ trợ cho phép tìm giao dịch theo nhiều loại mốc thời gian \(\#1053\)
* Bỏ quyền API:TOOL \(mặc định mọi user đều có thể dùng công cụ, miễn có quyền thao tác trên hệ thống\) \(\#804\)
* Bổ sung bộ mốc thời gian khác nhau tại danh sách giao dịch Alipay
* Thêm các nút tạo KNNB trên danh sách đơn, chi tiết đơn \(\#885\) \(\#886\)
* Một vài thay đổi nhỏ khác làm mượt giao diện và trải nghiệm

## \[0.18.0\] - 18:00 25/11/2019

### Chức năng mới

* Cho phép từ chối khiếu nại người bán mà không cần ấn tiếp nhận tại chi tiết khiếu nại người bán. Hành động này sẽ tương đương với tiếp nhận sau đó từ chối.
* Lấy đầy đủ thông tin đơn từ 1688 qua API \(đối với tài khoản doanh nghiệp\) để phát hiện đơn có sự sai lệch so với đơn của khách hàng \(\#408\)
* Trên công cụ lấy mã vận đơn, bổ sung lấy thêm các thông tin về sản phẩm, phí vận chuyển nội địa TQ, địa chỉ nhận hàng \(\#406\)
* Tự động phát hiện và cảnh báo những đơn có vấn đề: \(\#410\) \(\#358\) \(\#1005\)
  * có sự chênh lệch về giá trị thanh toán đơn
  * số lượng sản phẩm, link sản phẩm không đúng \(chỉ áp dụng cho đơn 1688 tài khoản doanh nghiệp\)
  * thông tin địa chỉ TQ có không có thông tin mã bill do hệ thống đưa ra
  * đơn ở trạng thái hủy/hết hàng, nhưng có giao dịch thu/chi không khớp
  * đơn đã mua sau 1 ngày mà không có giao dịch alipay
* Chức năng đánh dấu đơn đã được xử lý \(\#412\)
* Bổ sung bộ lọc tại quản lý Giao dịch Nhà cung cấp: đơn đã lấy được đủ thông tin, đơn chưa lấy đủ thông tin, loại vấn đề nghi ngờ với đơn \(\#413\)
* Cho phép xem danh sách các giao dịch nằm trong một file giao dịch alipay đã up lên \(\#641\)

### Cập nhật cải tiến

* Bổ sung log hiển thị thay đổi việc phân tài khoản mua hàng cho xử lý giao dịch bất thường \(\#661\)
* Cho phép có 2 giao dịch trùng mã nhưng ở 2 tài khoản mua hàng khác nhau \(\#961\)
* Bổ sung bộ lọc lý do bất thường tại danh sách giao dịch \(\#720\)
* Cho phép tải lại nội dung comment trên đơn của khách hàng/nội bộ \(\#875\)
* Một số chỉnh sửa giao diện không quan trọng, sửa lỗi giao diện \(\#977\)

## \[0.17.0\] - 18:00 13/11/2019

### Chức năng mới

* Cho phép map giao dịch thanh toán hộ vào giao dịch nhờ thanh toán hộ, nếu tổng giá trị giao dịch khớp nhau thì sẽ đánh dấu giao dịch là bất thường đã xử lý

### Cập nhật cải tiến

* Cải thiện trải nghiệm với công cụ đồng bộ vận đơn
  * Khi web Trung Quốc có captcha thì sẽ dừng việc crawl lại
  * Thêm cảnh báo lỗi: MHĐG đã bị hủy
  * Thêm cảnh báo: đăng nhập không đúng tài khoản \(chỉ áp dụng cho taobao\)
  * Fix lỗi không sử dụng được song song trên 2 account Chrome khác nhau trên cùng máu
  * thông báo về việc chưa cài đặt công cụ crawl khi chưa cài đặt
* Cập nhật chức năng upload file alipay, trong đó sẽ không ghi đè thông tin MHĐG nếu giao dịch đã được xử lý khớp MHĐG thủ công

## \[0.16.0\] - 18:00 05/11/2019

### Cập nhật cải tiến

* Sắp xếp lại menu chương trình sao cho việc phân bố các chức năng khoa học và dễ tìm hơn
* Cập nhật logic map giao dịch với MHĐG để tăng độ chính xác trong việc phân tích giao dịch tự động
* Cho phép đánh dấu đơn hàng mua chậm so với chính sách đặt ra \(nếu có\) lên M2 nhằm hoàn tiền cho khách khi áp dụng chính sách này
* Cải tiến bộ lọc danh sách giao dịch \(username đầy đủ thay vì chỉ có giao dịch viên\)
* Fix lỗi không mở được lịch sử hành động khi có vấn đề với comment trên đơn
* Hiển thị thêm số tiền ở danh sách khiếu nại người bán trên đơn

## \[0.15.0\] - 18:00 30/10/2019

### Chức năng mới

* Cho phép GDV có thể hủy nhanh KNNB ngay tại danh sách KNNB sau khi nhập lý do \(\#594\)
* Hiển thị thông tin đơn tại chi tiết giao dịch để nhanh chóng nắm được tình hình tài chính đơn \(\#724\)
* Bổ sung giao diện chi tiết giao dịch của đơn để theo dõi nhanh các thông tin giao dịch NCC trên đơn \(\#417\)
* Cho phép giới hạn mỗi giao dịch chi thanh toán sẽ chỉ chi cho 1 mã HĐG \(\#725\)
* Hiển thị rõ lý do giao dịch được đánh dấu bất thường trên giao diện danh sách giao dịch \(\#787\)
* Cho phép đánh dấu đơn có sai phạm trong quá trình mua để có thể thống kê, xử lý \(\#411\)  

### Cập nhật cải tiến

* Giao dịch khi được thêm mã hóa đơn gốc sẽ được chuyển trạng thái thành bất thường đã xử lý thay vì mất dấu vết bất thường \(\#723\)
* Cải thiện khả năng tự động phân tích giao dịch \(bao gồm giao dịch hoàn thanh toán hộ, hoàn thanh toán thường\) \(\#789, \#796, \#897\)
* Hiển thị trực tiếp ghi chú của NV kiểm soát trên danh sách giao dịch \(\#794\)
* Phân biệt log thêm mã vận đơn tự động và thêm mã vận đơn thủ công \(\#829\)
* Hiển thị log giao dịch \(\#829\)
* Ẩn các giao dịch không cần phải tính toán vào tài chính đơn \(\#829\)
* Bổ sung thông tin lý do đóng KNNB tại log tự động đóng KNNB \(\#829\)
* Luôn hiển thị danh sách KNNB khi click chuột vào biểu tượng KNNB tại chi tiết đơn thay vì sang luôn chi tiết KNNB đó \(\#829\)
* Fix lỗi liên quan xuất dữ liệu \(T901\)
* Bỏ giới hạn 255 ký tự ở một số trường thông tin lý do của giao dịch, lý do sai phạm trên đơn, lưu ý trên khách hàng \(T912\)
* Fix lỗi sai lý do giao dịch bất thường \(T913\)
* Giao dịch bất thường đã xử lý, sau khi bỏ đánh dấu đã xử lý sẽ check lại nguyên nhân bất thường thay vì mất hết lý do bất thường \(T917\)
* Hiển thị log đơn bị đánh dấu sai phạm\(T916\)

## \[0.14.0\] - 18:00 22/10/2019

### Chức năng mới

* Cho phép đánh dấu giao dịch là bất thường để xử lý \(\#155\)
* Cho phép mở KNNB nhanh từ chi tiết đơn \(khi nhấp chuột vào biểu tượng KNNB\) \(\#608\)
* Cho phép xuất dữ liệu kiểm soát đơn GDNCC \(\#650\)
* Hiển thị, kiểm tra giao dịch alipay thu/chi đối với những đơn hàng Hủy nhưng có giao dịch alipay \(\#665\)
* Chuẩn bị cho phép hiển thị danh sách KNNB trên Hệ thống quản lý đơn \(M2\) \(\#782\)

### Cập nhật cải tiến

* Đổi màu thời gian hết hạn của KNNB để phân biệt KNNB sắp hết hạn, đã hết hạn \(\#596\)

## \[0.13.0\] - 18:00 16/10/2019

### Cập nhật cải tiến

* KNNB lâu chưa phát hàng sẽ tự động đóng khi đơn chuyển sang trạng thái người bán giao kể cả khi KNNB đó chưa có ai tiếp nhận \(\#592\)
* phân quyền cho chức năng tự nhận đơn để khóa chức năng này khi cần thiết \(\#593\)
* bổ sung bộ lọc file giao dịch có dòng lỗi \(\#595\)
* tối ưu việc lấy mã vận đơn tự động trên tài khoản doanh nghiệp trên 1688, tăng hiệu suất xử lý \(\#621\)
* bổ sung logic phân tích mã hóa đơn gốc trên giao dịch alipay dựa theo mã một giao dịch alipay khác \(\#634\)
* cho phép giao dịch chuyển khoản có thể map vào mã hóa đơn gốc \(\#635\)
* cho phép các giao dịch thanh toán hộ được map vào mã hóa đơn gốc nhưng sẽ không tính toán doanh số mua hàng dựa vào các giao dịch này \(\#636\)
* thống kê số lượng giao dịch thu, giao dịch chi trên danh sách file giao dịch \(\#694\)
* fix lỗi không autopai được đối với đơn 1688 \(\#784\)
* trên danh sách đơn để crawl thông tin từ web gốc:
  * thông báo về việc cài đặt công cụ crawl mã vận đơn khi người dùng chưa cài đặt công cụ
  * thêm bộ lọc đã đủ mã vận đơn hay chưa
  * bổ sung bộ lọc trạng thái đối với danh sách đơn crawl mã vận đơn/thông tin đơn \(\#416\)
  * chỉ cho chọn từng tài khoản mua hàng một
* thêm log việc đơn được crawl mã vận đơn lúc nào
* trên danh sách giao dịch alipay:
  * bộ lọc giao dịch alipay chuyển thành được chọn từ danh sách thay vì phải nhập
  * bộ lọc mã giao dịch cho phép nhập các ký tự đầu của mã là tìm kiếm được
  * thêm bộ lọc tìm theo giá trị giao dịch

## \[0.12.0\] - 08/10/2019

* Cho phép hiển thị comment đơn \(với khách, nội bộ\) M2 trên M5

## \[0.11.0\] - 18:00 03/10/2019

### Chức năng mới

* Cho phép xuất dữ liệu đơn hàng phục vụ hạch toán riêng biệt từng web và dữ liệu kiểm soát mua hàng trên từng web \(\#505, \#506\)
* Cho phép sử dụng Chrome Extension để tự động crawl lấy mã vận đơn từ taobao, tmall, 1688

  [https://chrome.google.com/webstore/detail/purchasing-extension/iljhgijnagocdgpondpfjfipifihkccc](https://chrome.google.com/webstore/detail/purchasing-extension/iljhgijnagocdgpondpfjfipifihkccc)

### Cập nhật cải tiến

* Fix lỗi không paste được mã vận đơn, mã hóa đơn gốc khi trong đoạn copy có chứa ký tự trắng

## \[0.10.0\] - 18:00 26/09/2019

### Chức năng mới

* Chuẩn bị nền tảng cho phép hệ thống quản lý đơn \(admin\) hiển thị danh sách giao dịch Alipay \(\#542\)
* Chuẩn bị nền tảng cho công cụ lấy mã vận đơn mới \(\#306\)

### Cập nhật chức năng cũ

* Đổi màu icon thể hiện web của đơn hàng để phân biệt rõ ràng đơn đến từ các web dịch vụ khác nhau \(\#590\)
* Fix lỗi báo cáo doanh số giao dịch viên không format đúng mã hóa đơn gốc  

## \[0.9.0\] - 18:00 26/09/2019

### Cập nhật chức năng cũ

* Phân quyền chặt chẽ hơn để phân quyền giao dịch viên chỉ có thể xem giao dịch bất thường \(\#648\)
* Trên danh sách giao dịch Alipay \(\#649\):
  * thêm dấu âm với giao dịch chi
  * mặc định mở tab mới khi click vào mã đơn
  * thêm bộ lọc người xử lý giao dịch bất thường
  * thêm option cho phép mở tab mới để xem chi tiết giao dịch
* Danh sách đơn kiểm soát mua hàng: thêm bộ lọc trạng thái đơn, account mua hàng \(\#649\)

## \[0.8.0\] - 18:00 24/09/2019

### Chức năng mới

* hiển thị giao dịch Alipay ngay trên đơn
* không cho phép upload file giao dịch Alipay không khớp định dạng \(tên file không phù hợp với tài khoản mua hàng đã có trên hệ thống\)
* cho phép xóa mã hóa đơn gốc khỏi giao dịch Alipay \(giao dịch sẽ trở thành bất thường\)
* cho phép phân cụ thể giao dịch viên quản lý những tài khoản mua hàng nào, và danh sách giao dịch sẽ chỉ hiển thị các giao dịch của các tài khoản mua hàng đó nếu giao dịch viên không có quyền xem tất cả giao dịch

### Cập nhật các chức năng cũ

* cải thiện trải nghiệm đánh dấu đơn hàng ngoài và cho phép tìm kiếm đơn hàng ngoài trên hệ thống mua hàng
* cải thiện danh sách giao dịch mua hàng:
  * thể hiện số tiền giao dịch thu/chi với 2 màu sắc khác nhau
  * cho phép mở chi tiết đơn hàng trên site gốc theo mã hóa đơn gốc
  * hiển thị luôn file upload ra giao dịch đó và cho phép download
  * thêm các bộ lọc: có mã hóa đơn gốc, loại giao dịch thu chi
* cải thiện danh sách kiểm soát đơn mua hàng: thêm bộ lọc thời gian mua
* cải thiện log phân đơn để phân biệt tự nhận đơn và được phân đơn
* tách nhỏ các quyền: upload/download/xem danh sách file alipay
* bổ sung lý do được đánh dấu đã xử lý tự động khi nhập mã hóa đơn gốc cho giao dịch bất thường
* cho phép mở chi tiết đơn trên hệ thống admin \(quản lý đơn\) trên danh sách giao dịch Alipay

## \[0.7.0\] - 18:00 12/09/2019

### Thêm mới

* Thêm màn hình chi tiết giao dịch \(\#211\)
* Cho phép đánh dấu giao dịch NCC bất thường là đã xử lý \(resolved\) \(\#9, \#213\)
* Cho phép thêm ghi chú cho giao dịch NCC \(\#212\) 
* Cho phép xuất CSV danh sách giao dịch NCC \(\#154\)

### Chỉnh sửa

* Fix một loạt lỗi & cải thiện trải nghiệm người dùng \(\#120\)

## \[0.6.3\] - 26/08/2019

* Nhân viên kiểm soát vận hành muốn có thể map được các giao dịch chưa được map tự động với đơn để đảm bảo mọi giao dịch đều gõ nguồn gốc \(\#7\)
* GDV muốn đơn trên M5 có thêm trạng thái "Khách không nhận" để có thể đồng bộ trạng thái từ M2 \(\#293\)
* NV KSVH muốn có thể phân biệt được loại giao dịch để kiểm soát các giao dịch tốt hơn \(\#170\)
* NV KSVH muốn hệ thống không hiển thị các giao dịch không thực nhận để không phải xử lý các giao dịch này \(\#173\)
* KSVH muốn một số giao dịch không map vào đơn để xử lý riêng các giao dịch này \(\#356\)
* Nhân viên kiểm soát vận hành muốn xem được lịch sử giao dịch nhà cung cấp để phát hiện những giao dịch bất thường \(\#6\)
* KSVH muốn có thể phân biệt được giao dịch bất thường để tiến hành kiểm soát giao dịch nhanh hơn \(\#172\)

### Chỉnh sửa

* Báo 4xx không được redirect sang trang mới \(\#421\)
* Quản lý GDV muốn file chiết khấu có thêm cột Web hiển thị đơn của Web nào để có thể áp các chính sách khác nhau theo web nhập hàng \(\#384\)
* Thay đổi vị trí khối thông báo duyệt chuyển thẳng xuống dưới khu vực chọn dịch vụ \(\#401\)

## \[0.6.2\] - 02/08/2019

### Thêm mới

* Đánh dấu, theo dõi đơn hàng ngoài \(\#151\)
* Cảnh báo duyệt chuyển thẳng theo khu vực \(\#33\)
* Quản lý có thể khóa quyền comment nội bộ trên link sản phẩm \(\#246\)

### Chỉnh sửa

* Có thể upload nhiều ảnh trong phần chat \(\#245\)
* Tự động chuyển trạng thái đơn sang "Đã pai" khi tất cả các link sản phẩm đã pai \(\#248\)

## \[0.6.1\] - 01/08/2019

### Chỉnh sửa

* Hỗ trợ nhận nguồn đơn hàng từ nhiều đại lý

## \[0.6.0\] - 22/7/2019

### Thêm mới

* Chức năng Tạo mới Khiếu Nại Người Bán \(KNNB\)
* Chức năng Tiếp nhận & Xử lý KNNB
* Quản lý danh sách KNNB
* Giao Dịch Viên \(GDV\) có thể lưu lại được số tiền thực chi cho Nhà Cung Cấp \(NCC\) và số tiền NCC đã hoàn lại \(\#183\)

