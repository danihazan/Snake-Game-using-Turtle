# Snake Game using Turtle Graphics

A classic Snake Game implemented in Python using the `turtle` module. This interactive game challenges players to control a snake that grows in size as it eats food, while avoiding collisions with walls or itself.

<img src="https://github.com/user-attachments/assets/211ccea3-d8d7-4077-9a76-4a3274b83469" alt="Snake Game" width="300">
<img src="https://github.com/user-attachments/assets/b1935348-1cd7-482d-87ff-ecfdb103ed22" alt="Snake Game" width="300">
<img src="https://github.com/user-attachments/assets/7389f3e1-e6ac-4df6-95f1-0de32c6e6c9d" alt="Snake Game" width="300">

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Files in the Project](#files-in-the-project)
4. [How to Run](#how-to-run)
5. [Game Controls](#game-controls)

---

## Overview

The Snake Game is a timeless arcade game where the objective is to navigate the snake to eat food, increase its length, and score points. The game ends if the snake collides with itself or the boundaries of the screen.

---

## Features
- **Dynamic Snake Movement**: The snake moves smoothly and grows in size as it eats food.
- **Scorekeeping**: Real-time score display with a "Game Over" message on collision.
- **Randomized Food Placement**: Food appears at random positions within the game window.
- **Interactive Controls**: Arrow keys allow for precise direction changes.

---

## Files in the Project

1. **main.py**:
   - The main entry point of the game.
   - Initializes the game screen and starts the game loop.
   - Handles collision detection and game over logic.

2. **snake.py**:
   - Manages the snake's behavior, including movement, growth, and direction changes.
   - Contains the `Snake` class.

3. **food.py**:
   - Implements the `Food` class for generating and repositioning the food.
   - Ensures food appears at random locations within the game boundaries.

4. **scoreboard.py**:
   - Contains the `Scoreboard` class.
   - Displays and updates the score on the screen.
   - Handles the "Game Over" message display.


## How to Run

### Prerequisites
- Python 3.x installed on your system.

### Steps
1. Clone or download the project repository.
2. Navigate to the project directory.
3. Run the following command:
   ```bash
   python main.py
   
---
## Game Controls

- **Up Arrow (`↑`)**: Move the snake upwards.
- **Down Arrow (`↓`)**: Move the snake downwards.
- **Left Arrow (`←`)**: Move the snake to the left.
- **Right Arrow (`→`)**: Move the snake to the right.

### Additional Notes
- The snake cannot move directly backward into itself:
  - If the snake is moving upwards, it cannot move directly downwards.
  - If the snake is moving to the right, it cannot move directly left.
---





