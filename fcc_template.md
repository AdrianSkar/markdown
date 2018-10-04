--
title: Introducing Else If statements
---
## Introducing Else If statements

_Remember to use Read-Search-Ask if you get stuck. Try to pair program and write your own code._



#### Hint 1
Remember that _equality is different from assignment (`=`), which assigns the value at the right of the operator to a variable in the left._<sup>1</sup>
> _try to solve the problem now_

 
 ### Hint: 2
  Statements between the `if` statement and the `else` statement in an **else-if** flow are in the else-if format
> _try to solve the problem now_
 
####  Hint 1

The inequality operator (`!=`) will return `true` if the first value is not equal to the second one without taking value type into consideration.

> _try to solve the problem now_

>

##  Spoiler alert!

**Solution ahead!**

##  Basic code solution:

```javascript

// Setup

function testNotEqual(val) {

if (val != 99) { // Change this line

return "Not equal";

}

return "Equal";

}

// Change this value to test

testNotEqual(10);

```

###  Code explanation

The function first evaluates `if` the condition `(val != 99)` evaluates to `true`. If it does, it returns the statement between the curly braces ("Not equal"). If it doesn't, it returns the next `return` statement outside them ("Equal").

###  Resources

- ["Inequality operator" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Using_the_Equality_Operators#Inequality_(!))


<!--stackedit_data:
eyJoaXN0b3J5IjpbNjc2NjgwNzgyLC0yMTI4NDE5NTg0LDE3MT
g4ODEyNDksLTE1MTE5OTUxNDIsMTU4MDU5MjU5MSwxNzM0MzQy
MzU0XX0=
-->