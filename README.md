# Unexpected String Concatenation in JavaScript

This repository demonstrates a common, yet often surprising, error in JavaScript: unexpected string concatenation due to its dynamic typing system. 

The `bug.js` file contains a function `foo` that attempts to add two numbers. However, if one of the inputs is a string, JavaScript performs string concatenation instead of numerical addition, leading to unexpected results.  The `bugSolution.js` file showcases how to avoid this issue through explicit type checking or by using the `parseInt()` function to ensure numerical operation.

This simple example highlights the importance of understanding JavaScript's type coercion rules to avoid subtle and hard-to-debug errors.