# 🚀 Hướng dẫn Cài đặt Môi trường Phát triển Dự án Sasuke

Chào mừng team Dev đến với dự án **Sasuke (Matching App)**. 
Tài liệu này hướng dẫn cách chạy toàn bộ dự án (Database, Backend, Frontend) ở môi trường Local chỉ với vài lệnh cơ bản.

## 📋 1. Yêu cầu hệ thống (Prerequisites)
Trước khi bắt đầu, hãy đảm bảo máy tính của bạn đã cài đặt các phần mềm sau:
- **Git** (Để pull code về)./ Github Desktop tùy
- **Docker Desktop** (Bắt buộc phải bật lên để chạy Database MySQL).
- **Node.js** (Phiên bản 18.x trở lên) & npm (Dành cho Next.js).
- **Java 21** (JDK 21) & IDE (IntelliJ IDEA / VS Code / Eclipse) (Dành cho Spring Boot).

---

## 🛠 2. Các bước khởi chạy dự án

### Bước 1: Khởi động Database (MySQL)
Dự án sử dụng Docker để đồng bộ môi trường CSDL cho toàn team.
1. Mở phần mềm **Docker Desktop** và đảm bảo nó đang chạy (Engine running). - nhớ tải
2. Mở Terminal tại **thư mục gốc** của dự án và chạy lệnh:
   ```bash
   docker-compose up -d