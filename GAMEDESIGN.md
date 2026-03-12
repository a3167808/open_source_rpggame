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
# Combat
## Turn Order
