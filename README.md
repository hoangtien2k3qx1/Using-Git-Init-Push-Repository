# Using-Git-Init-Push-Repository

Để đẩy một dự án lên GitHub bằng cách sử dụng Git, bạn cần thực hiện một số bước cơ bản sau:

1. [Tạo một Repository trên GitHub]()

2. [Khởi tạo dự án và đồng bộ hóa với Git]()
Mở terminal hoặc command prompt và điều hướng đến thư mục dự án của bạn. Sau đó, bạn có thể sử dụng các lệnh sau để bắt đầu:

```xml
# Khởi tạo một repository Git trong thư mục dự án của bạn
git init

# Liên kết repository của bạn với repository trên GitHub
git remote add origin https://github.com/username/repository-name.git

# Đẩy các thay đổi lên repository trên GitHub
git add .
git commit -m "Initial commit"
git branch -M main  # Tên nhánh chính (main) có thể thay đổi tuỳ theo cài đặt mới của GitHub.
git push -u origin master
Nhập thông tin xác thực:
Khi bạn thực hiện lệnh git push, GitHub sẽ yêu cầu bạn cung cấp thông tin xác thực. Bạn cần nhập tên người dùng và mật khẩu của tài khoản GitHub hoặc sử dụng phương pháp xác thực qua SSH.
```

