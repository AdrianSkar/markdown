---
title: Comparison with the strict inequality operator
---
## Comparison with the strict inequality operator


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
function testStrictNotEqual(val) {
  if (val !== 17) {
    return "Not equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(10);
```

### Code explanation
The function first evaluates `if` the condition `(val !== 17)` evaluates to `true` considering both value and value type. If it does, it returns the statement between the curly braces ("Not equal"). If it doesn't, it returns the next `return` statement outside them ("Equal"). 

### Resources

- ["Inequality operator" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Using_the_Equality_Operators#Inequality_(!))
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEzMzcyNzA1ODYsLTE1MDg5MTIzMTQsLT
c3NDIxMDIzMiwtMjAzMDQ3MTkyOSw1NDI0NzMyNTgsMTc1ODQ4
MTkyMl19
-->