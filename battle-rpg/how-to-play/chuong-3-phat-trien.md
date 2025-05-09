---
description: Cùng bạn bè, đồng đội chơi để nhận thêm phần thưởng.
---

# Chương 3: Phát triển

## Cường hoá trang bị

Để cường hoá trang bị, bạn cần phải có Gem. Hãy kiểm tra kho gem của bạn bằng lệnh `catg`.

### Chỉ số cơ bản

#### Nhân vật

Để nâng cấp chỉ số cơ bản của nhân vật, bạn chỉ có cách tăng cấp độ nhân vật đó, bằng cách spam cùng bạn bè.

{% content-ref url="chuong-2-tham-ngan.md" %}
[chuong-2-tham-ngan.md](chuong-2-tham-ngan.md)
{% endcontent-ref %}

#### Vũ khí

Để nâng cấp chỉ số cơ bản của vũ khí, bạn cần Houtu (Gem 3). Mỗi cấp độ vũ khí sẽ cần một lượng Houtu để nâng cấp. Số lượng Houtu cần có thể tính bằng công thức: `Houtu = 3 ^ (Cấp độ vũ khí hiện tại)`.

{% hint style="warning" %}
Ở mỗi cấp độ, houtu sẽ có tỷ lệ thành công khi sử dụng khác nhau. Hãy sử dụng số lượng lớn houtu để tăng tỷ lệ thành công.
{% endhint %}

Chi tiết hơn về vũ khí:

{% content-ref url="chuong-1-su-khoi-dau/vu-khi.md" %}
[vu-khi.md](chuong-1-su-khoi-dau/vu-khi.md)
{% endcontent-ref %}

#### Bảo bối

Chỉ số cơ bản của bảo bối chính là % của các kỹ năng. Khi nâng bảo bối lên các cấp sẽ nhận được mức % tương ứng. Để nâng cấp bảo bối, bạn cần 4 bảo bối cùng loại và cấp độ. Xem thêm chi tiết về bảo bối ở phần:

{% content-ref url="chuong-1-su-khoi-dau/bao-boi.md" %}
[bao-boi.md](chuong-1-su-khoi-dau/bao-boi.md)
{% endcontent-ref %}

### Chỉ số mở rộng

Loại chỉ số này không tăng theo cấp độ của trang bị, mà cần gem để cường hoá.

