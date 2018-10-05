
---
title: Multiple Identical Options in Switch Statements
---
## Multiple Identical Options in Switch Statements
<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
<h2>Problem Explanation</h2>

If the break statement is omitted from a switch statement's case, the following case statement(s) are executed until a break is encountered. If you have multiple inputs with the same output, you can represent them in a switch statement like this:
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
## Useful Resources Link
[Mozilla Developer Network - Switch Statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)

Cases for 1, 2, and 3 will all produce the same result.

Write a switch statement to set answer for the following ranges:
<p>1-3 - "Low"</p>
<p>4-6 - "Mid"</p>
<p>7-9 - "High"</p>

Note:
You will need to have a case statement for each number in the range.

Solution Ahead!
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

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQyNjA0MDY2NSwtMTE1MDEzMzI2NywxNT
EzODQ2MjA0LC0yMTQ2NzY0NDQ3LC0yNDA2MDcwNTUsMjEzNTYw
MTYyNCw4MTUyMzY5NTgsODIwODE1Mjg3LC0xMTU2NDMyNjI2LC
01OTg5MjU0MDYsLTk5MjM0NjI5NywtMTM2NTAwNzc1NSwzNTUx
NDMwNDcsLTEyNTM4ODIzNzgsLTE0NDQwODQyNDQsLTEwOTIwMT
Y2MzUsMjkxNDcwMTgsLTE5MzU0MTYyMzAsLTE3MDM0OTE0NjUs
LTEzMDcxNzk0NjVdfQ==
-->