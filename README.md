# Lua Nil Handling Bug

This repository demonstrates a common, yet subtle, bug related to nil handling in Lua functions. The `foo` function is designed to add two numbers, but it unexpectedly returns `nil` if either input is `nil`. This behavior might lead to unexpected results in a larger application, where the programmer might anticipate a default value of 0 or another alternative.

The `bug.lua` file contains the erroneous code, while `bugSolution.lua` provides a corrected version with improved nil handling.