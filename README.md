<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400">
  </a>
</p>

<p align="center">
  <a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

---

# 📦 WEBSITE QUẢN LÝ KHO ĐIỆN TỬ

## 👤 Thông tin cá nhân

- Họ và tên: **Nguyễn Việt Tiến**  
- Mã sinh viên: **23010848**

---

## 📝 Mô tả dự án

Website hỗ trợ quản lý kho điện tử bao gồm:
- Quản lý sản phẩm, danh mục, nhà cung cấp
- Quản lý hóa đơn nhập/xuất, tồn kho
- Nhắc nhở xử lý đơn, gửi mail tự động
- Giao diện dễ sử dụng, có xác thực người dùng
- ![image](https://github.com/user-attachments/assets/0908c59f-b105-4799-9b8b-3c661539e7d8)
- các chức năng chính của dự án
- ![image](https://github.com/user-attachments/assets/de9565dd-dfe2-46b9-923c-f93ced31432e)


Ứng dụng được xây dựng bằng **Laravel**, với cơ sở dữ liệu **MySQL**, giao diện bằng **Tailwind CSS**, kết hợp **AJAX** và các chức năng như Reminder, Alert...

---
mô hình use case 
![image](https://github.com/user-attachments/assets/a583e9df-6711-4cd2-b99d-4d354097f3c5)


## 🔐 Tài khoản mẫu để đăng nhập hệ thống

🔑 Admin

Tài khoản: admin

Mật khẩu: 123456


---

## 🧰 Công nghệ sử dụng

- ⚙️ PHP (Laravel Framework)
- 🌐 Laravel Breeze
- 🎨 Tailwind CSS (frontend)
- 🐬 MySQL (Aiven / XAMPP)
- 📬 Laravel Mail & Scheduler
- ⚡ AJAX (jQuery)
- 🔔 SweetAlert (Laravel Alert)

---

## 🚀 Cài đặt & Chạy thử

```bash
git clone https://github.com/23010848/WEB_Quan_Li_Kho_Hang_Dien_Tu.git
cd WEB_Quan_Li_Kho_Hang_Dien_Tu
composer install
npm install
cp .env.example .env
php artisan key:generate
php artisan migrate
✨ Chức năng chính
Quản lý sản phẩm & danh mục

Quản lý nhà cung cấp

Quản lý hoá đơn nhập, xuất

Nhắc việc và gửi email tự động

Thống kê báo cáo tồn kho và doanh thu

Quản lý người dùng và phân quyền

🔐 Bảo mật hệ thống
CSRF protection: @csrf

Chống XSS: dùng {{ }} và escape đầu vào

Validation đầu vào người dùng

Middleware auth, verified, throttle

Sử dụng Gate để phân quyền

Dùng Query Builder để tránh SQL Injection

📚 Về Laravel Framework
Laravel là framework PHP hiện đại với cú pháp dễ hiểu, hỗ trợ phát triển ứng dụng web nhanh chóng và bảo mật. Laravel cung cấp:

Routing đơn giản

Container quản lý phụ thuộc mạnh mẽ

ORM Eloquent trực quan

Migrations đồng bộ CSDL

Job queue & event broadcasting

👉 Tài liệu chính thức Laravel

💡 Học Laravel
📘 Laravel Docs

🎥 Laracasts – hơn 2000 video học Laravel, PHP, testing, JS...

🤝 Góp ý / đóng góp
Cảm ơn bạn đã quan tâm đến dự án. Bạn có thể tạo Issue hoặc Pull Request nếu muốn đóng góp thêm tính năng hoặc báo lỗi.

📜 License
Dự án này và Laravel đều theo giấy phép MIT License.

🔗 Liên kết repo
🌐 GitHub: github.com/23010848/WEB_Quan_Li_Kho_Hang_Dien_Tu
