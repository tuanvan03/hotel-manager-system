# Đoàn Văn Tuấn - MSV 21000523
# Hệ Thống Quản Lý Khách Sạn

Hệ thống Quản Lý Khách Sạn là một ứng dụng desktop được thiết kế để tối ưu hóa và bảo mật tất cả các hoạt động trực tuyến của một khách sạn. Hệ thống này trang bị cho đội ngũ quản lý khách sạn sức mạnh và linh hoạt để quản lý toàn bộ hoạt động khách sạn một cách hiệu quả.

## Giao Diện

### Màn Hình Quản Lý Phòng (dành cho Quản Lý)

### Màn Hình Quản Lý Đặt Phòng (dành cho Lễ Tân)

## Yêu Cầu Hệ Thống

1. **Loại Ứng Dụng:** Phát triển ứng dụng desktop cho máy tính cá nhân. Chỉ người dùng được ủy quyền mới có thể truy cập ứng dụng, bao gồm nhân viên lễ tân, nhân viên bán hàng và quản lý khách sạn.

2. **Chức Năng Quản Lý:**
   - Thêm, sửa, xóa thông tin phòng.
   - Xem báo cáo doanh thu theo thời gian, loại phòng và hạng phòng.
   - Xem báo cáo về tình trạng phòng trống dựa trên thời gian, loại phòng và hạng phòng.
   - Xem báo cáo về khách hàng thường xuyên đặt phòng dựa trên thời gian và nguồn khách hàng.

3. **Chức Năng Lễ Tân:**
   - Tìm kiếm phòng trống theo yêu cầu của khách hàng.
   - Check-in khách hàng đã đặt phòng hoặc đặt phòng trực tiếp.
   - Trả phòng cho khách hàng.
   - Tạo và in hóa đơn thanh toán cho khách hàng.

4. **Chức Năng Bán Hàng:**
   - Tìm kiếm các phòng có sẵn.
   - Đặt phòng theo yêu cầu của khách hàng.

5. **Quản Lý Thông Tin Khách Sạn:**
   - Hiển thị và quản lý thông tin về khách sạn, bao gồm tên, địa chỉ, đánh giá sao.
   - Mô tả (văn bản và hình ảnh).

6. **Quản Lý Thông Tin Phòng:**
   - Tên phòng duy nhất.
   - Loại phòng.
   - Giá phòng.
   - Dịch vụ đi kèm.
   - Mô tả phòng.

7. **Quản Lý Thông Tin Khách Hàng:**
   - CMND (Chứng minh nhân dân hoặc hộ chiếu).
   - Loại giấy tờ tùy thân (CMND hoặc hộ chiếu).
   - Họ và tên.
   - Địa chỉ.
   - Số điện thoại.
   - Ghi chú dịch vụ đặc biệt (ví dụ: dành cho khách khuyết tật, sở thích ăn chay).

8. **Đặt Phòng và Quản Lý Điều Kiện:**
   - Cho phép đặt phòng hoặc sử dụng phòng cho nhiều khách hàng vào các thời điểm khác nhau.
   - Cho phép khách hàng đặt hoặc ở nhiều phòng vào các thời điểm khác nhau.
   - Đảm bảo rằng tại bất kỳ thời điểm nào, chỉ có một khách hàng ở trong một phòng và giá phòng cụ thể cho thời điểm đó.

9. **Hạn Chế Đặt Phòng:**
   - Cho phép khách hàng chỉ đặt phòng nếu phòng đó có sẵn trong thời gian yêu cầu.
   - Cho phép khách hàng thanh toán nhiều lần cho đến ngày trả phòng, với mỗi lần thanh toán, nhân viên lễ tân sẽ xuất hóa đơn.

10. **Chính Sách Hủy Phòng:**
    - Khách hàng có thể hủy đặt phòng miễn phí trước ngày nhận phòng.
    - Nếu khách hàng hủy sau ngày đặt, họ sẽ bị thêm vào danh sách đen và có thể bị từ chối đặt chỗ trong tương lai.
