Sudoku Pair Generator

A general k × k Sudoku pair generator that works by encoding a simple program to translate given k to partially solved Sudoku puzzle pair and finally into CNF formulas such that the 
CNF is satisfiable iff the puzzle has a solution and a pair of sudoku can be generated. The project is written in pySAT.
It guarantees that there is always a single unique solution for the puzzles it generates.

Features:-
1.Work for all values of k(k<=4)
2.Code is easy to read and understand
3.Reads k as given input and generate two separate unsolved sudokus 

Following shows the example of how to use this program:
1.Give input in form of k.
2.In read_csv file change name to input file
3.Run the program by writing py <name>.py

It may take some time to give output so one need to wait for a while for large value of k.