# Dangling Pointer Bug in C

This repository demonstrates a common C programming error: using a dangling pointer.  After `free(ptr)`, the memory pointed to by `ptr` is no longer valid.  Attempting to write to it results in undefined behavior, which can cause crashes, unexpected outputs, or seemingly random program failures.  The solution shows how to properly handle memory allocation and deallocation to prevent this issue. 

## How to Reproduce

1. Compile `bug.c`.
2. Run the compiled executable.  Behavior will be unpredictable but likely to crash or cause unexpected results.

## How to Fix

Refer to `bugSolution.c` for a corrected version.