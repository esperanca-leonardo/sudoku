# 🧩 Sudoku Solver
Sudoku Solver is a Java-based console application that efficiently solves Sudoku puzzles using a backtracking algorithm. It provides a simple and effective way to solve any standard 9x9 Sudoku board, ensuring all Sudoku rules are followed.

## 📑 Table of Contents

- [Key Features]
- [Demonstration Video]
- [How It Works]
- [Tools and Technologies Used]
- [Prerequisites]
- [Installation Instructions]
    - [Clone this repository]
    - [Navigate to the project directory]
    - [Compile the project]
    - [Run the application]
- [Observations]
- [License]

## 🚀 Key Features
- **Efficient Solving:** Utilizes a backtracking algorithm to solve Sudoku puzzles quickly and accurately.
- **Console-Based Interface:** Simple and straightforward console output for easy use without the need for a graphical interface.
- **Easy to Use:** Minimal setup required—just compile and run to solve any 9x9 Sudoku puzzle.
- **Customizable Puzzles:** Easily modify the Sudoku board within the code to solve different puzzles.

## 💡 How It Works
Board Initialization:
    The application initializes a 9x9 Sudoku board with predefined values. Empty cells are represented by 0.
Backtracking Algorithm:
    The solver scans the board to find empty cells.
    For each empty cell, it tries numbers from 1 to 9.
    It checks if placing a number violates Sudoku rules (no duplicates in the current row, column, or 3x3 subgrid).
    If a valid number is found, it places the number and recursively attempts to solve the rest of the board.
    If no valid number is found, it backtracks to the previous cell and tries the next number.
Solution Output:
    Once the board is successfully solved, the application prints the solved Sudoku board to the console.
    If the board is unsolvable, it notifies the user accordingly.







