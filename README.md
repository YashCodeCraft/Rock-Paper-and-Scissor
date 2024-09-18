# Rock, Paper, Scissors Game

A simple console-based Rock, Paper, Scissors game implemented in Python. The user can play a customizable number of rounds against the computer. The game determines the winner after comparing the player's and computer's guesses.

## Table of Contents

- Features
- How to Play
- Game Rules
- Installation
- Running the Game
- Requirements
- Project Structure

## Features

- The user can select the number of rounds (between 5 to 13).
- The game keeps track of wins, losses, and ties.
- The game is run in the terminal/console.

## How to Play

1. Run the Python script in a terminal or command prompt.
2. Enter the number of rounds you want to play (between 5 and 13).
3. For each round, choose one of the following:
    - 'r' for Rock
    - 'p' for Paper
    - 's' for Scissors
4. The computer will randomly choose its move.
5. The winner of each round will be determined based on the standard Rock, Paper, Scissors rules (explained below).
6. The game will show the total wins, losses, and ties after all rounds are played.

## Game Rules

- **Rock** beats **Scissors**.
- **Scissors** beat **Paper**.
- **Paper** beats **Rock**.
- If both the player and the computer choose the same item, it is a tie.

## Installation

1. Clone this repository or download the Python file.
   ```bash
   git clone https://github.com/YashCodeCraft/Rock-Paper-and-Scissor.git
   ```

2. Ensure that Python is installed on your system (Python 3.x recommended).
   
## Running the Game
To start the game, navigate to the directory where the Python file is located, then run the following command:

```bash
python3 main.py
```

## Requirements
- Python 3.x
- No additional libraries are required.

  
## Project Structure
```plaintext
rock-paper-scissors/
│
├── README.md           # Game instructions and documentation
├── main.py             # Python script for the game
└── .gitignore          # To ignore unnecessary files (optional)
```
