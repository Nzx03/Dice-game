# README.md

## Overview

This project is a simple dice-based game implemented in Python. The game allows for 2 to 4 players to compete by taking turns rolling a die to accumulate points. Players can choose how many times they want to roll in each turn but must be careful—rolling a 1 will reset the score for that turn!

## Rules

1. **Players**: The game supports 2 to 4 players.
2. **Turn Structure**:
   - At the beginning of each turn, the player decides how many dice rolls they want to make.
   - Players take turns rolling a virtual die. The possible results are numbers between 1 and 6.
   - If a player rolls a number between 2 and 6, the value is added to their current turn's score.
   - If a player rolls a 1, their current turn's score is reset to 0, and their turn ends.
   - Players can also choose to quit rolling at any time and keep the score they’ve accumulated so far.
3. **Winning**: After all players have taken their turn, the player with the highest total score wins.

## How to Run

1. **Prerequisites**: Ensure you have Python installed (version 3.x or higher).
2. **Running the Game**: Run the script using Python. You can use the command below:
   ```bash
   python <script_name>.py
   ```
3. **Game Interaction**: 
   - The game will prompt you for the number of players (between 2 and 4).
   - On each player's turn, input how many dice rolls you want to make.
   - Choose whether to roll (`r`) or quit the turn (`q`) after each roll.
   
## Example

- Input the number of players (e.g., 3).
- For each player's turn, specify how many times they want to roll.
- After each roll, decide whether to continue rolling or stop.
- The player with the highest score at the end of all turns wins!

## Features

- **Random Dice Rolls**: The game simulates rolling a die using Python's `random` module.
- **Turn-Based Gameplay**: Each player takes a turn, accumulating their score.
- **Interactive**: Players can decide how many rolls they want to attempt and whether to stop rolling during their turn.
  
## Improvements

- The game could be extended by adding more customization options, such as score limits or more complex scoring rules.
- It could also be modified to save the highest score and implement more rounds.

Enjoy the game!
