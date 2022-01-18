---
description: Among Wumpii game, a light custom of Among Us for discord.
---

# Discord version of Among us game

## Thông tin chung

Command `amongwumpii` or `aw`.&#x20;

Cooldown: `1s`

Subcommands (8): `info`, `join`, `list`, `mine`, `new`, `setting`, `start`, `leave`

{% hint style="info" %}
Gõ `cathelp amongwumpii [subcommand]` để xem hướng dẫn về các subcommand.
{% endhint %}

## Subcommand informations.

| Subcommand | Details                                                                                                                                                                                                                                                                                                                                                                   | Aliases | command                       |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ----------------------------- |
| info       | Kiểm tra thông tin một phòng đã tạo                                                                                                                                                                                                                                                                                                                                                   | `i`     | `cataw info <code>`           |
| join       | Tham gia phòng game                                                                                                                                                                                                                                                                                                                                                                 | `in`    | `cataw join <code>`           |
| list       | Xem danh sách phòng đang có                                                                                                                                                                                                                                                                                                                                                      | `ls`    | `cataw list`                  |
| mine       | Kiểm tra thông tin phòng hiện tại bạn đang tham gia                                                                                                                                                                                                                                                                                                                                                   | `me`    | `cataw mine`                  |
| new        | Tạo phòng mới                                                                                                                                                                                                                                                                                                                                                           | `n`     | `cataw new`                   |
| setting    | <p>Thay đổi cài đặt của phòng game. </p><p>Tuỳ chọn: </p><p><code>impostor</code>, </p><p><code>confirmEjected</code>, </p><p><code>totalTasks</code>, </p><p><code>voteTime</code>, </p><p><code>killCooldown</code>, </p><p><code>emergencyCooldown</code>, </p><p><code>maxCalls</code>, </p><p><code>visionRate</code> (max: 100).</p><p> Value must be a number.</p> | `set`   | `cataw <option> <value(int)>` |
| start      | Bắt đầu game phòng bạn đang host                                                                                                                                                                                                                                                                                                                                                   | `s`     | `cataw start`                 |
| leave      | Thoát phòng                                                                                                                                                                                                                                                                                                                                                                | `l`     | `cataw leave`                 |

{% hint style="warning" %}
Hãy chắc chắn bạn có bật **Allow direct messages from server members** trong **Privacy Settings** ít nhất một server có Doreamon, như vậy Doraemon mới có thể gửi tin nhắn cho bạn.
{% endhint %}

## Get started

### B1: Tạo phòng game

```sh
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

#### Role

Kill Crewmate or make them can not complete all their task

#### Command

`NEXT` or `BACK` for walk to another room\
`REPORT` if have a dead body in room\
`TASK`: ...\
`SABOTAGE`: Destroy something\
`KILL`: Kill someone in the room\
`TELEPORT`: Teleport to the opposite room

![](../../.gitbook/assets/en\_cataw\_impostor.png)

{% endtab %}

{% tab title="Crewmate" %}

#### Role

You need to complete all task or find out all Impostor in this game

#### Command

`NEXT` or `BACK` for walk to another room\
`REPORT` if have a dead body in room\
`TASK`: Do your task in the room

![](../../.gitbook/assets/en\_cataw\_crewmate.png)
{% endtab %}

{% endtabs %}

{% hint style="info" %}
Tất cả người chơi có thể join chung một phòng voice để cùng chơi game. Như vậy việc tranh luận ai là Impostor sẽ sôi động hơn.
{% endhint %}

