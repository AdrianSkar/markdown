---
title: Use Destructuring Assignment with the Rest Operator to Reassign Array Elements
---
## Use Destructuring Assignment with the Rest Operator to Reassign Array Elements

Remember that the rest operator allows for variable numbers of arguments. In this challenge, you have to get rid of the first two elements of an array.

## Hint 1: 

Assign the first two elements to two random variables.

## Hint 2:

Set the remaining part of the array to `...arr`.

## Hint 3:

Use destructuring to create the `arr` variable:

```javascript
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [arr] = list; // change this
  // change code above this line
  return arr;
}
```

## Hint 4:

Spread the `list` parameter values into `arr`.

```javascript
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [...arr] = list; // change this
  // change code above this line
  return arr;
}
```


## Spoiler Alert - Solution Ahead!
You can use random variables to omit the first two values:

```javascript
const source = [1,2,3,4,5,6,7,8,9,10];
function removeFirstTwo(list) {
"use strict";
  // change code below this line
  const source = [1,2,3,4,5,6,7,8,9,10];
  const [a, b, ...arr] = list; 
  // change code above this line
  return arr;
}
const arr = removeFirstTwo(source);
console.log(arr); // should be [3,4,5,6,7,8,9,10]
console.log(source); // should be [1,2,3,4,5,6,7,8,9,10];
```
## Solution 2:

You can also exclude the first two elements of the `arr` array using `,,`.

```javascript
const source = [1,2,3,4,5,6,7,8,9,10];
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [,,...arr] = list; // change this
  // change code above this line
  return arr;
}
const arr = removeFirstTwo(source);
console.log(arr); // should be [3,4,5,6,7,8,9,10]
console.log(source); // should be [1,2,3,4,5,6,7,8,9,10];
```

### Resources

- ["Destructuring assignment" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NjY3NjAyNDYsLTI5MTU4MzE1OCwtMT
A1OTA0NjAxNSwtNzg0MjY0MTM2LC0zOTYzMTA2NzgsMTk0NzAx
OTUzNywxNjE1OTUyMTAxLDIxMTcxNzc5MDgsLTEyMDMxNTEyOT
ksLTk0ODc3NDU4MCwtODE5NTk4MDg1LDIyOTczNDY3MCwtMTEy
MzE5MTg2LDE5NzM0NzgxNTcsLTE4NTQ4NTkyNTMsNTE0NjMxND
A5LC0xNzQ4Njc5OTIzLDEwMTkzODI5MjUsLTk4OTgxOTY0Nywt
MTUzMTEwODMyOV19
-->