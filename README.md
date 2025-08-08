# Sudoku-Solver

🧠 How It Works
Backtracking is used to explore all possible placements of numbers (1–9) in the Sudoku grid.

The algorithm checks if placing a number in an empty cell is safe (i.e., doesn't break the Sudoku rules).

If it’s safe, the number is placed, and the algorithm proceeds to solve the next empty cell.

If no valid number is found, it backtracks and tries a different number in the previous cell.


✅ Sudoku Rules Checked
Each row must contain the numbers 1–9, without repetition.

Each column must contain the numbers 1–9, without repetition.

Each 3x3 sub-grid must contain the numbers 1–9, without repetition.


📦 Features
Takes a hardcoded 9x9 board with empty cells represented by 0.

Solves the puzzle and prints the completed board to the console.

If no solution exists, it prints Cannot solve.


📄 File: SudokuSolver.java
Main Components
main(String[] args) – Initializes the board and calls the solver.

solve(int[][] board) – Recursively solves the Sudoku using backtracking.

isSafe(...) – Checks if placing a number in a specific cell is valid.

display(...) – Prints the solved Sudoku board.


▶️ How to Run
Make sure you have Java 8+ installed.

Save the code in a file named SudokuSolver.java under com/file_name/backtracking/.

Compile and run:
