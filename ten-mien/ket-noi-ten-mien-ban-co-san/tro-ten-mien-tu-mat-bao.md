# Trỏ tên miền từ Mắt Bão

Bạn truy cập trang quản trị tên miền của Mắt Bão và nhập thông tin tài khoản:\
[https://id.matbao.net/users/login/](https://id.matbao.net/users/login/)

Sau đó, bạn lần lượt chọn:

* Chọn mục **Tên Miền**
* Click vào tên miền cần trỏ&#x20;
* Vào mục **Quản lý DNS**

Mắt Bão hiện tại có 2 giao diện cấu hình trỏ DNS, bạn xem mình đang sử dụng giao diện nào thì làm theo hướng dẫn của giao diện đó.

### Giao diện cũ của Mắt Bão:

1. **Trỏ tên miền chính:**

**Thêm mới** 2 bản ghi sau:

Host record: www\
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn

Host record: @\
Type (Loại): A\
Value (Giá trị): 103.126.157.33

![](<../../.gitbook/assets/Screen Shot 2019-11-28 at 5.43.54 PM copy.png>)

![](<../../.gitbook/assets/Screen Shot 2019-11-28 at 6.00.50 PM copy.png>)

Sau khi thiết lập, danh sách bản ghi hiện 2 dòng như dưới là bạn đã làm đúng cách:

![](<../../.gitbook/assets/Screen Shot 2019-11-28 at 5.46.59 PM copy.png>)

**2. Trỏ tên miền phụ:**&#x20;

Giả sử tên miền chính của bạn là tenmiencuaban.vn, và bạn muốn tạo một tên miền phụ là abc.tenmiencuaban.vn.\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: abc\
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn&#x20;

![](<../../.gitbook/assets/Screen Shot 2019-11-28 at 6.04.24 PM copy.png>)

### Giao diện mới của Mắt Bão:

1. **Trỏ tên miền chính:**

**Thêm mới** 2 bản ghi sau:

Host record: www\
Type (Loại): CNAME\
Value (Giá trị): kdc.tempi.vn

Host record: @\
Type (Loại): A\
Value (Giá trị): 103.126.157.33&#x20;

![](<../../.gitbook/assets/image (7) (1).png>)

![](<../../.gitbook/assets/image (8) copy.png>)

![](<../../.gitbook/assets/image (9) copy.png>)

Sau khi tạo xong, phần danh sách bản ghi hiển thị đủ 2 bản ghi này là bạn đã tạo đúng cách:

![](<../../.gitbook/assets/image (10) copy.png>)

Sau khi đã trỏ thành công tên miền về hosting của Tempi, bạn cần tiếp tục [tạo và xác thực tên miền tại Tempi.](tao-va-xac-thuc-ten-mien-lai-tempi.md)\
