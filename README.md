# GAM207 Arena Shooter

A first-person arena shooter prototype built in **Unreal Engine 5.7** for the SNHU GAM-207 game development project. The project focuses on core gameplay systems, enemy AI, player feedback, and a small arena experience.

> **Project status:** Academic gameplay prototype. Features described here reflect the implemented project scope; this is not presented as a finished commercial game.

## Overview

GAM207 Arena Shooter is a hands-on Unreal Engine project exploring how separate gameplay systems work together in a first-person experience. The goal is to create a clear gameplay loop: move through an arena, engage an enemy, manage health, and use pickups to stay in the fight.

## Gameplay features

- **First-person movement and camera** for navigating the arena.
- **Projectile combat** with damage interactions.
- **Enemy AI** with patrol behavior, sight-based detection, pursuit, and attacks.
- **Health and damage systems** for both the player and enemy.
- **Player HUD** with a health bar and crosshair feedback.
- **Character animation** for idle and movement states.
- **Health pickup** to restore player health.
- **Speed boost pickup** with a temporary effect and respawn behavior.
- **Super jump mechanic** with a cooldown.
- **Enemy respawn** after defeat to support repeated gameplay testing.

## Built with

- **Unreal Engine 5.7**
- **Blueprint visual scripting**
- Unreal Engine's built-in AI, character, animation, UI, and collision systems

## Getting started

### Requirements

- A Windows PC capable of running Unreal Engine 5.7.
- Unreal Engine **5.7** installed through the Epic Games Launcher.
- Enough free memory and disk space for Unreal Engine and the project. Unreal Engine projects can be demanding on system resources.

### Open the project

1. Clone or download this repository.
2. If you use Git LFS, make sure Git LFS is installed and initialized before cloning so tracked large assets can be retrieved.
3. Open the project folder.
4. Double-click **`GAM207ArenaShooter.uproject`** to launch it in Unreal Engine 5.7.
5. Allow Unreal Engine to prepare shaders and load assets on the first launch. This can take some time.
6. Open the project’s gameplay level and use **Play** in the editor to test the experience.

If Unreal Engine reports missing files or assets, first confirm that the repository and any Git LFS content were fully downloaded. Avoid deleting project folders or generated files unless you have a verified backup.

## Controls

The exact key bindings depend on the current project input settings. Check **Edit → Project Settings → Input** (or the project's Enhanced Input assets, if used) to confirm the configured movement, look, fire, and jump controls.

## Project structure

This repository contains the Unreal Engine project and its associated game assets and configuration. The primary project file is:

- `GAM207ArenaShooter.uproject` — opens the project in Unreal Engine.

Blueprints, levels, UI widgets, character assets, and other resources are managed inside the project’s content directory.

## Development notes

This project was developed as part of an academic game-development workflow, with emphasis on implementing and testing individual systems before combining them into a playable prototype. The repository may evolve as bugs are fixed, visuals are refined, and the project is prepared for portfolio review.

For best results, use the Unreal Engine version listed above and keep a separate backup before making major project or asset changes.

## Credits and use

Created by **Rakim Spriggs** for the SNHU GAM-207 project.

This repository is shared for educational and portfolio purposes. Unreal Engine and any third-party assets, characters, animations, sounds, or other included resources remain subject to their respective licenses and terms. Check the relevant asset licenses before reusing or redistributing them.

---

*Thanks for checking out GAM207 Arena Shooter.*
