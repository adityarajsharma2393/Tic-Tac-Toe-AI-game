Tic-Tac-Toe AI Game 🎮

A Python-based Tic-Tac-Toe game where you play against an AI opponent powered by the Minimax algorithm. Using Python and Pygame, this game challenges you to beat an AI that’s designed to be practically unbeatable. Spoiler alert: after a few rounds, I realized I had about as much chance beating this AI as a paperclip has of winning a popularity contest!

##Project Overview

This project is a classic Tic-Tac-Toe game with an AI that plays optimally, making it a formidable opponent. The AI uses the Minimax algorithm to evaluate all possible moves, choosing the best one every time. The player can click on an empty cell to make their move, and the AI will respond with its own, leading to an intense (and often humbling) back-and-forth.

##Libraries Used

*Pygame: Essential for creating the game window, drawing the grid, handling user input, and managing the game loop.
*Sys: Used to handle a safe exit from the game.
*Math: Provides constants like infinity, which is useful for comparing maximum and minimum scores in the Minimax algorithm.

##Functions Implemented

*draw_board()
Draws the 3x3 grid and places the "X" and "O" symbols based on player and AI moves. This function provides a visual representation of the board, so you don’t have to play Tic-Tac-Toe blind!

*check_winner()
Checks all rows, columns, and diagonals to determine if there’s a winner. It’s like a referee that instantly spots three in a row.

*is_draw()
Checks if the board is full without a winner, resulting in a draw. This function stops the game from going on forever and declaring a winner when nobody’s winning.

*minimax()
The brains behind the AI’s strategy. The Minimax algorithm calculates the best possible move by simulating all potential moves and assigning scores based on outcomes. The AI then picks the move with the highest score, making it very tough to beat. Every time I tried, I found myself up against an AI that just wouldn’t lose!

*find_best_move()
Identifies the optimal move for the AI by using the Minimax function. This function ensures that the AI always chooses its move strategically, without a hint of randomness.

*main game loop
Controls the game’s flow, alternating between player and AI moves. It checks for win or draw conditions after each move, ensuring that the game progresses smoothly and ends when someone wins or the board is full.

##How to Play

Run the game using: python3 tic_tac_toe_ai.py

The game window will open with a 3x3 Tic-Tac-Toe grid.

Click on any empty cell to place your "X" on the board.

The AI will respond with an "O" in an optimal location.

The game ends when either the player or AI wins (three in a row), or the game results in a draw if the grid is filled without a winner.
