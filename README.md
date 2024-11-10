# Nine_To_Five (9 - 5)

A 2.5D platformer that takes you through a day in the life of a college student, from the morning rush to classes, social interactions, assignments, and an ever-moving sun marking the hours from 9 AM to 5 PM. Dive into the relatable, sometimes quirky world of college life and experience the ups and downs of an average day as a student.

---

## Table of Contents
1. [Game Overview](#game-overview)
2. [Unique Features](#unique-features)
3. [Controls](#controls)
4. [Installation](#installation)
5. [Deployment](#deployment)
6. [Gameplay Overview](#gameplay-overview)
7. [Documentation](#documentation)

---

## Game Overview

9 - 5 is a 2.5D platformer built in Unreal Engine 5.4.4 that offers a light-hearted simulation of college life. The player embarks on a day that starts at 9 AM and ends at 5 PM, moving through a series of typical college experiences: completing assignments, socializing with friends, meeting quirky characters, and even taking exams. The game uses 2D characters within a 3D environment, providing a unique visual style and gameplay experience.

## Unique Features
2.5D Visuals: The game employs 2D character sprites within a 3D environment, creating a unique hybrid experience that merges platforming mechanics with a visually distinct style.
Dynamic Sun Movement: Experience a full day in-game with realistic sun movement from morning to afternoon.
Relatable College Themes: Each level of the game represents different aspects of a student's day, from social encounters to academic pressures and more.

## Controls
WASD - Movement <br>
E - Interact with objects and NPCs <br>
Tab - Open Inventory

## Installation
To set up 9 - 5 on your machine, follow these steps:

1. Clone the Repository: 
```bash
git clone https://github.com/altf4-games/Nine_To_Five.git
```
2. Open the Project in Unreal Engine: <br>
3. Navigate to the cloned directory. <br>
4. Double-click on the Nine_To_Five.uproject file to open the project in Unreal Engine 5.4.4. <br>
```bash
Note: No additional prerequisites are required for setup beyond Unreal Engine 5.4.4.
```

## Deployment
To deploy 9 - 5 as a standalone executable:

Build the Project:
In Unreal Engine, go to File > Package Project and select the desired platform (e.g., Windows, Mac). <br>
Choose a target directory to save the packaged project. <br>
Click Package and allow the engine to compile and build the project. <br>
Run the Executable: <br>
After packaging completes, navigate to the output directory and locate the executable file (e.g., 9-5.exe on Windows). <br>
Double-click the executable to launch the game. <br>

## Gameplay Overview
Concept
9 - 5 immerses players in a single day of college life, where they navigate campus, interact with characters, complete assignments, and take part in various activities. The day progresses dynamically, with the sun shifting across the sky to mark the passage of time from morning to afternoon.

### Level Design
The game revolves around a central hallway that serves as a hub. From this hallway, the player can access various rooms
### Player Interactions
Dialogue System: Each NPC encounter presents unique dialogues, adding depth and variety to social interactions. <br>
Inventory: Players can collect and store items that will assist them in completing objectives and add context to each level. <br>
### Gameplay Highlights
Assignments: Locate and complete assignments throughout the day as part of your student responsibilities. <br>
Social Interactions: Meet friends, encounter quirky NPCs, and engage in lighthearted conversations. <br>
Exam Challenges: Face mini-exams. <br>
Day/Night Cycle: Experience realistic time progression with a moving sun that changes the lighting and mood of the scene.


## Documentation
### Folder Structure
```bash
9-5/
├── 2DSideScroller/
│   └── PlayerCharacter (Main Player Blueprint)
├── Audio/
│   └── BackgroundMusic, SoundEffects
├── Blueprints/
│   ├── NPCs (NPC interaction and behavior blueprints)
│   ├── Pickups (Collectible item blueprints)
│   └── Doors (Room transition blueprints)
├── Maps/
│   └── Levels (College Level & Main Menu)
├── PaperAssets/
│   ├── Sprites (2D character and item sprites)
│   └── Flipbooks (2D animations)
├── StarterContent/
│   └── Basic materials, textures, particles
├── StaticMesh/
│   └── 3D models
└── UI/
    └── HUD elements
```
2DSideScroller: Contains the main player character blueprint, handling movement and interactions. Uses Paper2D for 2D sprites and AdvancedCellShader for cell-shaded visuals.

Audio: Stores background music, sound effects, and ambient sounds.

Blueprints: Contains core gameplay blueprints:

NPCs: Interaction logic and behaviors for non-playable characters.
Pickups: Interactive item blueprints (e.g., food, assignments).
Doors: Controls room transitions from the main hallway hub.
Maps: Houses level maps, including the central hallway and various college rooms (e.g., dorm, cafeteria, library).

Paper Assets: Includes 2D sprites and flipbooks for character animations and other visual elements using Paper2D.

StarterContent: Unreal’s basic materials, textures, and particles, complementing custom assets.

StaticMesh: Contains 3D models for environmental objects, enhancing the 2.5D style.

UI: Widgets for inventory, dialogue, and HUD elements.
