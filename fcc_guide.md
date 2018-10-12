---
title: Iterate Through an Array with a For Loop
---
## Iterate Through an Array with a For Loop
### Problem explanation:
_Declare and initialize a variable `total` to `0`. Use a `for` loop to add the value of each element of the `myArr` array to `total`._

#### Hint 1
Remember the structure of a `for` loop:
`for ([initialization]; [condition]; [final-expression])
   statement`
   
· The `[initialization]` part is executed only once (the first time).
· The `[condition]` is checked on every iteration.
· The `[final-expression]` is executed along the `statement` if `[condition]` resolves to `true`.
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
eyJoaXN0b3J5IjpbLTE2Mjk1NjEwNTksLTE2MzU3MDc1MzEsLT
UxNzIyMzYzNSw2ODU2NzUxNDksLTgyNTMwNTQ4LC0xOTM0ODkz
MjUsMjA1Mjk5NTg2MCwxNTYxMDAxNzU3LDE4Mzc1NTIyOTMsLT
ExNTAxMzMyNjcsMTUxMzg0NjIwNCwtMjE0Njc2NDQ0NywtMjQw
NjA3MDU1LDIxMzU2MDE2MjQsODE1MjM2OTU4LDgyMDgxNTI4Ny
wtMTE1NjQzMjYyNiwtNTk4OTI1NDA2LC05OTIzNDYyOTcsLTEz
NjUwMDc3NTVdfQ==
-->