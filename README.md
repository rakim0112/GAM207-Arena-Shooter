# GAM-207 Arena Shooter — Final Project Part I

A playable arena shooter developed in **Unreal Engine 5.7** for Southern New Hampshire University's GAM-207 course. The project demonstrates character input, projectile combat, AI gameplay logic, interfaces, skeletal animations, and interactive pickups.

## Project features

- **Player gameplay:** keyboard/mouse movement and camera controls, projectile firing, and damage handling.
- **AI enemies:** behavior tree and blackboard tasks, movement and targeting, sight perception, projectile attacks, health, and respawning.
- **Game HUD:** player health display, crosshair, enemy health widgets, and player/AI scoring.
- **Character presentation:** skeletal character meshes and animation blueprints.
- **Pickups:** player health recovery and a temporary movement-speed boost.
- **Level design:** a 3D combat environment with cover, obstacles, enemy encounters, and pickups.

These systems are documented across the milestone commits. The submitted gameplay recording should demonstrate the actual behavior of the final saved build.

## Opening the project

1. Install a compatible **Unreal Engine 5.7** editor.
2. Clone the repository with **Git LFS** enabled to obtain Unreal asset files.
3. Open `GAM207ArenaShooter.uproject` in Unreal Engine.
4. Open the intended playable level and press **Play** to test movement, shooting, AI, UI, and pickups.

## Repository structure

- `Config/` — game and engine settings.
- `Content/` — Unreal levels, Blueprints, meshes, widgets, animations, and assets.
- `GAM207ArenaShooter.uproject` — Unreal Engine project descriptor.
- `.gitattributes` — Git LFS tracking for Unreal assets.

## Final submission requirements

For **Final Project Part I**, the course requires:

- A **narrated MP4 screencast** showing the graded gameplay and Blueprint systems.
- A **Microsoft Word document** containing the repository URL and a screenshot of commit history.
- The repository branch named **`FinalBranch`**.
- Incorporation of instructor feedback across the milestones.

**Repository:** https://github.com/rakim0112/GAM207-Arena-Shooter

> This README documents the repository and submission workflow. Verify the final playable build and push any newer locally saved Unreal levels and assets to `FinalBranch` before submitting.
