# Lua Stack Overflow in Deep Table Traversal

This repository demonstrates a common error in Lua: stack overflow caused by deep recursion when traversing nested tables.  The `foo` function recursively iterates through a table.  If the table is very deeply nested, the recursion depth exceeds Lua's stack limit, resulting in a stack overflow error.

The solution demonstrates how to prevent this issue by using an iterative approach instead of recursion.