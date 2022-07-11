# TIC-TAC-TOE
Multi-Player Game.
The following is a simple implementation of the game.
These are the various functions defined:
1) display_board(board):
This function prints out a board.The board is passed as a list, where each index corresponds to a position on the board.It returns a 3 x 3 board representation.
2) player_input():
This function takes in player input anfd assign their markers as 'X' or 'O'
3) place_marker():
This function takes in a board list object, a marker('X' or 'O') and a desired position(1-9) and assigns it to the board.
4) win_check(board,mark):
This function takes in a b oard and a mark(X or O) and then checks to see if that mark has won.
5) choose_first():
This function uses the random module to randomly decide which player goes first.
6) space_check(board,position):
This fumction returns a boolean indicating whether a space on the board is freely available.
7) full_board_check(board):
This function checks if the board is full and returns a boolean value.
8) player_choice(board):
This function asks for a players next position and then checks if its a free position and stores it for later use.
9) replay():
This function asks if the player wants to play again.
