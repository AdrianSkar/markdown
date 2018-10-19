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
In this exercise you need to "convert" a binary number into a decimal number using the `radix` parameter in order to specify the base on which the input number is represented on.
> _try to solve the problem now_

## Spoiler alert!

**Solution ahead!**

## Code solution:

```javascript
function convertToInteger(str) {
  return parseInt(str, 2);
}
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Use-parseInt-with-radix).

### Code explanation
- 


### Resources

- ["Math.random()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
- ["Math.floor()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor)
- ["Grouping operator" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping)



<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA1ODQyMTEyNyw4NTgxMzgwMCwxMDExOD
gxMTk1LDEwNjU4NzMwOTcsNDYzMzIwMjY4LDE5MTI1MzU0NDMs
LTU5Mzg3MjA1MiwtNjM5NTM1OTIwLDU3ODI1MDAwMCwtMzYxNT
EzMjE4LC0xNjI5NTYxMDU5LC0xNjM1NzA3NTMxLC01MTcyMjM2
MzUsNjg1Njc1MTQ5LC04MjUzMDU0OCwtMTkzNDg5MzI1LDIwNT
I5OTU4NjAsMTU2MTAwMTc1NywxODM3NTUyMjkzLC0xMTUwMTMz
MjY3XX0=
-->