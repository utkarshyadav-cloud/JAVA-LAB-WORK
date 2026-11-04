# Assignment 12: Insertion Sort

## 1. Experiment Title
Insertion Sort in Java.

## 2. Aim
To sort arrays using insertion sort and count the number of shifts.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Insertion sort is an intuitive, in-place, comparison-based sorting algorithm:

### 1. Working Principle:
Insertion sort builds the final sorted array one item at a time. It assumes the first element is already sorted. For each subsequent element (called the key), it compares the key with elements in the sorted portion from right to left.

### 2. Shifts:
When an element in the sorted portion is greater than key, it is shifted one position to the right (rr[j + 1] = arr[j]). Once the correct insertion point is found, the key is placed into rr[j + 1].

### 3. Complexity:
- Best-case time complexity (already sorted): O(n)
- Worst-case time complexity (reverse sorted): O(n²)
- Space complexity: O(1) (in-place)

## 5. Algorithm / Procedure

### Question 1: Insertion Sort (Array 1)
1. Start the program.
2. Declare and initialize array arr = {7, 3, 5, 1}.
3. Run a loop from i = 1 to arr.length - 1; set key = arr[i] and j = i - 1.
4. While j >= 0 and arr[j] > key, shift arr[j] to arr[j + 1] and decrement j.
5. Place key at arr[j + 1].
6. Display sorted array using Arrays.toString(arr).
7. Stop the program.

### Question 2: Insertion Sort (Array 2)
1. Start the program.
2. Declare and initialize array arr = {14, 3, 9, 21, 6}.
3. For each element starting from index 1, extract key and compare backward.
4. Shift elements larger than key to the right.
5. Insert key into its proper position.
6. Display sorted array using Arrays.toString(arr).
7. Stop the program.

### Question 3: Count Shifts in Insertion Sort
1. Start the program.
2. Declare array arr = {6, 5, 4, 3, 2, 1} and initialize shifts = 0.
3. Perform insertion sort; inside the while loop, increment shifts for each shift operation (rr[j + 1] = arr[j]).
4. Display the total number of shifts.
5. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- arr = {7, 3, 5, 1}

### Question 2:
- arr = {14, 3, 9, 21, 6}

### Question 3:
- arr = {6, 5, 4, 3, 2, 1}

## 7. Output

### Question 1:
```
Sorted: [1, 3, 5, 7]
```

### Question 2:
```
Sorted: [3, 6, 9, 14, 21]
```

### Question 3:
```
Shifts: 15
```

Result: All three Java programs were successfully written and executed to demonstrate insertion sort and counting total array shift operations.