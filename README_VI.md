# Football Booking System

## 📌 Tổng quan

Football Booking System là project thực hành để học **.NET / C#** từ cơ bản đến nâng cao.

Project mô phỏng hệ thống đặt sân bóng thực tế, nơi người dùng có thể:
- đăng ký / đăng nhập
- đặt sân bóng
- quản lý lịch đá
- tính tiền
- xem thống kê doanh thu

Project giúp thực hành:
- OOP
- Collections
- LINQ
- Delegates
- Exception Handling
- Async/Await
- File Handling
- Database
- ASP.NET Core API
- Authentication
- Design Patterns
- Clean Architecture

---

# 🎯 Mục tiêu học tập

Khi làm project này, bạn sẽ thực hành:

## Kiến thức C# cơ bản
- Variables & Data Types
- Conditions & Loops
- Methods
- Classes & Objects
- Constructors
- Encapsulation
- Inheritance
- Polymorphism
- Interfaces
- Abstract Classes

## Kiến thức C# nâng cao
- LINQ
- Delegates
- Action / Func / Predicate
- Generics
- Exception Handling
- Async/Await
- Extension Methods

## Kiến thức .NET
- Dependency Injection
- Logging
- Configuration
- Entity Framework Core
- REST API
- JWT Authentication

---

# ⚽ Chức năng chính

## 👤 Quản lý người dùng
- Đăng ký
- Đăng nhập
- Đăng xuất
- Xem profile
- Phân quyền Admin/User

## ⚽ Quản lý sân bóng
- Thêm sân
- Sửa sân
- Xóa sân
- Xem danh sách sân
- Tìm sân còn trống

## 📅 Hệ thống đặt sân
- Đặt sân
- Hủy sân
- Xem lịch sử đặt sân
- Kiểm tra khung giờ trống

## 💰 Hệ thống thanh toán
- Giá theo giờ
- Giá giờ cao điểm
- Tính tổng tiền

## 📊 Báo cáo & thống kê
- Tổng doanh thu
- Sân được đặt nhiều nhất
- Thống kê booking
- Thống kê người dùng

---

# 🏗 Cấu trúc project gợi ý

```text
FootballBookingSystem/
│
├── Models/
├── DTOs/
├── Interfaces/
├── Services/
├── Repositories/
├── Data/
├── Utils/
├── Exceptions/
├── Controllers/
├── Middleware/
├── Configurations/
├── Program.cs
└── README.md
```

---

# 🚀 Cách tạo project

## Tạo Console App

```bash
dotnet new console -n FootballBookingSystem
```

hoặc:

```bash
dotnet new webapi -n FootballBookingSystem
```

## Chạy project

```bash
dotnet run
```

---

# 🛠 Công nghệ đề xuất

| Mục đích | Công nghệ |
|---|---|
| Ngôn ngữ | C# |
| Framework | .NET 8 |
| Backend API | ASP.NET Core |
| Database | MySQL / SQL Server |
| ORM | Entity Framework Core |
| Authentication | JWT |
| Testing | xUnit |
| Logging | Serilog |

---

# 🎯 Mục tiêu cuối cùng

Xây dựng ứng dụng .NET theo phong cách production:
- clean code
- scalable architecture
- business logic thực tế
- modern backend development
