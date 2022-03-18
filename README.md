# sudoku-solver
Sudoku solver by backtracking algorithm

![image](https://user-images.githubusercontent.com/79546898/159029065-eef29960-ff89-48a6-bcdc-9e2ab9dc6abb.png)


As definied by Wikipedia in https://en.wikipedia.org/wiki/Sudoku_solving_algorithms

"A brute force algorithm visits the empty cells in some order, filling in digits sequentially, or backtracking when the number is found to be not valid. Briefly, a program would solve a puzzle by placing the digit "1" in the first cell and checking if it is allowed to be there. If there are no violations (checking row, column, and box constraints) then the algorithm advances to the next cell and places a "1" in that cell. When checking for violations, if it is discovered that the "1" is not allowed, the value is advanced to "2". If a cell is discovered where none of the 9 digits is allowed, then the algorithm leaves that cell blank and moves back to the previous cell. The value in that cell is then incremented by one. This is repeated until the allowed value in the last (81st) cell is discovered."

I coded the forementioned method and a generator of the possible solutions to each square for a given puzzle.
