

# Debugging  

## What is Code Debugging? 

** Code Debugging** is searching for errors in programming code.
Programming code might contain different types of errors. Many of these errors are difficult to diagnose.
Sometimes when programming code contains errors,  there are no error messages, and you will get no indications where to search for errors. 
  
## What is the Order of Execution?
Order of execution in *JavaScript* is dependent on the following components working together to pass and order information.
* The Callstack
* The Event Loop
* The Task Queue
* WebAPIs/External Resources




## Execution Context

What happens inside the execution context is two things basically: 
* The first is parsing the code line by line.
* The second is storing the variables and functions into the memory. 

#### It has two types:

1. Global Execution Context
2. Local Execution Context


 ![] (https://miro.medium.com/max/875/1*78luWh7gZV3c-99_eLpRWg.png)


1. **Global Execution Context** is the first thing that is created when you write JavaScript code.




![](https://miro.medium.com/max/875/1*CuL8xsqLb1GhpuHgmDKk0A.png)



2. **Local Execution Context** is created when you call a function.


![]( https://miro.medium.com/max/875/1*e-A-jDYmBTIfN2ADj13iaw.png)


## Execution Stack / Call Stack

*Javascript* can only run one thing at one time in the browser, so it queues the other action, events, functions in what is called the **execution stack**.

Whenever a script loads in the browser, the first element in the stack is the global execution context. 

However, when a function executes, an execution context is created and virtually placed on top of the global execution context. Once a function has finished executing, it gets popped off of the execution stack and returning control to the context below it.


![](https://miro.medium.com/max/875/1*lcTk7Ev0gp_H3Krup6G1EA.png)

## Understanding SCOPE in JS

*JavaScript* has a function scope. Each function creates a new scope. Scope determines the *visibility* of these variables.

Variables defined inside a function are not  *visible*from outside the function.


### Many types of errors in JavaScript:

* `Error`
* `EvalError`
* `InternalError`
* `RangeError`
* `ReferenceError`
* `SyntaxError`
* `TypeError`
* `URIError`





[For more information to error handling in JS 🙂](https://www.valentinog.com/blog/error/)



&copy; 2021