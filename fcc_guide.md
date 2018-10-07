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


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI0OTU5ODgwNSwtODI1MzA1NDgsLTE5Mz
Q4OTMyNSwyMDUyOTk1ODYwLDE1NjEwMDE3NTcsMTgzNzU1MjI5
MywtMTE1MDEzMzI2NywxNTEzODQ2MjA0LC0yMTQ2NzY0NDQ3LC
0yNDA2MDcwNTUsMjEzNTYwMTYyNCw4MTUyMzY5NTgsODIwODE1
Mjg3LC0xMTU2NDMyNjI2LC01OTg5MjU0MDYsLTk5MjM0NjI5Ny
wtMTM2NTAwNzc1NSwzNTUxNDMwNDcsLTEyNTM4ODIzNzgsLTE0
NDQwODQyNDRdfQ==
-->