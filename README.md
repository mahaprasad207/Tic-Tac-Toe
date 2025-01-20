# Tic-Tac-Toe Game

## Overview
This is a simple interactive Tic-Tac-Toe game built using HTML, CSS, and JavaScript. The game allows two players to take turns placing their marks (X or O) on a 3x3 grid and determines the winner or if the game ends in a draw.

## Features
- **Player Turns**: Alternates between Player X and Player O.
- **Winner Detection**: Automatically checks for a winner based on predefined win patterns.
- **Game Reset**: Provides options to reset the game either after a win or draw, or by starting a new game.
- **Responsive Design**: The layout adjusts to different screen sizes, providing an optimal experience on both desktops and mobile devices.

## Technologies Used
- **HTML**: Structured the game layout and interface.
- **CSS**: Styled the game grid, buttons, and interface with modern design principles (e.g., flexbox, box shadows).
- **JavaScript**: Implemented the game logic, player turns, winner check, and board reset functionality.

## How It Works
1. Players take turns clicking on the squares of the 3x3 grid.
2. The game tracks the turns and places an "X" or "O" on each clicked square.
3. The game continuously checks for a winning condition based on predefined win patterns.
4. If all squares are filled and no one wins, the game ends in a draw.
5. The game provides buttons to reset the game or start a new one once a winner is declared or the game ends in a draw.

## Game Logic
- **Player Turns**: Player O starts the game.
- **Win Patterns**: The game checks for 8 possible win patterns on the board (horizontal, vertical, and diagonal lines).
- **Draw**: If all 9 squares are filled without a winner, the game ends in a draw.
- **Reset**: Players can click the reset button to clear the board and start a new game.

## Demo
You can try the live demo of the Tic-Tac-Toe game here: https://mahaprasad207.github.io/Tic-Tac-Toe/

## Installation
1. Clone the repository:
   ```bash
   https://github.com/mahaprasad207/Tic-Tac-Toe.git

2. Open the index.html file in your browser to start the game.
## Future Improvements
AI Opponent: Implement an AI opponent for single-player mode.
Animations: Add animations for winning moves or a smoother transition between turns.
Mobile Optimization: Enhance the mobile experience by ensuring the game is fully touch-friendly.

## License
This project is licensed under the MIT License - see the **LICENSE** file for details.