---
title: Action Scenes
weight: 9
---

# Action Scenes

Action scenes are critical moments of gameplay where the narration of the game goes from a conversational flow to a more structured turn-based flow. Time slows down and every decision matters. For example, a combat against some bandits or a car chase are action scenes.

In action scenes, the GM first establishes which sides are participating in the scene (usually just the players and their opponents, but there could be more sides as well) and which side starts. Each side takes one turn at a time. When it’s the players’ side’s turn, one member of that side can take the following actions:
- Move from one place to another
- Make one roll

Then, the opposing side takes a turn. The GM can use a flat difficulty to represent an enemy's efforts or use contested rolls when players make attempts against non-player characters and vice versa, following [Combat rules]({{< relref "/gameplay/action-scenes#combat" >}}).

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

When a player attacks an enemy or vice versa, that player and the GM do a contested roll, with any banes the enemy incurs each reducing its health by one. Enemies do not gain boons. Enemy tags are not exhausted after successful use. Instead, the enemy cannot use that same tag again until they have used all other tags at least once.

---

## Example Combat Roll

The following is a full example of a roll:

1. If a character attempts to hit the Young Red Dragon above with their sword, then the GM calls for a contested roll between the player and the dragon.
2. The player adds their Combat stat (3◆), their `Broadsword` tag (2◆), and bonus from stress (1◆) for a total modifier of +6. The GM adds the dragon's bonus (+4) and a tag it can use in the moment, `Fire Breath` (4◆), for a total modifier of +8.
3. The player and the GM each roll simultaneously. The GM rolls a 10, which plus the dragon's modifier of +8, results in an 18. The player rolls a 4, which plus the player's modifier of +6, results in a 10.
4. Since the player rolled the lower result, they then choose whether or not to double down. Because the dragon's roll is an 18, the player would take four stress if they don't double down. However, the player decides to risk it all and double down. They roll a natural 20, which plus the player's modifier of +6, results in a 26.
5. Because the player rolled a 20, their original outcome increases by two tiers to a critical success. Because the player turned their failure into a success, the dragon's success becomes a failure.
6. Each player gets boons or banes using the other's roll as the difficulty. The player gains eight boons (critical success, difficulty 18), and the dragon takes five banes (failure, difficulty 26), resulting in five damage, which is enough to defeat it.