# calculate-diagonal-difference

The "Diagonal Difference" code challenge asks you to calculate the absolute difference between the sums of the diagonals of a square matrix. Here’s a summary of the problem:

## Problem Description:

Given a square matrix n x n:

1. Compute the sum of the primary diagonal (left-to-right).
2. Compute the sum of the secondary diagonal (right-to-left).
3. Return the absolute difference between the two sums.

## Input Format:

1. The first line contains a single integer, n, the size of the square matrix.
2. The next n lines each contain n space-separated integers, representing rows of the matrix.

## Output Format:

Return a single integer, the absolute difference between the sums of the diagonals.

## Constraints:

1. The matrix will always be square.
2. The matrix size (n) and elements are within reasonable limits to compute sums directly.

## Example:

- Input:

```
3
11 2 4
4 5 6
10 8 -12

```
- Output:
```
15
```
