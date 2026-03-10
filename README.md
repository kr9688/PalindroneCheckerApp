# Palindrome Checker App

## Objective

The objective of the PalindromeChecker App is to design and implement a console-based Java application that validates whether a given string is a palindrome under different conditions while strengthening programming fundamentals and data structure concepts.

---

## Use Case 7: Deque-Based Optimized Palindrome Checker

### Goal

Use a Deque (Double Ended Queue) to compare characters from the front and rear of the string efficiently.

---

## Project Flow

1. Accept a string input from the user.
2. Insert each character of the string into a Deque.
3. Remove the first and last characters from the deque.
4. Compare the removed characters.
5. If they match, continue comparing until the deque becomes empty or has one element.
6. If any mismatch occurs, the string is not a palindrome.
7. Display the result to the user.

---

## Key Concepts Used

### Deque (Double Ended Queue)

A data structure that allows insertion and deletion from both the **front** and **rear**.

### Front and Rear Access

Deque allows direct access to both ends of the data structure, making it efficient for palindrome comparisons.

### Optimized Data Handling

This method avoids creating separate reversed structures because both ends can be accessed directly.

---

## Data Structure Used

Deque (java.util.ArrayDeque)

---

## Program Compilation

Compile the program using:

```
javac UseCase7PalindromeCheckerApp.java
```

---

## Program Execution

Run the program using:

```
java UseCase7PalindromeCheckerApp
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

This use case demonstrates an optimized palindrome validation approach using a Deque. By comparing elements from both ends directly, the algorithm becomes efficient and avoids the need for additional reversal data structures.
