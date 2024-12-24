# Ada Array Index Out of Bounds Bug
This repository demonstrates a common error in Ada programming: accessing an array element outside of its defined bounds.  The `bug.ada` file contains the erroneous code, while `bugSolution.ada` provides the corrected version.

**Description:**
The original code iterates through the array using a loop that may exceed the array's boundaries under certain conditions leading to runtime exception. The corrected code demonstrates the proper way to handle array iteration and avoid such errors.

**How to reproduce:**
Compile and run `bug.ada` to observe the runtime error.
Compile and run `bugSolution.ada` to see the correct output.
