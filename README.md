# JavaScript Null Value Handling Bug

This repository demonstrates a common error in JavaScript:  incorrect handling of null values. The `bug.js` file contains a function that attempts to add two numbers, but fails to correctly handle the scenario where one or both inputs are null. This leads to unexpected behavior.

The `bugSolution.js` file provides a corrected version of the function, showcasing proper null value handling.

## Bug Description
The `foo` function in `bug.js` does not explicitly check for null values in its input parameters. As a result, when null is passed as an argument, it doesn't handle it gracefully and results in unexpected outputs or errors.  

## Solution
The improved `foo` function in `bugSolution.js` includes a check for null values before performing addition, providing a more robust and predictable outcome.  Null values are explicitly handled, preventing unexpected behavior.