# Trỏ tên miền từ iNET

Bạn truy cập trang chủ của iNET tại [https://inet.vn/](https://inet.vn/) và chọn **Đăng nhập**. Sau đó nhập thông tin tài khoản khách hàng tại iNET để đăng nhập vào hệ thống quản trị.

![](<../../.gitbook/assets/image (3) (1) copy.png>)

![](<../../.gitbook/assets/image (4) copy (1) copy.png>)

## Trỏ tên miền chính

Tại ô **Chọn template** có sẵn bạn chọn **Trỏ về Tempi** và bấm nút có dấu tích màu xanh ở cột bên phải để lưu lại là xong.

![](<../../.gitbook/assets/image (5) copy (1) copy.png>)

2 bản ghi dùng để trỏ tên miền chính về hosting Tempi  :

Host record: www\
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn&#x20;

Host record: @\
Type (Loại): A\
Value (Giá trị):  103.126.157.33

## Trỏ tên miền phụ

Giả sử tên miền chính của bạn là tenmiencuaban.vn, và bạn muốn tạo một tên miền phụ là abc.tenmiencuaban.vn thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: \
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn

Sau khi đã trỏ thành công tên miền về hosting của Tempi, bạn cần tiếp tục [tạo và xác thực tên miền tại Tempi.](tao-va-xac-thuc-ten-mien-lai-tempi.md)\
