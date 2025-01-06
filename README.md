# Uncommon JavaScript Error: TypeError when accessing length of undefined

This repository demonstrates a common yet easily overlooked JavaScript error: a TypeError that occurs when attempting to access the `length` property of an undefined variable.  The error arises from not properly handling cases where a variable might hold an unexpected value, such as `undefined`, before accessing its properties.

## The Bug

The `bug.js` file contains a function that attempts to determine the length of an input. It handles `null` gracefully but fails to handle the case where the input is `undefined`.

## The Solution

The `bugSolution.js` file provides a corrected version of the function.  It employs a simple check to ensure that the input is defined and has a `length` property before proceeding.