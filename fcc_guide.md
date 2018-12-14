---
title: Use Arrow Functions to Write Concise Anonymous Functions
---
## Use Arrow Functions to Write Concise Anonymous Functions

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
Again, ES6 is all about making JavaScript more elegant, and for some, more readable. 

Anonymous functions, as stated, can be created when you are sure that the function will not be called by name anywhere else.

## Hint 1:

Get rid of the `function` key word, and plug in this `=>` arrow.

## Hint 2:

Did you get rid of the `var` keyword?

## Spoiler alert - Solution ahead!

## Solution:

```javascript
const magic = () => {
  "use strict";
  return new Date();
};
```
## Alternative code solution:
```javascript
const magic = () => new Date ();
```
[Run code at repl.it](https://repl.it/@AdrianSkar/ES6-Use-arrow-functions)

Remember that _"When there is no function body, and only a return value, arrow function syntax allows you to omit the keyword `return` as well as the brackets surrounding the code."_


### Resources
- ["Object.freeze()" - *MDN Javascript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI4OTg3NDg0NSwtODE5NTk4MDg1LDIyOT
czNDY3MCwtMTEyMzE5MTg2LDE5NzM0NzgxNTcsLTE4NTQ4NTky
NTMsNTE0NjMxNDA5LC0xNzQ4Njc5OTIzLDEwMTkzODI5MjUsLT
k4OTgxOTY0NywtMTUzMTEwODMyOSwtMTExODk3OTg1MiwxNDY2
NzAxNTc0LDEyMjE1ODk2NiwxMjcyMDQxMDI0LDEzMDY5MTgzND
UsNjA2NzM3NzUzLDg1ODEzODAwLDEwMTE4ODExOTUsMTA2NTg3
MzA5N119
-->