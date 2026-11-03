# Phần 1. Phân tích
• So sánh sự đánh đổi giữa dung lượng Cache (MB/GB) và Cookies (~4KB) trong việc lưu trữ dữ liệu người dùng.
CACHE : Được lưu vào Ram dung lượng lớn 
dung lượng lớn 
COOKIES : Lưu trữ trình duyệt dung lượng Ram nhỏ 
tốc độ nhanh dung lượng ít 

# Phần 2. Triển khai
• Mô tả cấu trúc mẩu tin Cookie cần thiết (bao gồm Token, Max-Age, và các cờ bảo mật).

Token:  token là chuỗi kí tự mã hóa 
Max- Age:  là thời gian kí tự token tồn tại 
các cờ bảo mật :



# Phần 3. Kiểm thử
• Nếu shipper thay đổi giao diện nhưng trình duyệt vẫn hiện màu cũ, hãy hướng dẫn thao tác Hard Reload để xóa Cache đệm.

Giao diện đã cập nhật trên server nhưng trình duyệt vẫn hiển thị màu cũ, ảnh cũ, giao diện cũ 
Lý do: Trình duyệt lưu tệp vào đệm để tải nhanh  không tự tải phiên bản mới

Dùng khi phím tắt chưa đủ  áp dụng cho Chrome / Edge:

1.  Nhấn `F12` hoặc chuột phải  **Kiểm tra** (DevTools mở ra)
2.  **Nhấn giữ** nút Tải lại  trên thanh địa chỉ
3.  Chọn: **"Xóa đệm và Tải lại cứng"** (Empty Cache and Hard Reload)
4.  Trình duyệt xóa toàn bộ dữ liệu cũ của trang  tải trực tiếp từ server phiên bản mới nhất

