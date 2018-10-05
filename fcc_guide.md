---
title: Multiple Identical Options in Switch Statements
---
## Multiple Identical Options in Switch Statements

### Problem Explanation

_If the break statement is omitted from a switch statement's case, the following case statement(s) are executed until a break is encountered. If you have multiple inputs with the same output, you can represent them in a switch statement like this:_
```javascript
switch(val) {
  case 1:
  case 2:
  case 3:
    result = "1, 2, or 3";
    break;
  case 4:
    result = "4 alone";
}
```

_Cases for 1, 2, and 3 will all produce the same result._

_Write a switch statement to set answer for the following ranges:_
`1-3`- "Low"  
`4-6`- "Mid"  
`7-9`- "High"

_Note:
You will need to have a case statement for each number in the range._

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
Since you already has. 

### Resources
- ["Switch: Methods for multi-criteria case" - *MDN Javascript Reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTYzNTA2NDQxNSwtMTE1MDEzMzI2NywxNT
EzODQ2MjA0LC0yMTQ2NzY0NDQ3LC0yNDA2MDcwNTUsMjEzNTYw
MTYyNCw4MTUyMzY5NTgsODIwODE1Mjg3LC0xMTU2NDMyNjI2LC
01OTg5MjU0MDYsLTk5MjM0NjI5NywtMTM2NTAwNzc1NSwzNTUx
NDMwNDcsLTEyNTM4ODIzNzgsLTE0NDQwODQyNDQsLTEwOTIwMT
Y2MzUsMjkxNDcwMTgsLTE5MzU0MTYyMzAsLTE3MDM0OTE0NjUs
LTEzMDcxNzk0NjVdfQ==
-->