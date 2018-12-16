---
title: Write Arrow Functions with Parameters
---
## Write Arrow Functions with Parameters


Now, you are tasked at putting parameters inside arrow functions. 

## Hint 1:

Get rid of the `function` keyword. Put the arrow operator.

## Hint 2:

Make sure you changed the `var` to a `const`.

## Spoiler warning - Solution ahead!

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
- [Emerson, Helen. "Javascript anonymous functions". *Helephant.com*, 23 Aug 08.](http://helephant.com/2008/08/23/javascript-anonymous-functions) Accessed 16 Dec 2018.

<!--stackedit_data:
eyJoaXN0b3J5IjpbMjExNzE3NzkwOCwtMTIwMzE1MTI5OSwtOT
Q4Nzc0NTgwLC04MTk1OTgwODUsMjI5NzM0NjcwLC0xMTIzMTkx
ODYsMTk3MzQ3ODE1NywtMTg1NDg1OTI1Myw1MTQ2MzE0MDksLT
E3NDg2Nzk5MjMsMTAxOTM4MjkyNSwtOTg5ODE5NjQ3LC0xNTMx
MTA4MzI5LC0xMTE4OTc5ODUyLDE0NjY3MDE1NzQsMTIyMTU4OT
Y2LDEyNzIwNDEwMjQsMTMwNjkxODM0NSw2MDY3Mzc3NTMsODU4
MTM4MDBdfQ==
-->