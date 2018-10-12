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
for (var i = 0; i < myArr.length; i++) {
  total += myArr[i];
}
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-iterate-for-loop).

### Code explanation
· Inititialization: `i` gets a value of `0` and its used as a counter.
· Condition: the subsequent code is executed as long as `i` is less and the length of `myArr` (which is `5` but arrays are zero

### Sources
<span id="cite1">1</span>. ["Basic JavaScript: Comparison with the Equality Operator", fCC lesson at *Javascript Algorithms And Data Structures Certification*](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-equality-operator)

### Resources
- ["Boolean" - *MDN Glossary*](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

- [Samoshkin, Alexey. "Type coercion explained". *freeCodeCamp, Medium*, 17 Jan. 2018.](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839) Accessed 2 Sep 2018. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MTM3NTQ4NzIsLTE2Mjk1NjEwNTksLT
E2MzU3MDc1MzEsLTUxNzIyMzYzNSw2ODU2NzUxNDksLTgyNTMw
NTQ4LC0xOTM0ODkzMjUsMjA1Mjk5NTg2MCwxNTYxMDAxNzU3LD
E4Mzc1NTIyOTMsLTExNTAxMzMyNjcsMTUxMzg0NjIwNCwtMjE0
Njc2NDQ0NywtMjQwNjA3MDU1LDIxMzU2MDE2MjQsODE1MjM2OT
U4LDgyMDgxNTI4NywtMTE1NjQzMjYyNiwtNTk4OTI1NDA2LC05
OTIzNDYyOTddfQ==
-->