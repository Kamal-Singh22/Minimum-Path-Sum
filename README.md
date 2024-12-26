# Minimum-Path-Sum
Given a  𝑚 × 𝑛 m×n grid filled with non-negative numbers, find a path from the top-left corner to the bottom-right corner, which minimizes the sum of all numbers along its path.

Input Example:
Enter the number of rows (m): 
3
Enter the number of columns (n): 
3
Enter the grid values row by row:
1 3 1
1 5 1
4 2 1

Output Example:
The minimum path sum is: 7


How it Works
Dynamic Programming Approach:

Use a 2D array dp to store the minimum path sums.
Start from the top-left corner and iterate through the grid.
For each cell (i, j), the value of dp[i][j] is the minimum of the path sum from the top or left neighbor plus the current cell value.