* ![attack](https://cdn.discordapp.com/emojis/689391538601852959.png?v=1\&size=20)`attack`: Chỉ số tấn công.
* ![defense](https://cdn.discordapp.com/emojis/693700331216830474.png?v=1\&size=20)`defense`: Chỉ số phòng thủ.
* ![luck](https://cdn.discordapp.com/emojis/689391282350588106.png?v=1\&size=20)`luck`: Chỉ số này giúp tăng tỷ lệ chí mạng.
* ![wisdom](https://cdn.discordapp.com/emojis/689391102100635728.png?v=1\&size=20)`wisdom`: Chỉ số tốc độ, quyết định người đi trước.

Loại gem tương ứng với các chỉ số này:

* ![attack](https://cdn.discordapp.com/emojis/689391538601852959.png?v=1\&size=20)`attack`: Vermilion Bird ![Tiny Vermilion Bird](https://cdn.discordapp.com/emojis/698570646057255014.webp?size=20\&quality=lossless)
* ![defense](https://cdn.discordapp.com/emojis/693700331216830474.png?v=1\&size=20)`defense`: Azure Dragon ![Tiny Azure Dragon](https://cdn.discordapp.com/emojis/698566971549286462.webp?size=20\&quality=lossless)
* ![luck](https://cdn.discordapp.com/emojis/689391282350588106.png?v=1\&size=20)`lu`luck\`: Vermilion Bird ![Tiny Vermilion Bird](https://cdn.discordapp.com/emojis/698571667441451008.webp?size=20\&quality=lossless)
* ![wisdom](https://cdn.discordapp.com/emojis/689391102100635728.png?v=1\&size=20)`wisdom`: Blue Tortoise ![Tiny Blue Tortoise](https://cdn.discordapp.com/emojis/698566950229508138.webp?v=1\&size=20\&quality=lossless)

Mỗi loại gem sẽ có 4 cấp: `Tiny` (`+2`) > `Flawless` (`+5`) > `Royal` (`+8`) > `Galaxy` (`+10`) - tương ứng số chỉ số cộng thêm Bạn sẽ cần 4 gem để nâng gem lên cấp độ cao hơn. Lệnh:

```
catg cb [id gem] [số lượng]
```

Ví dụ:

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Lệnh cường hoá chỉ số mở rộng:

```
catup [loại trang bị] [id trang bị] [id loại gem] [số lượng gem]
```

Ví dụ cường hoá vũ khí (loại trang bị: `weapon` / `wp` )

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Không giống Houtu khi cường hoá vũ khí, các loại gem trên không tăng thêm tỷ lệ khi bạn sử dụng số lượng lớn.
{% endhint %}

{% hint style="info" %}
Bạn có thể thu thập gem bẳng `catwork`, hoặc thu thập hòm gemkhi đánh boss/adventure hay mua trong shop (ID: 3) /chợ Đô Rê và mở hòm để nhận ngẫu nhiên gem.![](<../../.gitbook/assets/image (10).png>)
{% endhint %}

#### Thú cưng

Hãy tìm kiếm trứng thật xịn để ấp nở thú cưng mạnh hơn và nhiều bổ trợ hơn. Tuy nhiên, tỷ lệ bổ trợ của thú cưng còn phụ thuộc vào sự trung thành (Loyalty - tối đa 100) có được từ việc chăm sóc. Hãy thường xuyên chăm sóc thú cưng bằng `catpet act feed|play|groom` để tăng và giữ điểm, nếu quá lâu không chăm sóc, thú cưng sẽ bị tụt điểm!!&#x20;



## Đồng đội

Sau khi đã tìm cho mình được trang bị phù hợp cũng như nhân vật yêu thích để sử dụng, hãy tìm cho mình những đồng đội mạnh mẽ để cùng nhau chinh phục các con boss khó nhằn:

* Xem team hiện tại: `cattm`
* Invite người khác vào team: `cattm i [user]`
* Chuyển key trưởng nhóm cho người khác: `cattm tf [user]`
* Đuổi một người ra khỏi team: `cattm k [user]`
* Cùng đồng đội chinh phục bảng xếp hạng: `catfight team` | `catf tm`. Cả đội sẽ cùng nhận được exp khi bạn tham gia trận chiến.

## Các loại boss

{% hint style="warning" %}
Tất cả các boss có chia sẻ thời gian hồi với nhau.
{% endhint %}

{% tabs %}
{% tab title="Boss ngày" %}
Những con boss ngày là những con boss cực kì mạnh mẽ, với 3 mức độ: Dễ, Vừa và Khó.\
Đối với những con boss này, mỗi ngày bạn sẽ chỉ có thể đánh bại nó và lãnh thưởng 1 lần ở mỗi mức độ.

| BOSS | Command   | Ngày trong tuần (GMT+7) |
| ---- | --------- | ----------------------- |
| `WA` | `f b wae` | Chủ nhật, Thứ 2         |
| `WB` | `f b wbe` | Thứ 3, 4                |
| `WC` | `f b wce` | Thứ 5                   |
| `WE` | `f b wee` | Thứ 6, 7                |

{% hint style="info" %}
Boss ngày không yêu cầu level các thành viên trong team.
{% endhint %}
{% endtab %}

{% tab title="Team 2" %}
Các con boss này bạn có thể thách thức liên tục cùng thành viên team, cùng nhau nhận thưởng. Cả team sẽ được nhận exp.

| Boss    | Level | Command  | Cooldown |
| ------- | ----- | -------- | -------- |
| `DEER`  | 5     | `f b de` |          |
| `ZEBRA` | 10    | `f b z`  |          |
| `ANT`   | 15    | `f b a`  |          |
{% endtab %}

{% tab title="Team 4" %}
Các con boss này bạn có thể thách thức liên tục cùng thành viên team, cùng nhau nhận thưởng. Cả team sẽ được nhận exp.

{% hint style="danger" %}
Bạn không thể thách thức các boss team 2 nếu team bạn có 3 hoặc 4 người.
{% endhint %}

| Boss        | Level | Command  | Cooldown |
| ----------- | ----- | -------- | -------- |
| `DBRA`      | 10    | `f b db` |          |
| `KING CRAB` | 15    | `f b k`  | 4m45s    |
| `PSY DUCK`  | 20    | `f b p`  | 8m20s    |
| `DRAB`      | 25    | `f b dr` |          |
| `EAGLE`     | 25    | `f b e`  |          |
| `DUGLE`     | 30    | `f b du` |          |
| `CEAGLE`    | 30    | `f b c`  |          |
| `TUSULEA`   | 30    | `f b t`  | 10m      |
{% endtab %}
{% endtabs %}
