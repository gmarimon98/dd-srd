---
title: Action Scenes
weight: 9
---

# Action Scenes

Action scenes are critical moments of gameplay where the narration of the game goes from a conversational flow to a more structured turn-based flow. Time slows down and every decision matters. For example, a combat against some bandits or a car chase are action scenes.

In action scenes, the GM first establishes which sides are participating in the scene (usually just the players and their opponents, but there could be more sides as well) and which side starts. Each side takes one turn at a time. When it’s the players’ side’s turn, one member of that side can take the following actions:
- Move from one place to another
- Make one roll

Then, the opposing side takes a turn. The GM can use a flat difficulty to represent an enemy's efforts or use contested rolls when players make attempts against non-player characters and vice versa, following [Combat rules]({{< relref "/content/gameplay/action-scenes#combat" >}}).

After taking a turn, a combatant gains the exhausted condition and is not eligible to take another turn. Once every member of a side is exhausted, remove the exhausted condition from them.

## Combat

Combat is a type of action scene where the players fight enemies. Enemies have the following attributes:
- A base combat bonus, ranging from +0 to +10
- A health value, ranging from 1 to around 10
- A list of tags, each with a level ranging from 1◆ to 5◆

For example, the following is an enemy:

**Young Red Dragon**
- Bonus: `+4`
- Health: `5`
- Tags:
    - `Fire Breath` 4◆
    - `Flying` 3◆
    - `Hardy Scales` 3◆
    - `Tail Swipe` 2◆

When a player attacks an enemy or vice versa, that player and the GM do a contested roll, with any banes the enemy incurs each reducing its health by one. Enemy tags are not exhausted after successful use. Instead, the enemy cannot use that same tag again until they have used all other tags at least once.