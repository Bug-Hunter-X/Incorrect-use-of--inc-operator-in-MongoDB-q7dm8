# Incorrect use of $inc operator in MongoDB
This example demonstrates an incorrect use of the `$inc` operator in a MongoDB update operation, leading to an error.
The `$inc` operator is used to increment a numeric field by a specified value. Attempting to increment a field with a non-numeric value will result in an error. 

## Bug
The provided code uses the `$inc` operator with a string value ('abc') instead of a numeric value. This results in an error when executed.

## Solution
The solution involves providing a numeric value to the `$inc` operator, allowing the field to be correctly incremented.