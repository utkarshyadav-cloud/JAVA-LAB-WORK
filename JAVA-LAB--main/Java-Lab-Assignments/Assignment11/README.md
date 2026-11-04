# Assignment 11: Bubble Sort and Selection Sort

## 1. Experiment Title
Bubble Sort and Selection Sort in Java.

## 2. Aim
To sort arrays in increasing order using bubble sort and selection sort, and count swaps.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Comparison-based sorting algorithms arrange elements in non-decreasing order:

### 1. Bubble Sort:
Bubble sort repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. Larger elements gradually "bubble up" to the end of the array.
- Pass count: rr.length - 1
- Best-case time complexity: O(n)
- Worst/Average-case time complexity: O(n²)

### 2. Selection Sort:
Selection sort divides the array into sorted and unsorted subarrays. In each pass, it locates the smallest element from the unsorted subarray and swaps it with the first unsorted element.
- Time complexity: O(n²) in all cases.

### 3. Swap Operation:
Swapping exchanges the values at two distinct indices using a temporary variable:
`java
int temp = arr[i];
arr[i] = arr[j];
arr[j] = temp;
```

## 5. Algorithm / Procedure

### Question 1: Bubble Sort
1. Start the program.
2. Declare and initialize array arr = {5, 1, 4, 2, 8}.
3. Run outer loop i from 0 to arr.length - 2.
4. Run inner loop j from 0 to arr.length - 2 - i.
5. If arr[j] > arr[j + 1], swap arr[j] and arr[j + 1].
6. Display sorted array using Arrays.toString(arr).
7. Stop the program.

### Question 2: Selection Sort
1. Start the program.
2. Declare and initialize array arr = {64, 25, 12, 22, 11}.
3. Run outer loop i from 0 to arr.length - 2.
4. Set minIdx = i; run inner loop j from i + 1 to arr.length - 1.
5. If arr[j] < arr[minIdx], update minIdx = j.
6. Swap arr[minIdx] with arr[i].
7. Display sorted array using Arrays.toString(arr).
8. Stop the program.

### Question 3: Count Swaps in Bubble Sort
1. Start the program.
2. Declare array arr = {5, 1, 4, 2, 8} and initialize swaps = 0.
3. Perform bubble sort on arr.
4. Each time a swap condition is satisfied and elements are swapped, increment swaps by 1.
5. Display the total number of swaps.
6. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- arr = {5, 1, 4, 2, 8}

### Question 2:
- arr = {64, 25, 12, 22, 11}

### Question 3:
- arr = {5, 1, 4, 2, 8}

## 7. Output

### Question 1:
```
Sorted: [1, 2, 4, 5, 8]
```

### Question 2:
```
Sorted: [11, 12, 22, 25, 64]
```

### Question 3:
```
Swaps: 4
```

Result: All three Java programs were successfully written and executed to demonstrate bubble sort, selection sort, and tracking element swaps.