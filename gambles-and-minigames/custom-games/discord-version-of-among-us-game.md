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

### Create a game step by step

#### Step 1: Create new game

```
cataw new
```

![cataw new](../../.gitbook/assets/vi\_cataw\_new.png)

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


![](../../.gitbook/assets/en\_cataw\_impostor.png)
{% endtab %}

{% tab title="Crewmate" %}


![](../../.gitbook/assets/en\_cataw\_crewmate.png)
{% endtab %}
{% endtabs %}

