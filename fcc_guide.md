---
title: Comparison with the greater than operator (>)
---
## Comparison with the greater than operator (>)


### Problem explanation:
· _Add the `greater than` operator to the indicated lines so that the return statements make sense.._

#### Hint 1
The greater than operator `(>)` compares both operands using type coercion (converting data types if necessary) and returns `true` if the first one is greater than the second one.
> _try to solve the problem now_
> 

## Spoiler alert!

**Solution ahead!**

## Basic code solution:

```javascript
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }
  
  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or under";
}

// Change this value to test
testGreaterThan(10);
```
<iframe height="400px" width="100%" src="https://repl.it/@AdrianSkar/Basic-JS-Comparison-with-greater?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

### Code explanation
The function first evaluates `if` the condition `(val > 100)` evaluates to `true` converting `val` to a number if necessary. If it does, it returns the statement between the curly braces ("Over 100"). If it doesn't, it checks if the next condition is `true` (returning "Over 10"). Otherwise the function will return "10 or under".

### Resources

- ["Non-identity / strict inequality (!==)" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Non-identity_strict_inequality_(!))
<!--stackedit_data:
eyJoaXN0b3J5IjpbNDQ0MjcwNTcxLDI5ODAwMjUxOSw5OTgwOD
U5MjcsLTEzMzcyNzA1ODYsLTE1MDg5MTIzMTQsLTc3NDIxMDIz
MiwtMjAzMDQ3MTkyOSw1NDI0NzMyNTgsMTc1ODQ4MTkyMl19
-->