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

## Game Mechanics
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

## What Will Be Used
- The Rust Programming Language
- Bevy Engine
- Rapier 2D Physics Engine

## Inspiration

Concept Art:

![image](https://user-images.githubusercontent.com/56494343/230964639-d793619b-b189-4de3-bcfe-653b1c1ea7e8.png)

Mechanism:

![image](https://user-images.githubusercontent.com/56494343/230964849-8a755d3f-3cf9-42fc-ae40-465ff577faa9.png)
