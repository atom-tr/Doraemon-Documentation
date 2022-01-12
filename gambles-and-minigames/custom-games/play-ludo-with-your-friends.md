---
description: >-
  Create ludo game with bet and play with your friends. When everyone's ready,
  the game starts!
---

# Play ludo with your friends

### Details

Command: ludo

{% hint style="info" %}
Use `cathelp ludo [subcommand]` for more details
{% endhint %}

Subcommands (11): `info`, `join`, `list`, `mine`, `new`, `dice`, `votekick`, `leave`, `ready`, `setting`, `unready`

### Subcommand details.

| Subcommand | Details                                                                                                                                                                                                                                                                                                                                                                   | command                       |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| info       | Check game info by code                                                                                                                                                                                                                                                                                                                                                   | cataw info \<code>            |
| join       | Join game                                                                                                                                                                                                                                                                                                                                                                 | cataw join \<code>            |
| list       | Get availables games                                                                                                                                                                                                                                                                                                                                                      | cataw list                    |
| mine       | Check your current game                                                                                                                                                                                                                                                                                                                                                   | cataw mine                    |
| new        | Create new game                                                                                                                                                                                                                                                                                                                                                           | cataw new                     |
| setting    | <p>Change your hosting game settings. </p><p>Fields: </p><p><code>impostor</code>, </p><p><code>confirmEjected</code>, </p><p><code>totalTasks</code>, </p><p><code>voteTime</code>, </p><p><code>killCooldown</code>, </p><p><code>emergencyCooldown</code>, </p><p><code>maxCalls</code>, </p><p><code>visionRate</code> (max: 100).</p><p> Value must be a number.</p> | cataw \<option> \<value(int)> |
| start      | Start your hosting game                                                                                                                                                                                                                                                                                                                                                   | cataw start                   |
| leave      | Leave game                                                                                                                                                                                                                                                                                                                                                                | cataw leave                   |

| Sub-cmd  | Details                                                          | Aliases       | Full Command                                                                                                                      |
| -------- | ---------------------------------------------------------------- | ------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| info     | Check ludo game info                                             | `i`           | `catld infor <id>`                                                                                                                |
| join     | Join a game                                                      | `in`          | `catld join <id>`                                                                                                                 |
| list     | See list ludo games in server                                    | `ls`          | `catld list`                                                                                                                      |
| mine     | See your ludo games in server                                    | `me`          | `catld mine`                                                                                                                      |
| new      | Create a ludo game with bet                                      | `n`           | `catld new`                                                                                                                       |
| dice     | Dice dice dice                                                   | `d`           | `catld dice`                                                                                                                      |
| votekick | Vote kick a user from a ludo game. User kicked can't not re-join | `vote` `kick` | `catld votekick @user`                                                                                                            |
| leave    | Leave a ludo game                                                | `out` `quit`  | `catld leave <id>`                                                                                                                |
| ready    | Ready to play a ludo game                                        | `rd` `ss`     | `catld ready`                                                                                                                     |
| setting  | Setting knockbet & showdetail                                    | `set`         | <p><code>catld set &#x3C;id> knockbet &#x3C;value></code></p><p></p><p><code>catld set &#x3C;id> showdetail true/false</code></p> |
| unready  | Unready                                                          | `urd`         | `catld unready`                                                                                                                   |
