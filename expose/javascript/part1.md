1. values added: 20
2. final result: 20
3. `var` doesn’t respect curly braces. For example, declaring `var` result inside the `if` block doesn’t ensure that it only exists inside that block, since `var` variables can be accessed from anywhere in the entire function.
4. values added: 20
5. Unlike `var`, `let` variables cannot be accessed outside the curly braces they were declared in. Since `result` is inside the curly braces of the `if` statement, it cannot be accessed on line 13, causing an error to be returned.
6. The code returns an error because, at line 7, there is an attempt to reassign a value to `result`. However, since `result` is a `const` variable, this results in an error.
7. The code returns an error because, at line 7, there is an attempt to reassign a value to `result`. However, since `result` is a `const` variable, this results in an error.