---
title: Generate Random Whole Numbers within a Range
---
## Generate Random Whole Numbers within a Range

**Help for passing the final test:**


### Problem explanation:
_Exercise_

#### Hint 1
`randomRange` should use both `myMax` and `myMin`, and return a random number in your range.

You cannot pass the final test if you are only re-using the function `ourRandomRange` inside your `randomRange` formula. You need to write your own formula that uses the variables `myMax` and `myMin`. It will do the same job as using `ourRandomRange`, but ensures that you have understood the principles of the `Math.floor()` and `Math.random()` functions.
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
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Comparison-with-greater-operator).

### Code explanation
The function first evaluates `if` the condition `(val == 12)` evaluates to `true`. If it does, it returns the statement between the curly braces ("Equal"). If it doesn't, it returns the next `return` statement outside them ("Not equal"). 

### Sources
<span id="cite1">1</span>. ["Basic JavaScript: Comparison with the Equality Operator", fCC lesson at *Javascript Algorithms And Data Structures Certification*](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-equality-operator)

### Resources
- ["Boolean" - *MDN Glossary*](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

- [Samoshkin, Alexey. "Type coercion explained". *freeCodeCamp, Medium*, 17 Jan. 2018.](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839) Accessed 2 Sep 2018. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU4MzkxNjU2LDEwMDkzNjc2NzAsLTkwND
UzMzcwNywtMjEyODQxOTU4NCwxNzE4ODgxMjQ5LC0xNTExOTk1
MTQyLDE1ODA1OTI1OTEsMTczNDM0MjM1NF19
-->