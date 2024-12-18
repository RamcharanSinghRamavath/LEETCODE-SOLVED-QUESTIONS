# Spiral Matrix Problem Repository

This repository contains the solution to the problem **54. Spiral Matrix** commonly asked in coding interviews.

## Problem Description
Given an m x n matrix, return all elements of the matrix in **spiral order**.

---

## Folder Structure
- **questions/**: Contains the problem description and constraints.
- **src/**: Contains the C++ implementation of the solution.

---

## How to Use?
1. Navigate to the `src` directory.
2. Compile the C++ code using your preferred compiler.
3. Test the solution with input matrices.

---

## Solution
The solution implements a systematic traversal through the matrix in four possible directions:
1. Left-to-right across the topmost row.
2. Top-to-bottom along the rightmost column.
3. Right-to-left across the bottommost row.
4. Bottom-to-top along the leftmost column.

These directions are repeated until all elements are visited.
## code-
## Usage

vector<vector<int>> matrix = {
    {1, 2, 3},
    {4, 5, 6},
    {7, 8, 9}
};

Solution solution;
vector<int> result = solution.spiralOrder(matrix);

// Output the results
for (int val : result) {
    cout << val << " ";
}


---

## Author
Link- [https://leetcode.com/problems/spiral-matrix/]
