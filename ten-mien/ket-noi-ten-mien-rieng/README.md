---
description: Hướng dẫn chi tiết Cách kết nối tên miền riêng của bạn về Tempi
---

# Kết nối tên miền riêng

## **Bước 1: Trỏ tên miền về Hosting của Temp**i

_**Trỏ tên miền chính:**_

Vào phần quản trị tên miền ở nơi bạn mua tên miền và cấu hình **2** bản ghi sau để điều hướng tên miền đó về địa chỉ của Tempi:

**Bản ghi bắt buộc**

Tên (Host record): **@**\
Type (Loại): **A**\
Value (Giá trị): **103.126.157.33**

**Bản ghi tuỳ chọn**

Tên (Host record): **www**\
Type (Loại): **CNAME**\
Value (Giá trị): **kdc.tempi.vn**

{% hint style="info" %}
Khi thêm bản ghi này, truy cập tên miền www.example.com sẽ được chuyển hướng về tên miền example.com
{% endhint %}

_**Trỏ tên miền phụ:**_

Giả sử tên miền chính là example.com, và bạn muốn tạo một tên miền phụ là abc.example.com thì chọn tên miền chính bạn muốn cài đặt, sau đó tạo một bản ghi mới với các giá trị như sau:\
Tên (Host record): **abc**\
Type (Loại): **CNAME**\
Value (Giá trị): **kdc.tempi.vn**

Dưới đây là hướng dẫn cụ thể cho từng nền tảng mà bạn mua tên miền:

{% content-ref url="tro-ten-mien-tu-nhan-hoa.md" %}
[tro-ten-mien-tu-nhan-hoa.md](tro-ten-mien-tu-nhan-hoa.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-mat-bao.md" %}
[tro-ten-mien-tu-mat-bao.md](tro-ten-mien-tu-mat-bao.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-tenten.md" %}
[tro-ten-mien-tu-tenten.md](tro-ten-mien-tu-tenten.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-inet.md" %}
[tro-ten-mien-tu-inet.md](tro-ten-mien-tu-inet.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-namecheap.md" %}
[tro-ten-mien-tu-namecheap.md](tro-ten-mien-tu-namecheap.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-godaddy.md" %}
[tro-ten-mien-tu-godaddy.md](tro-ten-mien-tu-godaddy.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-hostvn.md" %}
[tro-ten-mien-tu-hostvn.md](tro-ten-mien-tu-hostvn.md)
{% endcontent-ref %}

{% content-ref url="tro-ten-mien-tu-pa-viet-nam.md" %}
[tro-ten-mien-tu-pa-viet-nam.md](tro-ten-mien-tu-pa-viet-nam.md)
{% endcontent-ref %}



## Bước 2: Tạo và xác thực tên miền lại Tempi

{% content-ref url="tao-va-xac-thuc-ten-mien-lai-tempi.md" %}
[tao-va-xac-thuc-ten-mien-lai-tempi.md](tao-va-xac-thuc-ten-mien-lai-tempi.md)
{% endcontent-ref %}
