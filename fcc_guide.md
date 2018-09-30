---
title: Introducing Else statements
---
## Introducing Else statements

### Problem explanation:
· _Combine the `if` statements into a single `if/else` statement._

#### Hint 1
The logical AND (`&&`) operator compares both statements and returns `true` only if both are true or can be converted to true (truthy).
> _try to solve the problem now_
> 

#### Hint 2
Remember that this effect can be also achieved by nesting `if` statements.
> _try to solve the problem now_
> 

## Spoiler alert!

**Solution ahead!**

## Basic code solution:

```javascript
function testElse(val) {
  var result = "";
  // Only change code below this line
  
  if (val > 5) {
    result = "Bigger than 5";
  }
  
  else {
    return "5 or smaller";
  }
  
  // Only change code above this line
  return result;
}

// Change this value to test
testElse(4);
```
· [Run code at repl.it](https://repl.it/@AdrianSkar/Basic-JS-Comparison-with-the-and-operator)

### Code explanation
The function first evaluates `if` the condition `val <= 50` evaluates to `true` converting `val` to a number if necessary, then does the same with `val >=25` because of the logical AND (`&&`) operator; if both return true, the `return "Yes"` statement is executed. 

### Resources

- ["Logical operators" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_Operators)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwOTIwMTY2MzUsMjkxNDcwMTgsLTE5Mz
U0MTYyMzAsLTE3MDM0OTE0NjUsLTEzMDcxNzk0NjUsMTUxNjQ3
MjA4MiwtMzg5MTI0NTU0LC04OTcxODc2MTIsMjk4MDAyNTE5LD
k5ODA4NTkyNywtMTMzNzI3MDU4NiwtMTUwODkxMjMxNCwtNzc0
MjEwMjMyLC0yMDMwNDcxOTI5LDU0MjQ3MzI1OCwxNzU4NDgxOT
IyXX0=
-->