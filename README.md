# Palindrome Checker App

## Objective

The objective of the PalindromeChecker App is to design and implement a console-based Java application that validates whether a given string is a palindrome while strengthening programming fundamentals and data structure concepts.

---

## Use Case 9: Recursive Palindrome Checker

### Goal

Check whether a string is a palindrome using recursion by repeatedly comparing characters from the start and end of the string.

---

## Project Flow

1. Accept a string input from the user.
2. Start comparison between the first and last characters.
3. If the characters match, recursively call the function for the next inner characters.
4. Continue this process until the base condition is reached.
5. If all character comparisons match, the string is a palindrome.
6. Display the result.

---

## Key Concepts Used

### Recursion

A programming technique where a function calls itself to solve smaller instances of the same problem.

### Base Condition

Stops the recursion when the start index becomes greater than or equal to the end index.

### Call Stack

The call stack keeps track of each recursive method call until the base condition is met.

---

## Data Structure Used

Call Stack

---

## Program Compilation

Compile the program using:

```
javac UseCase9PalindromeCheckerApp.java
```

---

## Program Execution

Run the program using:

```
java UseCase9PalindromeCheckerApp
```

---

## Example Output

Example 1

```
Enter a string:
madam
The string is a Palindrome.
```

Example 2

```
Enter a string:
hello
The string is NOT a Palindrome.
```

---

## Conclusion

This use case demonstrates how recursion can be used to solve the palindrome problem efficiently by breaking the problem into smaller subproblems while utilizing the call stack.
