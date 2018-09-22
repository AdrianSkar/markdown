---
title: Comparison with the greater than operator (>)
---
## Comparison with the greater than operator (>)


### Problem explanation:
· _Add the `greater than` operator to the indicated lines so that the return statements make sense.._

#### Hint 1
The greater than operator `(>)` compares 
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
eyJoaXN0b3J5IjpbLTgxMzIxNDAwOCwyOTgwMDI1MTksOTk4MD
g1OTI3LC0xMzM3MjcwNTg2LC0xNTA4OTEyMzE0LC03NzQyMTAy
MzIsLTIwMzA0NzE5MjksNTQyNDczMjU4LDE3NTg0ODE5MjJdfQ
==
-->