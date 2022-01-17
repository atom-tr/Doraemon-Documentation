# Bảo bối

{% hint style="warning" %}
Bạn cần trang bị một nhân vật và weapon để có thể tham gia trận chiến.
{% endhint %}

## Các lệnh liên quan

* Xem danh sách vũ khí của Cat: `catgg ls`
* Xem thông tin vũ khí của game: `catgg i [ID gốc]`
* Chi tiết vũ khí: `catgg [ID hiện tại]`
* Sử dụng: `catgg use [ID hiện tại]`
* Đổi tên vũ khí: `catgg rn [ID hiện tại] [tên]`
* Nâng cấp vũ khí: `catup gg [ID hiện tại] [ID gem] [số lượng gem]`
* Bán nhân vật: `catsell gg [ID] [số lượng]`

{% hint style="info" %}
ID hiện tại của gg sẽ là: `[Cấp]+[ID gốc]`
{% endhint %}

{% hint style="info" %}
Xem đầy đủ các lệnh và thông tin chi tiết liên quan: **`cath gg`**
{% endhint %}

Ngoài gói **Starter Pack \(item 10\)** chỉ nhận được 1 lần khi bắt đầu chơi, bạn có thể có vũ khí bằng cách mở rương \(item 1\) hoặc mua từ người chơi khác.

Bạn có thể nhận rương vũ khí: mua ở shop với giá 25 dora `catbuy 4 [số lượng]` hoặc nhận được khi đánh bại boss.  
Bạn có thể tìm mua vũ khí bằng cách hỏi trực tiếp ở người chơi khác, hoặc tìm kiếm ở chợ Đô Rề: `catm gg`

{% hint style="warning" %}
Người chơi khi bán qua chợ Đô Rề sẽ phải chịu phí 10%. Các người chơi có Premium Batte 3 / 4 sẽ được miễn khoản phí này.
{% endhint %}

## Thông tin và chỉ số vũ khí

Để xem đầy đủ chi tiết nhân vật: `catgg i [ID gốc]`  
Xem thông tin nhân vật bạn đang có: `catgg [ID hiện tại]`

Các chỉ số:

