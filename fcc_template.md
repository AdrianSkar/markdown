---
title: Generate Random Whole Numbers within a Range
---
## Generate Random Whole Numbers within a Range

**Help for passing the final test:**


### Problem explanation:
_Exercise_

#### Hint 1
`randomRange` should use both `myMax` and `myMin`, and return a random number in your range.

You cannot pass the test if you are only re-using the function `ourRandomRange` inside your `randomRange` formula. You need to write your own formula that uses the variables `myMax` and `myMin`. It will do the same job as using `ourRandomRange`, but ensures that you have understood the principles of the `Math.floor()` and `Math.random()` functions.
> _try to solve the problem now_


## Spoiler alert!

**Solution ahead!**

## Basic code solution:

```javascript
function randomRange(myMin, myMax) {

  return Math.floor(Math.random() * (myMax - myMin + 1) + myMin);

}
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Random-whole-numbers-within-range).

### Code explanation
- `Math.random()` generates our random number betwee. 0 and 0.9 

### Sources
<span id="cite1">1</span>. ["Basic JavaScript: Comparison with the Equality Operator", fCC lesson at *Javascript Algorithms And Data Structures Certification*](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-equality-operator)

### Resources
- ["Boolean" - *MDN Glossary*](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

- [Samoshkin, Alexey. "Type coercion explained". *freeCodeCamp, Medium*, 17 Jan. 2018.](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839) Accessed 2 Sep 2018. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTk5NjY2NjUyNywxMTE1NTIzMDIsMTAwOT
M2NzY3MCwtOTA0NTMzNzA3LC0yMTI4NDE5NTg0LDE3MTg4ODEy
NDksLTE1MTE5OTUxNDIsMTU4MDU5MjU5MSwxNzM0MzQyMzU0XX
0=
-->