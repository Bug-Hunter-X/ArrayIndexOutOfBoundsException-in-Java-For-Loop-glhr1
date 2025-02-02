# ArrayIndexOutOfBoundsException in Java
This repository demonstrates a common Java error: the ArrayIndexOutOfBoundsException.  The `bug.java` file contains code that attempts to access an array index beyond its bounds. The `bugSolution.java` file shows the corrected code.

**Error:** The error arises from an off-by-one error in the for loop's condition. It iterates one time too many.

**Solution:** To avoid the error, the loop condition should be changed to `<` instead of `<=` to prevent access to an invalid array index.