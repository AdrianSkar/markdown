---
title: Using Objects for Lookups
---
## Using Objects for Lookups

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

Here’s the example:
```javascript
// Setup
function phoneticLookup(val) {
  var result = "";

  // Only change code below this line
  switch(val) {
    case "alpha": 
      result = "Adams";
      break;
    case "bravo": 
      result = "Boston";
      break;
    case "charlie": 
      result = "Chicago";
      break;
    case "delta": 
      result = "Denver";
      break;
    case "echo": 
      result = "Easy";
      break;
    case "foxtrot": 
      result = "Frank";
  }

  // Only change code above this line
  return result;
}

// Change this value to test
phoneticLookup("charlie");
```

Here’s a solution:
We do not change anything here:
```javascript
function phoneticLookup(val) {
  var result = "";
```
We need to convert the switch statement into an object. Transfer all `case` values to object properties: 

```javascript
function phoneticLookup(val) {
  var result = "";
  var lookup = {
    "alpha": "Adams",
    "bravo": "Boston",
    "charlie": "Chicago",
    "delta": "Denver",
    "echo": "Easy",
    "foxtrot": "Frank"
  };
  ```
After converting our case statements into object properties you can make use of the variable `result` to let the function return the correct value.

```javascript
  result = lookup[val];
 ```

·  Run code at [repl.it](https://repl.it/@AdrianSkar/Basic-JS-Comparison-with-greater-operator).

### Resources

- ["JavaScript object basics" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)


<!--stackedit_data:
eyJoaXN0b3J5IjpbNTY2MzM5MDA5LC04MjUzMDU0OCwtMTkzND
g5MzI1LDIwNTI5OTU4NjAsMTU2MTAwMTc1NywxODM3NTUyMjkz
LC0xMTUwMTMzMjY3LDE1MTM4NDYyMDQsLTIxNDY3NjQ0NDcsLT
I0MDYwNzA1NSwyMTM1NjAxNjI0LDgxNTIzNjk1OCw4MjA4MTUy
ODcsLTExNTY0MzI2MjYsLTU5ODkyNTQwNiwtOTkyMzQ2Mjk3LC
0xMzY1MDA3NzU1LDM1NTE0MzA0NywtMTI1Mzg4MjM3OCwtMTQ0
NDA4NDI0NF19
-->