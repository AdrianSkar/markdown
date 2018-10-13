---
title: Nesting For Loops
---
## Nesting For Loops

### Problem Explanation:

_If you have a multi-dimensional array, you can use the same logic as the prior waypoint to loop through both the array and any sub-arrays._

_Here is an example:_

```javascript
var arr = [
  [1,2], [3,4], [5,6]
];
for (var i=0; i < arr.length; i++) {
  for (var j=0; j < arr[i].length; j++) {
    console.log(arr[i][j]);
  }
}
```

_This outputs each sub-element in  `arr` one at a time. Note that for the inner loop, we are checking the  `.length`of  `arr[i]`, since  `arr[i]` is itself an array._

----------

_Modify function  `multiplyAll` so that it multiplies the  `product` variable by each number in the sub-arrays of  `arr`_

#### Hint 1
Hint X, remember that _text/paraphrasing_<sup><a href="#cite1">1</a></sup>
> _try to solve the problem now_
> 
:speech_balloon: Hint: 1

Make sure to check with <code>length</code> and not the overall array.

<em>try to solve the problem now</em>

:speech_balloon: Hint 2<br>

Use both <code>i</code> and <code>j</code> when multiplying the product.

<em>try to solve the problem now</em>

:speech_balloon: Hint 3<br>

Remember to use <code>arr[i]</code> when you multiply the sub-arrays with the <code>product</code> variable.

<em>try to solve the problem now</em>

<em>Spoiler Alert!</em>
<img src="https://discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif">

<br>
<strong>Solution Ahead!</strong>

:beginner: <strong>Basic Code Solution:</strong>
```
function multiplyAll(arr) {
  var product = 1;
  // Only change code below this line
  for(var i=0; i < arr.length; i++){
    for (var j=0; j < arr[i].length; j++){
      product = product * arr[i][j];
    }
  }
  // Only change code above this line
  return product;
}

// Modify values below to test your code
multiplyAll([[1,2],[3,4],[5,6,7]]);

```
:rocket: <strong><a href="https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/nesting-for-loops/">Run Code</a></strong>

<strong>Code Explanation:</strong>

<ul>
  <li>We check the length of <code>arr</code> in the <code>i</code> for loop and the <code>arr[i]</code> length in the <code>j</code> for loop.</li>
  <li>We multiply the <code>product</code> variable by itself because it equals 1, and then multiply it by the sub-arrays.</li>
  <li>The two sub-arrays to multiply are <code>arr[i]</code> and <code>j</code>.</li>
</ul>

Resources:

<ul>
  <li><a href="https://guide.freecodecamp.org/certifications/javascript-algorithms-and-data-structures/basic-javascript/nest-one-array-within-another-array">Nest One Array Within Another Array</a></li>
  <li><a href="https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/iterate-through-an-array-with-a-for-loop">Iterate Through An Array With A For Loop</a></li>
  <li><a href="https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/accessing-nested-arrays">Accessing Nested Arrays</a></li>
</ul>
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwOTUyMjM2MzYsLTYzOTUzNTkyMCw1Nz
gyNTAwMDAsLTM2MTUxMzIxOCwtMTYyOTU2MTA1OSwtMTYzNTcw
NzUzMSwtNTE3MjIzNjM1LDY4NTY3NTE0OSwtODI1MzA1NDgsLT
E5MzQ4OTMyNSwyMDUyOTk1ODYwLDE1NjEwMDE3NTcsMTgzNzU1
MjI5MywtMTE1MDEzMzI2NywxNTEzODQ2MjA0LC0yMTQ2NzY0ND
Q3LC0yNDA2MDcwNTUsMjEzNTYwMTYyNCw4MTUyMzY5NTgsODIw
ODE1Mjg3XX0=
-->