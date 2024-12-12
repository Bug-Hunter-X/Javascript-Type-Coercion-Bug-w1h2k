# Javascript Type Coercion Bug
This repo contains a simple Javascript bug demonstrating type coercion issues. The function `foo` is intended to add two numbers. However, if one of the inputs is a string, Javascript will perform string concatenation instead of numerical addition. This can lead to unexpected results.

## Bug
The `bug.js` file contains the buggy code. When calling `foo(1,"2")` the output is unexpected.

## Solution
The `bugSolution.js` file shows how to fix the bug using explicit type conversion using `parseInt()` to ensure both inputs are numbers before performing addition.