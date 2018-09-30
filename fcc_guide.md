---
title: Introducing Else statements
---
## Introducing Else statements

### Problem explanation:
· _Combine the `if` statements into a single `if/else` statement._

#### Hint 1
When the first  `if` statement returns `false` the next piece of code is executed/evaluated (like `return`, `if` or `else` statements).
> _try to solve the problem now_
> 

#### Hint 2
Sometimes `if` (`condition`) statements can be replaced by `else {code to execute} ` statements (in essence you are telling your function to do _"y"_ if it can't do _"x"_ instead of specifying _"x"_ several times) .  
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

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMzkxOTE5NjQsLTEwOTIwMTY2MzUsMj
kxNDcwMTgsLTE5MzU0MTYyMzAsLTE3MDM0OTE0NjUsLTEzMDcx
Nzk0NjUsMTUxNjQ3MjA4MiwtMzg5MTI0NTU0LC04OTcxODc2MT
IsMjk4MDAyNTE5LDk5ODA4NTkyNywtMTMzNzI3MDU4NiwtMTUw
ODkxMjMxNCwtNzc0MjEwMjMyLC0yMDMwNDcxOTI5LDU0MjQ3Mz
I1OCwxNzU4NDgxOTIyXX0=
-->