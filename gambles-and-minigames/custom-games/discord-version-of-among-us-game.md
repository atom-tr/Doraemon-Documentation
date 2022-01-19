---
description: Among Wumpii game, a light custom of Among Us for discord.
cover: https://i.ytimg.com/vi/MbMEc_o8oHk/maxresdefault.jpg
coverY: 0
---

# Discord version of Among us game

## Thông tin chung

Command `amongwumpii` or `aw`.

Cooldown: `1s`

Subcommands (8): `info`, `join`, `list`, `mine`, `new`, `setting`, `start`, `leave`

{% hint style="info" %}
Gõ `cathelp amongwumpii [subcommand]` để xem hướng dẫn về các subcommand.
{% endhint %}

## Subcommand informations

| Subcommand | Details                                                                                                                                                                                              | Aliases | command                       |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ----------------------------- |
| info       | Kiểm tra thông tin một phòng đã tạo                                                                                                                                                                  | `i`     | `cataw info <code>`           |
| join       | Tham gia phòng game                                                                                                                                                                                  | `in`    | `cataw join <code>`           |
| list       | Xem danh sách phòng đang có                                                                                                                                                                          | `ls`    | `cataw list`                  |
| mine       | Kiểm tra thông tin phòng hiện tại bạn đang tham gia                                                                                                                                                  | `me`    | `cataw mine`                  |
| new        | Tạo phòng mới                                                                                                                                                                                        | `n`     | `cataw new`                   |
| setting    | Thay đổi cài đặt của phòng game. Tuỳ chọn: `impostor`, `confirmEjected`, `totalTasks`, `voteTime`, `killCooldown`, `emergencyCooldown`, `maxCalls`, `visionRate` (max: 100). Value must be a number. | `set`   | `cataw <option> <value(int)>` |
| start      | Bắt đầu game phòng bạn đang host                                                                                                                                                                     | `s`     | `cataw start`                 |
| leave      | Thoát phòng                                                                                                                                                                                          | `l`     | `cataw leave`                 |

{% hint style="warning" %}
Hãy chắc chắn bạn có bật **Allow direct messages from server members** trong **Privacy Settings** ít nhất một server có Doreamon, như vậy Doraemon mới có thể gửi tin nhắn cho bạn.
{% endhint %}

## Get started

### B1: Tạo phòng game

```
cataw new
```

![cataw new](<../../.gitbook/assets/en\_cataw\_new (1).png>)

### B2 (tuỳ chọn): Tuỳ chỉnh cài đặt của phòng game

Cài đặt có thể chỉnh sửa: `impostor`, `confirmEjected`, `totalTasks`, `voteTime`, `killCooldown`, `emergencyCooldown`, `maxCalls`, `visionRate` (max: 100). **Giá trị đằng sau bắt buộc là số.** Ví dụ dưới chúng ta chỉnh số impostor thành 5:

```
cataw setting impostor 5
```

![cataw setting impostor](../../.gitbook/assets/en\_cataw\_setting\_1.png)

{% hint style="warning" %}
Số lượng impostor phải ít hơn Crewmate
{% endhint %}

### B3: Gửi ID phòng mời mọi người tham gia

ID phòng bạn sẽ nhận được ngay từ bước 1, hoặc bạn có thể kiểm tra lại với lệnh `cataw mine`. Người khác có thể tham gia phòng với lệnh:

```
cataw join 5VNS
```

Với 5VNS là ID phòng game.

### B4: Bắt đầu game

```
cataw start
```

hoặc ngắn hơn `cataw s`

![cataw s](../../.gitbook/assets/en\_cataw\_s.png)

### B5: Kiểm tra DMs từ Doraemon và bắt đầu chơi

Mỗi người chơi sẽ được ramdom với một role khác nhau. Các lệnh tương ứng với role người chơi sẽ được gửi kèm tin nhắn.

{% tabs %}
{% tab title="Impostor" %}
**Role Impostor**

Tấn công Crewmate, bằng bất cứ giá nào hãy khiến họ không thể hoàn thành toàn bộ task.

**Command Impostor**

`NEXT` or `BACK` di chuyển tới phòng bên cạnh\
`REPORT` lệnh có thể sử dụng khi bạn phát hiện xác ở trong room\
`TASK`: ...\
`SABOTAGE`: Phá huỷ\
`KILL`: Tấn công Crewmate chung phòng\
`TELEPORT`: Dịch chuyển tới phòng đối diện

![impostor](../../.gitbook/assets/en\_cataw\_impostor.png)
{% endtab %}

{% tab title="Crewmate" %}
**Role Crewmate**

Hoàn thành tất cả các task hoặc tìm ra được toàm bộ Impostor đang trà trộn.

**Command Crewmate**

`NEXT` or `BACK` di chuyển qua phòng bên cạnh\
`REPORT` lệnh có thể sử dụng khi bạn phát hiện xác ở trong room\
`TASK`: Hoàn thành task của crewmate

![crewmate](../../.gitbook/assets/en\_cataw\_crewmate.png)
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Tất cả người chơi có thể join chung một phòng voice để cùng chơi game. Như vậy việc tranh luận ai là Impostor sẽ sôi động hơn.
{% endhint %}
