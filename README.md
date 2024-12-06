# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.  The code attempts to populate an array but exceeds the valid index range, causing an `ArrayIndexOutOfBoundsException`. The solution shows how to correct the loop condition to avoid this error.

## Bug
The provided Java code attempts to populate an array but uses an incorrect loop condition. The loop iterates one time too many, leading to an exception.

## Solution
The solution modifies the for loop's termination condition to ensure the loop only iterates within the valid bounds of the array.
