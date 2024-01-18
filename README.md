# Bouncing Balloons Booleans

Welcome to the Bouncing Balloons Booleans game repository! This Unity game challenges players to control a floating balloon, avoiding bombs and collecting money for a dazzling fireworks display. The game is an outcome of Challenge 3 from a Unity Game Development bootcamp.

## Table of Contents

- [Overview](#overview)
- [Game Mechanics](#game-mechanics)
- [How to Play](#how-to-play)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)

## Overview

Bouncing Balloons Booleans is a casual Unity game where players control a balloon, trying to stay afloat while avoiding bombs and collecting money. The game features a simple yet challenging gameplay loop, providing an entertaining experience.

## Game Mechanics

The game includes the following key mechanics:

- **Balloon Control:** Players control a balloon that floats upward when the spacebar is pressed.
- **Obstacle Spawning:** Bombs and money objects are spawned at random intervals from the right side of the screen.
- **Collision Detection:** Collisions with bombs result in an explosion and the game ending. Money collisions trigger fireworks.
- **Ground Interaction:** The balloon bounces back up when colliding with the ground.

## How to Play

1. **Stay Afloat:**
   - Use the spacebar to control the balloon's upward movement. Keep the balloon afloat to avoid collisions.

2. **Avoid Bombs:**
   - Colliding with bombs ends the game. Dodge bombs to survive longer.

3. **Collect Money:**
   - Collect money objects to trigger a festive fireworks display.

4. **Bounce Back:**
   - If the balloon collides with the ground, it bounces back up.

## Scripts

### 1. `RepeatBackgroundX.cs`

This script manages the seamless repetition of the background, creating a continuous scrolling effect.

### 2. `SpawnManagerX.cs`

Controls the spawning of bombs and money objects at random intervals.

### 3. `MoveLeftX.cs`

Moves game objects (excluding the background) to the left. Objects are destroyed if they go off-screen.

### 4. `PlayerControllerX.cs`

Manages the player's balloon control, collision detection, and game state. It includes features such as upward floating, collision responses, and the ability to trigger fireworks.

## Contributing

If you're interested in contributing to the Bouncing Balloons Booleans game, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE), allowing for both personal and commercial use.

Feel free to reach out with any questions, feedback, or suggestions.

Enjoy playing and developing Bouncing Balloons Booleans!
