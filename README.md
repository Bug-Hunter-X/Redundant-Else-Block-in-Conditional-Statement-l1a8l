# Redundant Else Block in Conditional Statement

This repository demonstrates a common JavaScript coding issue: using an explicit `else` block when the conditional already implies a return value.  The `else` block is redundant and can be simplified.

**Bug:**
The `foo` function unnecessarily uses an `else` block when the `if` condition already returns a value. This increases code complexity without adding any functionality.

**Solution:**
The solution simplifies the function by removing the redundant `else` block. The function now directly returns the result of the comparison.