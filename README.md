# Prog1_Opt
Programming assignment 01 of Optimization
The library I use is "Rglpk" regarding that lp() function in library "lpSolve" has a default condition that variables are non-negative.
There is a flaw in Exercise 2_2:
When the objective function is x2, the optimal solution of variable x1 should be an interval, but the solver just give a specific number.
