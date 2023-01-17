# Sudoku Solver

Are you tired of struggling to pass some of the evil rounds in daily sudoku challenges? Do you find that learning from your own mistakes is not enough? Look no further, the sudoku_solver is here to assist you!

This solver uses a recursive backtracking algorithm to repeatedly try different numbers in empty spots to find the correct solution for the puzzle. The `find_empty` function helps the solver locate empty spots and the `is_valid` function checks if the number being placed in a spot is allowed. It may take some time to solve the puzzle, but the solver will find the correct answer.

To use the solver, input a 2D list of integers representing the sudoku puzzle. Empty cells should be represented by the integer 0 and filled cells should contain integers from 1 to 9. See the example below for a 9x9 sudoku board:


```
board = [
[7, 8, 0, 4, 0, 0, 1, 2, 0],
[6, 0, 0, 0, 7, 5, 0, 0, 9],
[0, 0, 0, 6, 0, 1, 0, 7, 8],
[0, 0, 7, 0, 4, 0, 2, 6, 0],
[0, 0, 1, 0, 5, 0, 9, 3, 0],
[9, 0, 4, 0, 6, 0, 0, 0, 5],
[0, 7, 0, 3, 0, 0, 0, 1, 2],
[1, 2, 0, 0, 0, 7, 4, 0, 0],
[0, 4, 9, 2, 0, 6, 0, 0, 7]
]
```
