# Assignment 13: Strings: Methods and Palindromes

## 1. Experiment Title
Strings: Methods and Palindromes in Java.

## 2. Aim
To use String methods, reverse words, check palindromes and generate substrings.

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Strings represent sequences of characters and are immutable objects in Java:

### 1. Immutability:
Once created, a String object cannot be altered. Any method that appears to modify a string actually creates and returns a new String object.

### 2. Built-in String Methods:
- length(): Returns the number of characters in the string.
- indexOf(char): Returns the index of the first occurrence of the specified character, or -1 if not found.
- 	oUpperCase(): Converts all characters in the string to uppercase.
- charAt(index): Returns the character at the specified 0-based index.
- substring(beginIndex, endIndex): Returns a new substring from eginIndex (inclusive) to endIndex (exclusive).

### 3. Palindrome:
A word or phrase is a palindrome if it reads the same forward and backward (e.g. "racecar"). It can be validated by comparing characters from both ends moving inward.

## 5. Algorithm / Procedure

### Question 1: Common String Methods
1. Start the program.
2. Declare String str = "Programming".
3. Display its length using str.length().
4. Find the position of 'g' using str.indexOf('g').
5. Convert str to uppercase using str.toUpperCase() and display.
6. Stop the program.

### Question 2: Reverse a String using charAt
1. Start the program.
2. Declare String word = "Java" and initialize String reversed = "".
3. Loop from i = word.length() - 1 down to 0.
4. Append word.charAt(i) to reversed.
5. Print the reversed string.
6. Stop the program.

### Question 3: Check Palindrome
1. Start the program.
2. Declare String word = "racecar" and boolean isPalindrome = true.
3. Initialize two pointers: left = 0, right = word.length() - 1.
4. While left < right, if word.charAt(left) != word.charAt(right), set isPalindrome = false and break.
5. Advance left and decrement right.
6. Print whether word is a palindrome.
7. Stop the program.

### Question 4: Generate All Substrings
1. Start the program.
2. Declare String str = "abc".
3. Run outer loop i from 0 to str.length() - 1.
4. Run inner loop j from i + 1 to str.length().
5. Print str.substring(i, j).
6. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- str = "Programming"

### Question 2:
- word = "Java"

### Question 3:
- word = "racecar"

### Question 4:
- str = "abc"

## 7. Output

### Question 1:
```
Length: 11
Position of g: 3
Upper case: PROGRAMMING
```

### Question 2:
```
Reversed: avaJ
```

### Question 3:
```
racecar is a palindrome
```

### Question 4:
```
a
ab
abc
b
bc
c
```

Result: All four Java programs were successfully written and executed to demonstrate standard String methods, string reversal, palindrome detection, and generating substrings.