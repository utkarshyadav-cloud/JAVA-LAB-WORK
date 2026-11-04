# Assignment 15: StringBuilder Methods

## 1. Experiment Title
StringBuilder Methods in Java.

## 2. Aim
To build and modify text using append(), insert() and deleteCharAt().

## 3. Software / Tools Required
- Programming Language: Java
- JDK (Java Development Kit)
- IDE: IntelliJ IDEA / Eclipse / VS Code
- Any text editor (if IDE is not available)

## 4. Theory
Mutable string manipulation using StringBuilder in Java:

### 1. StringBuilder:
Unlike immutable String, StringBuilder represents a mutable sequence of characters. Modifications alter the underlying buffer directly without instantiating new objects, making it far more efficient for iterative modifications.

### 2. Core StringBuilder Methods:
- ppend(value): Appends the string representation of any data type to the end of the sequence.
- insert(offset, value): Inserts characters or strings at the specified index position.
- deleteCharAt(index): Removes the character at the specified zero-based index.
- length(): Returns the number of characters currently in the sequence.

## 5. Algorithm / Procedure

### Question 1: Append Text and Display Length
1. Start the program.
2. Instantiate StringBuilder sb with "Hello".
3. Append " World" using sb.append(" World").
4. Print the modified sb and its length using sb.length().
5. Stop the program.

### Question 2: Append Numbers and Remove Trailing Comma
1. Start the program.
2. Instantiate an empty StringBuilder sb.
3. Loop from i = 1 to 5, appending each number and a comma: sb.append(i).append(",").
4. Remove the trailing comma using sb.deleteCharAt(sb.length() - 1).
5. Print the resulting StringBuilder.
6. Stop the program.

### Question 3: Insert Text at Beginning
1. Start the program.
2. Instantiate StringBuilder sb with "Java".
3. Insert "Hello " at index 0 using sb.insert(0, "Hello ").
4. Print the updated StringBuilder.
5. Stop the program.

## 6. Input
The following values are used in the experiment:

### Question 1:
- Initial string: "Hello", append: " World"

### Question 2:
- Loop range: 1 to 5

### Question 3:
- Initial string: "Java", insert at 0: "Hello "

## 7. Output

### Question 1:
```
Hello World
Length: 11
```

### Question 2:
```
1,2,3,4,5
```

### Question 3:
```
Hello Java
```

Result: All three Java programs were successfully written and executed to demonstrate mutable string creation, appending, inserting, and deleting characters using the StringBuilder class.