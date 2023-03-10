#### What is a ‘call’?

The process of invoking or executing a function. When a function is called, the control is transferred to the function body, and the statements inside the function are executed.

#### How many ‘calls’ can happen at once?

calls to functions are executed synchronously and only one call can happen at a time. 

### What does LIFO mean?

LIFO stands for Last In, First Out. In the context of a call stack, it means that the last function added to the stack will be the first one to be executed. As each function returns, it is removed from the stack, and the previous function in the stack becomes the current one to be executed.

### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

* function4
* function3
* function2
* function1 (currently executing)

### What causes a Stack Overflow?

A stack overflow occurs when the call stack exceeds its maximum size

#### What is a ‘reference error’?

When a code tries to access a variable or function that has not been declared or is not in scope

#### What is a ‘syntax error’?

Occurs when the code violates the rules of the language's syntax, making it impossible for the code to be parsed and executed. 

#### What is a ‘range error’?

a code tries to manipulate a numeric value outside of its valid range

#### What is a ‘type error’?

Type error is when a code tries to perform an operation on a value of a type that is not compatible with the operation. 

#### What is a breakpoint?

A point in the code where the execution of the code can be paused or stopped for debugging purposes. 

#### What does the word ‘debugger’ do in your code?

Debugger is a tool used to help developers find and fix bugs in their code.

[Home](https://shiloh206.github.io/reading-notes)