#  Maman 13 - 8 Queens Puzzle Solver

Explanation about the project – Solving the 8 Queens Problem
This project solves the 8 Queens problem on a chessboard of size 8x8.
The goal is to place 8 queens on the board so that no queen threatens another queen, meaning no two queens are in the same row, column, or diagonal.

The project uses Object-Oriented Programming (OOD) and a Graphical User Interface (GUI) to display the board, place the queens, and highlight the possible solutions.

For the project to access the relevant files for building the queens and the board, you need to save the Maman 13 folder into the following path:
C:\Maman13

How to run the project:
Open a Workspace window.
Create an instance of the solver and start the game.
In the Workspace window, paste the following code:

| queenSolver |
queenSolver := QueenSolver new.
queenSolver start.

How to stop the program:
Use the keyboard shortcut: Alt + . (Alt and the period key)

Blocking squares:
To block a specific square on the board, preventing a queen from entering it, right-click on the square.
The square will be marked in red, indicating that it is blocked.
Clicking the square again will remove the block.

