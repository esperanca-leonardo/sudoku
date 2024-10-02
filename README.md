# 🧩 Sudoku Solver
Sudoku Solver is a Java-based console application that efficiently solves Sudoku puzzles using a backtracking algorithm. It provides a simple and effective way to solve any standard 9x9 Sudoku board, ensuring all Sudoku rules are followed.

## 📑 Table of Contents

- [Key Features](#-key-features)
- [Demonstration Video]
- [How It Works](#-how-it-works)
- [Tools and Technologies Used](#-tools-and-technologies-used)
- [Prerequisites](#-prerequisites)
- [Installation Instructions](#-installation-instructions)
    - [Clone this repository](#1-clone-this-repository)
    - [Navigate to the project directory](#2-navigate-to-the-project-directory)
    - [Compile the project](#3-compile-the-project)
    - [Run the application](#4-run-the-application)
- [Observations](#-observations)

## 🚀 Key Features
- **Efficient Solving:** Utilizes a backtracking algorithm to solve Sudoku puzzles quickly and accurately.
- **Console-Based Interface:** Simple and straightforward console output for easy use without the need for a graphical interface.
- **Easy to Use:** Minimal setup required—just compile and run to solve any 9x9 Sudoku puzzle.
- **Customizable Puzzles:** Easily modify the Sudoku board within the code to solve different puzzles.

## 💡 How It Works
- **Board Initialization:**
    - The application initializes a 9x9 Sudoku board with predefined values. Empty cells are represented by 0.
- **Backtracking Algorithm:**
    - The solver scans the board to find empty cells.
    - For each empty cell, it tries numbers from 1 to 9.
    - It checks if placing a number violates Sudoku rules (no duplicates in the current row, column, or 3x3 subgrid).
    - If a valid number is found, it places the number and recursively attempts to solve the rest of the board.
    - If no valid number is found, it backtracks to the previous cell and tries the next number.
- **Solution Output:**
    - Once the board is successfully solved, the application prints the solved Sudoku board to the console.
    - If the board is unsolvable, it notifies the user accordingly.

## 🔧 Tools and Technologies Used
- **Java:** A versatile and widely-used programming language, ideal for building robust applications.
- **IDE (Optional):** Integrated Development Environment for writing and debugging Java code.
- **Git:** Version control system for tracking changes and collaborating on the project.

## 📋 Prerequisites
Before running the application, ensure you have the following prerequisites installed:
- **Java Development Kit (JDK) 8 or higher:** Required to compile and run Java applications.
- **Git:** (Optional) For cloning the repository.

## 📝 Installation Instructions
### 1. Clone this repository
```bash
git clone https://github.com/esperanca-leonardo/sudoku.git
```
### 2. Navigate to the project directory
```bash
cd toolbox-backend
```

### 3. Compile the project
Ensure you have the JDK installed. Open your terminal or command prompt and run:
```bash
javac App.java
```
This command compiles the App.java file and generates the App.class bytecode file.

### 4. Run the application
After successful compilation, run the application using:
```bash
java App
```
The application will attempt to solve the predefined Sudoku puzzle and display the result in the console.

## 📌 Observations
- **Custom Puzzles:** To solve a different Sudoku puzzle, modify the board array in the App class. Replace the 0s with the known numbers of your puzzle.
- **Unsolvable Puzzles:** If the application prints "Unsolved board :(", it means the provided Sudoku puzzle does not have a valid solution.
- **Extensibility:** While currently a console application, the solver can be extended with a graphical user interface (GUI) or integrated into larger applications as needed.


















