---
description: >-
  Vũ khí chính là trang bị quyết định phần lớn sát thương đánh cũng như khả năng
  phòng thủ cơ bản lại đòn đánh của địch.
---

# Vũ khí

{% hint style="warning" %}
Bạn cần trang bị một nhân vật và weapon để có thể tham gia trận chiến.
{% endhint %}

## Các lệnh liên quan

* Xem danh sách vũ khí của Cat: `catwp ls`
* Xem thông tin vũ khí của game: `catwp i [ID gốc]`
* Chi tiết vũ khí: `catwp [ID hiện tại]`
* Sử dụng: `catwp use [ID hiện tại]`
* Đổi tên vũ khí: `catwp rn [ID hiện tại] [tên]`
* Nâng cấp vũ khí: `catup wp [ID hiện tại] [ID gem] [số lượng gem]`
* Bán nhân vật: `catsell wp [ID] [số lượng]`

{% hint style="info" %}
ID hiện tại của wp sẽ là: `[Cấp]+[ID gốc]`
{% endhint %}

{% hint style="info" %}
Xem đầy đủ các lệnh và thông tin chi tiết liên quan: **`cath wp`**
{% endhint %}

Ngoài gói **Starter Pack \(item 10\)** chỉ nhận được 1 lần khi bắt đầu chơi, bạn có thể có vũ khí bằng cách mở rương \(item 1\) hoặc mua từ người chơi khác.

Bạn có thể nhận rương vũ khí: mua ở shop với giá 25 dora `catbuy 1 [số lượng]` hoặc nhận được khi đánh bại boss.  
Bạn có thể tìm mua vũ khí bằng cách hỏi trực tiếp ở người chơi khác, hoặc tìm kiếm ở chợ Đô Rề: `catm wp`

{% hint style="warning" %}
Người chơi khi bán qua chợ Đô Rề sẽ phải chịu phí 10%. Các người chơi có Premium Batte 3 / 4 sẽ được miễn khoản phí này.
{% endhint %}

## Thông tin và chỉ số vũ khí

Để xem đầy đủ chi tiết nhân vật: `catwp i [ID gốc]`  
Xem thông tin nhân vật bạn đang có: `catwp [ID hiện tại]`

Các chỉ số:

* Chỉ số cơ bản:  ![](https://cdn.discordapp.com/emojis/689391397643747368.png?v=1)`damage` và ![](https://cdn.discordapp.com/emojis/689391171411247196.png?v=1)`shield` sẽ tăng mỗi khi bạn cường hóa vũ khí
* Chỉ số mở rộng:  ![](https://cdn.discordapp.com/emojis/689391538601852959.png?v=1)`attack` ![](https://cdn.discordapp.com/emojis/693700331216830474.png?v=1)`defense` ![](https://cdn.discordapp.com/emojis/689391282350588106.png?v=1)`luck` ![](https://cdn.discordapp.com/emojis/689391102100635728.png?v=1)`wisdom` sẽ tăng khi bạn dùng gem nâng cấp \(max +10\) không tăng lên khi bạn cường hóa.

{% tabs %}
{% tab title="catwp i \[ID\]" %}
Lệnh để xem một vũ khí có trong game:

![SIG P228](../../.gitbook/assets/image%20%2810%29.png)
{% endtab %}

{% tab title="catwp \[ID\]" %}
Xem thông tin chỉ số của vũ khí bạn đang sử hữu:  
Bạn sẽ thấy chỉ số cơ bản được tăng thêm khi cường hóa lên 2, và chỉ số mở rộng bạn đã cường hóa.

![SIG P228](../../.gitbook/assets/image%20%289%29%20%281%29.png)
{% endtab %}
{% endtabs %}

## Cường hóa vũ khí

Để nâng cấp vũ khí của bạn, bạn cần sử dụng Houtu \(gem 3\) để nâng cấp. Số lượng và tỷ lệ sẽ phụ thuộc vào cấp độ hiện tại của vũ khí bạn. Số lượng Huotu cần để 100% nâng cấp thành công được tính bằng phép tính: `3^[Cấp hiện tại]` 

{% hint style="success" %}
Vũ khí sẽ có thể nâng cấp 8 lần - **Cấp 9 là cấp cao nhất**
{% endhint %}

{% hint style="warning" %}
Sau khi **nâng cấp vũ khí** lên level mới, **ID vũ khí sẽ thay đổi** đồng thời các **chỉ số mở rộng** đã được cường hóa **sẽ bị reset**
{% endhint %}



