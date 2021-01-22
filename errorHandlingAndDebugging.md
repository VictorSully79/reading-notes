# Error Handling & Debugging

### The order of exection in Javascript is important to understand and if code is not written properly it can lead to errors.

### JS uses 'Execution Contexts of differant types.

- Global 
- Function
- Eval

### The contexts correlate to the 'Variable Scope

- Global Scope
- Function-Level Scope

### JS interpreters process one line at a time, stacking the function needs on top of the current task. The concept of 'Hoisting' is a term used to describe how JS takes all of the variables and functions and 'hoists' them on top of the execution context.

### The code happens in two phases.  "Prepare" and "Execute".  First the scope is created along with variables, functions and arguments.  Then the "Execute" happens where those variable values are assigned to run the code and execute statements.


## Scope

### JS is said to have "lexical scope". Each execution contains the variables object plus the variables object for each parent execution context.


### If a variable is not found in the current context it JS can look for it further up the "stack" but it can slow down performance. 

## Errors

### If an error is generated JS calls it an exception. It then looks for an "error handling code" 

## Error Objects

### Error objects help in finding mistakes that were made. An error object has:

- name (type of error)
- message (description)
- fileNumber (name of the JS file)
- lineNumber (line number of error)

### Type of Objets

- Error (generic)
- SyntaxError (syntax has not been followed)
- ReferenceError (Tried to reference a variable that is not declare/within the scope)
- TypeError (An unexpected data type that cannot be coerced)
- RangeError (Numbers not in acceptable range)
- URIError ()encodeURI90, decodeURI9(), and similar methods used incorrectly.