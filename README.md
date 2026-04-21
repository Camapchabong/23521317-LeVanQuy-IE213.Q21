# BÁO CÁO THỰC HÀNH - KỸ THUẬT PHÁT TRIỂN HỆ THỐNG WEB

## 1. Thông tin sinh viên

- **Họ tên:** Lê Văn Quý
- **MSSV:** 23521317
- **Môn học:** IE213.Q21 – Kỹ thuật phát triển hệ thống Web
- **Lớp:** IE213.Q21.2

---

## 2. Cấu trúc thư mục

```
23521317-LeVanQuy-IE213.Q21
│
├── README.md
├── Lab01
├── Lab02
├── Lab03
├── Lab04
├── Lab05
└── Lab06
```

## 3. Danh sách các Lab

### Lab01

Nội dung chính:

- Thiết lập và cấu hình MongoDB Atlas.
- Kết nối thông qua MongoDB Compass.
- Tạo cơ sở dữ liệu (database) và các bộ sưu tập (collection).
- Thực hiện các thao tác CRUD bằng mongosh.
- Thực hiện các câu lệnh truy vấn.

### Lab02

Nội dung chính:

- Thiết lập môi trường NodeJS
- Khởi tạo server với ExpressJS
- Kết nối MongoDB Atlat
- Kiến trúc mã nguồn theo mô hình DAO – Controller – Route
- Xây dựng API /api/v1/movies để truy xuất dữ liệu movies

### Lab03

Nội dung chính:

- Xây dựng chức năng Review (POST, PUT, DELETE)
- Tạo Controller và DAO cho review
- Hoàn thiện API backend
- Thêm API nâng cao

### Lab04

Nội dung chính:

- Hiểu cách thiết lập phần frontend trong mô hình MERN Stack bằng ReactJS.
- Giới thiệu một số package quan trọng thường dùng trong quá trình xây dựng mã nguồn frontend.
- Thực hành xây dựng thanh điều hướng (Navigation Header Bar) với sự hỗ trợ của Bootstrap.
- Nắm được cách phân chia và tổ chức các component trong dự án.

### Lab05

### Lab06

## 4. Cách chạy chương trình

### Hướng dẫn cho Lab01:

- Đăng nhập: Truy cập vào tài khoản MongoDB Atlas.
- Kết nối: Copy chuỗi kết nối (Connection String) và dán vào MongoDB Compass để truy cập Cluster.
- Mở Shell: Sử dụng terminal hoặc Mongo Shell (mongosh) đã tích hợp sẵn.
- Thực thi: Mở các file script trong thư mục Lab01 và chạy các lệnh tương ứng trên Shell.

### Hướng dẫn cho Lab02:

- Mở Terminal tại thư mục dự án và cài đặt dependency npm install
- Chạy server bằng câu lệnh npm run start
- Truy cập API http://localhost:3000/api/v1/movies

### Hướng dẫn cho Lab03:

- Di chuyển vào thư mục backend cd lab02/movie-reviews/backend
- Cài đặt dependency npm install
- Chạy server npm start
- Truy cập API http://localhost:3000/api/v1/movies

### Hướng dẫn cho Lab04:

Di chuyển vào thư mục frontend bằng lệnh: cd Lab04/movie-reviews/frontend
Cài đặt các dependency cần thiết bằng lệnh: npm install
Khởi chạy ứng dụng bằng lệnh: npm start
Truy cập giao diện tại địa chỉ: http://localhost:3000
