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
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }
  
  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

// Change this value to test
testGreaterThan(10);
```

### Code explanation
The function first evaluates `if` the condition `(val > 100)` evaluates to `true` converting `val` to a number if necessary. If it does, it returns the statement between the curly braces ("Over 100"). If it doesn't, it checks if the nec
### Resources

- ["Non-identity / strict inequality (!==)" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Non-identity_strict_inequality_(!))
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5MTM0NTk5OSwyOTgwMDI1MTksOTk4MD
g1OTI3LC0xMzM3MjcwNTg2LC0xNTA4OTEyMzE0LC03NzQyMTAy
MzIsLTIwMzA0NzE5MjksNTQyNDczMjU4LDE3NTg0ODE5MjJdfQ
==
-->