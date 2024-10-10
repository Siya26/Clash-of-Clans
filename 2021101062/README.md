# Assignment 3.1

- Everything mentioned in the assignment has been implemented.

- To run the game : `python3 game.py`
- To view replays : `python3 replay.py`  and select the replay you want to watch according to mentioned date and time.
- For Victory : All buildings apart from walls get destroyed from the map in all three levels.
- For Defeat : If all troops and King die before destroying all buildings apart from walls.

## Controls :

### Hero :

- w : move up
- a : move left
- d : move right
- s : move down
- 1 : Special Attack
- space : Normal Attack

### Barbarian :

- z : spawn at point 1
- x : spawn at point 2
- c : spawn at point 3

### Dragon :

- v : spawn at point 1
- b : spawn at point 2
- n : spawn at point 3

### Archer :

- i : spawn at point 1
- o : spawn at point 2
- p : spawn at point 3

### Balloon :

- j : spawn at point 1
- k : spawn at point 2
- l : spawn at point 3

### Stealth Archer :

- t : spawn at point 1
- y : spawn at point 2
- u : spawn at point 3

### Healer :

- e : spawn at point 1
- f : spawn at point 2
- g : spawn at point 3

q : Quit Game

## Game Additions :

### Stealth Archer :
- Attack radius = 4
- Attack = 1
- It can be attacked only after 10s after it has been spawned (invisible for the first 10s). Used time library to implement this feature.

### Healer :
- Attributes mentioned in the assignment are implemented.

### Bonus :
```
Levels of various buildings is initiated in the respective classes and it has been hardcoded.
```
- Level of hut = 1
- Level of cannon = 2
- Level of wall = 3
- Level of wizard tower = 4
- Level of townhall = 5
- Explosion of wall (when its level >= 3), results in damage of troops which lie in the area mentioned in the assignment. 
## Assumptions :

- Rage and Heal Spell can be applied multiple times.
- The limit for troops in each level is as follows :
    - Barbarians : 10
    - Archers : 7
    - Balloon : 5
    - Dragon : 3
    - Stealth Archers : 7
    - Healer : 5
- You have to choose the type of troop movement at start of the game.
- You have to choose the hero after each level.
- Healers only heal the nearest troop to them. 