* Ký năng: 
* Chỉ số mở rộng:  ![](https://cdn.discordapp.com/emojis/689391538601852959.png?v=1)`attack` ![](https://cdn.discordapp.com/emojis/693700331216830474.png?v=1)`defense` ![](https://cdn.discordapp.com/emojis/689391282350588106.png?v=1)`luck` ![](https://cdn.discordapp.com/emojis/689391102100635728.png?v=1)`wisdom` sẽ tăng khi bạn dùng gem nâng cấp \(max +10\) không tăng lên khi bạn cường hóa.
* Các loại gadget được xếp hạng từ cao tới thấp: ![:uls:](https://cdn.discordapp.com/emojis/693704060972433478.png?v=1) ![:ss:](https://cdn.discordapp.com/emojis/693699322004504607.png?v=1) ![:as:](https://cdn.discordapp.com/emojis/693699320863784972.png?v=1) ![:js:](https://cdn.discordapp.com/emojis/693699320842551307.png?v=1) ![:uxr:](https://cdn.discordapp.com/emojis/693703707245936640.png?v=1) ![:ur:](https://cdn.discordapp.com/emojis/693699222515744809.png?v=1) ![:rr:](https://cdn.discordapp.com/emojis/693699222729654284.png?v=1) ![:sr:](https://cdn.discordapp.com/emojis/693699222855352400.png?v=1) ![:ucn:](https://cdn.discordapp.com/emojis/693702729930899466.png?v=1) ![:sn:](https://cdn.discordapp.com/emojis/693699121541808138.png?v=1) ![:qn:](https://cdn.discordapp.com/emojis/693699122657493032.png?v=1) ![:cn:](https://cdn.discordapp.com/emojis/693699121529225267.png?v=1) 

{% tabs %}
{% tab title="catgg i \[ID\]" %}
Lệnh để xem một bảo bối có trong game:

![](../../.gitbook/assets/igg50%20%281%29%20%281%29.png)
{% endtab %}

{% tab title="catg \[ID\]" %}
Xem thông tin chỉ số của bảo bối bạn đang sử hữu:

![](../../.gitbook/assets/gg250.png)
{% endtab %}
{% endtabs %}

## Kỹ năng của bảo bối

![Gomu Gomu no Mi](../../.gitbook/assets/gg250.png)

* **Loại**: ![:uxr:](https://cdn.discordapp.com/emojis/693703707245936640.png?v=1) 
* **Kĩ năng**: **75%** ![:DENY\_DMG:](https://cdn.discordapp.com/emojis/701257192933687346.png?v=1) `Không nhận 25/{30}/35/50/75% sát thương từ đối thủ trong 1 lượt` 
* **Mana tiêu thụ**: `40` 
* **Thời gian hồi chiêu**: `3`

Với thông tin kỹ năng, ta có 75% là ngưỡng sức mạnh của kỹ năng của loại bảo bối ![:uxr:](https://cdn.discordapp.com/emojis/693703707245936640.png?v=1), và các số 25/{30}/35/50/75% là sức mạnh của từng cấp của bảo bối. Với {xx%} là sức mạnh hiện tại. Từ 2 con số này ta có thể tính được % sức mạnh của bảo bối bạn sử dụng.  
VD với gg 250 trên ta có: 75%\*30% = 22.5%, tức bạn sẽ không nhận 22.5% sát thương từ đối thủ trong 1 lượt.

## Nâng cấp bảo bối

Cần 4 bảo bối cùng cấp và loại để có thể dung luyện lên cấp tiếp theo: `catgg cb [ID hiện tại] [số lượng]`

{% hint style="success" %}
Vũ khí sẽ có thể nâng cấp 4 lần - **5\* là cấp cao nhất**
{% endhint %}

{% hint style="warning" %}
Sau khi **nâng cấp bảo bối** lên level mới, **ID bảo bối sẽ thay đổi** đồng thời các **chỉ số mở rộng** đã được cường hóa **sẽ bị reset**
{% endhint %}

## Bộ bảo bối gợi ý cho Newbie

Nếu các bạn chưa có đủ thông tin để tự build cho mình một bộ skill thích hợp cho bản thân, cũng như chưa đủ tài nguyên để có cho mình những bảo bối mong muốn. Mình gợi ý cho các bạn một bộ bảo bối có thể gắn bó với bạn lâu dài mà dễ kiếm:

{% tabs %}
{% tab title="Mini Tank" %}
**Mini Tank:** Như mô tả của nó, chỉ là một bảo bối nhỏ loại **QN** khá dễ kiếm, nhưng mang lại cho bạn khả năng tăng sát thương mỗi 4 turn. Nếu bạn có thể có cho mình 256 mini tank 1\*, bạn có thể dung luyện lên 5\* để có được kỹ năng: Tăng `45% * 90% = 40.5%` Sát thương cơ bản cho đòn đánh tiếp theo.

![B&#x1EA3;o b&#x1ED1;i Mini Tank](../../.gitbook/assets/image%20%2815%29.png)
{% endtab %}

{% tab title="Camera" %}
**Camera:** Sở hữu kỹ năng cực kỳ hữu dụng cho cả PVP và PVE, hãy thử tưởng tượng bạn copy thành công kỹ năng hạng **`SS`** của Boss mà bình thường bạn không bao giờ được sở hữu và sử dụng nó. ^^.

![B&#x1EA3;o b&#x1ED1;i Camera](../../.gitbook/assets/image%20%2816%29.png)
{% endtab %}

{% tab title="Magic Clock" %}
**Magic Clock:** Bảo bối với kỹ năng cướp lượt đi của đối thủ, giúp bạn nắm cho mình tỷ lệ thắng cao hơn khi có được 2 lượt đi liên tiếp

![B&#x1EA3;o b&#x1ED1;i Magic Clock](../../.gitbook/assets/image%20%2814%29.png)
{% endtab %}
{% endtabs %}

