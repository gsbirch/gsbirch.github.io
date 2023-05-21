---
layout: page
title: Party Shooter
subtitle: A fast paced casual FPS to compete with your friends!
---

[Download](https://drive.google.com/file/d/1AuwU0v7oqLcdqL5f5_u8eMEcbnIr37rP/view?usp=sharing)


### Changelog
#### Dev Build 3 (unreleased)
- Gameplay
    - Player movement no longer uses physics
    - Weapons no longer show up on enemies
    - Player model now changes color to correspond with player color
    - The winner now shows up on the end screen
    - Added a sensitivity slider (hit ESC to access it!)
    - Player rotation is now visible for all clients
    - Player model now strafes left/right and walks backwards
- Lobby
    - The host can now modify the respawn time on the lobby screen
    - Player list shows up in lobby for all players
    - Maximum player name length is now 16 characters
    - Entering nothing into the address/port inputs will now default to localhost:7777
- Weapons
    - Added the shotgun weapon
    - Pizza now explodes with more projectiles in a sphere
    - Pizza now explodes upon any collision
    - Goo ball from fish and pizza projectile now both kill players
    - Meteor from meteor staff now explodes in a large radius upon collision
    - Increased force of Playing Card projectile
- Fixes
    - The game now runs on port 7777
    - Fixed bug where Map1's pillars could not be gooped
    - Fixed bug where player's weapon was swapped upon suicide in Random Deathmatch
    - Fixed serialization error with weapons
    - Fixed bug where setting gamemode/map before a client joins would give the client an error
