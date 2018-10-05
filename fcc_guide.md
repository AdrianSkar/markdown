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
As with the [previous exercise](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/replacing-if-else-chains-with-switch) you are about to change how the function returns the correct value, meaning you don't have to reuse or modify that part of the function but to substitute it.
> _try to solve the problem now_

#### Hint 2
In order to return `true` or `false` you don't need two statements nor use `if` ones. The correct [comparison operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators) is all you need.
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
eyJoaXN0b3J5IjpbOTUzMDI1OTQ0LDE4Mzc1NTIyOTMsLTExNT
AxMzMyNjcsMTUxMzg0NjIwNCwtMjE0Njc2NDQ0NywtMjQwNjA3
MDU1LDIxMzU2MDE2MjQsODE1MjM2OTU4LDgyMDgxNTI4NywtMT
E1NjQzMjYyNiwtNTk4OTI1NDA2LC05OTIzNDYyOTcsLTEzNjUw
MDc3NTUsMzU1MTQzMDQ3LC0xMjUzODgyMzc4LC0xNDQ0MDg0Mj
Q0LC0xMDkyMDE2NjM1LDI5MTQ3MDE4LC0xOTM1NDE2MjMwLC0x
NzAzNDkxNDY1XX0=
-->