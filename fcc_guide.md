---
title: Comparison with the greater than operator (>)
---
## Comparison with the greater than operator (>)


### Problem explanation:
· _Add the `greater than` operator to the indicated lines so that the return statements make sense.._

#### Hint 1
The greater than operator `(>)` compares both operands using type coercion (converting data types if necessary) and returns `true` if the first one is greater than the second one.
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

- ["Non-identity / strict inequality (!==)" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Non-identity_strict_inequality_(!))
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY4NDYyMDM0LDI5ODAwMjUxOSw5OTgwOD
U5MjcsLTEzMzcyNzA1ODYsLTE1MDg5MTIzMTQsLTc3NDIxMDIz
MiwtMjAzMDQ3MTkyOSw1NDI0NzMyNTgsMTc1ODQ4MTkyMl19
-->