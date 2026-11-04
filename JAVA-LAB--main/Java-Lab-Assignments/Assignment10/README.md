# Assignment 10: Switch and ArrayList

## 1. Experiment Title
Switch and ArrayList in Java.

## 2. Aim
To use switch to select a case and use ArrayList to store, access and modify values.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Multi-branch decision making and dynamic collections in Java:

### 1. Switch Statement:
The switch statement tests a variable against multiple case values. The reak keyword terminates the switch block once a matching case is executed, preventing fall-through. An optional default case handles unmatched values.

### 2. ArrayList:
ArrayList is part of the java.util framework and provides a resizable, dynamic array.
Key methods:
- dd(value): Appends an element to the end of the list.
- size(): Returns the total number of elements.
- get(index): Retrieves the element at the specified index.
- set(index, value): Replaces the element at the specified index.
- emove(index): Removes the element at the specified index and shifts subsequent elements left.

## 5. Algorithm / Procedure

### Question 1: Display Day using Switch
1. Start the program.
2. Declare integer day = 3.
3. Use a switch(day) block with cases 1 to 3 and default.
4. Case 3 prints "Wednesday" and breaks.
5. Stop the program.

### Question 2: Create and Access ArrayList
1. Start the program.
2. Import java.util.ArrayList.
3. Instantiate an ArrayList<Integer> list.
4. Add elements 10, 20, 30, and 40.
5. Print the full list, its size using size(), and element at index 2 using get(2).
6. Stop the program.

### Question 3: Update and Remove Elements from ArrayList
1. Start the program.
2. Import java.util.ArrayList.
3. Instantiate an ArrayList<Integer> list with elements 10, 20, 30, and 40.
4. Replace element at index 1 with 25 using set(1, 25).
5. Remove element at index 3 using remove(3).
6. Print the modified list and its updated size.
7. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- day = 3

### Question 2:
- Elements added: 10, 20, 30, 40

### Question 3:
- Initial elements: 10, 20, 30, 40
- Update: index 1 set to 25
- Remove: index 3

## 7. Output

### Question 1:
```
Wednesday
```

### Question 2:
```
[10, 20, 30, 40]
Size: 4
Item at index 2: 30
```

### Question 3:
```
[10, 25, 30]
Size: 3
```

Result: All three Java programs were successfully written and executed to demonstrate switch-case decision structures and dynamic list operations using Java ArrayList.