---
title: Write Arrow Functions with Parameters
---
## Write Arrow Functions with Parameters

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
Here is a [cool resource about anonymous functions in JavaScript](http://helephant.com/2008/08/23/javascript-anonymous-functions/), in case you are still wondering what they are, and their role.

Now, you are tasked at putting parameters inside arrow functions. 

## Hint 1:

Get rid of the `function` keyword. Put the arrow operator.

## Hint 2:

Make sure you changed the `var` to a `const`.

## Spoiler Warning - Solution Ahead!

## Solution:

```javascript
const myConcat = (arr1, arr2) => {
  "use strict";
  return arr1.concat(arr2);
};
// test your code
console.log(myConcat([1, 2], [3, 4, 5]));
```
## Alternative code solution:
```javascript
const magic = () => new Date ();
```
- [Run code at repl.it](https://repl.it/@AdrianSkar/ES6-Use-arrow-functions)

Remember that _"When there is no function body, and only a return value, arrow function syntax allows you to omit the keyword `return` as well as the brackets surrounding the code."_


### Resources
- ["Arrow functions" - *MDN Javascript reference*](http://helephant.com/2008/08/23/javascript-anonymous-functions)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMDgzMTE4NiwtOTQ4Nzc0NTgwLC04MT
k1OTgwODUsMjI5NzM0NjcwLC0xMTIzMTkxODYsMTk3MzQ3ODE1
NywtMTg1NDg1OTI1Myw1MTQ2MzE0MDksLTE3NDg2Nzk5MjMsMT
AxOTM4MjkyNSwtOTg5ODE5NjQ3LC0xNTMxMTA4MzI5LC0xMTE4
OTc5ODUyLDE0NjY3MDE1NzQsMTIyMTU4OTY2LDEyNzIwNDEwMj
QsMTMwNjkxODM0NSw2MDY3Mzc3NTMsODU4MTM4MDAsMTAxMTg4
MTE5NV19
-->