---
description: Tạo nhiệm vụ cần hoàn thành để tham gia giveaway
---

# 📜 Task

Nhiệm vụ của Cat hoặc tùy chỉnh cho các giveaway

{% hint style="info" %}
Sử dụng `cathelp task [lệnh con]` để xem chi tiết hơn
{% endhint %}

## Details

Command: `task` Các lệnh con (7):

* `create`: Tạo nhiệm vụ
* `delete`: Gỡ bỏ nhiệm vụ
*   `edit`: Chỉnh sửa nhiệm vụ. Fields (trường) & values (giá trị):

    > Các giá trị nhập cách nhau bởi dấu phẩy (,). Nhập giá trị `undefined` để đặt lại trường đó.

    * `quantity`: number
    * `title`, `content`: text
    * `channels`, `guilds`, `users`: IDs
    * `before`/`after`: date (`2020-12-30`)
    * `timeout`: duration (`3h4m5s`)
    * `random`, `allowcontain`: `true`/`false`
    * `links`: message link
    * `items`: item ID
* `info`: Thông tin nhiệm vụ
* `mine`: Xem tất cả các nhiệm vụ được giao hoặc sử dụng search để tìm
* `reroll`: Thử tìm lại 1 nhiệm vụ mới cho bạn
* `list`: Xem tất cả nhiệm vụ tùy chỉnh của bạn hoặc sử dụng search để tìm

## Examples
