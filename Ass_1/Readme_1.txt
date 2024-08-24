Sudoku Pair Solver
A general k × k Sudoku pair solver that works by encoding a simple program to translate partially solved Sudoku puzzle pair into CNF formulas such that the 
CNF is satisfiable iff the puzzle has a solution. The project is written in pySAT.

Features:-
1.Work for all values of k
2.Code is easy to read and understand
3.Reads a csv file as input 

Following shows the example of how to use this program:
1.Give input in form of k and a csv file containing two partially filled sudoku of k x k size.
2.In read_csv file change name to input file
3.Run the program by writing py <name>.py

It may take some time to give output so one need to wait for a while for large value of k.
