# Bouncing Balloons Booleans Game

Welcome to the Bouncing Balloons Booleans game repository! This Unity game, developed as Challenge 3 in a Unity Game Development bootcamp, brings together balloons, collisions, and a bit of boolean fun. Let's explore the game and its components.

## Table of Contents

- [Overview](#overview)
- [Game Mechanics](#game-mechanics)
- [How to Play](#how-to-play)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)

## Overview

Bouncing Balloons Booleans is a delightful Unity game where players interact with bouncing balloons. The game involves spawning balloons at random intervals, avoiding collisions, and managing balloon destruction when they go beyond certain positional limits. It's a simple yet engaging experience suitable for various audiences.

## Game Mechanics

The game features the following key mechanics:

- **Spawn Management:** Balloons are spawned at random intervals from the top of the play area, creating a dynamic and unpredictable environment.
- **Collision Detection:** Collisions with other game objects trigger balloon destruction, providing a challenging aspect to the gameplay.
- **Destruction Limits:** Balloons are destroyed if they go beyond specified positional limits, ensuring a tidy and manageable play area.
- **Player Interaction:** Players can launch a dog into the air using the spacebar, adding a fun and strategic element to the game.

## How to Play

1. **Dodge Balloons:**
   - Use your arrow keys or A/D keys to move your character left or right to dodge incoming balloons.

2. **Launch Dogs:**
   - Press the spacebar to launch your adorable pet dog into the air. The dog can only be launched when positioned at the spawn origin.

3. **Scoring:**
   - The game is endless, and the challenge is to achieve the highest score possible by dodging balloons and launching dogs.

## Scripts

### 1. `SpawnManagerX.cs`

This script manages the spawning of random balloons at the top of the play area.

### 2. `DetectCollisionsX.cs`

Handles the detection of collisions, destroying the balloon game object upon contact.

### 3. `DestroyOutOfBoundsX.cs`

Destroys game objects (both balloons and dogs) if they go beyond specified positional limits.

### 4. `MoveForwardX.cs`

Moves game objects forward at a specified speed.

### 5. `PlayerControllerX.cs`

Controls the player's ability to launch their dog into the air using the spacebar.

## Contributing

If you're interested in contributing to the Bouncing Balloons Booleans game, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE), allowing for both personal and commercial use.

Feel free to reach out with any questions, feedback, or suggestions.

Enjoy bouncing balloons and launching dogs in Bouncing Balloons Booleans!
