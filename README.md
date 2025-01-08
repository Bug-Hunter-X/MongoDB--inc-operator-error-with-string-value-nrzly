# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error occurs when attempting to increment a field with a string value instead of a number. The solution provides the correct implementation.
## Bug
The bug lies in the incorrect usage of the `$inc` operator. It attempts to increment the `age` field by the string value '1', resulting in an error.
## Solution
The solution corrects the problem by passing a numerical value to the `$inc` operator. This ensures the update operation is performed correctly.