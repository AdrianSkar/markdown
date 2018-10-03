---
title: Chaining If Else Statements
---
## Chaining If Else Statements

* ```If```: the first conditional in every if/else statement, case the conditional is *true*, execute the code and ignore the rest.
* ```Else if```: can never be used as the first conditional. It is always a conditional after an ```if```, case the conditional is true, execute the code. Otherwise jumps into the next conditional.
* ```Else```: case all the previous conditionals are *false*, **else** is executed.

### Problem explanation:
_Write chained  `if`/`else if`statements to fulfill the following conditions_:

_`num < 5`- return "Tiny"  
`num < 10`- return "Small"  
`num < 15`- return "Medium"  
`num < 20`- return "Large"  
`num >= 20`- return "Huge"_

## Solution:
```javascript
function testSize(num) {
  if(num < 5)
    return 'Tiny';
  else if(num < 10)
    return 'Small';
  else if(num < 15)
    return 'Medium';
  else if(num < 20)
    return 'Large';
  else
    return 'Huge';
}
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMDE2NzEwMDldfQ==
-->