# MongoDB $inc Operator Error with Non-numeric Value
This example demonstrates an error that occurs when using the `$inc` operator in MongoDB with a non-numeric value. The `$inc` operator is used to increment or decrement a numeric field. If a non-numeric value is provided, an error will be thrown.

## Bug
The `bug.js` file contains code that attempts to increment a field with a string value, leading to a MongoDB error.

## Solution
The `bugSolution.js` file provides a corrected version of the code. It ensures that the field to be incremented is a numeric value before using `$inc` operator.