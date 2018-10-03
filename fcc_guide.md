---
title: Chaining if...else statements
---
##  Chaining if...else statements

### Problem explanation:
_Write chained  `if`/`else if`statements to fulfill the following conditions_:

_`num < 5`- return "Tiny"  
`num < 10`- return "Small"  
`num < 15`- return "Medium"  
`num < 20`- return "Large"  
`num >= 20`- return "Huge"_

#### Hint 1
Remember that you can combine (chain) several `if...else` statements one after the other until your last one using `else if (condition) {do this}`.
> _try to solve the problem now_
> 
> 
#### Hint 2
Sometimes, when you write more code than you are used to and it doesn't work, the little things are what betray us. Checking for missing semicolons, brackets, etc. can prove very useful.
> _try to solve the problem now_


## Spoiler alert!

**Solution ahead!**

## Code solution:

```javascript
function testSize(num) {
  // Only change code below this line
  if (num < 5){
    return "Tiny";
  }
  else if (num < 10) {
    return "Small";
  }
  else if (num < 15){
    return "Medium";
  }
  else if (num < 20){
    return "Large";
  }
  else {
    return "Huge";
  }
  // Only change code above this line
}

// Change this value to test
testSize(7);
```
· Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Chaining-ifelse-statements)

### Code explanation
The function first evaluates `if` the condition `(num < 5)` evaluates to `true`. If it does, it returns the statement between the curly braces ("Tiny"). If it doesn't, it checks the next condition until the last `else` statement. 


### Resources

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExNTY0MzI2MjYsLTU5ODkyNTQwNiwtOT
kyMzQ2Mjk3LC0xMzY1MDA3NzU1LDM1NTE0MzA0NywtMTI1Mzg4
MjM3OCwtMTQ0NDA4NDI0NCwtMTA5MjAxNjYzNSwyOTE0NzAxOC
wtMTkzNTQxNjIzMCwtMTcwMzQ5MTQ2NSwtMTMwNzE3OTQ2NSwx
NTE2NDcyMDgyLC0zODkxMjQ1NTQsLTg5NzE4NzYxMiwyOTgwMD
I1MTksOTk4MDg1OTI3LC0xMzM3MjcwNTg2LC0xNTA4OTEyMzE0
LC03NzQyMTAyMzJdfQ==
-->