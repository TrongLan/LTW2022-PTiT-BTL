# LTW2022-PTiT-BTL
Đây là bài tập lớn môn lập trình web tại PTIT.

# MÔ TẢ HỆ THỐNG
- Cho phép người dùng đăng ký tài khoản trên hệ thống. Thông tin tài khoản gồm email, tên tài khoản, mật khẩu.
- Người dùng đã đăng ký tài khoản có thể đăng nhập, đổi mật khẩu, viết bài, đăng bài viết lên trên hệ thống; có thể bình luận, đánh giá sao, báo cáo các bài viết của người dùng khác.
- Với nhóm người dùng chưa đăng ký tài khoản thì không được đăng tải bài viết, chỉ được tìm kiếm theo chủ đề, tiêu đề và xem các bài viết trên hệ thống nhưng không được bình luận đánh giá.
- Một tài khoản có thể đăng tải nhiều bài viết, được chỉnh sửa hoặc xóa bài viết của mình.
- Khi viết bài, người viết chọn chủ đề cho bài viết đó, bài viết cần có tiêu đề và nội dung (trang viết bài giống như trình soạn thảo văn bản)
- Một bài viết có thể nhận được nhiều bình luận, được chấm điểm đánh giá từ các tài khoản người dùng khác.
- Đối với người quản trị:
  - Có quyền xóa bất kỳ tài khoản, bài viết, bình luận (việc xóa dựa vào các báo cáo của các tài khoản về một bài viết/một tài khoản, quản trị viên sẽ quyết định có xóa hay không)
  - Thống kê bài viết theo chủ đề và điểm đánh giá cao trong tuần/tháng.
  - Thêm chủ đề mới trên ứng dụng

# MỘT VÀI MÀN HÌNH DEMO
- Trang khách
- Trang admin
  
- Trang người dùng

# QUÁ TRÌNH THỰC HIỆN BLOGGLE PROJECT & ĐÓNG GÓP CỦA CÁC THÀNH VIÊN
GIAI ĐOẠN I: PHÂN TÍCH THIẾT KẾ (Lân, Trí, Thanh)
- Xây dựng, phân tích yêu cầu chức năng
- Thiết kế cơ sở dữ liệu
- Thiết kế giao diện

GIAI ĐOẠN II: CHUẨN BỊ PROJECT
- Tạo project Spring Boot, thêm các thư viện cần thiết (Trí)
- Code các lớp thực thể, cấu hình project kết nối với cơ sở dữ liệu (Thanh, Trí)
- Tạo cấu trúc thư mục trong project (Lân)

GIAI ĐOẠN III: LÀM CHỨC NĂNG ĐĂNG NHẬP (Thanh)
- Tìm hiểu Spring Security
- Thực hiện phân quyền truy nhập cho admin và người dùng

GIAI ĐOẠN IV: LÀM CÁC CHỨC NĂNG CỦA ADMIN
- Xem danh sách tài khoản, xóa tài khoản (Trí)
- Xem xếp hạng bài viết trong tuần theo chủ đề (Lân)
- Xem danh sách bài viết bị báo cáo, xóa bài viết (Lân)
- Thêm và sửa chủ đề (Thanh)

GIAI ĐOẠN V: LÀM CÁC CHỨC NĂNG CỦA NGƯỜI DÙNG
- Đăng ký tài khoản (mã hóa mật khẩu, validate dữ liệu) (Thanh, Lân)
- Đổi mật khẩu (dùng cho cả tài khoản admin) (Trí)
- Đăng tải, chỉnh sửa, xóa bài viết (Lân, Trí, Thanh)
- Đăng, xóa bình luận (Lân, Thanh)
- Chấm điểm bài viết (đánh giá theo sao) (Lân)

GIAI ĐOẠN VI: CODE GIAO DIỆN (Lân)
- Giao diện khách
- Giao diện Admin
- Giao diện người dùng
