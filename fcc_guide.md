---
title: Returning Boolean Values from Functions
---
## Returning Boolean Values from Functions

### Problem Explanation

_Fix the function `isLess` to remove the `if/else` statements._
```js
// Fix this code
  if (a < b) {
    return true;
  } else {
    return false;
  }
```

#### Hint 1
As with the previous exercise you are about to c
> _try to solve the problem now_

## Spoiler alert!

**Solution ahead!**

## Code Solution:
```javascript
function sequentialSizes(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
    case 1:
    case 2:
    case 3:
      return "Low";
      break;
    case 4:
    case 5:
    case 6:
      return "Mid";
      break;
    case 7:
    case 8:
    case 9:
      return "High";
      break;
  } 
  // Only change code above this line  
  return answer;  
}
// Change this value to test
sequentialSizes(1);
```

## Alternative code solution:

```javascript
function sequentialSizes(val) {
  var answer = "";
  // Only change code below this line
  switch(val){
    case 1: case 2: case 3:
      answer = "Low";
      break;
    case 4: case 5: case 6:
      answer = "Mid";
      break;
    case 7: case 8: case 9:
      answer = "High";
  }
  // Only change code above this line  
  return answer;  
}
// Change this value to test
sequentialSizes(1);
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Multiple-opts-in-switch).

### Code explanation
Since you already have a variable named `answer` defined and the function returns it, you can just modify its value on each group of case statements to fit the exercise requirements. 

### Resources
- ["Switch: Methods for multi-criteria case" - *MDN Javascript Reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwNzE1MzQxMzgsMTgzNzU1MjI5MywtMT
E1MDEzMzI2NywxNTEzODQ2MjA0LC0yMTQ2NzY0NDQ3LC0yNDA2
MDcwNTUsMjEzNTYwMTYyNCw4MTUyMzY5NTgsODIwODE1Mjg3LC
0xMTU2NDMyNjI2LC01OTg5MjU0MDYsLTk5MjM0NjI5NywtMTM2
NTAwNzc1NSwzNTUxNDMwNDcsLTEyNTM4ODIzNzgsLTE0NDQwOD
QyNDQsLTEwOTIwMTY2MzUsMjkxNDcwMTgsLTE5MzU0MTYyMzAs
LTE3MDM0OTE0NjVdfQ==
-->