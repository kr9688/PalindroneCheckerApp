# Palindrome Checker App

## Objective

The objective of the PalindromeChecker App is to design and implement a console-based Java application that validates whether a given string is a palindrome while strengthening programming fundamentals and data structure concepts.

---

## Use Case 8: Linked List Based Palindrome Checker

### Goal

Check whether a string is a palindrome by converting the string into a singly linked list and comparing the two halves of the list.

---

## Project Flow

1. Accept a string input from the user.
2. Convert each character of the string into a node of a singly linked list.
3. Use the fast and slow pointer technique to locate the middle of the list.
4. Reverse the second half of the linked list.
5. Compare the first half with the reversed second half.
6. If all nodes match, the string is a palindrome.
7. Display the result.

---

## Key Concepts Used

### Singly Linked List

A dynamic data structure where elements are stored in nodes and connected using references.

### Node Traversal

Accessing each element sequentially using the `next` reference.

### Fast and Slow Pointer Technique

Two pointers move at different speeds to efficiently find the middle of the linked list.

### In-Place Reversal

The second half of the linked list is reversed without using extra memory.

---

## Data Structure Used

Singly Linked List

---

## Program Compilation

Compile the program using:

```
javac UseCase8PalindromeCheckerApp.java
```

---

## Program Execution

Run the program using:

```
java UseCase8PalindromeCheckerApp
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

This use case demonstrates how a singly linked list can be used to validate palindrome logic efficiently by using pointer techniques and in-place list reversal.
