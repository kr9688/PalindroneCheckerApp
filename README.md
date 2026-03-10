# Palindrome Checker App

## Objective

The objective of the PalindromeChecker App is to develop a console-based Java application that checks whether a given string is a palindrome while reinforcing fundamental programming and data structure concepts.

---

## Use Case 5: Stack-Based Palindrome Checker

### Goal

Use a stack data structure to reverse the characters of a string and verify whether the string is a palindrome.

---

## Project Flow

1. Accept a string input from the user.
2. Create a stack to store characters.
3. Push each character of the string into the stack.
4. Pop characters from the stack one by one.
5. Compare the popped character with the original string.
6. If all characters match, the string is a palindrome.
7. If any mismatch occurs, the string is not a palindrome.
8. Display the result.

---

## Key Concepts Used

### Stack

A linear data structure that follows the **Last In First Out (LIFO)** principle.

### Push Operation

Used to insert characters into the stack.

### Pop Operation

Used to remove characters from the stack in reverse order.

### Reversal Logic

The stack automatically reverses the order of elements, which helps in palindrome validation.

---

## Data Structure Used

Stack (java.util.Stack)

---

## Program Compilation

Compile the program using:

```
javac UseCase5PalindromeCheckerApp.java
```

---

## Program Execution

Run the program using:

```
java UseCase5PalindromeCheckerApp
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

This use case demonstrates how the stack data structure can be used to reverse characters efficiently and validate whether a string is a palindrome using the LIFO principle.
