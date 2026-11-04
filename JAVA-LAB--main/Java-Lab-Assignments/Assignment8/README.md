# Assignment 8: Matrices: Transpose and Row Sums

## 1. Experiment Title
Matrices: Transpose and Row Sums in Java.

## 2. Aim
To create two-dimensional arrays, print matrices, transpose them and calculate row sums.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Two-dimensional arrays represent tables or matrices in Java:

### 1. Two-Dimensional Array:
A 2D array is an array of arrays organized into rows and columns.
- Syntax: int[][] matrix = new int[rows][cols];
- Element access: matrix[row][col] where row is the row index and col is the column index.

### 2. Matrix Transpose:
The transpose of a matrix exchanges its rows and columns. For any element at row i and column j:
	ranspose[j][i] = matrix[i][j]

### 3. Row Sums:
The sum of each row is obtained by iterating over each row index i and summing matrix[i][j] for all column indices j.

## 5. Algorithm / Procedure

### Question 1: Create and Print 3 by 4 Matrix
1. Start the program.
2. Declare a 2D integer array m of size 3x4 and variable val = 1.
3. Use nested loops to fill m[i][j] with sequential integers 1 to 12.
4. Use nested loops to print each element with spaces and a newline after each row.
5. Stop the program.

### Question 2: Transpose of a 3x3 Matrix
1. Start the program.
2. Initialize a 3x3 integer matrix with values 1 to 9.
3. Create a 3x3 array transpose.
4. Using nested loops, assign transpose[j][i] = matrix[i][j].
5. Print the transposed matrix in row-major order.
6. Stop the program.

### Question 3: Calculate Sum of Each Row
1. Start the program.
2. Initialize a 3x3 integer matrix.
3. Loop through each row i from 0 to matrix.length - 1.
4. Initialize rowSum = 0; sum matrix[i][j] across all columns j.
5. Print the row number and its sum.
6. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- Matrix size: 3 rows, 4 columns (values 1 to 12)

### Question 2:
- Matrix:
  `
  1 2 3
  4 5 6
  7 8 9
  `

### Question 3:
- Matrix:
  `
  1 2 3
  4 5 6
  7 8 9
  `

## 7. Output

### Question 1:
```
1 2 3 4 
5 6 7 8 
9 10 11 12 
```

### Question 2:
```
1 4 7 
2 5 8 
3 6 9 
```

### Question 3:
```
Row 1 sum: 6
Row 2 sum: 15
Row 3 sum: 24
```

Result: All three Java programs were successfully written and executed to demonstrate 2D array declaration, matrix printing, transpose calculation, and row summation.