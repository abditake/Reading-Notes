# [Class 09: - Error Handling & Debugging](/README.md)

- ## JavaScript book, Ch. 10, “Error Handling & Debugging”(pg.456-492)
<hr>


# Error Handling & Debugging
- ## `Execution context`: every statement has 3 execution contexts
```
1. global context

2. function context

3. eval context

```

- ## `variable scope`: also corresponds with global context and function context. A variable that is within a function is local not global. A variable that is outside the function is global. 

- ## `stacking`: when a statement needs data from another function it stacks the new function on top of the current task.

- ## `Exception`: points in your code that the interpreter stops and looks for exception-handling code. 

- ## `debugging`: is the process of finding errors in your code and fixing them.

## JavaScript has 7 different types of errors. Each Creates its own object, which can tell you its line number and gives a description of the error. 

## you can use try, catch, finally statements in areas areas in your code you're expecting an error