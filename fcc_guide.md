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
- [Run code at repl.it](https://repl.it/@AdrianSkar/ES6-Write-arrow-functions-with-params)

Remember that _"When there is no function body, and only a return value, arrow function syntax allows you to omit the keyword `return` as well as the brackets surrounding the code."_


### Resources
- [Emerson, Helen. "Javascript anonymous functions". *Helephant.com*, 23 Aug 08.](http://helephant.com/2008/08/23/javascript-anonymous-functions) Accessed 16 Dec 2018.

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTcwNzEwNjAwNCwyMTE3MTc3OTA4LC0xMj
AzMTUxMjk5LC05NDg3NzQ1ODAsLTgxOTU5ODA4NSwyMjk3MzQ2
NzAsLTExMjMxOTE4NiwxOTczNDc4MTU3LC0xODU0ODU5MjUzLD
UxNDYzMTQwOSwtMTc0ODY3OTkyMywxMDE5MzgyOTI1LC05ODk4
MTk2NDcsLTE1MzExMDgzMjksLTExMTg5Nzk4NTIsMTQ2NjcwMT
U3NCwxMjIxNTg5NjYsMTI3MjA0MTAyNCwxMzA2OTE4MzQ1LDYw
NjczNzc1M119
-->