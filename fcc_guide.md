---
title: Use Destructuring Assignment with the Rest Operator to Reassign Array Elements
---
## Use Destructuring Assignment with the Rest Operator to Reassign Array Elements

Remember that the rest operator allows for variable numbers of arguments. In this challenge, you have to get rid of the first two elements of an array.

## Hint 1: 

Assign the first two elements to two random variables.

## Hint 2:

Set the remaining part of the array to `...arr`.

---
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
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [a, b, ...arr] = list; 
  // change code above this line
  return arr;
}
```
## Solution 2:

You can also exclude the first two elements of the `arr` array using `,,`.

```javascript
function removeFirstTwo(list) {
  "use strict";
  // change code below this line
  const [,,...arr] = list; // change this
  // change code above this line
  return arr;
}
```

### Resources

- ["Destructuring assignment" - *MDN JavaScript reference*]([https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment))


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNTkwNDYwMTUsLTc4NDI2NDEzNiwtMz
k2MzEwNjc4LDE5NDcwMTk1MzcsMTYxNTk1MjEwMSwyMTE3MTc3
OTA4LC0xMjAzMTUxMjk5LC05NDg3NzQ1ODAsLTgxOTU5ODA4NS
wyMjk3MzQ2NzAsLTExMjMxOTE4NiwxOTczNDc4MTU3LC0xODU0
ODU5MjUzLDUxNDYzMTQwOSwtMTc0ODY3OTkyMywxMDE5MzgyOT
I1LC05ODk4MTk2NDcsLTE1MzExMDgzMjksLTExMTg5Nzk4NTIs
MTQ2NjcwMTU3NF19
-->