## Tic Tac Toe Solver

A JavaScript Tic Tac Toe bot that computes the result of the Tic Tac Toe board assuming optimal play from both sides, and recommends the best move to play. Comes with an HTML board displaying the board, score, and best move.
<br>
<br>
Uses an alpha-beta negamax search with move ordering (guided by a transposition table) to reduce the tree size and branching factor. At root, the entire search runs <2ms.
<br>
For performance, the board is compactly represented in two 9-bit integer bitboards, where fast bitwise operations can make/undo moves and detect wins/draws extremely quickly.
<br>
The main goal is to solve as fast as possible without using any external information or databases.
