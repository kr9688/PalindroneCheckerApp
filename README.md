# Palindrome Checker App

## Objective

The objective of the PalindromeChecker App is to design and implement a console-based Java application that validates whether a given string is a palindrome under different conditions while strengthening programming fundamentals and software design principles.

---

## Use Case 12: Strategy Pattern for Palindrome Algorithms

### Goal

Select different palindrome checking algorithms dynamically using the Strategy Design Pattern.

---

## Project Flow

1. Accept a string input from the user.
2. Define a `PalindromeStrategy` interface.
3. Implement multiple strategies such as `StackStrategy` and `DequeStrategy`.
4. Allow the user to select the strategy at runtime.
5. Execute the selected algorithm to check whether the string is a palindrome.
6. Display the result.

---

## Key Concepts Used

### Interface

Defines a common contract for different palindrome checking strategies.

### Polymorphism

Different implementations of the same interface can be used interchangeably.

### Strategy Pattern

A design pattern that allows selecting an algorithm at runtime without modifying the client code.

---

## Data Structures Used

* Stack
* Deque

Each strategy can use a different data structure internally.

---

## Program Compilation

Compile the program using:

```
javac UseCase12PalindromeCheckerApp.java
```

---

## Program Execution

Run the program using:

```
java UseCase12PalindromeCheckerApp
```

---

## Example Output

```
Enter a string:
madam

Choose Algorithm:
1. Stack Strategy
2. Deque Strategy

1
The string is a Palindrome.
```

---

## Conclusion

This use case demonstrates how the Strategy Design Pattern enables flexible selection of different palindrome algorithms while promoting clean, modular, and maintainable code.
