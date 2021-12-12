# quantum_tiq_taq_toe
## Introduction
Quantum Tic Tac Toe is a unique spin on the classic tic tac toe game. It differs from the classic version of
the game courtesy of the superposition rule which is essentially the crux of the game. Rather than having
a discrete position for a particular X or O, each of the two can be in two different squares simultaneously
until the outcome of the game is measured; at which point the superposition collapses and one of the two
chosen squares hosts the symbol. Each state in the game can either be an entangled state or a non-entangled
one.

## The rules of the game
The rules for this version of the game are mostly the same as the classical version of the game except for one major difference which is with
regards to the way a move can be made on the game board.
1. This is a two player game in which each player takes turns to place their symbol (either an X or an O) on either one square (classical) or a combination of any two squares (superposition) on a 3 by 3 game board.
2. Each square of the game board can still only house a single symbol. In the case that the move made was classical, the symbol stays there till the end of the game. However, if the move made was a superposition move then one of the indexes chosen to host the symbol would result in being blank after the measurements have been taken.
3. As in the classical version, in order to win, a player is supposed to achieve a sequence of 3 symbols in a row, either vertically, horizontally or diagonally

## How to play?
1. Run the Jupyter Notebook file in the repository.
2. When the libraries have been imported and the last cell begins to execute, player 1 will be prompted to input his/her choice of move and then (depending upon their choice of move) they will be prompted to enter their choice of index/indices.
3. Once player 1 has made their move, it will be player 2's turn and the process will repeat.
4. Once a sequence is made, or a stalemate is achieved, the game will end.

## Note
**For more clarification on the concept and the rules, please refer to the pdf provided**
