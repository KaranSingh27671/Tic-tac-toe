Description

This is a console-based Tic Tac Toe game implemented in C++. Two players can play the game on the same computer. The game demonstrates basic C++ programming concepts such as loops, conditionals, functions, and arrays.

Features

3x3 Tic Tac Toe board displayed in the console.

Two-player mode (Player X and Player O).

Input validation to prevent invalid moves.

Detects and announces:

Win for either player

Draw if all cells are filled without a winner

Alternates turns automatically between players.

How to Run

Make sure you have a C++ compiler installed (e.g., g++, Code::Blocks, Visual Studio).

Copy the tic_tac_toe.cpp code into your project folder.

Compile the code:

g++ tic_tac_toe.cpp -o tic_tac_toe


Run the executable:

./tic_tac_toe   # Linux/Mac
tic_tac_toe.exe # Windows


Follow the prompts to enter row and column numbers (0-2) to place your move.

Code Structure

displayBoard: Displays the current state of the 3x3 board.

checkWin: Checks if the current player has won.

isDraw: Checks if the board is full and there’s no winner.

main: Controls the game loop, handles player input, and manages turns.

Skills Demonstrated

C++ basics: loops, conditionals, functions

2D arrays

Game logic and algorithms

Input validation

Console output formatting

Sample Gameplay
-------------
|   |   |   |
-------------
|   |   |   |
-------------
|   |   |   |
-------------
Player X, enter row and column (0-2): 0 0
-------------
| X |   |   |
-------------
|   |   |   |
-------------
|   |   |   |
-------------
