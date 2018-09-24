---
title: Comparisons with the && (logical AND) operator
---
## Comparisons with the && (logical AND) operator

### Problem explanation:
· _Combine the two if statements into one statement which will return `"Yes"` if `val`is less than or equal to `50` and greater than or equal to `25`. Otherwise, will return `"No"`._

#### Hint 1
The greater than operator `(>)` compares both operands using type coercion (converting data types if necessary) and returns `true` if the first one is greater than the second one.
> _try to solve the problem now_
> 

## Spoiler alert!

**Solution ahead!**

## Basic code solution:

```javascript
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }
  
  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or under";
}

// Change this value to test
testGreaterThan(10);
```
· [Run code at repl.it](https://repl.it/@AdrianSkar/Basic-JS-Comparison-with-greater)

### Code explanation
The function first evaluates `if` the condition `(val > 100)` evaluates to `true` converting `val` to a number if necessary. If it does, it returns the statement between the curly braces ("Over 100"). If it doesn't, it checks if the next condition is `true` (returning "Over 10"). Otherwise the function will return "10 or under".

### Resources

- ["Greater than operator (>)" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Greater_than_operator_(%3E))
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMjA3ODI4MzYsLTM4OTEyNDU1NCwtOD
k3MTg3NjEyLDI5ODAwMjUxOSw5OTgwODU5MjcsLTEzMzcyNzA1
ODYsLTE1MDg5MTIzMTQsLTc3NDIxMDIzMiwtMjAzMDQ3MTkyOS
w1NDI0NzMyNTgsMTc1ODQ4MTkyMl19
-->