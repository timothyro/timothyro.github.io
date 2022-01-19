---
layout: project
type: project
image: images/vacay-square.png
title: Sudoku Solver
permalink: projects/sudoku
# All dates must be YYYY-MM-DD format!
date: 2021-04-12
labels:
  - Java
  - Eclipse
summary: Solves a given sudoku problem through brute force much faster than any human could.
---

<img class="ui medium right floated rounded image" src="../images/vacay-home-page.png">

In ICS 211 we learned about Java and using the Eclipse IDE. We had an assignment later in the semester to make a sudoku solver that seemed like it would be easy in theory, but implementing it was harder than I originally thought. The program took a 2D array (for rows and columns) of either blank spaces or numbers to build a board to print in the console output. Next it would solve the sudoku problem and print the finished solution in a sudoku format in the console output. 

When I first started ICS 211, I had no idea how recursion worked, but this project really helped me get a better idea of how recursion could be used on a larger scale than just finding a number to a power or some simple example problem. Through recursion, the program would continuously fill in values in each spot of the sudoku and test to see if it was a legal move. If it was, then the value would be kept and the next space would be attempted. If it was not a legal move, the program would go back a step and change the previous number to see if that would still be legal. For a human this would take much longer than just solving the problem normally, but for a computer this way is the fastest since it can complete many calculations in just a single second. 
