# Chương 1: Sự khởi đầu

## Khởi đầu Doraemon Battle

Để bắt đầu chơi Doraemon Battle cũng như xem hướng dẫn chơi, hãy dùng lệnh:

```s
cattutorial
```

Sau khi dùng lệnh này, 1 **Starter Pack (item 10)** sẽ được thêm vào kho đồ của bạn.

## **Inventory**

Kiểm tra kho đồ bằng lệnh `catinv`, sử dụng các item trong túi bằng lệnh `catuse <id>`. Ví dụ để sử dụng **Starter Pack** vừa nhận được:

```s
catuse 10
```

Gói khởi đầu sẽ bao gồm: 2 nhân vật, 2 vũ khí và 3 bảo bối ngẫu nhiên.

## **Use Character**

Để kiểm tra những nhân vật bạn đang có:

```s
catc
```

`catc` là lệnh rút gọn của `catcharacter`

![catc](../../../.gitbook/assets/vi\_catc.png)

Khi show nhân vật lên, bạn cần để ý ID của nhân vật, để trang bị nhân vật chiến đấu bạn cần biết ID nhân vật bạn muốn.

```s
catc use [ID]
```

Để xem thêm về nhân vật:

{% content-ref url="nhan-vat.md" %}
[nhan-vat.md](nhan-vat.md)
{% endcontent-ref %}

## Use Weapon

Để kiểm tra những vũ khí bạn đang sở hữu:

```s
catwp
```

`catwp` là lệnh rút gọn của `catweapon`

![catwp](../../../.gitbook/assets/vi\_catwp.png)

Để trang bị vũ khí, bạn để ý lấy ID của wp ở dưới icon mỗi vũ khí:

{% content-ref url="vu-khi.md" %}
[vu-khi.md](vu-khi.md)
{% endcontent-ref %}

```s
catwp use [ID]
```

Để tìm hiểu rõ hơn về vũ khí:

## Use Gadget

Để kiểm tra bảo bối bạn đang sở hữu:

```s
catg
```

`catgg` là lệnh rút gọn của `catgadget`

![catgg](../../../.gitbook/assets/vi\_catgg.png)

Mỗi bảo bối sẽ đem lại cho bạn một kỹ năng khác nhau. Bạn có 3 vị trí để trang bị. Để trang bị bạn dùng lệnh:

```s
catgg use [ID gadget] [1 | 2 | 3]
```

Để tìm hiểu thêm:

{% content-ref url="bao-boi.md" %}
[bao-boi.md](bao-boi.md)
{% endcontent-ref %}

## Next Step

Như vậy bạn đã trang bị đầy đủ trang bị để có thể tham gia **Doraemon Battle.**\
Cùng chuyển qua giai đoạn tiếp theo:

{% content-ref url="../chuong-2-tham-ngan.md" %}
[chuong-2-tham-ngan.md](../chuong-2-tham-ngan.md)
{% endcontent-ref %}
