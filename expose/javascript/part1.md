# Part 1

### Question 1:
Line 9 print: `values added:  20`

### Question 2:
Line 13 print: `final result:  20`

### Question 3:
Line 9 print: `values added:  20`

### Question 4:
The code return an error that `ReferenceError: result is not defined`. The reason is `result` is defined in `if else` statement and the `result` is defined as `lat`. `lat` can only be used within the function and it cannot by used outside `if else` statement.

### Question 5:
The code return an error that `Uncaught TypeError TypeError: Assignment to constant variable` which means `result` is a `const` type that is constant and cannot be re-assign values. Thus, it will cause error and exited with code 1. The Line 9 will not print anything.

### Question 6:
The code will return an error and the reason is same as Question 5. The value of `result` cannot be changed since it is a `const` type. The code exited with this error and Line 13 will not print anything.