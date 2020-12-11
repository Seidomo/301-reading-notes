
#  **THE CALL STACK**

A **CALL STACK** is a mechanism for a interpreter like javascript to keep track of its place in a script that calls multiple  function.
its also called execution stack, program stack, control stack.


## THE JAVASCRIPT CALL STACK

In javascript an understanding of the call back will give you clarity to how 
function hierarchy and execution order works and it means its synchronous.
The understanding of the call stack is vital to Asynchronous programming.

## LIFO

```
**LAST IN, FIRST OUT**

```
When we say that the call stack, operates by the data structure principle of Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## WHAT CAUSES A STACK OVER FLOW?

A stack overflow occurs when there is a function that calls itself without an exit point. the browser has a maximum stack call that it can accomodate befor throwing a stack error.

## DEBBUGING

Most developers spend time reading code and trying to debbug.

**TYPES OF ERRORS**

- Reference errors
- Syntax errors
- Range errors
- Type  errors 


Finding erorrs or debugging is mostly done in the console log.












* [Reference](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)
* [Reference](https://en.wikipedia.org/wiki/Call_stack)
* [Reference](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)