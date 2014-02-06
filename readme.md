# HearthStone Cards

A list of of all existing cards in "Hearthstone: Heroes of Warcraft" (a game by [Blizzard](blizzard.com)) in JSON format. Images of the cards are included.

**The entire repository is 122.1MB in size.**

## Example

### Common cards

```json
{
    "name": "Ysera",
    "rarity": "Legendary",
    "type": "Minion",
    "race": "Dragon",
    "mana": 9,
    "attack": 4,
    "health": 12,
    "descr": "At the end of your turn, draw a Dream Card.",
    "image": "EX1_572",
    "flavorText": "Ysera rules the Emerald Dream. Which is some kind 
        of green-mirror-version of the real world, or something?"
}
```

![Ysera](https://raw.github.com/nckg/Hearthstone-Cards/master/cards/original/EX1_572.png)

### Class specific cards

```json
{
    "name": "King Krush",
    "rarity": "Legendary",
    "type": "Minion",
    "race": "Beast",
    "hero": "Hunter",
    "mana": 9,
    "attack": 8,
    "health": 8,
    "descr": "Charge",
    "image": "EX1_543",
    "flavorText": "The best defense against King Krush is to 
        have someone you don’t like standing in front of you."
}
```

![King Krush](https://raw.github.com/nckg/Hearthstone-Cards/master/cards/original/EX1_543.png)

## Bower

You can install it with [Bower](http://bower.io/).

```terminal
    bower install hearthstone-cards
```

## Suggestions or issues?

[Send a pull request](https://github.com/nckg/Hearthstone-Cards/pulls) or [create an issue](https://github.com/nckg/Hearthstone-Cards/issues)
