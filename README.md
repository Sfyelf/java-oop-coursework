# Java OOP Coursework

Repository này tổng hợp các bài tập môn Lập trình hướng đối tượng (Java), gồm nhiều bài độc lập theo từng chủ đề.

## Cấu trúc chính

- `JUnit/`:
  - `Week4.java`: các hàm xử lý cơ bản (`max2Int`, `minArray`, `calculateBMI`).
  - `Week4Test.java`: test JUnit cho các hàm trong Week4.
- `QuanLySinhVien/`:
  - `Student.java`, `StudentManagement.java`: mô hình quản lý sinh viên và nhóm lớp.
- `Transaction/` và `Tuan5/src/`:
  - Bài tập tài khoản ngân hàng với chức năng nạp/rút tiền và in lịch sử giao dịch.
- `JavaFX-demo/`, `TestJavaFx/`:
  - Dự án Maven JavaFX mẫu (`HelloApplication`, `HelloController`, FXML).

## Yêu cầu môi trường

- JDK 22 (các dự án Maven JavaFX đang cấu hình `target release: 22`).
- Maven (hoặc dùng Maven Wrapper `mvnw` trong từng thư mục JavaFX).

## Cách chạy nhanh

### 1) Chạy test cho dự án Maven

```bash
cd /tmp/workspace/Sfyelf/java-oop-coursework/JavaFX-demo
sh mvnw test
```

```bash
cd /tmp/workspace/Sfyelf/java-oop-coursework/TestJavaFx
sh mvnw test
```

### 2) Chạy các bài Java thuần

Biên dịch/chạy trực tiếp bằng `javac` và `java` trong từng thư mục bài tập như `JUnit/`, `QuanLySinhVien/`, `Transaction/`, `Tuan5/src/`.

## Ghi chú

- Trong repository có một số file `.zip` là bản nén của từng bài tập.
- Mỗi thư mục là một bài độc lập, có thể học/chạy riêng.
