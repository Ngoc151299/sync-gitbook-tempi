# Trỏ tên miền từ GoDaddy

Truy cập trang quản trị tên miền của GoDaddy và nhập thông tin tài khoản. Trong phần **Domain Manager (Quản lý tên miền),** bấm chọn vào tên miền bạn muốn trỏ.

Kéo xuống phần **Additional Setting (Thiết lập bổ sung)** và chọn **Manage DNS:**

<figure><img src="../../.gitbook/assets/image (7) (2).png" alt=""><figcaption></figcaption></figure>

## Trỏ tên miền chính:

Thêm mới 2 bản ghi sau:

Host record: www\
Type (Loại): CNAME\
Points to: kdc.tempi.vn

Host record: @\
Type (Loại): A\
Value (Giá trị): 103.126.157.33\
_Lưu ý: Thay tenmiencuaban.vn thành tên miền bạn đang cấu hình._

## Trỏ tên miền phụ:

Giả sử tên miền chính của bạn là tenmiencuaban.vn, và bạn muốn tạo một tên miền phụ là abc.tenmiencuaban.vn\
Chọn tên miền chính bạn muốn cài đặt. Sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: abc\
Type (Loại): CNAME\
Points to: kdc.tempi.vn

<figure><img src="../../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

Sau khi đã trỏ thành công tên miền về hosting của Tempi, bạn cần tiếp tục [tạo và xác thực tên miền tại Tempi.](tao-va-xac-thuc-ten-mien-lai-tempi.md)\
