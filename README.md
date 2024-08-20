# Sudoku_Backtrack_Solver

Welcome to the Sudoku Backtracker Solver project! This project provides a web-based interface to solve Sudoku puzzles using a C++ backend. The web interface allows users to input a Sudoku grid, solve it, and view the results directly in the browser.

## Project Structure

- **C++ Solver**: A C++ program that solves Sudoku puzzles using a backtracking algorithm.
- **Node.js Server**: An Express.js server that interfaces with the C++ solver and provides a RESTful API.
- **Frontend**: A simple HTML/CSS/JavaScript frontend that allows users to input Sudoku puzzles and view solutions.

## Features

- **Solve Sudoku**: Submit a Sudoku puzzle to get the solution.
- **Reset Grid**: Clear the grid and start fresh.
- **Interactive UI**: A user-friendly grid with input validation and visual feedback.

## Getting Started

### Prerequisites

1. **Node.js**: Download and install Node.js (includes npm).
2. **C++ Compiler**: Ensure you have a C++ compiler installed (e.g., `g++`).

### Setup Instructions

#### 1. Clone the Repository
`git clone https://github.com/AmritanshuRaj45/sudoku_backtrack_solver.git`
*`cd sudoku-solver`*
#### 2. Build the C++ Solver
Compile the C++ solver:
g++ -o sudoku_solver sudoku_solver.cpp
This command creates an executable file named sudoku_solver (or sudoku_solver.exe on Windows) in the project directory.
#### 3. Install Node.js Dependencies
Navigate to the directory and install dependencies:
cd Sudoku_solver
npm install
#### 4. Start the Node.js Server
Start the server:
node server.js
The server will be available at http://localhost:3000.
