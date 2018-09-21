---
title: Comparison with the inequality operator
---
## Comparison with the inequality operator


### Problem explanation:
· _Add the inequality operator `!=` in the `if` statement so that the function will return "Not Equal" when `val` is not equivalent to `99`._

#### Hint 1
Remember from last exercises that _unlike the equality operator, which attempts to convert both values being compared to a common type, the strict equality operator does not perform a type conversion._<sup><a href="#cite1">1</a></sup>
> _try to solve the problem now_
> 

## Spoiler alert!

**Solution ahead!**

## Basic code solution:

```javascript
// Setup
function compareEquality(a, b) {
	if (a === b) { // Change this line
	return  "Equal";
	}
	return  "Not Equal";
}

// Change this value to test
compareEquality(10, "10");
```

### Code explanation
The function first evaluates `if` the condition `(a === b)` evaluates to `true` considering both type and value. If it does, it returns the statement between the curly braces ("Equal"). If it doesn't, it returns the next `return` statement outside them ("Not equal"). 

### Sources

<span id="cite1">1</span>. ["Basic JavaScript: Comparison with the Strict Equality Operator", fCC lesson at *Javascript Algorithms And Data Structures Certification*](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/comparison-with-the-strict-equality-operator)

### Resources

- ["Using the Equality Operators" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators#Using_the_Equality_Operators)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3NTgyOTk5NTEsLTIwMzA0NzE5MjksNT
QyNDczMjU4LDE3NTg0ODE5MjJdfQ==
-->