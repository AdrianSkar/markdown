--
title: Introducing Else If statements
---
## Introducing Else If statements

_Remember to use Read-Search-Ask if you get stuck. Try to pair program and write your own code._



#### Hint 1
Remember that _equality is different from assignment (`=`), which assigns the value at the right of the operator to a variable in the left._<sup>1</sup>
> _try to solve the problem now_

 
####  Hint 2

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
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Comparison-with-greater-operator).

###  Code explanation

The function first evaluates `if` the condition `(val != 99)` evaluates to `true`. If it does, it returns the statement between the curly braces ("Not equal"). If it doesn't, it returns the next `return` statement outside them ("Equal").

###  Resources

- ["Inequality operator" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Using_the_Equality_Operators#Inequality_(!))


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTkwNDUzMzcwNywtMjEyODQxOTU4NCwxNz
E4ODgxMjQ5LC0xNTExOTk1MTQyLDE1ODA1OTI1OTEsMTczNDM0
MjM1NF19
-->