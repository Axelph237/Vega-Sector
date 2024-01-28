![[banner_3.jpg|p+tc banner+small]]
____
## Melee Weapons
These types of weapons function 


____

## Ranged Weapons
Ranged weapons perform much like a melee weapon, but have the additional complexity of determining range.

### Range
Ranged weapons have an optimal range denoted as `low #-high #`. A target who is between or at these distances is considered to be **in range**, otherwise they are **out of range**.

### Stability Checks
A ranged weapon has two different `stability` numbers shown in a pair as `(lower # / higher #)`. The lower of the two numbers is used for `stability` checks when the target is out of range. Otherwise, the higher number is used.


_____

## Firearms
Firearms are considered ranged weapons, but also have their own special rules.

### Making an Attack
After determining a target with a firearm, a creature must choose how many shots they will take. They do this by spending a number of dice from their `magazine` pool from one up to the weapon's `fire rate`. These dice are considered **committed** until the end of the action.

### Determining Hits
Firearms use a unique set of dice when making `stability` checks. This set of dice is determined by the firearm's `handling` stat. For instance, if a weapon has a `handling` of `2d6,1d4` it would roll two d6s and a d4 in order to make its `stability` check.

### Dealing Damage
After rolling to hit, a creature rolls all of its committed dice. For every failed point during the `stability` check, one dice of the creature's choice must be removed from the now rolled committed dice. Then, all remaining committed dice are totaled to determine the damage dealt.

### Running out of Ammo
When a creature runs out of ammo (usually due to spending all of the dice in their `magazine` pool), they must take a reload action before attacking with this weapon again. A reload action has an exhaustion of one.