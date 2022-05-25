# Debugging

[Home](../index.md)

## JavaScript and JQuery

### Chapter 10: Error Handling and Debugging

No one writes perfect code the first time. Even the most skilled developer makes mistakes once in a while. Thankfully, there are numerous tools at a developers disposal when it comes to debugging their code.

#### The Stack

JavaScript runs one line of code at a time interpreting your code in real time. Whenever one line refers to another line before it can be fully executed, JavaScript saves that one into the stack so that it can return to it after executing the referred to step.

#### Execution Context and Hoisting

Everytime JavaScript enters a new execution context it follows two big picture steps.

1. Prepare - Variables (keyword var only), Function, and Arguments and created
2. Execute - Execute code in the order it is written.

Within each execution context are variables, functions, and arguments. Inner levels can access the variables and functions of the outer variables but the outer levels cannot acces the inner levels. That is becuase they are not created until the inner levels are initiated and once the execution context has completed it releases all of it's variables back to memory to make space for any new content and improve efficiency of calls to the Cache or Random Access Memory.

#### Errors

When JavaScript in encounters an error it looks for error handling code known as an exception handler from inner levels of context all the way to global scope until it finds directions for what to do with the error, otherwise it throws an error and the code terminates.

#### Eror Objects

When an Error Object is created it contains the following for attributes.

| Property | Description |
| --- | --- |
| name | type of execution |
| message | description |
| fileNumber | Name of the JavaScript file |
| lineNumber | Line number of error |

There are seven types of JavaScript errors you may encounter.

| Object | Description |
| --- | --- |
| Error | Generic error - the other errors are all based upon this error |
| SyntaxError | Syntax has not been followed |
| ReferenceError | Tried to reference a variable that is not declared/within scope |
| TypeError | An unexpected data type that cannot be coerced |
| RangeError | Numbers not in acceptable range |
| URIError | encodeURI(), decord URI(), and similar methods used incorrectly |
| EvalError | eval() function used incorrectly |

#### Breakpoints and Stepping through Code

Breakpoint allow you to pause the execution of code at a certain point so you can check the state of your variables to see if they are the values they should be. You can then step line by line and watch as all your variables are update. You can also add a conditional breakpoint so that the execution will stop only if the described argument evaluates to true! Lastly you can insert the `debugger` keyword directly into your JavaScript which will automatically stop the execution if the developer tab is open in the browser.

#### Handling Exceptions

If you know your code might fail, hopefully from areas outside of your control (eg userinput, or server connectivity). Use the try keyword to encapsulate code that might encounter an error. Use the catch keyword to encapsulate code that explains what to do if you encounter this error. It takes has one optional paramater that represents the error being thrown. Use the finally clause to execute code that will execute whether or not the try block of code executes successfully. If you know your code might result in an error you can throw your own errors before the system does. You would use the following syntax to do so `throw new Error('message');`

## Things I want to know more about

- The use of JSON and it's applications.
- Implementations of the `try catch finally` code sequence. I just want practice with it.
- How errors are generated when interacting with servers.
