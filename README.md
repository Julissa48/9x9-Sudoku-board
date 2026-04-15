Sudoku Puzzle Generator
Julissa Rodriguez
This project consisted of me generating a solved Sudoku board. The program builds a 9×9 Sudoku by creating a random 3×3 matrix with numbers 1–9. Then it processes by copying the previous board and using methods that shift the rows, columns, and elements. The result is a Sudoku board where each row contains the numbers 1 through 9 exactly once and each column contains the numbers 1 through 9 exactly once.
You can run the program by compiling javac SudokuBoard.java and then running the program java SudokuBoard to see the Sudoku on the terminal.
The program starts by creating a 3×3 matrix filled with random numbers 1–9 with no repeats. It then copies the previous matrix and performs 3 transformations that include moving the first row to the bottom, shifting columns, and moving elements in a circular pattern, creating a full set of 9 unique 3×3 blocks. Then it prints all the matrices as a full Sudoku board.
SudokuBoard.java
README.md
DesignDocument.pdf