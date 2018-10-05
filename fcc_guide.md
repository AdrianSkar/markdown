---
title: Selecting from Many Options with Switch Statements
---
## Selecting from Many Options with Switch Statements

_If you have many options to choose from, use a `switch` statement. A `switch` statement tests a value and can have many `case` statements which define various possible values. Statements are executed from the first matched `case` value until a `break` is encountered._

_Here is a pseudocode example:_

```js
  switch(num) {
    case value1:
      statement1;
      break;
    case value2:
      statement2;
      break;
    ...
    case valueN:
      statementN;
      break;
  }
```

### A bit more explanation
A switch statement first evaluates its expression. It then looks for the first `case` clause whose expression evaluates to the same value as the result of the input expression (using the [strict comparison](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Comparison_Operators), (`===`) and transfers control to that clause, executing the associated statements. (If multiple cases match the provided value, the first case that matches is selected, even if the cases are not equal to each other.)

If no matching `case` clause is found, the program looks for the optional `default` clause, and if found, transfers control to that clause, executing the associated statements. If no `default` clause is found, the program continues execution at the statement following the end of `switch`. By convention, the `default` clause is the last clause, but it does not need to be so.

The optional `break` statement associated with each case label ensures that the program breaks out of switch once the matched statement is executed and continues execution at the statement following switch. If `break` is omitted, the program continues execution at the next statement in the `switch` statement.<sup><a href="#cite1">1</a></sup>


### Problem Explanation: 
_Write a switch statement which tests `val` and sets `answer` for the following conditions:_
- `1` - "alpha",
- `2` - "beta",
- `3` - "gamma",
- `4` - "delta".

## Hint 1
Remember that `case` values are tested with strict equality (`===`).
> Try to solve the problem now!

## Hint 2
Do not see _"following conditions"_ as an ordered list as it looks in the original freeCodeCamp demo, but as values and statements, as shown here
>Try to solve the problem now!

## Spoiler Alert!
### Are you completely sure what you want a look? ...

## Basic Code Solution

```js
function caseInSwitch(val) {
  var answer = "";
  // Only change code below this line
  switch(val) {
    case 1:
      return "alpha";
      break;
    case 2:
      return "beta";
      break;
    case 3:
      return "gamma";
      break;
    case 4:
      return "delta";
      break;
  }

  // Only change code above this line  
  return answer;  
}

// Change this value to test
caseInSwitch(1);
```
### Code explanation
It is common to ignore that `case` values are tested with strict equality with any need of other expression, like so:
`case === value`

## Alternative code solution:
```javascript
function caseInSwitch(val) {
  var answer = "";
  // Only change code below this line
  switch (val){
    case 1:
      answer="alpha";
      break;
    case 2:
      answer="beta";
      break;
    case 3:
      answer="gamma";
      break;
    case 4:
      answer="delta";
      break;
  }
  // Only change code above this line  
  return answer;  
}
// Change this value to test
caseInSwitch(1);
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Switch-statements).

### Code explanation
Since you already have a variable defined at the beginning of the function named `answer` and it's defined as the last return statement, you can assign new values to it for each case and will return the expected answer depending on the value you pass to the function. 


### Sources
<span id="cite1">1</span>. [Description of "switch" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch#Description).




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExNTAxMzMyNjcsMTUxMzg0NjIwNCwtMj
E0Njc2NDQ0NywtMjQwNjA3MDU1LDIxMzU2MDE2MjQsODE1MjM2
OTU4LDgyMDgxNTI4NywtMTE1NjQzMjYyNiwtNTk4OTI1NDA2LC
05OTIzNDYyOTcsLTEzNjUwMDc3NTUsMzU1MTQzMDQ3LC0xMjUz
ODgyMzc4LC0xNDQ0MDg0MjQ0LC0xMDkyMDE2NjM1LDI5MTQ3MD
E4LC0xOTM1NDE2MjMwLC0xNzAzNDkxNDY1LC0xMzA3MTc5NDY1
LDE1MTY0NzIwODJdfQ==
-->