Tic Tac Toe Game
A simple implementation of the classic Tic Tac Toe game in Python.
Game Description
This game allows two players, X and O, to take turns marking a square on a 3x3 grid. The first player to get three in a row (horizontally, vertically, or diagonally) wins the game. If all squares are filled and no player has won, the game is a tie.
Features
Simple and intuitive gameplay
Input validation to prevent invalid moves
Automatic detection of winner or tie
Installation and Usage
Clone the repository: git clone https://github.com/your-username/tic-tac-toe.git
Navigate to the repository: cd tic-tac-toe
Run the game: python main.py
Gameplay
The game will display the current state of the board.
The current player will be prompted to enter their move (1-9).
The game will update the board and check for a winner or tie.
Players will alternate turns until the game is won or tied.
Code Structure
The code is organized into three main functions:
print_board(board): prints the current state of the board
check_winner(board): checks if there's a winner or tie
main(): the main game loop
Contributing
Feel free to fork the repository and submit pull requests with improvements or bug fixes.
License
This code is released under the MIT License. See LICENSE for details.
Example Use Case
Code
$ python main.py
  1 | 2 | 3 
---+---+---
 4 | 5 | 6 
---+---+---
 7 | 8 | 9 
Player X, enter your move (1-9): 5
  1 | 2 | 3 
---+---+---
 4 | X | 6 
---+---+---
 7 | 8 | 9 
Player O, enter your move (1-9): 2
  1 | O | 3 
---+---+---
 4 | X | 6 
---+---+---
 7 | 8 | 9 
...
