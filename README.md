# JavaScript Function Bug: Unexpected NaN

This repository demonstrates a common, yet subtle, bug in JavaScript functions related to handling null and undefined values. The `foo` function is designed to return null if either input is null; however, it unexpectedly returns NaN (Not a Number) when an undefined value is passed.

The goal is to enhance the function to correctly handle both null and undefined inputs, consistently returning null in such cases.  The solution provided in `bugSolution.js` addresses this issue.

## How to reproduce the bug

Clone the repository and run `bug.js`. Observe the unexpected NaN output when undefined values are passed to the function.

## Solution

The solution is in `bugSolution.js`. It explicitly checks for both null and undefined values, ensuring a consistent return of null in those scenarios.