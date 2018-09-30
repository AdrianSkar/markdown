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
The function first evaluates `if` the condition `val <= 50` evaluates to `true` converting `val` to a number if necessary, then does the same with `val >=25` because of the logical AND (`&&`) operator; if both return true, the `return "Yes"` statement is executed. 

### Resources

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTUzNDIzNDcxLC0xMDkyMDE2NjM1LDI5MT
Q3MDE4LC0xOTM1NDE2MjMwLC0xNzAzNDkxNDY1LC0xMzA3MTc5
NDY1LDE1MTY0NzIwODIsLTM4OTEyNDU1NCwtODk3MTg3NjEyLD
I5ODAwMjUxOSw5OTgwODU5MjcsLTEzMzcyNzA1ODYsLTE1MDg5
MTIzMTQsLTc3NDIxMDIzMiwtMjAzMDQ3MTkyOSw1NDI0NzMyNT
gsMTc1ODQ4MTkyMl19
-->