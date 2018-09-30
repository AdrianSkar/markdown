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
Sometimes `if` (`condition`) statements can be replaced by `else {code to execute instead} ` statements (in essence you are telling your function to do _"y"_ if it can't do _"x"_ instead of specifying _"x"_ several times) .  
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
· [Run code at repl.it](https://repl.it/@AdrianSkar/Introducing-else-statements)

### Code explanation
The function first evaluates `if` the condition `val > 5` evaluates to `true`. If it doesn't,it executes the next statement (`else` { return "5 or smaller"}.  

### Resources

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkxMzkyNTIyMiwtMTA5MjAxNjYzNSwyOT
E0NzAxOCwtMTkzNTQxNjIzMCwtMTcwMzQ5MTQ2NSwtMTMwNzE3
OTQ2NSwxNTE2NDcyMDgyLC0zODkxMjQ1NTQsLTg5NzE4NzYxMi
wyOTgwMDI1MTksOTk4MDg1OTI3LC0xMzM3MjcwNTg2LC0xNTA4
OTEyMzE0LC03NzQyMTAyMzIsLTIwMzA0NzE5MjksNTQyNDczMj
U4LDE3NTg0ODE5MjJdfQ==
-->