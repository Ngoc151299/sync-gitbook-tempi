---
hidden: true
---

# Tên Miền

## Bước 1: Trỏ tên miền về hosting của Tempi

_**Trỏ tên miền chính:**_

Vào phần quản trị tên miền ở nơi bạn mua tên miền và cấu hình **2** bản ghi sau để điều hướng tên miền đó về địa chỉ của Tempi:

Host record: **www**\
Type (Loại): **CNAME**\
Value (Giá trị): **dns.tempi.vn**

Host record: @\
Type (Loại): URL Redirect\
Value (Giá trị):   http://www.tenmiencuaban.vn\
Lưu ý: Thay tenmiencuaban.vn thành tên miền bạn đang cấu hình.

_**Trỏ tên miền phụ:**_

Giả sử tên miền chính của bạn là tenmiencuaban.vn, và bạn muốn tạo một tên miền phụ là abc.tenmiencuaban.vn thì:\
Chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới và điền các giá trị như sau:\
Host record: **abc**\
Type (Loại): **CNAME**\
Value (Giá trị): **dns.tempi.vn**

Dưới đây là hướng dẫn cụ thể cho từng nền tảng mà bạn mua tên miền:

{% content-ref url="tro-ten-mien-tu-inet.md" %}
[tro-ten-mien-tu-inet.md](tro-ten-mien-tu-inet.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-hostvn.md" %}
[tro-ten-mien-tu-hostvn.md](tro-ten-mien-tu-hostvn.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-tenten.md" %}
[tro-ten-mien-tu-tenten.md](tro-ten-mien-tu-tenten.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-mat-bao.md" %}
[tro-ten-mien-tu-mat-bao.md](tro-ten-mien-tu-mat-bao.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-pa-viet-nam.md" %}
[tro-ten-mien-tu-pa-viet-nam.md](tro-ten-mien-tu-pa-viet-nam.md)
{% endcontent-ref %}

## Bước 2: Tạo và xác thực tên miền tại Tempi

{% content-ref url="tao-va-xac-thuc-ten-mien-lai-tempi.md" %}
[tao-va-xac-thuc-ten-mien-lai-tempi.md](tao-va-xac-thuc-ten-mien-lai-tempi.md)
{% endcontent-ref %}
