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
Make sure to check with `length` and not the overall array.
> _try to solve the problem now_
> 
#### Hint 2
Remember to select the proper values inside arrays (eg: `arr[i][y]`) when you multiply them with the `product` variable.
> _try to solve the problem now_
> 


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
eyJoaXN0b3J5IjpbLTI3Mjk5OTczNSwtNTkzODcyMDUyLC02Mz
k1MzU5MjAsNTc4MjUwMDAwLC0zNjE1MTMyMTgsLTE2Mjk1NjEw
NTksLTE2MzU3MDc1MzEsLTUxNzIyMzYzNSw2ODU2NzUxNDksLT
gyNTMwNTQ4LC0xOTM0ODkzMjUsMjA1Mjk5NTg2MCwxNTYxMDAx
NzU3LDE4Mzc1NTIyOTMsLTExNTAxMzMyNjcsMTUxMzg0NjIwNC
wtMjE0Njc2NDQ0NywtMjQwNjA3MDU1LDIxMzU2MDE2MjQsODE1
MjM2OTU4XX0=
-->