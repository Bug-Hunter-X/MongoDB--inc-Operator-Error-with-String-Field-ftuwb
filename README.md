# MongoDB $inc Operator Error with String Field

This repository demonstrates an error that can occur when using the `$inc` operator in MongoDB with a field that is not of a numeric type (e.g., a string).  The `$inc` operator is only designed to increment numeric values. Attempting to use it with a string results in an error.

The `bug.js` file shows the incorrect usage. The `bugSolution.js` demonstrates how to correctly handle this situation, either by converting the field to a number or by using a different approach depending on the desired behavior.
