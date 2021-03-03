# The Call Stack
- Notes taken from: https://developer.mozilla.org/en-US/docs/Glossary/Call_stack

- The JavaScript Call Stack - What It Is and Why - It's Necessary
by:Charles Freeborn

- JavaScript Error Messages && debugging by: Diogo Spinola

## Call Stack?
### A call stack is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions - what function is currently being run and what functions are called from within that function, etc.

### Since the call stack is single, function(s) execution is done one at a time, from top to bottom.  

### Asynchronous JavaScript:
- callback function
- event loop
- task cue

### Call Stacks function LIFO or Last In First Out.

### Manage function invocation (call): The call stack maintains a record of the position of each stack frame.  It KNOWS the next function to be executed.

## Stack OverFlow = Bad
### Stck overflow's occur when there is a recursive function.  A function that calls itself without an exit point.  

## DeBugging = Good
### First indication something is wrong is the infamous ERROR MESSAGE.

- Reference error- trying to use a variable that is not yet declared
- Syntax error- something likely cannot be parsed due to syntax
- Range error- tried to manipulate an object with some kind of length with an invalid length
- Type error- trying to use or access a property that is incompatible

### `console.log()` is often the easiest way to start debugging.  