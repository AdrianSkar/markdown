--
title: Introducing Else If statements
---
## Introducing Else If statements

_Remember to use Read-Search-Ask if you get stuck. Try to pair program and write your own code._



### Hint 1
Remember that _equality is different from assignment (`=`), which assigns the value at the right of the operator to a variable in the left._<sup>1</sup>
> _try to solve the problem now_

 
 ### Hint: 2
  Statements between the `if` statement and the `else` statement in an **else-if** flow are in the else-if format
> _try to solve the problem now_
 

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
:rocket: [Run code](https://repl.it/@RyanPisuena/GoldenWorriedRuntime)
 ## Code explanation
The structure of an **else-if logic flow** is an initial `if` statement, one more `if-else` statements, and one final `else`.
 
### Resources
- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkxNDI0NTkxNCwtMjEyODQxOTU4NCwxNz
E4ODgxMjQ5LC0xNTExOTk1MTQyLDE1ODA1OTI1OTEsMTczNDM0
MjM1NF19
-->