# [game name] Concepts and Design

## Main Idea
- 2d coop platformer escape room game
- Level based game
- Level consist of set of blocks and items, player spawn in specific location
- Level have limited size with 1 screen or maybe multiple screen with Celeste like transition
- There will be default levels and user defined levels. So there will be also a level editor
- The final objective of the level is up to level creator. Example:
    - combination lock(s)
    - locked door
    - players have to stand on particular location or do particular movements
    - Objective is not clear as player have to look for the objective first
- Because this is a coop game, the number of player to play this game is 2, no less, but maybe more

## Features
- Locked door/ block that can be opened or maybe despawned with corresponding colored key
- Block that can be moved
- Mobs that can help, annoy, kill, or do something to player
- Asymmetric player privileges. Example:
    - Player specific clue item
    - Player 1 can move block, player 2 can't
    - Player 1 can't see block, player 2 can
    - Item/ that behaves differently or maybe also the looks depending on the player viewing it
- Spell: item or entity that can change player behaviour. Example:
    - Shrink player/ make player huge
    - Jump boost
    - Super speed
- Some block are breakable and not breakable. Some breakable block drops item. And some of it can drop different item. So basically, like Minecraft
- "Smart blocks". Basically like redstone in Minecraft
    - Piston
    - Power source: can be energy based or binary and stregth based. So like Minecraft
    - Explosive
    - Locked doors that can only be opened by power