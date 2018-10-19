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
convertToInteger("10011");
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Use-parseInt-with-radix).

### Code explanation
- The function takes `str` and returns an integer instead of a string but "understanding" its a binary number instead of a decimal one thanks to the `radix` parameter (2).


### Resources

- ["parseInt()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/parseInt)
- ["Radic" - *MDN JavaScript reference*](https://en.wikipedia.org/wiki/Radix)
- ["Grouping operator" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Grouping)



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNjYzNjYxMDgsODU4MTM4MDAsMTAxMT
g4MTE5NSwxMDY1ODczMDk3LDQ2MzMyMDI2OCwxOTEyNTM1NDQz
LC01OTM4NzIwNTIsLTYzOTUzNTkyMCw1NzgyNTAwMDAsLTM2MT
UxMzIxOCwtMTYyOTU2MTA1OSwtMTYzNTcwNzUzMSwtNTE3MjIz
NjM1LDY4NTY3NTE0OSwtODI1MzA1NDgsLTE5MzQ4OTMyNSwyMD
UyOTk1ODYwLDE1NjEwMDE3NTcsMTgzNzU1MjI5MywtMTE1MDEz
MzI2N119
-->