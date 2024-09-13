# Unbeatable Tic-Tac-Toe in C++

This is a console-based Tic-Tac-Toe game developed in C++ where a player competes against an AI that always plays the best possible move. The AI is designed to be unbeatable, meaning it either wins or forces a draw, making it a challenging opponent for the player.

## Features
- **Unbeatable AI**: The AI uses strategic algorithms to block player moves and prioritize winning, ensuring the player can never win.
- **Offensive and Defensive Strategies**: The AI checks for opportunities to win but also defends against the player’s possible winning moves.
- **User Interaction**: The game is controlled via simple numerical input from the player.
- **Game State Visualization**: The current state of the board is printed to the console, giving players a clear view of each move.

## How it Works
- The board is represented as a 3x3 grid.
- Players take turns to place their marker ('O' for Player, 'X' for AI) by selecting a number corresponding to an empty position.
- The AI algorithm checks for winning combinations or blocks the player's winning moves and plays accordingly.
- The game ends with either a win, draw, or loss.

## Running the Project
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/Manish-exe/unbeatable-tictactoe.git
2. Compile the code using a C++ compiler
   ```bash
   g++ unbeatable_tictactoe.cpp -o tictactoe
3. Run the executable
   ```bash
   ./tictactoe
## Program Flow
![image](https://github.com/user-attachments/assets/e1abd362-a187-4d9e-a5ce-32adc5e603f0)

