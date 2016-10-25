### The Call Stack

Is a stack data structure that stores information about the active subroutines of a computer program. This kind of stack is also known as an execution stack. Although maintenance of the call stack is important for the proper functioning of most software, the details are normally hidden and automatic in high-level programming languages. Many computer instruction sets provide special instructions for manipulating stacks. When a subroutine is called, the location (address) of the instruction at which it can later resume needs to be saved somewhere. Using a stack to save the return address has important advantages over alternative calling conventions. One is that each task has its own stack, and thus the subroutine can be reentrant, that is, can be active simultaneously for different tasks doing different things. Another benefit is that recursion is automatically supported. When a function calls itself recursively, a return address needs to be stored for each activation of the function so that it can later be used to return from the function activation.

### Synchronous Callback

A synchronous callback is invoked before a function returns, that is, while the API receiving the callback remains on the stack.

### Asynchronous Callback

A synchronous callback is invoked before a function returns, that is, while the API receiving the callback remains on the stack. An example might be: list.foreach(callback); when foreach() returns, you would expect that the callback had been invoked on each element.

### Callback Function

A callback function, also known as a higher-order function, is a function that is passed to another function (let’s call this other function “otherFunction”) as a parameter, and the callback function is called (or executed) inside the otherFunction. A callback function is essentially a pattern (an established solution to a common problem), and therefore, the use of a callback function is also known as a callback pattern.

