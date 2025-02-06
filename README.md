# Bubblegum Bloodbath
A 2D platformer built entirely using C++ that adheres to ECS architecture. It features multiple playable levels, a final boss battle, diverse weapons with unique mechanics, and fully customizable game settings. It also includes a level editor that allows users to create, modify, and save their own levels.

## Game Trailer
[YouTube URL](https://youtu.be/APVTMvT-CXE)

## Features
- Levels
  - 3 prebuilt levels
  - Boss level
- Custom Level Editor
  - Allows you to:
    - Create new levels
    - Modify existing levels
    - Save levels 
- Overworld Level Select Map
- Collisions
- Movement
  - Our Game's Movement Abilities:
    - Double Jump w cooldown
    - Dash (with invulnerability) with resource cost
- Bullets / Weapons
  - Our Game's Weapons are:
    - Shotgun (several bullets fired in a spread)
    - Grenade (thrown with an arc then does AoE damage)
    - Laser Cannon (uses raycast)
    - Poison Dart (does damage over time)
    - Machine Gun (similar mechanics to Shotgun, different spread and timing)
  - Weapons are swappable during gameplay via hotkey
- NPCs
  - Our Game's NPCs are:
    - Bats fly and deal knockback
    - Spiders drop down and jump at the player
    - Crawlers ignore the player and act as a moving, "static", hazard
- Hit Points / Damage
  - Player / enemies in the game have hit points (life) and take damage / die
- Objects / Inventory
  - Different items that are obtainable during the game via interaction:
    - Speed Boost Candy
    - Roll Candy
    - Double Damage Candy
    - Full Health
    - Key
  - UI displays inventory of these items, allowing for their use after obtaining
- Ray Casting for Visibility
  - Bats fly towards the player if they can see them
  - Spiders drop and attack if the player walks under them
  - Laser affects all npcs in its path
- Gravity
- Camera / World View
  - Our Game's Camera Views:
    - Standard main camera view of gameplay
    - Mini-map of local area that shows player position
- Audio
  - Background music during gameplay and menu scenes
  - Sound effects that occur for events such as getting hit, item pickup, etc
- Options Menu
  - Allows you to change the following settings:
    - Music Volume
    - Sound Effects
    - Game Difficulty - Normal, Easy (deal 2x, take 0.5x damage), Hard (deal 0.5x, take 2x damage)
    - Rebind main gameplay scene keys - for example moving left / right, jump, shoot, etc
- Status Effects
  - Our Game's Status Effects are:
    - Invincibility
    - Poison
    - Speed boost
    - Double damage
- HUD
  -  HUD which displays information such as:
    - Player health
    - Grenade Ammo
    - Game Progression
    - Double jump cooldown
    - Status Effects / Timers
    - Boss Health Bar
- Moving Tiles
- Shaders
  - Our Game's Shaders:
    - Invincibility
    - Poison
    - Speed boost
    - Shake
- Parallax
  - Our Game's Parallax:
    - Clouds move in the background at half-speed
- Ray Casting for Simple Lighting Effect
  - Our Game's Lighting Effect:
    - The boss will attack the player with a "flashbang" effect that creates an opaque white overlay (and deals damage)
- Steering
  - Our Game's Steering:
    - Bats use steering to smooth their movement as they follow the player
- Fancy NPC AI that goes above and beyond (boss goes through several phases, has three unique attacks, and will react to the player's movements)
- Particle System

## Awards
- [Best Overall Project](BestProjectBB.pdf)
- Best Aesthetic

## Contributers
- Ethan Denny
- Fathima Manooja
- Ripudaman Singh
- Raunak Sarmacharya
