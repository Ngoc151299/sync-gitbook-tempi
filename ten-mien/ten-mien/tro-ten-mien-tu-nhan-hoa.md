# Trỏ tên miền từ Nhân Hoà

Bạn truy cập trang quản trị tên miền của Nhân Hòa và nhập thông tin tài khoản:\
[https://zonedns.vn/](https://zonedns.vn/)

1. **Trỏ tên miền chính:**

**Thêm mới** 2 bản ghi sau:

Host record: www\
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn

Host record: @\
Type (Loại): A\
Value (Giá trị): 103.126.157.33

![](<../../.gitbook/assets/1421808992\_tao\_record (1) copy (1) copy (1).png>)

![](<../../.gitbook/assets/1421808992\_tao\_record (1.1) (1) copy.png>)

**2. Trỏ tên miền phụ:**&#x20;

![](<../../.gitbook/assets/1421808992\_tao\_record (1.3) (1) copy.png>)

Giả sử tên miền chính của bạn là tenmiencuaban.vn, bạn muốn tạo một tên miền phụ là abc.tenmiencuaban.vn thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: abc\
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn

Sau khi đã trỏ thành công tên miền về hosting của Tempi, bạn cần tiếp tục [tạo và xác thực tên miền tại Tempi.](tao-va-xac-thuc-ten-mien-lai-tempi.md)
