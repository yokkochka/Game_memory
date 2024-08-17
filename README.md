# Memory Game with Pygame
### Pet project (autumn 2023)

This repository contains a memory game built using the Pygame library. The game challenges players to match pairs of cards with various shapes and colors. It includes a leaderboard and animations for level transitions and victories.

## Description

The game presents a grid of cards face down. Players take turns flipping two cards at a time, trying to find matching pairs. The game includes different levels with increasing difficulty, and it tracks the player's score and remaining steps. Upon completing a level, the game advances to a new level with a larger grid. The player can view their score and name on a leaderboard.

## Features

- **Multiple levels**: Increase the grid size and difficulty with each new level.
- **Card matching**: Flip and match pairs of cards based on color and shape.
- **Score tracking**: Keep track of the player's score and remaining steps.
- **Victory animation**: Display an animation when the player completes a level.
- **Leaderboard**: Save and display the top scores.
- **User input**: Enter a name to save to the leaderboard.
- **Game restart**: Restart the game or return to the leaderboard upon completion.

## Usage

1. **Start the game**: Run the script to start the game.
2. **Play the game**: Click on cards to flip them and try to match pairs.
3. **View leaderboard**: When the game ends, you can view the leaderboard and enter your name to save your score.
4. **Restart or quit**: Choose to restart the game or quit from the leaderboard screen.

## Installation and running

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your_username/your_repository.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd your_repository
    ```

3. **Ensure required modules are installed:**
    Install the necessary modules using pip:
    ```bash
    pip install pygame
    ```

4. **Run the script:**

## Screenshots

### Main Game Screen
![Game Screen](./screenshots/game_screen.png)

## File Structure

- `game_memory.py`: Main script file for the game.
- `leaderboard.txt`: File to store top scores.
- `music_dir/`: Directory containing the music file for the game.
- `materials/`: Directory for screenshots of the game.

