# MongoDB $inc operator error: String increment value
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB, where a string is provided as an increment value.  The `$inc` operator requires a numerical value to increment a field.

The `bug.js` file contains the incorrect code, while `bugSolution.js` provides the corrected version.

This is a common error for developers new to MongoDB's update operators.