# Unexpected behavior with null or undefined arguments

This repository demonstrates a common issue in JavaScript where unexpected behavior can occur when null or undefined values are passed as arguments to a function.

## Description
The `foo` function in `bug.js` has a conditional check for null or undefined values as arguments. However, there might be cases where the function continues execution, even after returning early or not handling null values properly.

## Solution
The `bugSolution.js` file provides an updated version of the `foo` function that explicitly handles null and undefined values, ensuring that the function behaves as intended.

## How to reproduce the bug
1. Clone this repository.
2. Open `bug.js` and examine the code.
3. Run the code with various inputs including `null` and `undefined` values for `a` and `b`.
4. Observe the output and compare with the expected outcome.

## How to use the solution
1. Open `bugSolution.js` and observe how the issues are fixed.
2. Run the code with various inputs including `null` and `undefined` values for `a` and `b`.
3. Verify the solution correctly handles null and undefined arguments.
