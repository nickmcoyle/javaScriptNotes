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
*constructor functions

### UPPERCASE uses:
*constants
*global variables