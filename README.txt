# My Snake Game

## Overview
This is a classic Snake Game implemented in Python using the `turtle` module. The player controls a snake, which moves around the board, eating food to grow longer. The game ends if the snake runs into the wall or itself.

## Features
- Smooth snake movement with keyboard controls (arrow keys for up, down, left, and right).
- Food spawns in random locations and increases the snake's length upon eating.
- A scoreboard that updates the score with each piece of food eaten and resets if the snake collides with the wall or itself.

## How to Run
To play the game, you need Python installed on your computer. Clone this repository, navigate to the directory containing the game, and run the `main.py` file using Python:

```bash
git clone https://github.com/johnsoncr9/snake.git
cd snake-game
python main.py

## Dependencies
- Python 3
- turtle module (standard library)
- time module (standard library)
- os module (standard library)

## Files in This Repository
- main.py: The main game loop and window setup.
- snake.py: The Snake class that handles snake attributes and movement.
- food.py: The Food class for food attributes and random placement.
- scoreboard.py: The Scoreboard class for scoring and game reset.

## How to Play
- Use the arrow keys to control the direction of the snake.
- The game will automatically end and reset if the snake collides with the wall or itself.
- Enjoy the game, and try to beat your high score!

## License
This project is open-source and available under the MIT License.