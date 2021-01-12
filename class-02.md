# Text


## Tags = Markup
 1. Structural
 1. Semantic

## Structural Tags
1. Headings '<h1>' through '<h6>'
1. Paragraphs '<p>'
1. Bold '<b>'
1. Italic '<i>'
1. Superscript '<sup>'
1. Subscript '<sub>'
## Empty elements only use a closing where you want event to occur
1. Horizontal Rule '<hr />'
1. Line Break '<br />

## Semantic Tags
1. Bold '<strong>'
1. Italic '<em>'
1. Block Quote '<blockquote>'
1. Short Quote '<q>'
1. Abbreviations and Acrynyms '<abbr>'
1. Cite '<cite>'
1. Definition '<dfn>'
1. Address '<address>'
1. Show changes in content with '<ins>' and '<del>'
1. Strike Through '<s>' 


# Using CSS to Design Your Page
## CSS?

### While HTML is the *Bones* of your structure CSS or Cascading Style Sheets is the fashionable interior designer.



### CSS allows the user to control HTML elemets as if they were in their own box. Basically, if my wife tells me to paint the living room walls I don't go through and paint over everything hanging on them.  Furniture must be moved and pictures taken down so only the defined space of *the wall* gets painted.



## How does CSS do this?

### CSS uses two things a **Selector** and a **Declaration**. Selector indicates what the rule applies to and declaration says what to do. Example:

```css
p {font-family: VictorsAwesomeFont;}
```
### This would indicate everything in the "p" element should be displayed in VictorsAwesomeFont.  


### It doesn't just work with fonts.  It can control every element of your HTML in one form or another.  


## Basic Javascript

### Javascript uses scripts.  Each script is broken down in to individual steps called statements.

### Scripts use variables to store temporary bits of information

### variables must first be declared before they can be used.  
'var randomname;'

### After a variable is declared it can then be assigned a value.
'randomname = 5;'

### Three types of variables: numbers, strings and booleans (true or false)

## Variable's Have Rules
1. Names must start with a letter, $ or_
1. No dash - or . can be in the name
1. No keywords or reserved words
1. Variables are case sensitive
1. Use names that describe variable
1. If Variable is made of more than one word use caps to start second word ie. randomName

## Arrays store a list of values. These values are accessed as if they are in an ordered list.  This list starts at "0" -ZERO dont forget 0 or 1-1=0.  Ok that should remind me.   

## Expressions
### JavaScript uses expressions.  These are broken down to assigning a variable and assigning two or more values to return a single value.


### Expressions use Operators to assign value. These are Operators:


`+` Adds

`-` Subtracts

`/` Divides

`*` Multiplies

`++` Adds One to the Current Number

`--` Subtracts One From the Current Number

`%` Divides Two Values and Returns the Remainder


## Functions
### Functions allow you to take a group of statments and lump them together to be used in multiple locations.  


# Loops


## Operators are?
### Operators evaluate situations comparing values in a way defined by the operator. These include:
`==` Equal To

`!=` Not Equal To 

`===` Strict Equal To

`!==` Strict Not Equal To

`>` Greater Than

`<` Less Than

`>=` Greater Than or Equal To

`<=` Less Than or Equal To

## Logical Operators?
### Operators typically ask a single question with an answer of **True** or **False**.  This can is simple but what if you need to compare more than one item? That is the work of Logical Operators. 


### `&&` `||` and `!` are all Logical Operators allowing you to compare two objects.

`&&` Logical And

`||` Logical Or

`!`  Logical Not

## Loops?
### Loops are just that, a series of instructions that will continue for a predetermined amount of cycles or until a condition is met.

### Loops have 3 parts: Initialization, Conndition and Update. They begin by setting a variable which is usually zero.  Then comes the condition which tells the loop how long to run and/or when to stop.  The update contiues the cycle until the condition is met.  


