# Ignoring Errors in Go

This repository demonstrates a common error in Go programming: ignoring the error returned by a function.  The `calculate` function demonstrates a scenario where division by zero could occur.  The `main` function shows an example where the error is checked, but the program still proceeds without handling the potential issue, which could lead to unexpected behavior in a larger application.

The `bugSolution.go` file shows the corrected version where the error is handled appropriately.