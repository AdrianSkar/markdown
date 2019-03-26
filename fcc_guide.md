---
title: Use Destructuring Assignment with the Rest Operator to Reassign Array Elements
---
## Use Destructuring Assignment with the Rest Operator to Reassign Array Elements
<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
Remember that the rest operator allows for variable numbers of arguments. In this challenge, you have to get rid of the first two elements of an array.

## Hint 1: 

Assign the first two elements to two random variables.

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
eyJoaXN0b3J5IjpbMzE2NTAxMTc3LC03ODQyNjQxMzYsLTM5Nj
MxMDY3OCwxOTQ3MDE5NTM3LDE2MTU5NTIxMDEsMjExNzE3Nzkw
OCwtMTIwMzE1MTI5OSwtOTQ4Nzc0NTgwLC04MTk1OTgwODUsMj
I5NzM0NjcwLC0xMTIzMTkxODYsMTk3MzQ3ODE1NywtMTg1NDg1
OTI1Myw1MTQ2MzE0MDksLTE3NDg2Nzk5MjMsMTAxOTM4MjkyNS
wtOTg5ODE5NjQ3LC0xNTMxMTA4MzI5LC0xMTE4OTc5ODUyLDE0
NjY3MDE1NzRdfQ==
-->