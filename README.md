# TIC_TAC_TOE_GAME

This is a Tic-Tac-Toe game implemented using Python. The game is played on a 3x3 grid by two players who take turns marking the spaces on the board. One player marks with "X", and the other marks with "O". The objective is to be the first player to place three of their marks in a row, either horizontally, vertically, or diagonally.

# Libraries and Functions Used:

1. Standard Input/Output Functions:
The game uses input() for taking user input (row and column selection) and print() to display messages and the game board.

2. Custom Functions:
print_board(board): This function prints the current state of the game board. It formats the board as a 3x3 grid, separating rows and columns with vertical bars (|) and using dashes (-) as row dividers.

Input: The 2D list board representing the Tic-Tac-Toe board.

Output: Displays the board in a formatted structure.

check_winner(board): This function checks whether there is a winner. It examines each row, column, and diagonal to determine if any player has three matching marks in a row.

Input: The 2D list board.

Output: Returns a tuple with two values: a boolean indicating whether there is a winner (True or False), and the winner's mark ('X' or 'O').

is_board_full(board): This function checks if the board is full, meaning all cells are occupied.

Input: The 2D list board.

Output: Returns True if the board is full, and False otherwise.

main(): This is the main function that controls the game flow. It initializes the board, manages player turns, handles input validation, and checks for a winner or a tie after each move.

This function continues running in a loop until either a player wins or the game ends in a tie.
