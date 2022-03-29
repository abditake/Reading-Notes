# [Class 11: Understanding the JavaScript Call Stack](/README.md)

- ## Understanding the JavaScript Call Stack
- ## JavaScript error messages

<hr>

# Understanding the JavaScript Call Stack

- ## What is a ‘call’?
        - function invocation
- ## How many ‘calls’ can happen at once?
        - it's done one at a time.

- ## What does LIFO mean?
        -Last in first out
- ## Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

    ```
                                 _________________
                push  --------> |                 |  ---->  pop
                                |                 |<------Top
                                |_________________|
                                |                 |
                                |                 |
                                |_________________|
                                |                 |
                                |                 |
                                |_________________|
                                |                 |
                                |                 |
                                |_________________|
                                |                 | 
                                |                 |
                                |_________________|



    ```

- ## What causes a Stack Overflow?
            - when there is a recursive function without an exit point.


<hr>

# JavaScript error messages

- ## What is a ‘refrence error’?
            - is an error when an object that hasn't been introduced(initialized) or doesn't exist is being referenced.

- ## What is a ‘syntax error’?
            - error with how you are writing the code for the computer to understand. when something you wrote cannot be parsed.

- ## What is a ‘range error’?
            - setting an object to an invalid length 
- ## What is a ‘type error’?
            - when the type of data you are using is incompatible with how you are accessing it. 
- ## What is a breakpoint?
            - breakpoint is a certain place in a code where you will stop executing code.

- ## What does the word ‘debugger’ do in your code?
            - when your code hits a certain code block that isn't work it breaks you out of your code.
