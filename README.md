# Unexpected Loop Iterations in JavaScript

This repository demonstrates a subtle bug related to loop termination in JavaScript using a `break` statement within a `while` loop.  The loop's behavior might not be immediately obvious, potentially leading to unexpected results or errors.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides a corrected version and explanation.

## Bug Description
The `while` loop in `bug.js` is intended to iterate a specific number of times before exiting. However, the placement and behavior of the `break` statement can cause confusion. The loop continues to execute until the condition `i === 5` is met, resulting in an additional iteration that might not be expected.

## Solution
The `bugSolution.js` file offers a clearer approach to controlling loop iterations, demonstrating best practices to prevent similar issues in your own code.