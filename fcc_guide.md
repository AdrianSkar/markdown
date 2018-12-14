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
As long as you got rid of the `var` keyword, you’re good.

## Alternative code solution:
```javascript
const magic = () => new Date ();
```
- [Run code at repl.it](https://repl.it/@AdrianSkar/ES6-Use-arrow-functions)

Remember that _"When there is no function body, and only a return value, arrow function syntax allows you to omit the keyword `return` as well as the brackets surrounding the code."_


### Resources
- ["Arrow functions" - *MDN Javascript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTUzOTYzNDEyNiwtOTQ4Nzc0NTgwLC04MT
k1OTgwODUsMjI5NzM0NjcwLC0xMTIzMTkxODYsMTk3MzQ3ODE1
NywtMTg1NDg1OTI1Myw1MTQ2MzE0MDksLTE3NDg2Nzk5MjMsMT
AxOTM4MjkyNSwtOTg5ODE5NjQ3LC0xNTMxMTA4MzI5LC0xMTE4
OTc5ODUyLDE0NjY3MDE1NzQsMTIyMTU4OTY2LDEyNzIwNDEwMj
QsMTMwNjkxODM0NSw2MDY3Mzc3NTMsODU4MTM4MDAsMTAxMTg4
MTE5NV19
-->