[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=4663710&assignment_repo_type=AssignmentRepo)
# Autograding Example: C++
This example project is written in C++, and tested with make and [Catch2](https://github.com/catchorg/Catch2).

### The assignment
The tests are failing right now because of a bad base case in the factorial function. Correcting the base case will fix the tests.

### Setup command
N/A

### Run command
`make clean test`

### Notes
- `g++` can be used to compile and link C++ applications for use with existing test harnesses or other C++ testing frameworks.
- If students push `a.out` files, the autograder may attempt to run that version instead of a newly compiled binary. If this happens, and your student isn't on Linux, the script will crash. To fix this issue, it's recommended to clean before building.
