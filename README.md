# My New Project

Đây là repository được tạo để thực hành quy trình làm việc cơ bản với Git và GitHub.

## Mục tiêu

- Tạo Local Repository bằng Git.
- Kết nối Local Repository với Remote Repository trên GitHub.
- Thêm file vào Staging Area.
- Tạo commit.
- Push commit lên GitHub.

## Các lệnh Git đã sử dụng

### git init

Khởi tạo một Git Repository mới trong thư mục hiện tại.

### git remote add origin <repository-url>

Liên kết Local Repository với Remote Repository trên GitHub.

- origin: tên đại diện cho Remote Repository.
- repository-url: địa chỉ Repository trên GitHub.

### git add README.md

Đưa file README.md vào Staging Area để chuẩn bị commit.

### git commit -m "Add README.md file"

Tạo một commit để lưu lại trạng thái của các file đã được đưa vào Staging Area.

Tùy chọn -m dùng để thêm thông điệp mô tả nội dung của commit.

### git branch -M main

Đổi tên nhánh hiện tại thành main.

### git push -u origin main

Đẩy các commit của nhánh main từ Local Repository lên Remote Repository có tên origin.

Tùy chọn -u thiết lập nhánh main local theo dõi nhánh main trên remote.

## Kết quả

File README.md đã được commit và push lên GitHub thành công.
