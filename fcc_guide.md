---
title: Use the parseInt Function with a Radix
---
## Use the parseInt Function with a Radix


### Problem explanation:
_Use `parseInt()` in the `convertToInteger` function so it converts a binary number to an integer and returns it._

#### Hint 1
If you use a variable to assign the result of `parseInt(str)` to it, remember to return that variable. 
Otherwise you can just 
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
- `Math.random()` generates our random number between 0 and ≈ 0.9.
- Before multiplying it, it resolves the part between parenthesis `(myMax - myMin + 1)` because of the grouping operator `(   )`.
- The result of that multiplication is followed by adding `myMin` and then "rounded" to the largest integer less than or equal to it (eg: 9.9 would result in 9)
If the values were `myMin = 1, myMax= 10`, one result could be the following:
· a) `Math.random() = 0.8244326990411024`
· b) `(myMax - myMin + 1) = 10 - 1 + 1 -> 10`
· c) `a * b =  8.244326990411024`
· d) `c + myMin = 9.244326990411024`
· e) `Math.floor(9.244326990411024) = 9`


### Resources

- ["Math.random()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
- ["Math.floor()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor)
- ["Grouping operator" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping)



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4NjAxNzM3MjEsODU4MTM4MDAsMTAxMT
g4MTE5NSwxMDY1ODczMDk3LDQ2MzMyMDI2OCwxOTEyNTM1NDQz
LC01OTM4NzIwNTIsLTYzOTUzNTkyMCw1NzgyNTAwMDAsLTM2MT
UxMzIxOCwtMTYyOTU2MTA1OSwtMTYzNTcwNzUzMSwtNTE3MjIz
NjM1LDY4NTY3NTE0OSwtODI1MzA1NDgsLTE5MzQ4OTMyNSwyMD
UyOTk1ODYwLDE1NjEwMDE3NTcsMTgzNzU1MjI5MywtMTE1MDEz
MzI2N119
-->