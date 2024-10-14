# Turtle Crossing Game

This is a simple Turtle graphics-based game where the player controls a turtle character that must cross a busy road filled with cars. The goal is to reach the other side safely while avoiding collisions with the moving cars. As the player successfully crosses, the game becomes progressively harder with increasing levels.

## Features

- Control the player using keyboard inputs.
- Randomly generate cars that move across the screen.
- Detect collisions between the player and cars.
- Track levels and display the game score.
- Simple and engaging gameplay suitable for all ages.

## Project Structure

### Main Application File

- `main.py`: The main script that runs the game, initializes the screen, player, car manager, and scoreboard. Contains the main game loop to manage the game's logic and interactions.

### Classes

- **Player**: Handles the player's movement and checks if the player has reached the finish line.
- **CarManager**: Manages the creation and movement of cars on the screen.
- **Scoreboard**: Displays the current level of the player and handles the game-over screen.

