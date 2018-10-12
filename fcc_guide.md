---
title: Iterate Through an Array with a For Loop
---
## Iterate Through an Array with a For Loop
### Problem explanation:
_Declare and initialize a variable `total` to `0`. Use a `for` loop to add the value of each element of the `myArr` array to `total`._

#### Hint 1
Remember the structure of a `for` loop:
`for ([initialization]; [condition]; [final-expression])
   statement`
   
· The `[initialization]` part is executed only once (the first time).
· The `[condition]` is checked on every iteration.
· The `[final-expression]` is executed along the `statement` if `[condition]` resolves to `true`.
> _try to solve the problem now_


## Spoiler alert!

**Solution ahead!**

## Code solution:

```javascript
for (var i = 0; i < myArr.length; i++) {
  total += myArr[i];
}
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-iterate-for-loop).

### Code explanation
- Inititialization: `i` gets a value of `0` and its used as a counter.
- Condition: the subsequent code is executed as long as `i` is less and the length of `myArr` (which is 5; five numbers but arrays are zero based).
- Final-expression: `i` is incremented by `1`.
- Statement: The function adds `myArr[i]`'s value to `total` until the condition isn't met like so:

`total` + `myArr[0]` -> 0 + 2 = 2 
`total` + `myArr[1]` -> 2 + 3 = 5
`total` + `myArr[2]` -> 5 + 4 = 9
`total` + `myArr[3]` -> 9 + 5 = 14 
`total` + `myArr[4]` -> 14 + 6 = 20

## Alternative code solution:

```javascript
for (var y = myArr.length - 1; y >= 0; y--) {
  total += myArr[y];
}
```
·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-iterate-for-loop).

### Code explanation
This works similarly to the last solution but it's faster<sup><a href="#cite1">1</a></sup> although it might not meet your requirements if order is important.
- Initialization: `y` gets the `myArr.length` value once so the function doesn't need to check it at `condition` every time the loop is executed.
- Condition: the loop is executed as long as `y` is greater than `0`.
- Final-expression: `y` is decremented by `1`.
- Statement: The function adds `myArr[y]`'s value to `total` until the condition isn't met like so:



### Sources
<span id="cite1">1</span>. ["Are loops really faster in reverse?",  *stackoverflow.com*](https://stackoverflow.com/questions/1340589/are-loops-really-faster-in-reverse)

### Resources
- ["Boolean" - *MDN Glossary*](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)

- ["if...else" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

- [Samoshkin, Alexey. "Type coercion explained". *freeCodeCamp, Medium*, 17 Jan. 2018.](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839) Accessed 2 Sep 2018. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0ODE2OTgzMzgsLTM2MTUxMzIxOCwtMT
YyOTU2MTA1OSwtMTYzNTcwNzUzMSwtNTE3MjIzNjM1LDY4NTY3
NTE0OSwtODI1MzA1NDgsLTE5MzQ4OTMyNSwyMDUyOTk1ODYwLD
E1NjEwMDE3NTcsMTgzNzU1MjI5MywtMTE1MDEzMzI2NywxNTEz
ODQ2MjA0LC0yMTQ2NzY0NDQ3LC0yNDA2MDcwNTUsMjEzNTYwMT
YyNCw4MTUyMzY5NTgsODIwODE1Mjg3LC0xMTU2NDMyNjI2LC01
OTg5MjU0MDZdfQ==
-->