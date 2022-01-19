---
description: >-
  Khi bạn đã có danh vọng, không còn gì để cố gắng thì đây chính là thời gian
  cho may rủi.
---

# Nghiện ngập time

## Vòng quay may rủi (Luckywheel)

## Infomation

Quay Vòng quay May mắn để nhận vô số phần thưởng. Chìa khóa (key) có thể được mua trong shop.

- Command: `luckywheel`
- Aliases: `lw`
- Các loại: --`nip` hay `n`--, `dorayaki` hay `d`, --`prepoint` hay `p`--
- Lệnh con:
  - `info`: `i` - Xem Vòng quay hiện tại
  - `reset`: `rs` - Đặt lại Vòng quay. Cần dùng 1 key.
  - `roll`: `r` - Quay đều quay đều

Câu lệnh đầy đủ:

```s
catlw [info|reset|roll] [nip|dorayaki|prepoint]
```

### Làm sao để nghiện

- B1: Phải có tiền - Check bằng lệnh `catd`
- B2: Phải có key - Check bằng lệnh `catinv`, xem hiện tại bạn đang còn key trong túi không. Nếu không qua B3
- B3: Mua key - Check bằng lệnh `catshop` để lấy id của key, sau do dùng lệnh `catbuy 19 [số lượng]` để mua. (19 là ID của key)
- B4: Kiểm tra vòng quay hiện tại - Check bằng lệnh `catlw info d`. Lúc này bạn sẽ thấy phần thưởng hiện tại của Vòng quay + số lượng key cần cho lượt quay tiếp theo.\
  ![catlw i d](../../.gitbook/assets/catlw\_i\_d.png)
  - CLAIMED: là những phần quà bạn đã nhận ở lần quay trước, không thể nhận lại.
- B5: Quay đều - `catlw r d`
- B6: Reset vòng quay hiện tại để có vòng quay mới - `catlw rs d` 