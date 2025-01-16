# Java ArrayIndexOutOfBoundsException Example
This repository contains a simple Java program that demonstrates a common ArrayIndexOutOfBoundsException. The bug is in the for loop's condition, causing an attempt to access an element beyond the array's bounds. The solution provides a corrected version.

## Bug
The `bug.java` file shows the erroneous code.  The loop condition `i <= arr.length` should be `i < arr.length` to prevent the out-of-bounds access.

## Solution
The `bugSolution.java` file provides the corrected code with the corrected for loop condition.