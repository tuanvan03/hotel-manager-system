# design-a-hotel-manager-system
Hệ thống quản lý khách sạn là phần mềm được xây dựng để xử lý mọi hoạt động trực tuyến của khách sạn một cách dễ dàng và an toàn. Hệ thống này sẽ cung cấp cho ban quản lý khách sạn sức mạnh và sự linh hoạt để quản lý toàn bộ hệ thống.

### Màn hinh quản lí phòng dành cho quản lí

### Màn hình quản lí đặt phòng dành cho lễ tân

### Yêu cầu của hệ thống quản lí khách sạn
1.Phát triển ứng dụng quản lý khách sạn dưới dạng ứng dụng desktop cho máy tính cá nhân. Chỉ những người dùng được ủy quyền mới có thể truy cập ứng dụng, bao gồm nhân viên lễ tân, nhân viên bán hàng và quản lý khách sạn.
2.Cho phép người quản lý khách sạn:
  Thêm, sửa, xóa thông tin phòng.
  Xem báo cáo doanh thu theo thời gian, loại phòng và loại phòng.
  Xem báo cáo về tình trạng phòng trống dựa trên thời gian, loại phòng và loại phòng.
Xem báo cáo về khách hàng thường xuyên đặt phòng dựa trên thời gian và nguồn khách hàng.
3. Cho phép nhân viên lễ tân thực hiện các công việc sau:
  Tìm kiếm phòng trống theo yêu cầu của khách hàng.
  Khách hàng check-in đã đặt phòng hoặc đặt phòng trực tiếp.
  Khách hàng trả phòng.
  Tạo và in hóa đơn thanh toán cho khách hàng.
4.Cho phép nhân viên bán hàng:
  Tìm kiếm các phòng có sẵn.
  Đặt phòng theo yêu cầu của khách hàng.
5. Hiển thị và quản lý thông tin về khách sạn, bao gồm:
  Tên, địa chỉ, đánh giá sao
  Mô tả (văn bản và hình ảnh)
6.Hiển thị và quản lý thông tin về từng phòng, bao gồm:
  Tên phòng(duy nhất)
  Loại phòng
  Giá phòng
  Dịch vụ đi kèm
  Mô tả phòng
7.Nắm bắt và quản lý thông tin về từng khách hàng, bao gồm:
  CMND (CMND hoặc hộ chiếu)
  Loại giấy tờ tùy thân (CMND hoặc hộ chiếu)
  Họ và tên
  Địa chỉ
  Số điện thoại
  Ghi chú dịch vụ đặc biệt (ví dụ: dành cho khách khuyết tật, sở thích ăn chay)
8.Cho phép đặt phòng hoặc sử dụng phòng cho nhiều khách hàng vào các thời điểm khác nhau.
9.Cho phép khách hàng đặt hoặc ở nhiều phòng vào các thời điểm khác nhau.
10.Đảm bảo rằng tại bất kỳ thời điểm nào, chỉ có một khách hàng ở trong một phòng và giá phòng cụ thể cho thời điểm đó.
11.Cho phép khách hàng chỉ đặt phòng nếu phòng đó có sẵn trong thời gian yêu cầu.
12.Cho phép khách hàng thanh toán nhiều lần cho đến ngày trả phòng. Với mỗi lần thanh toán, nhân viên lễ tân sẽ xuất hóa đơn.
13.Hủy phòng:
  Khách hàng có thể hủy đặt phòng miễn phí trước ngày nhận phòng.
  Nếu khách hàng hủy sau ngày đặt, họ sẽ bị thêm vào danh sách đen và có thể bị từ chối đặt chỗ trong tương lai.
