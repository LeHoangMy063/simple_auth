# Hướng dẫn triển khai Simple Authentication trong Node.js

# Hướng dẫn chạy và kiểm thử Basic Authentication
Ứng dụng 'simple_auth' minh họa cách sử dụng **Basic Authentication** trong Node.js.

# Giới thiệu

Repo này minh họa 2 phương pháp xác thực phổ biến trong Node.js:

- `Basic Authentication (basic_auth.js)`: Client gửi thông tin đăng nhập trực tiếp trong header Authorization.
- `Cookie-based Authentication (cookie_auth.js)`: Client gửi thông tin đăng nhập qua API /login, server tạo cookie lưu trạng thái đăng nhập, và client sẽ gửi cookie trong các request sau.
---
# Cài đặt & chạy ứng dụng

Clone repo về máy:
```bash 
    git clone <https://github.com/LeHoangMy063/simple_auth>
    cd simple_auth

Cài dependencies:

  npm install
