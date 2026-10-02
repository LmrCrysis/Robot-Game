# RobotGame

A third-person sci-fi gameplay prototype built with **Unreal Engine 5**
using **Blueprint visual scripting**.

## Overview

Control a robot, explore sci-fi environments, avoid fire hazards,
collect useful items, and repair a teleportation device.

The project includes a sci-fi interior and a desert canyon environment.

Nice — the push went through. Quick verification first, then the finishing touches I promised.

## Screenshots

| Sci-Fi Interior | Desert Canyon | Teleporter |
|---|---|---|
| ![Interior](Screenshots/interior.png) | ![Canyon](Screenshots/canyon.png) | ![Teleporter](Screenshots/teleporter.png) |


## How to Run

1. Install [Git LFS](https://git-lfs.com) and clone the repository:
   git clone https://github.com/LmrCrysis/Robot-Game.git
2. Download the required asset packs (see below) and place them in the Content/ folder.
3. Open RobotGame.uproject with Unreal Engine 5.x.

## Gameplay Features

- Third-person player movement, camera controls, and jumping.
- Player health, fire-hazard damage, and death handling.
- Collectible key card and access-controlled animated doors.
- Battery and antenna pickups with interaction prompts.
- Teleporter progression using enum-based states:
  - NeedBattery
  - NeedAntena
  - ReadyToTeleport
- Camera fading during level transitions.

## Required Asset Packs

This project uses third-party assets from Fab / the Unreal Marketplace.
Their licenses do not allow redistribution, so they are not included in
this repository. To run the project, download these packs and copy them
into Content/:

| Pack | Used For |
|---|---|
| OldWest | Desert canyon environment |
| Sci_fi_hallway | Sci-fi interior |
| RBots | Robot character |
| MsvFx Niagara Explosion Pack 01 | Explosion effects |
| FreeGameSoundsVol1 | Sound effects |
| TorchFire | Fire hazard visuals |
| Characters | Character models |
| BlipCharacter | Character |
| _SplineVFX | VFX |

(Replace the pack names with exact Fab listing names/links where possible.)

## Technical Implementation

- Blueprint events and gameplay scripting.
- Collision and overlap-based interactions.
- Timelines for door animation.
- Enums and conditional logic for teleporter progression.
- Custom materials for the robot, environment, and teleport device.

## My Contributions

Implemented the gameplay Blueprints, pickup interactions, health
system, door logic, teleporter puzzle, and six custom materials.

## Project Status

Personal gameplay prototype.

## Developer

**Dhruv Chauhan**
B.Tech student, IIT (ISM) Dhanbad

GitHub: https://github.com/LmrCrysis
