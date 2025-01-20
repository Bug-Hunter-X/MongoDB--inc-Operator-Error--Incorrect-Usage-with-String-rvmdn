# MongoDB $inc Operator Error: Incorrect Usage with String

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment a numerical field in a document. However, using a string value instead of a number will lead to an unexpected behavior.

## Bug
The bug lies in the incorrect usage of the `$inc` operator. The code attempts to increment the `counter` field by '1', which is a string. This results in the `counter` field not being incremented correctly.

## Solution
The solution involves passing a numerical value to the `$inc` operator instead of a string. The correct code should increment the `counter` field by 1 (a number).