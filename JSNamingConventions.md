# This document will cover the naming conventions for variables, classes, and functions in JavaScript

### Definitions
**camelCase:** capitalizes the first letter of each word excluding the first word and removes spaces between words

**PascalCase:** capitalizes the first letter of each word including the first word and removes spaces between words

**UPPERCASE:** all letters are capitalized and spaces between words are removed

**Note:** Whether or not you use camelCase or PascalCase, all names should begin with a letter and be descriptive of their purpose.
For example, poorly named variable:
```javascript 
var x = 0; //the name x tells us nothing about what this variable does
```
versus a well named variable: 
```javascript
var speedingTickets = 0; //very descriptive
```

### camelCase uses:
* variable names
* function names *excluding constructor functions*

### PascalCase uses:
* constructor functions

### UPPERCASE uses:
* constants
* global variables

### Correct formatting code blocks, functions, loops
* always use 4 spaces when indenting, don't use tab because it creates different amounts of spaces in different programs
* put opening brakets at the end of the first line after one space
* put the closing bracket on its own line without a space
* add a semicolon at the end of function expressions statements like the following
```javascript
var exampleFunction = function() {
    return "this is a function expression, so you must include a semicolon after the bracket";
};
```

* it is not neccessary to add a semicolon at the end of function declarations like the following
```javascript
function myFunc() {
    return "no semicolon neccessary after the bracket";
}
```

### Proper use of spaces
Always put spaces after operators `= + - / *` 
```javascript
if(10 + 9 == 19) {
    console.log("that's a great example");
}
```
always include a space after commas
```javascript
var myArray = ["Chocolate", "Pistachio", "Banana"];
```