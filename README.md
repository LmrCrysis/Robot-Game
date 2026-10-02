# RobotGame

A third-person sci-fi gameplay prototype built with **Unreal Engine 5**
using **Blueprint visual scripting**.

## Overview

Control a robot, explore sci-fi environments, avoid fire hazards,
collect useful items, and repair a teleportation device.

The project includes a sci-fi interior and a desert canyon environment.


## Screenshots

| Sci-Fi Interior | Desert Canyon | Teleporter |
|---|---|---|
| ![Interior](<img width="1876" height="878" alt="Screenshot 2026-10-02 191858" src="https://github.com/user-attachments/assets/acec6e38-a8b1-46ea-ab9b-8e20d1e596fa" />
 ,<img width="1881" height="887" alt="Screenshot 2026-10-02 191841" src="https://github.com/user-attachments/assets/97503067-dd43-4e34-991c-d19045ea0118" />
) | ![Canyon](,<img width="1877" height="882" alt="Screenshot 2026-10-02 191957" src="https://github.com/user-attachments/assets/13932901-b5f1-423f-9848-a3e84df3c52f" />
,<img width="1883" height="880" alt="Screenshot 2026-10-02 191932" src="https://github.com/user-attachments/assets/19bf022c-2bae-47fb-b29c-7d90ff2e687e" />
) | ![Teleporter](<img width="1880" height="882" alt="Screenshot 2026-10-02 192224" src="https://github.com/user-attachments/assets/386925ea-ed2b-4ca9-856f-5bd73af4ddf3" />
,<img width="1882" height="872" alt="Screenshot 2026-10-02 192217" src="https://github.com/user-attachments/assets/ed3ffc1e-967f-4aaf-b000-2f7cac783ec5" />
,<img width="1882" height="877" alt="Screenshot 2026-10-02 192206" src="https://github.com/user-attachments/assets/14d0e408-146c-4b43-b552-67602c89a24a" />
,<img width="1886" height="876" alt="Screenshot 2026-10-02 192145" src="https://github.com/user-attachments/assets/6021c35d-90ad-4f02-9d17-4575d6a78312" />
,<img width="1877" height="880" alt="Screenshot 2026-10-02 192129" src="https://github.com/user-attachments/assets/fb402fb6-7d2d-4693-9ce0-349aedf58a67" />
,<img width="1882" height="880" alt="Screenshot 2026-10-02 192115" src="https://github.com/user-attachments/assets/02bc0122-c3f3-44c0-8513-52c59e9d440a" />
,<img width="1891" height="870" alt="Screenshot 2026-10-02 192053" src="https://github.com/user-attachments/assets/751060b4-aff3-4dc2-b698-baa25f16b128" />
,<img width="1892" height="881" alt="Screenshot 2026-10-02 192041" src="https://github.com/user-attachments/assets/868846d2-9481-4362-ad45-8911cd5d64b6" />
<img width="1892" height="881" alt="Screenshot 2026-10-02 192041" src="https://github.com/user-attachments/assets/9a09ad4a-abcf-41d4-9b09-e9adab1b99f3" />
,<img width="1868" height="883" alt="Screenshot 2026-10-02 192030" src="https://github.com/user-attachments/assets/d5846039-9114-4681-9f24-750f68443ea0" />
) |


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
