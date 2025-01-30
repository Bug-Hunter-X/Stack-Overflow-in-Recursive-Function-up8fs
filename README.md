# Stack Overflow Bug in Hack

This repository demonstrates a common error in recursive functions written in Hack: stack overflow. The `foo` function calculates the factorial of a given integer recursively.  However, for large inputs, the numerous recursive calls exceed the available stack space, resulting in a stack overflow error.

The `bug.hack` file contains the buggy code.  The solution, which avoids stack overflow by using iteration, is presented in `bugSolution.hack`.