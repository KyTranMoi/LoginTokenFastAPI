# LoginTokenFastAPI

# Cài đặt redis 
Trên Windows:

Tải Redis từ https://github.com/microsoftarchive/redis/releases và cài đặt nó.
Khởi chạy Redis bằng cách mở Command Prompt và chạy redis-server.
# Kiểm tra Redis:

redis-cli ping

# Dùng lệnh taskkill để dừng tiến trình:
taskkill /PID <PID> /F
# Sau khi giải phóng cổng 6379, bạn có thể khởi động lại Redis server:

redis-server
