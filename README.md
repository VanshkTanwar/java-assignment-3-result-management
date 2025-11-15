
# Student Result Management System (Java)

## Description
A console-based Java application that manages student records (roll, name, marks for 3 subjects),
validates input using custom checked exception `InvalidMarksException`, calculates average, and shows pass/fail.

## Features
- Custom exception `InvalidMarksException` for invalid marks (outside 0-100).
- Demonstrates `throw`, `throws`, `try-catch-finally`.
- Handles built-in exceptions (invalid integer input).
- Stores multiple students in an array.
- Simple interactive console menu.

## How to run
1. Compile:
   `javac InvalidMarksException.java Student.java ResultManager.java`
2. Run:
   `java ResultManager`

## Notes
- This implementation uses arrays (capacity = 100). You can change capacity in `main`.
- Understand and rewrite parts in your own words before submission to adhere to academic policies.

