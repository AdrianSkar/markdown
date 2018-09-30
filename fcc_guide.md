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

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTM4NzEwNjg0OSwtMTA5MjAxNjYzNSwyOT
E0NzAxOCwtMTkzNTQxNjIzMCwtMTcwMzQ5MTQ2NSwtMTMwNzE3
OTQ2NSwxNTE2NDcyMDgyLC0zODkxMjQ1NTQsLTg5NzE4NzYxMi
wyOTgwMDI1MTksOTk4MDg1OTI3LC0xMzM3MjcwNTg2LC0xNTA4
OTEyMzE0LC03NzQyMTAyMzIsLTIwMzA0NzE5MjksNTQyNDczMj
U4LDE3NTg0ODE5MjJdfQ==
-->