## Question 1: Digital Clock Simulation

Write a program that simulates a digital clock counting seconds, starting from 00:00:00 (HH: MM) up to a user-defined time limit in seconds. Use nested for loops for hours, minutes, and seconds up to the specified limit.

Input:
An integer seconds_limit representing how long the clock should run.

Output:
Print each second in HH:MM format, simulating the passage of time.

For seconds_limit = 5, the output should be:
00:00:00
00:00:01
00:00:02
00:00:03
00:00:04
00:00:05

<br>

## Question 2: Pascal's Triangle

Write a program that prints Pascal's Triangle up to a given number of rows, n. Pascal's Triangle is a triangle of numbers where each row represents the coefficients of the binomial expansion.

Each number in a row is the sum of the two numbers directly above it. Use nested for loops to generate each row based on the previous row.

For n = 5:
       1
      1 1
     1 2 1
    1 3 3 1
   1 4 6 4 1

<br>

## Question 3: Number Spiral Matrix

Write a program that generates a square matrix of numbers in a spiral pattern. The matrix should be filled with consecutive integers starting from 1, spiraling inwards in a clockwise direction from the top-left corner.

For n = 4:
1   2   3   4
12  13  14   5
11  16  15   6
10   9   8   7

Hints:

Use a 2D list to keep track of the grid.
Use four directions (right, down, left, up) in a repeating sequence, changing direction when you hit the edge of the grid or an already-filled cell.
Update the current position based on the direction.

<br>

## Question 4: Checkerboard Pattern

Write a program that prints an n x n checkerboard pattern with alternating X and O characters. Use nested for loops and conditionals to alternate between X and O based on the row and column indices.

Input:
An integer n (size of the board).

Output:
A checkerboard pattern of size n, alternating between X and O in a grid.

For n = 5, the output should be:
X O X O X
O X O X O
X O X O X
O X O X O
X O X O X

<br>

## Question 5: Conway's Game of Life

Simulate the next generation of Conway's Game of Life, a cellular automaton with the following rules:

Any live cell with 2 or 3 live neighbors survives.
Any dead cell with exactly 3 live neighbors becomes a live cell.
All other cells die or remain dead.

Write a program to print the board state after one generation. Use nested for loops to iterate over the grid and calculate the number of neighbors for each cell.

Input:
An integer n (size of the grid).
A n x n grid of 0s and 1s, where 1 represents a live cell and 0 a dead cell.

Output:
Print the grid state after applying the rules of the game for one generation.

For n = 4 and initial grid:
0 1 0 0
0 0 1 0
1 1 1 0
0 0 0 0

The output after one generation should be:
0 0 0 0
1 0 1 0
0 1 1 0
0 1 0 0



