# Assignment 7: Counting Steps and Complexity

## 1. Experiment Title
Counting Steps and Complexity in Java.

## 2. Aim
To count loop iterations and state the time complexity of each approach.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Time complexity characterizes how an algorithm's execution time scales with input size n:

### 1. Linear Time Complexity - O(n):
A single loop iterating from 1 to n executes exactly n iterations. The step count increases proportionally with input size.

### 2. Quadratic Time Complexity - O(n²):
When one loop of size n is nested inside another loop of size n, the total number of operations executed is 
 × n = n².

### 3. Logarithmic Time Complexity - O(log n):
When an input value n is repeatedly divided by 2 in a loop (repeated halving), the loop terminates in log₂(n) iterations. For example, dividing 1024 by 2 repeatedly reaches 1 in 10 steps.

## 5. Algorithm / Procedure

### Question 1: Linear Loop - O(n)
1. Start the program.
2. Initialize steps = 0.
3. Run a loop from i = 1 to 10.
4. Increment steps by 1 in each iteration.
5. Print the total steps.
6. Stop the program.

### Question 2: Nested Loops - O(n²)
1. Start the program.
2. Initialize steps = 0.
3. Run an outer loop from i = 1 to 10.
4. Run an inner loop from j = 1 to 10.
5. Increment steps by 1 in each inner iteration.
6. Print the total steps.
7. Stop the program.

### Question 3: Repeated Halving - O(log n)
1. Start the program.
2. Initialize n = 1024 and count = 0.
3. While n > 1, divide n by 2 (n = n / 2) and increment count.
4. Print the total halving steps.
5. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- Loop bound n = 10

### Question 2:
- Outer loop bound = 10, Inner loop bound = 10

### Question 3:
- n = 1024

## 7. Output

### Question 1:
```
Steps: 10
```

### Question 2:
```
Steps: 100
```

### Question 3:
```
Halving steps: 10
```

Result: All three Java programs were successfully written and executed to demonstrate step counting and analyze algorithmic time complexity for O(n), O(n²), and O(log n) workflows.