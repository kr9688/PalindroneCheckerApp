# Palindrome Checker App

## Objective

The objective of the PalindromeChecker App is to design and implement a console-based Java application that validates whether a given string is a palindrome under different conditions while strengthening core programming fundamentals and data structure concepts.

---

## Use Case 10: Case-Insensitive & Space-Ignored Palindrome

### Goal

Check whether a string is a palindrome while ignoring spaces and character case.

---

## Project Flow

1. Accept a string input from the user.
2. Normalize the string by:

    * Removing spaces.
    * Converting all characters to lowercase.
3. Compare characters from the beginning and end of the string.
4. If characters match, continue comparison.
5. If any mismatch occurs, the string is not a palindrome.
6. Display the result.

---

## Key Concepts Used

### String Preprocessing

The input string is cleaned before comparison to remove unnecessary characters like spaces.

### Regular Expressions

Used to remove spaces from the string.

Example:

```
replaceAll("\\s+", "")
```

### Case Normalization

Converts all characters to lowercase so comparisons are case-insensitive.

---

## Data Structure Used

String / Character Array

---

## Program Compilation

Compile the program using:

```
javac UseCase10PalindromeCheckerApp.java
```

---

## Program Execution

Run the program using:

```
java UseCase10PalindromeCheckerApp
```

---

## Example Output

Example 1

```
Enter a string:
Never Odd Or Even
The string is a Palindrome.
```

Example 2

```
Enter a string:
Hello World
The string is NOT a Palindrome.
```

---

## Conclusion

This use case demonstrates how preprocessing techniques such as removing spaces and ignoring case can improve palindrome validation for real-world text inputs.
