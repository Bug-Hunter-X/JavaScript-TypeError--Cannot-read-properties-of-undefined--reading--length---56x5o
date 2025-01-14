# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: `TypeError: Cannot read properties of undefined (reading 'length')`. This error occurs when attempting to access the `length` property of a variable that is either `undefined` or `null`. 

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a solution to fix this problem.  The solution involves explicitly handling the cases where the input is `undefined` or `null` before attempting to access the `length` property.

## How to Reproduce

1. Clone this repository.
2. Navigate to the repository's directory.
3. Run `node bug.js` to see the error.
4. Run `node bugSolution.js` to see the corrected behavior.

## Solution

The solution is to add a check for `undefined` or `null` before accessing the `length` property.  This ensures that the code doesn't throw an error when dealing with unexpected input values.