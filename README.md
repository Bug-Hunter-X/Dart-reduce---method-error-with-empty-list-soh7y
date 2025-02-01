# Dart reduce() method and empty lists

This repository demonstrates a common error when using the `reduce()` method in Dart with an empty list. The `reduce()` method requires at least one element in the list; otherwise, it throws a `RangeError`.  The solution shows how to handle this gracefully by checking for an empty list before using `reduce()`. 

## Bug
The `bug.dart` file contains code that attempts to use `reduce()` on an empty list, resulting in a runtime error.

## Solution
The `bugSolution.dart` file provides a solution that checks for an empty list and handles it appropriately, preventing the error.