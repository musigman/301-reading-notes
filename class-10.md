# Reading Day: 09.17.20
## The Call Stack
A **Call Stack** is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions. It's like the JavaScript interpreter in a web browser.

- When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.

- Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.

- When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.

- If the stack takes up more space than it had assigned to it, it results in a "stack overflow".
 
 ## The 'JavaScript' Call Stack
The call stack is primarily used for function invocation. Since the function(s) execution is done one at a time from top to bottom, this means the call stack is synchronous.

In asynchronous JavaScript, we have a callback function, an event loop and a task queue. The callback function has been pushed to the stack by the event loop.

At the most basic level, a call stack is a data structure that uses the **Last In, First Out** (LIFO) principle to temporarily store and manage function invocation (call).

## LIFO:
This means that the last function that gets pushed into the stack is the first to be popped out when the functions returns.

## Temporary Storage
When a function is invoked, the function, its parameters and variables are pushed into the call stack to form a stack frame, which is a memory location in the stack. The memory is cleared when the function returns as it pops out of the stack.

## The Call
The call stack maintains a record of the position of each stack frame. It knows the next function to be executed, and removes it after function execution. This is what makes code execution in JavaScript synchronous.

## The Cause of Stack Overflow
A stack overflow occurs when there is a recursive function without an exit point. The browser has a maximum stack call that it will accommodate before throwing a stack error.

## Summary
- Calls stacks are single threaded and can only do one thing at a time.
- Code execution is synchronous.
- A function invocation creates a stack frame that occupies a temporary memory.
- It works as a (Last In, First Our data structure)

## Error Messages
I spent two hours tonight debugging my lab. I hope I can retain what I've learned today and use the tools to create break points for code to run.

Tonight I saw error messages and patiently worked to fix them. Some of them were capitalization errors, some were naming conflicts. 

## Reference Errors
These errors happen when you try to use a variable that has not yet declared. Reference errors are a common thing when using *const* and *let*. The time between hoisting and beign declared is referred to as the **TDZ** Temporal Dead Zone. 

## Syntax Errors
Ohhhh... 2 hours of my life tonight! Yes, syntax is important. Knowing when to use Upper case, camel case, when to not use camel case, and correctly referencing the database are key!

## Handling Errors and Summary
This means anything after an error message won't be executed. I have more to consider now with writing code and debugging. The console logs should not be included in final code. The next I submit a lab I will think to remove console logs.


[<== Back to Table of Contents](index.md)