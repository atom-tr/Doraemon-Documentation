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

Ngoài gói **Starter Pack (item 10)** chỉ nhận được 1 lần khi bắt đầu chơi, bạn có thể có vũ khí bằng cách mở rương (item 1) hoặc mua từ người chơi khác.

Bạn có thể nhận rương vũ khí: mua ở shop với giá 25 dora `catbuy 1 [số lượng]` hoặc nhận được khi đánh bại boss.\
Bạn có thể tìm mua vũ khí bằng cách hỏi trực tiếp ở người chơi khác, hoặc tìm kiếm ở chợ Đô Rề: `catm wp`

{% hint style="warning" %}
Người chơi khi bán qua chợ Đô Rề sẽ phải chịu phí 10%. Các người chơi có Premium Batte 3 / 4 sẽ được miễn khoản phí này.
{% endhint %}

## Thông tin và chỉ số vũ khí

Để xem đầy đủ chi tiết nhân vật: `catwp i [ID gốc]`\
Xem thông tin nhân vật bạn đang có: `catwp [ID hiện tại]`

Các chỉ số:

* **Yêu cầu cấp độ**: Cấp độ hiện tại của nhân vật bạn sở hữu phải đạt ngưỡng này mới có thể sữ dụng vũ khí.
* Chỉ số cơ bản: ![](https://cdn.discordapp.com/emojis/689391397643747368.png?v=1&size=20)`damage` và ![](https://cdn.discordapp.com/emojis/689391171411247196.png?v=1&size=20)`shield` sẽ tăng mỗi khi bạn cường hóa vũ khí
* Chỉ số mở rộng: ![](https://cdn.discordapp.com/emojis/689391538601852959.png?v=1&size=20)`attack` ![](https://cdn.discordapp.com/emojis/693700331216830474.png?v=1&size=20)`defense` ![](https://cdn.discordapp.com/emojis/689391282350588106.png?v=1&size=20)`luck` ![](https://cdn.discordapp.com/emojis/689391102100635728.png?v=1&size=20)`wisdom` sẽ tăng khi bạn dùng gem nâng cấp (max +10) không tăng lên khi bạn cường hóa.

{% tabs %}
{% tab title="catwp i [ID]" %}
Lệnh để xem một vũ khí có trong game:

<hr>

VD ở đây chúng ta xem thông tin vũ khí có ID 61: `catwp i 61`

> **BATTLE WEAPON**
>
>
> ![:SuitNo6:](https://cdn.discordapp.com/emojis/810055238315933726.webp?size=20\&quality=lossless) No.6 Suit
>
> **ID cố định**: `61`\
> **Mô tả**: Bộ suit của nhà Germa dành riêng cho người chị cả No.6 (biệt danh Poison Pink). Nó giúp tối ưu tốc độ cho Poison Pink, tăng khả năng bay lượn giúp phòng thủ tốt hơn và khả năng đánh chớp nhoáng. -- Custom weapon from player **B O O B O O#6363**
>
> **Nguyên tố**: ![:fi:](https://cdn.discordapp.com/emojis/702510320064921641.webp?size=20\&quality=lossless)\
> **Tỉ lệ xuất hiện**: `0.25%`\
> **Chỉ dành Premium**: `false`\
> **Khả năng giao dịch**: `true`\
> **Yêu cầu cấp độ**: `25`\
> **Lượt thu thập**: `1642`\
> **Công khai**: `true`
>
> Chỉ số cơ bản ![:da:](https://cdn.discordapp.com/emojis/689391397643747368.webp?size=20\&quality=lossless) `180` ![:sh:](https://cdn.discordapp.com/emojis/689391171411247196.webp?size=20\&quality=lossless) `50`\
> Chỉ số mở rộng ![:of:](https://cdn.discordapp.com/emojis/689391538601852959.webp?size=20\&quality=lossless) `60` ![:de:](https://cdn.discordapp.com/emojis/693700331216830474.webp?size=20\&quality=lossless) `25` ![:lu:](https://cdn.discordapp.com/emojis/689391282350588106.webp?size=20\&quality=lossless) `50` ![:wi:](https://cdn.discordapp.com/emojis/689391102100635728.webp?size=20\&quality=lossless) `35`
>
> [![](https://images-ext-1.discordapp.net/external/FB8WN9V9RxSALcn936i7G2MfNg9yxA-yJXRNZRBZWMI/https/media.discordapp.net/attachments/681423309786972201/804306728019034162/image0.png?width=306\&height=240)](https://media.discordapp.net/attachments/681423309786972201/804306728019034162/image0.png)
{% endtab %}

{% tab title="catwp [ID]" %}
Xem thông tin chỉ số của vũ khí bạn đang sử hữu:\
Bạn sẽ thấy chỉ số cơ bản được tăng thêm khi cường hóa lên 8, và chỉ số mở rộng bạn đã cường hóa.

<hr>

> ![](https://images-ext-1.discordapp.net/external/dOmjULqxxQnfUUQgJ3To3N3hGwhSebifv8q86SVLE48/https/cdn.discordapp.com/avatars/423327141921423361/764e55505d8c943253ab32e87a96734a.webp?width=25\&height=25) 👾 Atom.'s No.6 Suit
>
>
> **ID**: `861` \
> **Biệt danh**: ![:SuitNo6:](https://cdn.discordapp.com/emojis/810055238315933726.webp?size=20\&quality=lossless) Poison-Pink Suit \
> **Mô tả**: Bộ suit của nhà Germa dành riêng cho người chị cả No.6 (biệt danh Poison Pink). Nó giúp tối ưu tốc độ cho Poison Pink, tăng khả năng bay lượn giúp phòng thủ tốt hơn và khả năng đánh chớp nhoáng. -- Custom weapon from player **B O O B O O#6363**&#x20;
>
> **Nguyên tố**: ![:fi:](https://cdn.discordapp.com/emojis/702510320064921641.webp?size=20\&quality=lossless) \
> **Hạn sử dụng**: Vĩnh viễn \
> **Cấp cường hóa**: ![:8:](https://cdn.discordapp.com/emojis/695465557134147604.webp?size=20\&quality=lossless) \
> **Số lượng**: 1 Sử dụng \
> `cathelp weapon` để xem danh sách lệnh liên quan
>
> Chỉ số cơ bản ![:da:](https://cdn.discordapp.com/emojis/689391397643747368.webp?size=20\&quality=lossless) `180(+168)` ![:sh:](https://cdn.discordapp.com/emojis/689391171411247196.webp?size=20\&quality=lossless) `50(+46)`\
> Chỉ số mở rộng ![:of:](https://cdn.discordapp.com/emojis/689391538601852959.webp?size=20\&quality=lossless) `60(+10)` ![:de:](https://cdn.discordapp.com/emojis/693700331216830474.webp?size=20\&quality=lossless) `25(+10)` ![:lu:](https://cdn.discordapp.com/emojis/689391282350588106.webp?size=20\&quality=lossless) `50(+10)` ![:wi:](https://cdn.discordapp.com/emojis/689391102100635728.webp?size=20\&quality=lossless) `35(+10)`
>
> [![](https://images-ext-1.discordapp.net/external/FB8WN9V9RxSALcn936i7G2MfNg9yxA-yJXRNZRBZWMI/https/media.discordapp.net/attachments/681423309786972201/804306728019034162/image0.png?width=306\&height=240)](https://media.discordapp.net/attachments/681423309786972201/804306728019034162/image0.png)
{% endtab %}
{% endtabs %}

## Cường hóa vũ khí

Để nâng cấp vũ khí của bạn, bạn cần sử dụng Houtu (gem 3) để nâng cấp. Số lượng và tỷ lệ sẽ phụ thuộc vào cấp độ hiện tại của vũ khí bạn. Số lượng Huotu cần để 100% nâng cấp thành công được tính bằng phép tính: `3^[Cấp hiện tại]`

{% hint style="success" %}
Vũ khí sẽ có thể nâng cấp 8 lần - **Cấp 9 là cấp cao nhất**
{% endhint %}

{% hint style="warning" %}
Sau khi **nâng cấp vũ khí** lên level mới, **ID vũ khí sẽ thay đổi** đồng thời các **chỉ số mở rộng** đã được cường hóa **sẽ bị reset**
{% endhint %}
