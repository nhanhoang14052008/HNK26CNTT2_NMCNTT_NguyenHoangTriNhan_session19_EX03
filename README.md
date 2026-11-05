# 1. Input (Đầu vào)
Backup Codes (mã dự phòng) đã được tạo và lưu trữ an toàn trước đó.

Tài khoản AWS cần khôi phục quyền truy cập.

Thông tin xác thực tài khoản (username/password).

# 2. Process (Xử lý)
Truy cập trang đăng nhập AWS chính thức.

Nhập username và password của tài khoản.

Khi hệ thống yêu cầu mã MFA, chọn phương thức sử dụng Backup Codes.

Nhập một mã dự phòng chưa sử dụng để xác thực.

Sau khi đăng nhập thành công, gỡ bỏ thiết bị Google Authenticator cũ khỏi tài khoản.

Hủy các Backup Codes cũ và tạo bộ Backup Codes mới.

Thiết lập MFA trên thiết bị mới và lưu mã dự phòng ở nơi an toàn.

# 3. Output (Đầu ra)
Khôi phục quyền truy cập tài khoản AWS.

Thiết bị MFA cũ không còn được tin cậy.

Backup Codes cũ bị vô hiệu hóa.

Bộ mã dự phòng mới được bảo vệ an toàn.

Hệ thống tiếp tục hoạt động và giảm nguy cơ bị truy cập trái phép.

# 4. Tại sao không được lưu Backup Codes dưới dạng ảnh trong thư viện điện thoại?
Nếu mất điện thoại, kẻ nhặt được có thể xem ảnh chứa Backup Codes.

Ảnh có thể tự động đồng bộ lên Google Photos hoặc iCloud.

Nếu tài khoản lưu trữ ảnh bị xâm nhập, mã dự phòng cũng có thể bị đánh cắp.

Kẻ xấu có thể sử dụng mã để vượt qua bước xác thực MFA.

Giải pháp: Lưu Backup Codes trong trình quản lý mật khẩu an toàn hoặc bản giấy cất tại nơi bảo mật, không lưu trực tiếp trong thư viện ảnh điện thoại.
