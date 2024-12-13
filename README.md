# PHP: Inefficient `count()` in `for` loop

This repository demonstrates a common, yet easily avoidable, inefficiency in PHP `for` loops. The example uses `count()` within the loop condition, leading to unnecessary function calls and reduced performance.  The solution provides a more efficient approach.

**Bug:** The `bug.php` file contains a `for` loop that repeatedly calls `count()`. This is redundant because the loop counter already tracks the array's index.

**Solution:**  The `bugSolution.php` file shows the corrected code, using a more efficient iteration method.