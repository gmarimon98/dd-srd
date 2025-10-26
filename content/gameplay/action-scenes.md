---
title: Action Scenes
weight: 9
---

# Action Scenes

Action scenes are critical moments of gameplay where the narration of the game goes from a conversational flow to a more structured turn-based flow. Time slows down and every decision matters. For example, a combat against some bandits or a car chase are action scenes.

In action scenes, the GM first establishes which sides are participating in the scene (usually just the players and their enemies, but there could be a third side as well) and which side starts. Each side takes one turn at a time. When it’s the players’ side’s turn, one member of that side can take the following actions:
- Move from one place to another
- Make one roll

Then, the opposing side takes a turn. However, only players roll dice. Whenever other characters or enemies act, the GM imposes a roll on one or more players. A member of a side cannot take another turn until all members of that side have taken a turn.

## Combat

Combat is a type of action scene where the players fight enemies. Enemies have the following attributes:
- A difficulty, ranging from 10 to 25
- A health value, ranging from 1 to around 10
- A list of tags, each with a star value ranging from 1✦ to 5✦
- A weakness, which if invoked in the roll, causes successful combat rolls to deal one extra damage

For example, the following is an enemy:

**Young Red Dragon**
- Difficulty: `10`
- Health: `5`
- Weakness: `Cold`
- Tags:
    - `Fire Breath` 4✦
    - `Flying` 3✦
    - `Hardy Scales` 3✦
    - `Tail Swipe` 2✦
    - `Snapping Jaws` 1✦
    - `Razor Claws` 1✦

When attacking an enemy, make a roll against their difficulty plus an additional tag of the GM’s choice. An enemy’s tags are not exhausted after use. Instead, the enemy cannot use that same tag again until they have used all other tags at least once. If the roll is successful, the player applies damage to the enemy’s health based on the [**Outcomes Table**]({{< relref "/reference#outcomes" >}}).

When defending against an enemy, the player rolls defensively against the difficulty plus an additional tag of the GM’s choice. If successful, the player can also apply damage when attacked, as per the [**Outcomes Table**]({{< relref "/reference#outcomes" >}}).

---

## Example Combat Roll

The following is a full example of a combat roll:

1. A character chooses to attack the above Young Red Dragon, using their Combat stat (3✦), Broadsword (2✦), and one drive (1✦).
2. In response, the Young Red Dragon uses its Tail Swipe (2✦) to try to keep its distance from the player character. This results in a modifier of +6 for the player (plus one boon if successful) and a difficulty of 12.
3. The player rolls a 20 and scores a critical success, dealing 3 damage to the Young Red Dragon, bringing it down to 2 health remaining. 
4. Because the attack resulted in a critical success, the player gains boons based on the [**Difficulty Table**]({{< relref "/reference#difficulty" >}}), gaining 2 boons (plus 1 from the spent drive) as per the difficulty 12 row.
