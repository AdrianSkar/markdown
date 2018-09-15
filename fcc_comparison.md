
---
title: Comparison with the strict equality operator
---
## Comparison with the strict equality operator


### Problem explanation:
_Use the strict equality operator in the `if` statement so the function will return "Equal" when `val`` is strictly equal to ``7``_

#### Hint 1
Remember from last exercise that _equality is different from assignment (`=`), which assigns the value at the right of the operator to a variable in the left._<sup>1</sup>
> _try to solve the problem now_
> 
#### Hint 2
 Unlike the equality operator, which attempts to convert both values being compared to a common type, the strict equality operator does not perform a type conversion.<sup>2</sup>
> _try to solve the problem now_

## Spoiler alert!

**Solution ahead!**

## Basic code solution:

```javascript

function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not equal";
}
// Change this value to test
testEqual(10);

```

### Code explanation
The function first evaluates `if` the condition `(val == 12)` evaluates to `true`. If it does, it returns the statement between the curly braces ("Equal"). If it doesn't, it returns the next `return` statement outside them ("Not equal"). 

### Sources
1. ["Basic JavaScript: Comparison with the Equality Operator", fCC lesson at *Javascript Algorithms And Data Structures Certification*](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-equality-operator)

### Resources
- ["Boolean" - *MDN Glossary*](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)


- [Kondov, Alexander. "Understanding JS: Coercion". *Hackernoon*](https://hackernoon.com/understanding-js-coercion-ff5684475bfc), Accessed 13 Sep. 2018
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0OTI2Nzk0NDUsLTE2MjU1OTA0ODMsNT
MzMTY0NzI3LDEyMDcyNjY3NDMsLTExNjMxNjY2MzUsLTY4MDU2
MjEyOCwtNTEwNzk5NDkyXX0=
-->