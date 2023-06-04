---
layout: page
title: Party Shooter
subtitle: A fast paced FPS to play with your friends!
---

![A screenshot of Party Shooter in action](https://i.ibb.co/nDJcCK4/Screenshot-from-2023-05-21-23-00-23.png)

[Download it here!](https://drive.google.com/file/d/1AuwU0v7oqLcdqL5f5_u8eMEcbnIr37rP/view?usp=sharing)

[Roadmap](https://docs.google.com/document/d/1osJVQJvNAARqba06AudZiacfWA5Lcw23Md3RyFO1VB4/edit?usp=sharing)

Party Shooter is a fast paced FPS developed in Unity! In Party Shooter, lobbies of up to 8 players can compete in various game modes such as deathmatch or king of the hill. They can score points by hitting other players with wacky weapons such as a pizza that explodes into smaller slices or a fish that leaves poisonous puddles on the ground. Party Shooter is currently in *pre-alpha*, with Dev Builds being released as they are developed. 

### Changelog
#### Dev Build 3.1 (Current Version)
- Sensitivity options are now finer
- Shifted content of lobby screen around so all player names can be seen
- Removed Ravine's moving platforms and exchanged them with jump pads
- Unaliving yourself with goop gun/pizza/meteor staff now subtracts a point
- Increased the fire rate for the playing card
- Decreased the spread of the seeds from the melon slice
- Slowed fire rate of meteor staff (this is a temporary fix, the meteor staff will recieve a larger nerf later)
- Fixed duplicate spawn point on Ravine
#### Dev Build 3
- General
    - Added the new map: Ravine!
    - Added fullscreen mode (press F11!)
- Gameplay
    - Weapons no longer show up on enemies
    - Player model now changes color to correspond with player color
    - The winner now shows up on the end screen
    - Added a settings menu with sensitivity and volume (hit ESC to access it!)
    - Player rotation is now visible for all clients
    - Player model now strafes left/right and walks backwards
    - Players now give off a footstep sound effect while moving
    - All weapons now have custom kill and death messages
    - Made the notification toast a little smaller
- Lobby
    - The host can now modify the respawn time on the lobby screen
    - Player list shows up in lobby for all players
    - Maximum player name length is now 16 characters
    - Entering nothing into the address/port inputs will now default to localhost:7777
- Weapons
    - Added the melon slice (shoot a bunch of seeds in a cone!)
    - Pizza now explodes with more projectiles in a sphere
    - Pizza now explodes upon any collision
    - Pizza has a custom kill sound effect
    - Goo ball from fish and pizza projectile now both kill players
    - Meteor from meteor staff now explodes in a large radius upon any collision
    - Increased force of Playing Card projectile
- Fixes
    - The game now runs on port 7777
    - Fixed bug where Map1's pillars could not be gooped
    - Fixed bug where player's weapon was swapped upon suicide in Random Deathmatch
    - Fixed serialization error with weapons
    - Fixed bug where setting gamemode/map before a client joins would give the client an error
    - Fixed bug that allowed host to start game before map and gamemode were set
    - Fixed issue where moving to fast could cause you to collide with your own projectiles

#### Dev Build 2
- All weapons received a minor buff
- Each grassy corner of Map1 now has a different material to distingush them
- Fixed bug where game could not support more than 4 players

#### Dev Build 1
- Initial Release
- Fixed bug where players could not add port to connect

