# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating through an array.  The error occurs when the loop index attempts to access an element beyond the array's bounds.  The solution shows how to correct the loop condition to avoid this error.

**Buggy Code:**
The `BuggyArray.java` file contains the code with the off-by-one error.  This code attempts to access index 5 of an array of length 5, leading to an `ArrayIndexOutOfBoundsException`.

**Fixed Code:**
The `FixedArray.java` file provides the corrected code.  The loop condition is modified to prevent accessing indices beyond the array's bounds, ensuring correct array traversal.