# Uncommon Assembly Errors

This repository demonstrates two uncommon but potentially serious errors that can occur in x86 assembly code:

1. **Memory Access Violations:** Caused by improper index register handling leading to out-of-bounds memory access.
2. **Stack Corruption:** Resulting from exceptions or premature returns before proper stack cleanup.

The `bug.asm` file shows examples of these errors. `bugSolution.asm` provides corrected versions demonstrating proper memory validation and stack management.  These examples highlight the importance of meticulous attention to detail in low-level programming.