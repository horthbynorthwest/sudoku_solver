# Python Sudoku solver

I really wanted to start diving into some new things that python could do, so I found a tutorial that explains the Backtracking algorithm. 

Why we don't use a naive algorithm here:
* Inefficient
* Slow
* Essentially tries every number 1-9 in every square until it happens upon the right answer
* Continues with solutions even when they're already incorrect

Backtracking:
How does the backtracking algorithm work:
 1. Pick an empty square
 2. Try all numbers
 3. Find a number that works
 4. Repeat until we hit an error
 5. Backtrack:
	 - remove the number that errored
	 - Go back to the previous entered number and try something else
	 - continue until we have a solution that can possible work
 6. Continue onward once we have a solution that can work.


Thank you to [Tech with Tim](https://www.youtube.com/watch?v=eqUwSA0xI-s&list=PLzMcBGfZo4-kE3aF6Y0wNBNih7hWRAU2o&index=1&ab_channel=TechWithTim) for the tutorial

See my [Wiki](https://github.com/horthbynorthwest/sudoku_solver/wiki) for my explainations of what the code is doing!