# Trỏ tên miền từ TenTen

Bạn truy cập trang quản trị tên miền của Tenten và nhập thông tin tài khoản:\
&#x20;[https://domain.tenten.vn/](https://domain.tenten.vn/)

1. **Trỏ tên miền chính:**

**Thêm mới** 2 bản ghi sau:

![](<../../.gitbook/assets/Screen Shot 2019-11-28 at 6.14.24 PM copy (1) copy.png>)

Host record: www\
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn

Host record: @\
Type (Loại): A\
Value (Giá trị):  103.126.157.33&#x20;

![](<../../.gitbook/assets/Screen Shot 2019-11-28 at 6.17.51 PM copy (1) copy.png>)

Giả sử tên miền chính của bạn là tenmiencuaban.vn, bạn muốn tạo một tên miền phụ là abc.tenmiencuaban.vn thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: abc\
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn

Sau khi đã trỏ thành công tên miền về hosting của Tempi, bạn cần tiếp tục [tạo và xác thực tên miền tại Tempi.](tao-va-xac-thuc-ten-mien-lai-tempi.md)\
