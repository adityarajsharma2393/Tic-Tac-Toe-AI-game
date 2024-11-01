Tic-Tac-Toe AI Game 🎮

##Project Overview

This project is a classic Tic-Tac-Toe game with an AI that plays optimally, making it a formidable opponent. The AI uses the Minimax algorithm to evaluate all possible moves, choosing the best one every time. The player can click on an empty cell to make their move, and the AI will respond with its own, leading to an intense (and often humbling) back-and-forth.

##Libraries Used

*Pygame: Essential for creating the game window, drawing the grid, handling user input, and managing the game loop.
*Sys: Used to handle a safe exit from the game.
*Math: Provides constants like infinity, which is useful for comparing maximum and minimum scores in the Minimax algorithm.

##Functions Implemented

*draw_board()
Draws the 3x3 grid and places the "X" and "O" symbols based on player and AI moves. This function provides a visual representation of the board.

*check_winner()
Checks all rows, columns, and diagonals to determine if there’s a winner. It’s like a referee that instantly spots three in a row.

*is_draw()
Checks if the board is full without a winner, resulting in a draw. This function stops the game from going on forever and declaring a winner when nobody’s winning.

*minimax()
The brains behind the AI’s strategy. The Minimax algorithm calculates the best possible move by simulating all potential moves and assigning scores based on outcomes. The AI then picks the move with the highest score, making it very tough to beat. Every time I tried, I found myself up against an AI that just wouldn’t lose!

*find_best_move()
Identifies the optimal move for the AI by using the Minimax function. This function ensures that the AI always chooses its move strategically, without a hint of randomness.


