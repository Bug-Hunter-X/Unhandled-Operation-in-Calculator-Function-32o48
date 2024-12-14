# Unhandled Operation in Calculator Function

This repository demonstrates a common JavaScript error: failing to handle all cases in a switch statement. The `calculate` function is designed to add or subtract two numbers based on the provided operation. However, it lacks handling for multiplication.  This leads to unexpected results when an unsupported operation is used.

## Bug Report

The `calculate` function incorrectly handles the '*' operation. Instead of performing multiplication, it returns 0. This is due to a missing `case '*'` in the `switch` statement.

## Solution

The solution adds a `case '*'` to the `switch` statement to handle multiplication correctly. This ensures that all supported operations are handled appropriately.
