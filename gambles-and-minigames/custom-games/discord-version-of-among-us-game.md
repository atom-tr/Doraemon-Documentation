---
description: Among Wumpii game, a light custom of Among Us for discord.
---

# Discord version of Among us game

### Details

Command `amongwumpii` or `aw`.&#x20;

Cooldown: `1s`

Subcommands (8): `info`, `join`, `list`, `mine`, `new`, `setting`, `start`, `leave`

{% hint style="info" %}
Use `cathelp amongwumpii [subcommand]` for more details
{% endhint %}

### Subcommand informations.

| Subcommand | Details                                                                                                                                                                                                                                                                                                                                                                   | Aliases | command                       |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ----------------------------- |
| info       | Check game info by code                                                                                                                                                                                                                                                                                                                                                   | `i`     | `cataw info <code>`           |
| join       | Join game                                                                                                                                                                                                                                                                                                                                                                 | `in`    | `cataw join <code>`           |
| list       | Get availables games                                                                                                                                                                                                                                                                                                                                                      | `ls`    | `cataw list`                  |
| mine       | Check your current game                                                                                                                                                                                                                                                                                                                                                   | `me`    | `cataw mine`                  |
| new        | Create new game                                                                                                                                                                                                                                                                                                                                                           | `n`     | `cataw new`                   |
| setting    | <p>Change your hosting game settings. </p><p>Fields: </p><p><code>impostor</code>, </p><p><code>confirmEjected</code>, </p><p><code>totalTasks</code>, </p><p><code>voteTime</code>, </p><p><code>killCooldown</code>, </p><p><code>emergencyCooldown</code>, </p><p><code>maxCalls</code>, </p><p><code>visionRate</code> (max: 100).</p><p> Value must be a number.</p> | `set`   | `cataw <option> <value(int)>` |
| start      | Start your hosting game                                                                                                                                                                                                                                                                                                                                                   | `s`     | `cataw start`                 |
| leave      | Leave game                                                                                                                                                                                                                                                                                                                                                                | `l`     | `cataw leave`                 |

{% hint style="warning" %}
Make sure you turn **Allow direct messages from server members** on in **Privacy Settings**. Doraemon need it for send you DMs.
{% endhint %}

### Create a game step by step

#### Step 1: Create new game

```
cataw new
```

![cataw new](broken-reference)

#### Step 2 (option): Change your hosting game settings

Available settings: `impostor`, `confirmEjected`, `totalTasks`, `voteTime`, `killCooldown`, `emergencyCooldown`, `maxCalls`, `visionRate` (max: 100). **Value must be a number.** For example, i set number of impostor in room to 5:

```
cataw setting impostor 5
```

![cataw setting impostor](../../.gitbook/assets/en\_cataw\_setting\_1.png)

{% hint style="warning" %}
Number of impostor must be higher than Crewmate
{% endhint %}

#### Step 3: Send friend room code

Another user can join your game with command:

```
cataw join 5VNS
```

#### Step 4: Start game

```
cataw start
```

or just `cataw s`

![cataw s](../../.gitbook/assets/en\_cataw\_s.png)

#### Step 5: Each member check your own DMs to play

Each member will have a ramdom role of this game. With each role is each list of command. Check DMs for informations

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
Join a voice channel for more interesting when you guys find Impostor
{% endhint %}

