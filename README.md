# Dead Cells Mod UI
A comprehensive interface for modding the game Dead Cells

## With the development of https://github.com/dead-cells-core-modding/core this tool might be more impactful and its restrictions reduced

Modding in Dead Cells is quite limited, but it can be made easier so anyone can adjust the game to their liking.

## THIS REPOSITORY IS ONLY IN ITS CONCEPT STAGE AND HAS NO PLANNED DEADLINES

### Mockup:

![deadcellsuiprototype](https://github.com/user-attachments/assets/d95dd0e5-8b16-4323-84c0-330d17916763)

# Planned Features

## Weapons Page

In the aplication, the Weapons page is where you change the data from weapons and items, which can be selected by a list (read from the datascp file from res.pak)<br>
For each weapon, you can:
* Change the color it scales with (Brutality, Tactics, Survival, or a combination of them)
* Change the base price of the item sold in shops
* Change the Legendary Affix (*can be limited for some effects)
* Change the Tags (Will affect what mutations, affixes, etc. can be attached to the weapon)
* View each attack from the weapon's combo (selectable by its tabs)
* Change the selected attack's Damage, Crit Multipler, Cooldown, Delay, Hit Frame, Hitbox, Sounds and Sprites
* View the attack animation in motion
* View the full combo animation in motion
* Change aditional properties (very limited)

For each item, you can:
* Change the color it scales with (Brutality, Tactics, Survival, or a combination of them)
* Change the damage of the item, if it has damage
* Change the cooldown of the item

### Limitations

Not everything can be changed, as some items are hard coded to have a specific behavior. That is why you can't change the crit condition on weapons, some Legendary Affixes don't work in all weapons, and why you don't have full control on any additional property the item might have.

## Affixes

To change editable values from item affixes.

## Blueprints

To change Blueprint spawning behavior, such as the percentage an enemy will have a blueprint in the level.

## Hero

To change base values for the beheaded, such as jump height, speed, health, etc. Can be very risky to change
