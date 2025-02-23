# Null Pointer Dereference Bug in C++

This repository demonstrates a common but dangerous error in C++: dereferencing a null pointer.  Dereferencing a null pointer results in undefined behavior, typically causing a segmentation fault or crash. The example shows how this can happen and how to prevent it.

## Bug Description
The `bug.cpp` file contains code that attempts to dereference a null pointer.  This leads to a runtime error.

## Solution
The `bugSolution.cpp` file provides a corrected version of the code. The solution involves checking if the pointer is null before dereferencing it, preventing the runtime error.