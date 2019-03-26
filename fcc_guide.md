---
title: Use Destructuring Assignment with the Rest Operator to Reassign Array Elements
---
## Use Destructuring Assignment with the Rest Operator to Reassign Array Elements
<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
Remember that the rest operator allows for variable numbers of arguments. In this challenge, you have to get rid of the first two elements of an array.

## Hint 1: 

Assign the first two elements to two random variables .

## Hint 2:

Set the remaining part of the array to `...arr`.

---
## Hint 1

Use destructuring to create the `arr` variable.

```javascript
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [arr] = list; // change this
  // change code above this line
  return arr;
}
```

## Hint 2 

Spread the `list` parameter into `arr`.

```javascript
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [...arr] = list; // change this
  // change code above this line
  return arr;
}
```

## Hint 3 

Exclude the first two elements of the `arr` array with `,,`.

```javascript
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [,,...arr] = list; // change this
  // change code above this line
  return arr;
}
```

## Spoiler Alert - Solution Ahead!

```javascript
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [a, b, ...arr] = list; 
  // change code above this line
  return arr;
}
```

### Resources

- ["Array.prototype.map()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
- ["Array.prototype.filter()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- ["Array.prototype.reduce()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
- ["Number.isInteger()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isInteger)
- ["Math.pow()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/pow)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTYxNzg0Nzg2MSwtNzg0MjY0MTM2LC0zOT
YzMTA2NzgsMTk0NzAxOTUzNywxNjE1OTUyMTAxLDIxMTcxNzc5
MDgsLTEyMDMxNTEyOTksLTk0ODc3NDU4MCwtODE5NTk4MDg1LD
IyOTczNDY3MCwtMTEyMzE5MTg2LDE5NzM0NzgxNTcsLTE4NTQ4
NTkyNTMsNTE0NjMxNDA5LC0xNzQ4Njc5OTIzLDEwMTkzODI5Mj
UsLTk4OTgxOTY0NywtMTUzMTEwODMyOSwtMTExODk3OTg1Miwx
NDY2NzAxNTc0XX0=
-->