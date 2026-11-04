# Assignment 2: Decisions and Loops with Numbers

## 1. Experiment Title
Decisions and Loops with Numbers in Java.

## 2. Aim
To use if, else-if and loops to make decisions and repeat steps with whole numbers.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Conditional statements and loops form the backbone of control flow in Java:

### 1. If-Else Statement:
The if-else statement selects a block of code to execute based on a boolean condition. If the condition evaluates to true, the if-block executes; otherwise, the else-block executes.

### 2. Else-If Ladder:
An else-if ladder tests multiple conditions sequentially. As soon as one condition evaluates to true, its statement block executes and the rest of the ladder is skipped.

### 3. Modulo Operator (%):
The modulo operator finds the remainder after integer division. It is commonly used for checking divisibility (e.g., 
 % 2 == 0 checks if a number is even).

### 4. Leap Year Conditions:
A year is a leap year if it is divisible by 4 and not divisible by 100, or if it is divisible by 400:
((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0))

### 5. For Loop:
A for loop repeats a block of statements a specific number of times. It consists of initialization, condition testing, and increment/decrement expressions.

## 5. Algorithm / Procedure

### Question 1: Even or Odd
1. Start the program.
2. Declare an integer variable n and initialize it with 27.
3. Check if n % 2 == 0 using an if-else statement.
4. If true, print that n is even; otherwise, print that n is odd.
5. Stop the program.

### Question 2: Grade Calculation
1. Start the program.
2. Declare an integer variable marks and initialize it with 83.
3. If marks >= 90, print "Grade: A".
4. Else if marks >= 75, print "Grade: B".
5. Else print "Grade: C".
6. Stop the program.

### Question 3: Leap Year Check
1. Start the program.
2. Declare an integer variable year and initialize it with 2024.
3. Check if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)).
4. If true, print "Leap year"; otherwise print "Not a leap year".
5. Stop the program.

### Question 4: Factorial using For Loop
1. Start the program.
2. Declare an integer variable n = 5 and fact = 1.
3. Run a for loop from i = 1 to n.
4. In each iteration, multiply fact by i (fact *= i).
5. Display the calculated factorial value.
6. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- n = 27

### Question 2:
- marks = 83

### Question 3:
- year = 2024

### Question 4:
- n = 5

## 7. Output

### Question 1:
```
27 is odd
```

### Question 2:
```
Grade: B
```

### Question 3:
```
Leap year
```

### Question 4:
```
Factorial of 5 is 120
```

Result: All four Java programs were successfully written and executed to demonstrate conditional statements, branch logic, and loop iterations with numbers.