
---
title: Comparison with the Inequality Operator
---
## Comparison with the Inequality Operator


### Problem explanation:
· _Add the inequality operator `!=` in the `if` statement so that the function will return "Not equal" when `val` is not equivalent to `99`._

#### Hint 1
The inequality operator (`!=`) will return `true` if the first value is not equal to the second one without taking value type into consideration.
> _try to solve the problem now_
> 

## Spoiler alert!

**Solution ahead!**

## Basic code solution:

```javascript
// Setup
function testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not equal";
  }
  return "Equal";
}

// Change this value to test
testNotEqual(10);
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Comparison-with-the-inequality-operator).

### Code explanation
The function first evaluates `if` the condition `(val != 99)` evaluates to `true`. If it does, it returns the statement between the curly braces ("Not equal"). If it doesn't, it returns the next `return` statement outside them ("Equal"). 

### Resources

- ["Inequality operator" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Using_the_Equality_Operators#Inequality_(!))
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ2NjcwMTU3NCwxMjIxNTg5NjYsMTI3Mj
A0MTAyNCwxMzA2OTE4MzQ1LDYwNjczNzc1Myw4NTgxMzgwMCwx
MDExODgxMTk1LDEwNjU4NzMwOTcsNDYzMzIwMjY4LDE5MTI1Mz
U0NDMsLTU5Mzg3MjA1MiwtNjM5NTM1OTIwLDU3ODI1MDAwMCwt
MzYxNTEzMjE4LC0xNjI5NTYxMDU5LC0xNjM1NzA3NTMxLC01MT
cyMjM2MzUsNjg1Njc1MTQ5LC04MjUzMDU0OCwtMTkzNDg5MzI1
XX0=
-->