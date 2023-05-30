# Sudoku-Game-in-C++
Sudoku-Game-C++
Sudoku Game
This is a simple Sudoku game implemented in C++. It allows you to play Sudoku by providing a partially filled grid, and it uses backtracking to solve the puzzle.

How to Play
Open the terminal or command prompt. Compile the code using a C++ compiler:

g++ sudoku.cpp -o sudoku Run the executable:

./sudoku** The Sudoku grid will be displayed, with empty cells represented by 0. Enter the numbers to fill the empty cells, row by row. Press Enter after each number. Once you've filled all the cells, the program will attempt to solve the Sudoku puzzle. If a solution is found, it will be displayed. If not, a message will indicate that the puzzle is unsolvable.

Customizing the Puzzle
You can customize the initial Sudoku puzzle by modifying the grid variable in the main() function of the code. The grid is represented as a 2D vector, where 0 represents an empty cell, and other numbers represent filled cells.

std::vector<std::vector<int>> grid = {
 {5, 3, 0, 0, 7, 0, 0, 0, 0},
 {6, 0, 0, 1, 9, 5, 0, 0, 0},
 {0, 9, 8, 0, 0, 0, 0, 6, 0},
 {8, 0, 0, 0, 6, 0, 0, 0, 3},
 {4, 0, 0, 8, 0, 3, 0, 0, 1},
 {7, 0, 0, 0, 2, 0, 0, 0, 6},
 {0, 6, 0, 0, 0, 0, 2, 8, 0},
 {0, 0, 0, 4, 1, 9, 0, 0, 5},
 {0, 0, 0, 0, 8, 0, 0, 7, 9}
};

License
This project is licensed under the MIT License.
