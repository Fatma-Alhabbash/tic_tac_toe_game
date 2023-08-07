# Tic Tac Toe Game
## Here is a fully functional project written in Python that shows how to create Tic Tac Toe Game

What is the game? 

Tic-Tac-Toe is a classic two-player game played on a grid, traditionally a 3x3 grid. The goal of the game is to be the first player to form a horizontal, vertical, or diagonal line of three of their symbols (usually "X" or "O") on the grid.

The functions used in this project are explained below:
1. ```create_empty_board()``` function:
   This function creates a 3×3 empty board. 
2. ```show_board(board)``` function:
   This function displays the board by taking the parameter board which is an array of the values in the board.
3. ```set_players()``` function:
   This function set players randomly (X, O)
4. ```take_input(board, player, player_input)``` function:
   This function takes 3 parameters:
   - board: This is an array of the values in the board.
   - player: Set the player (X or O).
   - player_input: Represents the position the player wants to draw (X or O).
   After it takes these three parameters it returns the updated board.
5. ```check_full_board(board)``` function:
   This takes the board as a parameter and then checks if the board is full (there is no position where the player can draw (X or O) or not.
6. ```check_win(board)``` function:
   Using the board as a parameter, this function checks if any player wins if three of his or her symbols are lined up in a horizontal, vertical, or diagonal pattern.
7. ```play()``` function:
   This is the main function that will call all the needed functions to start the game.

*Thanks for taking the time to review this project. I hope you found it useful.*


   
