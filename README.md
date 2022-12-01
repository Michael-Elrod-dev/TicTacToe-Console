# TicTacToe-Console

This program creates a game of Tic-Tac-Toe without a graphical user interface and prints to the console. The players get the choose how many players there are, the number of connections you need to win, the size of the board, the tokens each player uses, and which data structure the game is implemented with.

The two implementations for the program are a speed efficient and a memory effiecent implementation.

The speed efficient implementation uses an array to store the entire game board. Boards of large sizes may produce issues related to memory managment.

The memory efficient implementation uses a hash map to store all the values of the game board, but will run a bit slower.

# Run

The following commands can be used with the given makfile to run this program:

**make:** Compiles all files execpt the files marked Test

**make** run: Runs the program

**make test:** Compiles all files including the files marked Test

**make testGB:** Runs TestGameBoard which includes a multitude of test cases for the programs array implementation (GameBoard)

**make testGBmem:** Runs TestGameBoardMem which includes a multitude of test cases for the programs hash map implementation (GameBoardMem)

**make clean:** Removes all .class files

**This code was written for educational purposes and should not be used for efficiency**
