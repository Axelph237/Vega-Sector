## Consumable
Consumable items are... consumed after use. When used, one item from a stack of consumable items is removed.

## Explosive
Explosive items resolve damage differently from other weapons. The number of dice an explosive weapon's `Power` has is proportionate to its area of affect. i.e. if its `Power` is `3d4`, it has a total area of affect of a 10 ((3 dice * 5 feet) - 5 feet for the directly hit square) foot radius.

Damage is resolved as follows: for every 5 feet away a creature is, it takes one less dice of damage.

> [!example]
> An attack is made with an explosive weapon of **Power** 4d6 (area of affect: 15 feet).
> The attack roll resolves to: 1 + 3 + 4 + 6 = 14
> - Creatures directly hit will take all 14 damage.
> - Creatures 5 feet away will take 13 (3 + 4 + 6) damage.
> - Creatures 10 feet away will take 10 (4 + 6) damage.
> - Creatures 15 feet away will take 6 damage.

Explosive damage is unavoidable by movement or team affiliation, but strong barricades completely nullify any potential damage taken.

## Throwable
Hit or miss rolls. Have two stats: `Power`, `Stability`. Handling dice default to `2d12` for throwables.

For every failed point on the `Stability` check, the item is throw 5 feet farther from its intended destination (where determined by GM).

When a throwable is thrown, it must then be retrieved by visiting the space it was thrown to.