# Tic-tac-toe
1.This is a simple implementation of the Tic-Tac-Toe game in Python. The game is played on a 3x3 grid, where two players take turns to mark a square with their respective symbol ('X' or 'O'). 
The player who first places three of their symbols in a horizontal, vertical, or diagonal row wins the game.

# Features
1.User Input Validation: Ensures that the input is a digit between 1 and 9 and that the chosen position on the board is empty.
2.Game Board Display: Shows the current state of the game board after every move.
3.Win Checking: Checks for a win condition after every move.
4.Player Switching: Alternates turns between Player 'X' and Player 'O'.

# How to Run
1.Copy the Code: Copy the code to a Python (.py) file, for example, tic_tac_toe.py.
2.Run the Script: Execute the script using Python.
python tic_tac_toe.py

# Code Overview
1.Initialization: The game board is initialized as a 3x3 list with empty strings.
2.Display Function: display_current() prints the current state of the game board.
3.User Input: user_choice() prompts the user to input a number between 1 and 9.
4.Board Update: update_board(choice, player) updates the board with the player's move.
5.Win Check: check_win(player) checks if the current player has won the game.
6.Main Loop: main() contains the game loop, alternating between players and checking for a win after each move.

# Example Game Play
1.The game starts with Player 'X'.
2.Players take turns to enter a number between 1 and 9 to place their symbol on the board.
3.The game ends when one player gets three in a row or all positions are filled.
