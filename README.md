# MongoDB $inc Operator Usage Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB's `updateOne` method.  The incorrect usage can lead to unexpected results or errors.

## Problem
The `$inc` operator is intended to increment a numeric field.  However, incorrect syntax can lead to unexpected behavior or failure.  The provided example shows the difference between correct and incorrect usage.

## Solution
Ensure that the field name within `$inc` is enclosed in quotes.

## How to reproduce the bug
1. Clone the repository.
2. Create a MongoDB collection with a document containing a numeric field.
3. Run `bug.js` to observe the incorrect behavior.
4. Run `bugSolution.js` to see the corrected version. 

## How to fix the bug
Always enclose the field name in quotes within the `$inc` operator to avoid errors.