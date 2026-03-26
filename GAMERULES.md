# Exploration
## Map placements
The map size is a square that is determined based on the player count (e.g. player count: 2, map size: 10 x 10).
Players are placed randomly on the map in a "fog of war" format.
Enemy NPCs (Barbarians) are placed randomly on the map.

### Player behaviour
Each player starts with 3 henchmen that can explore independantly.
In a single player turn each henchman can either:
 + move: move one tile at a time
 + attack: attack another player in vicinity
 + use card: activate card
A single round consists of an exploration component, and an optional combat component:
 1. exploration : each player uses their henchmen
 2. combat : can occur in 2 ways
    + if a player uses "attack" on a nearby henchmen
    + if 2 or more henchmen land on the same tile
Once players have done everything in their turn they press 'ready'.
Player turns take place based on who pressed 'next turn' first.

## Card Management
Cards are obtained as a combat reward by defeating barbarians, or by exploring rare landmarks. Players can choose from 3 random cards.
The main cards types are:
### Combat cards
- Deal x damage to enemies within 1 space
- Next combat numbers appear for longer
- Next combat incrase time for inputting numbers
### Defence cards
- Avoid next combat
- Decrease attacking player's time for inputting numbers
- Heal 5 HP
### Exploration cards
- Move 3 spaces instead of 1
- Reveal the location of nearest landmark
- Reveal enemy location
### Recruitment cards
- Gain 1 Viking
### Raiding cards
- Steal a card from a player
# Combat
## Turn Order
