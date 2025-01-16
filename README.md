# Unhandled Undefined Value in JavaScript Function

This repository demonstrates a common error in JavaScript: failure to handle `undefined` values gracefully. The `foo` function correctly handles `null`, but throws an error when given `undefined` as input. The solution shows how to properly check for both `null` and `undefined` to prevent this error.

## Bug

The `bug.js` file contains the buggy code.  The function `foo` attempts to access the `.length` property of its input, which throws a TypeError when the input is `undefined`. 

## Solution

The `bugSolution.js` file provides the corrected version. It explicitly checks for both `null` and `undefined` before accessing the `.length` property. This ensures the function handles all possible input scenarios without errors. 