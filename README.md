Writing

# Week 6 Assignment - Safe Functions

## Files

- `safe_tools.py` \- Contains three functions that handle errors using try and except.
- `README.md` \- Describes the assignment files and explains error handling.

## Why can the if check not catch abc on its own?

An if check cannot catch `"abc"` as an invalid whole number just by checking the text because the error occurs when Python tries to convert it using `int()`. The `try` and `except ValueError` statements handle this conversion error and allow the program to continue running instead of crashing.
