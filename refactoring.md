# Concepts of Functional Programming in Javascript
notes taken from the above named article by: TK

## Functional Programming?
### Functionsl Programming is "a style of building the structure and elements of computer programs that treats computation as the avaluation of mathematical functions and avoids changing-state and mutable data"-Wikipedia

## Pure Functions?
- It returns the same result if given the same arguments
- It does not cause any observable side effects

### If a funtions reads external files it is not a pure function because the content can change. The same is true for a random number generator because the outcome can change.  

### In a "Pure Function" you also do not want an observable side effects i.e changing a global variable.  

## Immutability
### Data states that are immutable cannot be changed after creation.
`pure functions + immutable data = referential transparency`

### If a function consistently yields the same result for the same input, it is referntially transparent.  

## First Class Funtions
### The idea of functions as first-class entities is that functions are also treated as values and used as data. These functions can:
- refer to it from constants and variables
- pass it as a parameter to other functions
- return it as result from other functions

### Higher Order Functions
- takes one or mure functions as arguments, or
- returns a function as its result

# Refactoring JavaScript for Performance and Readability (with Examples!)
notes taken from the aboved named article by: Andrew Healey

### Good code lives in the middle ground between speed and comprehension.  

## Strategies for Easier to Read Code
### Strategies:
- Return early from functions
- Cache variables so functions can be read like sentences
- Check for Web APIs before implementing your own functionality
