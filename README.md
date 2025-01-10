# Handling Unexpected Null Values in JavaScript Function Arguments

This repository demonstrates a common yet often overlooked error in JavaScript: the improper handling of null values passed as function arguments.

## The Problem

Many JavaScript functions implicitly assume their input arguments will have certain values.  When a null or undefined value is passed unexpectedly, it can lead to errors like `TypeError: Cannot read properties of null (reading '... ')` or unexpected behavior. This bug showcases such a scenario and provides a solution.

## The Bug (`bug.js`)

The `bug.js` file contains a function that is vulnerable to null values.  Without proper handling, passing null values causes a runtime error.

## The Solution (`bugSolution.js`)

The `bugSolution.js` file demonstrates how to effectively handle potential null values. By adding explicit checks for null values at the start of the function, we prevent the runtime error and provide more robust behavior.

## How to Run

1. Clone the repository.
2. Open the `bug.js` and `bugSolution.js` files.
3. Execute the code (e.g., using Node.js).  Observe the difference in behavior when null values are passed as arguments.