---
title: Comparison with the inequality operator
---
## Comparison with the inequality operator


### Problem explanation:
· _Add the inequality operator `!=` in the `if` statement so that the function will return "Not Equal" when `val` is not equivalent to `99`._

#### Hint 1
The "Not Equal" operator (`!=`) will return `true` if, and only if, the first value is not equal_<sup><a href="#cite1">1</a></sup>
> _try to solve the problem now_
> 

## Spoiler alert!

**Solution ahead!**

## Basic code solution:

```javascript
// Setup
function testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testNotEqual(10);
```

### Code explanation
The function first evaluates `if` the condition `(a === b)` evaluates to `true` considering both type and value. If it does, it returns the statement between the curly braces ("Equal"). If it doesn't, it returns the next `return` statement outside them ("Not equal"). 

### Sources

<span id="cite1">1</span>. ["Basic JavaScript: Comparison with the Strict Equality Operator", fCC lesson at *Javascript Algorithms And Data Structures Certification*](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-strict-equality-operator)

### Resources

- ["Using the Equality Operators" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Using_the_Equality_Operators)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU4MDk0MjM0OCwtMjAzMDQ3MTkyOSw1ND
I0NzMyNTgsMTc1ODQ4MTkyMl19
-->