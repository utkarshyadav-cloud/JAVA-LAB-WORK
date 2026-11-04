# Assignment 4: Writing Functions

## 1. Experiment Title
Writing Functions in Java.

## 2. Aim
To write methods with parameters and return values, and call them from main.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Methods are modular blocks of reusable code in Java:

### 1. Methods:
A method is a named block of code that performs a specific task. Defining methods promotes code reusability and clean program architecture.

### 2. Parameters and Return Values:
- **Parameters:** Variables defined in the method signature that receive argument values passed by the caller.
- **Return Value:** The value transmitted back to the caller using the eturn statement. The return type is declared in the method signature.

### 3. Static Keyword:
A method declared with static belongs to the class itself rather than an instance of the class. It can be invoked directly from the static main() method without instantiating an object.

### 4. Mathematical Combinations and Permutations:
- Factorial: 
! = 1 × 2 × ... × n
- Combination: 
Cr = n! / (r! × (n - r)!)
- Permutation: 
Pr = n! / (n - r)!

## 5. Algorithm / Procedure

### Question 1: Combination nCr
1. Start the program.
2. Define a static method fact(int n) that computes and returns factorial of n using a loop.
3. Define a static method nCr(int n, int r) that returns fact(n) / (fact(r) * fact(n - r)).
4. In main(), call nCr(5, 2) and print the result.
5. Stop the program.

### Question 2: Permutation nPr
1. Start the program.
2. Define a static method fact(int n) to calculate factorial.
3. Define a static method nPr(int n, int r) that returns fact(n) / fact(n - r).
4. In main(), call nPr(5, 2) and print the result.
5. Stop the program.

### Question 3: Maximum of Two Numbers
1. Start the program.
2. Define a static method maxOf(int a, int b).
3. Compare a and b; return a if a > b, else return b.
4. In main(), invoke maxOf(14, 9) and display the returned maximum value.
5. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- n = 5, r = 2

### Question 2:
- n = 5, r = 2

### Question 3:
- a = 14, b = 9

## 7. Output

### Question 1:
```
5C2 = 10
```

### Question 2:
```
5P2 = 20
```

### Question 3:
```
Larger: 14
```

Result: All three Java programs were successfully written and executed to demonstrate method definition, parameter passing, return statements, and calling static methods.