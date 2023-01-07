# Tích hợp giao thức gửi email
Để Simplemag có thể gửi email cho người dùng, chúng ta có 2 lựa chọn như sau:

1. **Mặc định**: sử dụng dịch vụ gửi email của OSD.VN
2. **SMTP**: dịch vụ SMTP do bạn khai báo

Để thực hiện tích hợp, bạn cần vào **Hệ thống** -> **Tích hợp** -> Tab **Dịch vụ giao tiếp** -> **Giao thức email** -> Chọn **Mặc định** hoặc **SMTP**. Những lựa chọn này sẽ có ý nghĩa như sau:

## 1. Mặc định
OSD.VN trang bị hệ thống gửi email có sẵn cho toàn bộ khách hàng, tuy nhiên, với 1 số website cần gửi thông tin xác nhận với người dùng thì phần thông tin người gửi sẽ không đảm bảo thương hiệu của bạn. 
Những thông tin trong phần người gửi sẽ có:

Tên người gửi: simplemag
Email người gửi: simplemag@due...

## 2. Giao thức SMTP
Tình huống này bạn sẽ đảm bảo được tính nhất quán về thương hiệu, thông tin gửi email sẽ không bị lộ với người sử dụng.

![Cấu hình email với giao thức SMPT](img/email-smtp.jpg)

Thông tin chi tiết cần điền như sau:

### 2.1. From (email)
Là địa chỉ email sẽ xuất hiện tại trường from của email gửi cho khách hàng.

### 2.2. Máy chủ
Điền tên máy chủ SMTP sẽ gửi email. Ví dụ: _smtp.gmail.com_

### 2.3. Tên đăng nhập
Điền tài khoản email dùng để đăng nhập vào máy chủ SMTP. Ví dụ: _osdvn@gmail.com_

### 2.4. Mật khẩu
Điền mật khẩu của khoản email dùng để đăng nhập vào máy chủ SMTP.

### 2.5. Cổng
Điền cổng của máy chủ SMTP. Ví dụ: 25, 465, 587,... 

Trong tình huống máy chủ SMTP không hỗ trợ giao thức bảo mật, bạn sẽ để trống trường này.
