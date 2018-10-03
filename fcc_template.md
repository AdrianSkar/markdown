---
title: Chaining If Else statements
---
##  Chaining If Else statements

### Problem explanation:
_Write chained  `if`/`else if`statements to fulfill the following conditions:

`num < 5`- return "Tiny"  
`num < 10`- return "Small"  
`num < 15`- return "Medium"  
`num < 20`- return "Large"  
`num >= 20`- return "Huge"_

#### Hint 1
Remember that you can combine (chain) several `if...else` statements one after the other until your last one using `else if (condition) {do this}`.
> _try to solve the problem now_
> 
#### Hint 2
Sometimes, when you write more code than you are used to and it doesn't work, the little things are what betray us. Checking for missing semicolons, brackets, etc. can prove very useful.
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
<span id="cite1">1</span>. ["Basic JavaScript: Comparison with the Equality Operator", fCC lesson at *Javascript Algorithms And Data Structures Certification*](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-equality-operator)

### Resources
- ["Boolean" - *MDN Glossary*](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

- [Samoshkin, Alexey. "Type coercion explained". *freeCodeCamp, Medium*, 17 Jan. 2018.](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839) Accessed 2 Sep 2018. QUIT, advanced for this exercise
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcxODg4MTI0OSwtMTUxMTk5NTE0MiwxNT
gwNTkyNTkxLDE3MzQzNDIzNTRdfQ==
-->