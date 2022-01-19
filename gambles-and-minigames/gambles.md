---
description: Gấp đôi tới chết!
cover: >-
  https://www.medianama.com/wp-content/uploads/2019/04/cards-gaming-gambling.jpg.jpg
coverY: -67.2442396313364
---

# 🎲 Gambles

Chơi game cùng Doraemon hoặc với người chơi khác (PvP) bằng catnip

## Slot machine

* Command: `slotmachine` - Chơi slot machine
* Aliases: `sm`, `slot`

```
catsm [số tiền cược]
```

## Bầu cua - A traditional gamble

* Command: `baucua` - Chơi bầu cua
* Aliases: `bc`

```
catbc [mức cược] (lựa chọn)
```

## Xì dách

* Command: `blackjack`, `xidach` - Chơi Xì dách với bạn bè
* Aliases: `bj`
* Sub-command (7): `info`, `join`, `list`, `mine`, `new`, `start`, `leave`
  * `info`: Thông tin phòng
  * `join`: Tham gia phòng
  * `list`: Danh sách phòng chờ xì dách tại server
  * `mine`: Danh sách phòng chờ xì dách của bạn
  * `new`: Tạo phòng mới
  * `start`: Bắt đầu trò chơi
  * `leave`: Rời phòng

## Xóc đĩa - Gấp đôi tới chết

* Command: `xocdia`, `coinflip` - Chơi xóc đĩa
* Aliases: `cf`, `xd`
* Xóc dĩa với 2 chế độ:
  * Cơ bản: chọn `t`, `s` - thắng x2 tiền cược
  * Mở rộng: chọn `1s`-`3s` hoặc `1t`-`3t` - thắng x3.5 tiền cược, chọn `4s`,`4n` hoặc `0s`, `0n` - thắng x15 tiền cược

```
catcf [tiền cược] (lựa chọn)
```

Example:

```
catcf 500
catcf all t
catcf all 3t
```

## Đoán số

Đoán số! Sẽ có ba cấp độ gợi ý xuất hiện một cách ngẫu nhiên. Khi chế độ tự động (auto) được bật, bạn chỉ cần nhập số muốn đoán.

* Command: `guessthenumber`
* Aliases: `gtn`
* Sub-command:
  * `catgtn [số]` - Đoán số
  * `catgtn info`
  * `catgtn auto` - Bật chế độ tự động, bạn sẽ không cần nhập `catgtn` để đoán số

## Liêng

Chơi Liêng với 2 chế độ: thường và tố

* Command: `lieng`, `threecard` - Chơi liêng
* Aliases: `l`, `tc`
* Sub-command:
  * `info`: Thông tin game
  * `join`: Tham gia chơi liêng
  * `list`: Danh sách đang chờ chơi liêng trong server
  * `mine`: Danh sách những ván liêng đang chờ của bạn
  * `new`: Tạo 1 game mới. Sử dụng up sẽ tạo ván Liêng tố
  * `start`: Bắt đầu game
  * `leave`: Rời game

## Lotto

Mua vé và thắng giải Jackpot. Có 9 vé số tương ứng từ 1 đến 9. Kỳ lotto bắt đầu từ 0h mỗi ngày và kết thúc vào lúc 18h30. Phần thưởng được chia theo tỉ lệ vé thắng giải được mua cho người chơi tương ứng. Nếu không ai trúng giải, jackpot được cộng dồn cho hôm sau.

* Command: `lotto` - Mua vé Lotto
* Aliases: `lt`, `xs`, `xoso`
* Sub-command:
  * `info`: Kiểm tra thông tin kỳ xổ số hiện tại
  * `buy`: Mua vé số và thắng giải Jackpot.
