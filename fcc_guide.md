---
title: Use the Conditional (Ternary) Operator
---
## Use the Conditional (Ternary) Operator

### Problem explanation:
_Use the `conditional operator`in the `checkEqual`function to check if two numbers are equal or not. The function should return either true or false._

#### Hint 1
If you use a variable to assign the result of `parseInt(str)` to it, remember to return that variable. 
Otherwise you can just use a `return` statement for your function.
> _try to solve the problem now_
> 
#### Hint 2
In this exercise you need to "convert" a binary number into a decimal number using the `radix` parameter in order to specify the base on which the input number is represented on.
> _try to solve the problem now_

## Spoiler alert!

**Solution ahead!**

## Code solution:

```javascript
function convertToInteger(str) {
  return parseInt(str, 2);
}
convertToInteger("10011");
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Use-parseInt-with-radix).

### Code explanation
- The function takes `str` and returns an integer instead of a string but "understanding" its a binary number instead of a decimal one thanks to the `radix` parameter (2).


### Resources

- ["parseInt()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt)
- ["Radix" - *Wikipedia*](https://en.wikipedia.org/wiki/Radix)




<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI5OTE2NjA5Myw2MDY3Mzc3NTMsODU4MT
M4MDAsMTAxMTg4MTE5NSwxMDY1ODczMDk3LDQ2MzMyMDI2OCwx
OTEyNTM1NDQzLC01OTM4NzIwNTIsLTYzOTUzNTkyMCw1NzgyNT
AwMDAsLTM2MTUxMzIxOCwtMTYyOTU2MTA1OSwtMTYzNTcwNzUz
MSwtNTE3MjIzNjM1LDY4NTY3NTE0OSwtODI1MzA1NDgsLTE5Mz
Q4OTMyNSwyMDUyOTk1ODYwLDE1NjEwMDE3NTcsMTgzNzU1MjI5
M119
-->