# Assignment 3: Star and Number Patterns

## 1. Experiment Title
Star and Number Patterns in Java.

## 2. Aim
To use nested loops to print star and number patterns in rows.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Patterns are constructed using nested loops:

### 1. Nested Loops:
A nested loop is a loop placed inside the body of another loop.
- **Outer Loop:** Controls the number of rows printed.
- **Inner Loop:** Controls the columns or items printed in each individual row.

### 2. Console Output Methods:
- System.out.print(): Prints text on the current line without advancing to the next line.
- System.out.println(): Prints a newline, moving the cursor to the beginning of the next row.

## 5. Algorithm / Procedure

### Question 1: Square Star Pattern
1. Start the program.
2. Run an outer loop from i = 1 to 4 to represent each row.
3. Run an inner loop from j = 1 to 4 to print "*" on the same line.
4. Call System.out.println() after the inner loop to start a new row.
5. Stop the program.

### Question 2: Right Triangle Star Pattern
1. Start the program.
2. Run an outer loop from i = 1 to 4.
3. Run an inner loop from j = 1 to i to print "*" on the same line.
4. Call System.out.println() after each row.
5. Stop the program.

### Question 3: Number Triangle Pattern
1. Start the program.
2. Run an outer loop from i = 1 to 4.
3. Run an inner loop from j = 1 to i to print j followed by a space.
4. Call System.out.println() after each row.
5. Stop the program.

### Question 4: Inverted Triangle Star Pattern
1. Start the program.
2. Run an outer loop from i = 4 down to 1 (decrementing i).
3. Run an inner loop from j = 1 to i to print "*" on the same line.
4. Call System.out.println() after each row.
5. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- Rows = 4, Columns = 4

### Question 2:
- Rows = 4

### Question 3:
- Rows = 4

### Question 4:
- Rows = 4

## 7. Output

### Question 1:
```
****
****
****
****
```

### Question 2:
```
*
**
***
****
```

### Question 3:
```
1 
1 2 
1 2 3 
1 2 3 4 
```

### Question 4:
```
****
***
**
*
```

Result: All four Java programs were successfully written and executed to demonstrate nested loop control structures for rendering star and number patterns.