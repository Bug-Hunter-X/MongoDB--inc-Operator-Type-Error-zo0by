# MongoDB $inc Operator Type Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB updates. The `$inc` operator requires a numerical value, but using a string will cause an error.

## Bug
The bug is in the `bug.js` file, where a string value ('1') is incorrectly passed to the `$inc` operator.

## Solution
The solution is in `bugSolution.js`. It shows the correct usage of the `$inc` operator with a numerical value.
