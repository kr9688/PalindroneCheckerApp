# Palindrome Checker App

## Objective

The objective of the PalindromeChecker App is to design and implement a console-based Java application that validates whether a given string is a palindrome while strengthening core programming fundamentals and object-oriented programming concepts.

---

## Use Case 11: Object-Oriented Palindrome Service

### Goal

Encapsulate the palindrome checking logic inside a dedicated class and expose a method to verify whether a string is a palindrome.

---

## Project Flow

1. Accept a string input from the user.
2. Create a `PalindromeChecker` class.
3. Implement the `checkPalindrome()` method inside the class.
4. Pass the input string to the method.
5. The method checks whether the string is a palindrome.
6. Return the result to the main application.
7. Display the result to the user.

---

## Key Concepts Used

### Encapsulation

The palindrome checking logic is encapsulated inside the `PalindromeChecker` class.

### Single Responsibility Principle

The `PalindromeChecker` class is responsible only for validating whether a string is a palindrome.

### Method Abstraction

The `checkPalindrome()` method exposes the functionality without exposing internal implementation details.

---

## Data Structure Used

Internal logic uses simple string indexing (array-like access).

---

## Program Compilation

Compile the program using:

```
javac UseCase11PalindromeCheckerApp.java
```

---

## Program Execution

Run the program using:

```
java UseCase11PalindromeCheckerApp
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

This use case demonstrates how object-oriented design principles such as encapsulation and single responsibility can be applied to organize palindrome validation logic in a reusable and maintainable structure.
