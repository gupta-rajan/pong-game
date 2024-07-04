# Pong Game in Python using Pygame

This is a simple implementation of the classic Pong game using the Pygame library in Python. The game features two paddles and a ball, and can be played by two players on the same keyboard.

## Features

- Two-player gameplay with paddles controlled by the keyboard
- Ball movement and collision detection with paddles and walls
- Scoring system with a winning score
- Reset functionality after a player wins

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Clone this repository to your local machine:
https://github.com/gupta-rajan/pong-game.git

2. Navigate to the project directory:
cd pong-game

3. Install the Pygame library if you haven't already:
pip install pygame

## Running the Game

To start the game, run the `solution.py` file:
python solution.py

## How to Play
- Player 1 controls the left paddle using the `W` (up) and `S` (down) keys.
- Player 2 controls the right paddle using the `UP` and `DOWN` arrow keys.
- The objective is to score 10 points before the opponent by hitting the ball past their paddle.

## Game Controls
- `W` key: Move left paddle up
- `S` key: Move left paddle down
- `UP` arrow key: Move right paddle up
- `DOWN` arrow key: Move right paddle down

## Code Structure
- `Paddle` class: Represents a paddle in the game.
- `Ball` class: Represents the ball in the game.
- `draw` function: Draws the game objects (paddles, ball, and score) on the window.
- `handle_collision` function: Handles the ball's collision with the paddles and walls.
- `handle_paddle_movement` function: Handles the movement of the paddles based on player input.
- `main` function: The main game loop that initializes game objects, handles events, updates game state, and renders the game.

## Acknowledgements

- The Pygame library documentation and tutorials
- Classic Pong game concept
Feel free to contribute to this project by forking the repository and submitting pull requests.

Enjoy the game!