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

`cd sudoku-solver`
#### 2. Build the C++ Solver
Compile the C++ solver:
`g++ -o sudoku_solver sudoku_solver.cpp`

This command creates an executable file named sudoku_solver (or sudoku_solver.exe on Windows) in the project directory.
#### 3. Install Node.js Dependencies
Navigate to the directory and install dependencies:
`cd Sudoku_solver`

`npm install express`
#### 4. Start the Node.js Server
Start the server:
`node server.js`

The server will be available at http://localhost:3000.
### Usage
  *  Open the Web Interface: Visit http://localhost:3000 in your web browser.
  * Input a Sudoku Puzzle: Fill in the Sudoku grid. Each cell accepts numbers from 1 to 9.
  * Solve the Puzzle: Click the Solve button to solve the puzzle. The solution will be displayed in the grid.
  * Reset the Grid: Click the Reset button to clear the grid.
## Demo and Screenshots
### First look:-

![image](https://github.com/user-attachments/assets/e47f3bf4-77ed-45c9-ba79-0a2bcfeb2db6)
### Aftering entering input:-

![image](https://github.com/user-attachments/assets/512c5c6a-c57b-4009-8c14-e6711925e49c)
### After clicking Solve:-

![image](https://github.com/user-attachments/assets/9f3a25aa-83ef-4121-81fb-f78c261f3a59)
### if the input is not valid or break Sudoku rules:-

![image](https://github.com/user-attachments/assets/9d00b07f-8061-4353-ab7a-25e967e1687d)
## Troubleshooting
  *No Solution Exists: Ensure that the input grid is valid and follows Sudoku rules.
  *Errors: Check server logs and make sure the C++ executable is correctly built and in the same directory as server.js.
## Contributing
Feel free to open issues or submit pull requests if you find any bugs or have improvements in mind!

## License
This project is licensed under the MIT License - see the LICENSE file for details.
