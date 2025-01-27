# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java programming error: the `ArrayIndexOutOfBoundsException`.  The code attempts to access an element beyond the valid index range of an array, leading to a runtime exception. The solution shows how to correct the code to prevent this error.

## Bug Description:
The bug lies in the loop's termination condition.  The loop iterates one time too many resulting in an attempt to access index 5 in an array with only 5 elements (indices 0-4).