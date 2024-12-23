# Dự Án JobHunter

JobHunter là nền tảng tìm kiếm việc làm, giúp người dùng tìm việc và ứng tuyển trực tuyến. Backend sử dụng Spring Boot, frontend sử dụng React.js.

## Các Tính Năng Chính

### Người Dùng Chưa Đăng Nhập:
- Đăng ký/Đăng nhập.
- Xem danh sách công ty và công việc.
- Tìm kiếm công việc theo kỹ năng và vị trí.

### Người Dùng Đã Đăng Nhập:
- Rải CV và xem lịch sử rải CV.
- Đăng ký nhận email theo kỹ năng.

### Phân Quyền:
- **Admin**: Quản lý người dùng, công ty, công việc.
- **Người Dùng Thường**: Quyền hạn hạn chế, không phân quyền đặc biệt.

## Phân Quyền Người Dùng
- **Backend**: Phân quyền qua **Interceptor** và các API.
- **Frontend**: Kiểm tra quyền truy cập dựa trên trạng thái đăng nhập và quyền của người dùng.

## Frontend Dự Án

 Frontend được phát triển bằng **React.js** và không phải do tôi làm. Bạn có thể tham khảo mã nguồn tại [Jobhunter-reactJs](https://github.com/tugithubbb/Jobhunter-reactJs). -->

