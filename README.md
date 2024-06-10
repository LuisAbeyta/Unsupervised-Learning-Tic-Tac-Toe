## Project Description##

This program consist of one python file to create agents that are able to learn and play tic-tac-toe against another agent and users. One of the classes created is a tic-tac-toe class that keep track of the current board state, available moves, and is able to declare a winner.
The second class is the player class that keep track of moves made in current game, store best moves made in the past, and choose a move for the current board. The moves chosen are based on store values that are created using a Q learning algortihm that updates the values after
a reward is received for a win, loss, or draw. The rest of the program trains the multiple agents on a 3x3 board and a 4x4 board, once training is completed a user can play agianst the trained agents.
