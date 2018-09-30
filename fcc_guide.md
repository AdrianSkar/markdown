
---
title: Introducing Else If statements
---
## Introducing Else If statements

 Remember to use Read-Search-Ask if you get stuck. Try to pair program and write your own code.

 ### Problem explanation:
```javascript
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }
  
  if (val < 5) {
    return "Smaller than 5";
  }
  
  return "Between 5 and 10";
}

// Change this value to test
testElseIf(7);
```
We'll be modifying the existing code above so that it follows the flow of logic that an **else-if** statement has.

 ### Hint: 1
 ``` javascript
   if (val > 10) {
    return "Greater than 10";
  }
  ```
  All `if` statements and their variants start off with an `if` statement.
> _try to solve the problem now_
 
 ### Hint: 2
  ``` javascript
  else if (val < 5) {
    return "Smaller than 5";
  }
  ```
  Statements between the `if` statement and the `else` statement in an **else-if** flow are in the else-if format
> _try to solve the problem now_
 
 ### Hint: 3
``` javascript
else {
  return "Between 5 and 10";
  }
 ```
 The last statement in an **else-if** flow is in the `else` format
 ### Spoiler Alert!
![spoiler](http://discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif)
 Solution ahead!
 ## Basic code solution:
```javascript
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }
  
  else if (val < 5) {
    return "Smaller than 5";
  }
  
  else {
  return "Between 5 and 10";
  }
}

// Change this value to test
testElseIf(7);
```
:rocket: [Run Code](https://repl.it/@RyanPisuena/GoldenWorriedRuntime)
 ## Code explanation
The structure of an **else-if logic flow** is an initial *if statement*, one more *if-else statements*, and one final *else statement*
 
 Relevant Link:  [else-if statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

 
 # :clipboard: NOTES FOR CONTRIBUTIONS:
 * :warning: DO NOT add solutions that are similar to any existing solutions. If you think it is similar but better, then try to merge (or replace) the existing similar solution.
* Add an explanation of your solution.
* Categorize the solution in one of the following categories — Basic, Intermediate and Advanced.  :traffic_light:
* Please add your username only if you have added any relevant main contents. (  :warning: DO NOT remove any existing usernames)
 See  :point_right: [Wiki Challenge Solution Template](https://forum.freecodecamp.org/t/freecodecamp-algorithm-challenge-template-guide/14272) for reference.

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ0NDQ2MDE1MSwtMTI1Mzg4MjM3OCwtMT
Q0NDA4NDI0NCwtMTA5MjAxNjYzNSwyOTE0NzAxOCwtMTkzNTQx
NjIzMCwtMTcwMzQ5MTQ2NSwtMTMwNzE3OTQ2NSwxNTE2NDcyMD
gyLC0zODkxMjQ1NTQsLTg5NzE4NzYxMiwyOTgwMDI1MTksOTk4
MDg1OTI3LC0xMzM3MjcwNTg2LC0xNTA4OTEyMzE0LC03NzQyMT
AyMzIsLTIwMzA0NzE5MjksNTQyNDczMjU4LDE3NTg0ODE5MjJd
fQ==
-->