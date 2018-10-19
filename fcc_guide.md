---
title: Use the parseInt Function with a Radix
---
## Use the parseInt Function with a Radix


### Problem explanation:
_Use `parseInt()` in the `convertToInteger` function so it converts a binary number to an integer and returns it._

#### Hint 1
If you use a variable to assign the result of `parseInt(str)` to it, remember to return that variable. 
Otherwise you can just use a `return` statement for your function.
> _try to solve the problem now_
> 
#### Hint 
In this exercise you need to "convert" a binary number into a 
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
eyJoaXN0b3J5IjpbMTgyNzM3MzAzMiw4NTgxMzgwMCwxMDExOD
gxMTk1LDEwNjU4NzMwOTcsNDYzMzIwMjY4LDE5MTI1MzU0NDMs
LTU5Mzg3MjA1MiwtNjM5NTM1OTIwLDU3ODI1MDAwMCwtMzYxNT
EzMjE4LC0xNjI5NTYxMDU5LC0xNjM1NzA3NTMxLC01MTcyMjM2
MzUsNjg1Njc1MTQ5LC04MjUzMDU0OCwtMTkzNDg5MzI1LDIwNT
I5OTU4NjAsMTU2MTAwMTc1NywxODM3NTUyMjkzLC0xMTUwMTMz
MjY3XX0=
-->