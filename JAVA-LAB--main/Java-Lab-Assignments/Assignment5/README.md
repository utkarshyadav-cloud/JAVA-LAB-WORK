# Assignment 5: Arrays: Traversal and Counting

## 1. Experiment Title
Arrays: Traversal and Counting in Java.

## 2. Aim
To create arrays, visit every element, calculate totals and count values.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Arrays are fundamental linear data structures in Java:

### 1. Array Basics:
An array is a fixed-size container that stores elements of the same data type sequentially in memory.
- Indexing starts at 0 and goes up to rray.length - 1.
- The length field returns the total number of elements in the array.

### 2. Traversal:
Linear traversal involves visiting each element of the array using a loop (such as a standard for loop or enhanced for-each loop) to inspect or modify its contents.

### 3. Aggregation and Counting:
- An accumulator variable (sum) can sum up values during traversal.
- A tracking variable (largest) can identify extrema by comparing each item with the current maximum.
- A counter variable (count) can track elements satisfying specific conditions.

## 5. Algorithm / Procedure

### Question 1: Display Elements with Indexes
1. Start the program.
2. Declare and initialize an integer array arr = {3, 4, 5}.
3. Loop from i = 0 to arr.length - 1.
4. Print index i and element arr[i].
5. Stop the program.

### Question 2: Sum and Largest Element
1. Start the program.
2. Declare and initialize array arr = {12, 45, 7, 33, 21}.
3. Initialize sum = 0 and largest = arr[0].
4. Traverse the array; accumulate each element into sum and update largest if arr[i] > largest.
5. Print the sum and largest element.
6. Stop the program.

### Question 3: Count Values Greater than 10
1. Start the program.
2. Declare and initialize array arr = {5, 12, 2, 14, 7}.
3. Initialize count = 0.
4. Loop through array; if arr[i] > 10, increment count.
5. Display the final count.
6. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- arr = {3, 4, 5}

### Question 2:
- arr = {12, 45, 7, 33, 21}

### Question 3:
- arr = {5, 12, 2, 14, 7}

## 7. Output

### Question 1:
```
Index 0: 3
Index 1: 4
Index 2: 5
```

### Question 2:
```
Sum: 118
Largest: 45
```

### Question 3:
```
Count greater than 10: 2
```

Result: All three Java programs were successfully written and executed to demonstrate 1D array creation, linear traversal, calculating totals, and conditional counting.