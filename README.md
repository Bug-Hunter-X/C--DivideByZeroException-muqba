# C# DivideByZeroException Example

This repository demonstrates a common programming error in C#: division by zero. The `bug.cs` file contains code that will throw a `DivideByZeroException` if executed. The `bugSolution.cs` file provides a solution to handle this exception.

## Bug

The `MyMethod()` function in `bug.cs` attempts to divide an integer by zero, resulting in a runtime exception.

## Solution

The `bugSolution.cs` file shows how to prevent the exception using a simple `if` statement to check if the divisor is zero before performing the division.  More robust solutions may involve using `try-catch` blocks to handle the exception gracefully, particularly in larger applications.