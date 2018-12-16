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
- [Emerson, Helen. "Javascript anonymous functions". *Helephant.com*, 23 Aug 08.](http://helephant.com/2008/08/23/javascript-anonymous-functions) Accessed 16 Dec 2018.

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEyMDMxNTEyOTksLTk0ODc3NDU4MCwtOD
E5NTk4MDg1LDIyOTczNDY3MCwtMTEyMzE5MTg2LDE5NzM0Nzgx
NTcsLTE4NTQ4NTkyNTMsNTE0NjMxNDA5LC0xNzQ4Njc5OTIzLD
EwMTkzODI5MjUsLTk4OTgxOTY0NywtMTUzMTEwODMyOSwtMTEx
ODk3OTg1MiwxNDY2NzAxNTc0LDEyMjE1ODk2NiwxMjcyMDQxMD
I0LDEzMDY5MTgzNDUsNjA2NzM3NzUzLDg1ODEzODAwLDEwMTE4
ODExOTVdfQ==
-->