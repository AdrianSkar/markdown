---
title: Use the Conditional (Ternary) Operator
---
## Use the Conditional (Ternary) Operator

### Problem explanation:
_Use the `conditional operator` in the `checkEqual` function to check if two numbers are equal or not. The function should return either true or false._

#### Hint 1
Remember that the "traditional" `if...else` syntax can be re-written using the conditional operator (`condition ? )
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
eyJoaXN0b3J5IjpbMTQxOTE2NDAzMCwxMzA2OTE4MzQ1LDYwNj
czNzc1Myw4NTgxMzgwMCwxMDExODgxMTk1LDEwNjU4NzMwOTcs
NDYzMzIwMjY4LDE5MTI1MzU0NDMsLTU5Mzg3MjA1MiwtNjM5NT
M1OTIwLDU3ODI1MDAwMCwtMzYxNTEzMjE4LC0xNjI5NTYxMDU5
LC0xNjM1NzA3NTMxLC01MTcyMjM2MzUsNjg1Njc1MTQ5LC04Mj
UzMDU0OCwtMTkzNDg5MzI1LDIwNTI5OTU4NjAsMTU2MTAwMTc1
N119
-->