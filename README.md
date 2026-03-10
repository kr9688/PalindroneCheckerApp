# Palindrome Checker App

## Objective

The objective of the PalindromeChecker App is to design and implement a console-based Java application that validates whether a given string is a palindrome under different conditions while reinforcing programming fundamentals and data structure concepts.

---

## Use Case 6: Queue + Stack Based Palindrome Check

### Goal

Demonstrate the behavioral difference between Queue (FIFO) and Stack (LIFO) while validating whether a string is a palindrome.

---

## Project Flow

1. Accept a string input from the user.
2. Insert each character into a **Queue** using enqueue operation.
3. Push each character into a **Stack**.
4. Dequeue characters from the queue.
5. Pop characters from the stack.
6. Compare the dequeued and popped characters.
7. If all characters match, the string is a palindrome.
8. If a mismatch occurs, the string is not a palindrome.
9. Display the result.

---

## Key Concepts Used

### Queue

A linear data structure that follows the **First In First Out (FIFO)** principle.

### Stack

A linear data structure that follows the **Last In First Out (LIFO)** principle.

### Enqueue & Dequeue Operations

* **Enqueue:** Inserts an element into the queue.
* **Dequeue:** Removes the element from the front of the queue.

### Stack vs Queue

This use case demonstrates the behavioral difference between **FIFO** and **LIFO** data structures.

### Logical Comparison

Characters removed from the queue are compared with characters removed from the stack to verify palindrome logic.

---

## Data Structures Used

* Queue (java.util.Queue)
* Stack (java.util.Stack)

---

## Program Compilation

Compile the program using:

```
javac UseCase6PalindromeCheckerApp.java
```

---

## Program Execution

Run the program using:

```
java UseCase6PalindromeCheckerApp
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

This use case demonstrates how Queue and Stack data structures behave differently (FIFO vs LIFO) and how their operations can be combined to validate palindrome logic efficiently.
