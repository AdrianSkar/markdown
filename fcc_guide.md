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
_This outputs each sub-element in <code>arr</code> one at a time. Note that for the inner loop, we are checking the length of arr[i], since arr[i] is itself an array.

<ul>
  <li>Modify function <code>multiplyAll</code> so that it multiplies the <code>product</code> variable by each number in the sub-arrays of <code>arr</code>.</li>
  <li>Make sure the second for loop is nested inside the first.</li>
</ul>

<strong>Relevant Links</strong>
<ul>
  <li><a href="https://guide.freecodecamp.org/certifications/javascript-algorithms-and-data-structures/basic-javascript/nest-one-array-within-another-array">Nest One Array Within Another Array</a></li>
  <li><a href="https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/iterate-through-an-array-with-a-for-loop">Iterate Through An Array With A For Loop</a></li>
  <li><a href="https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/accessing-nested-arrays">Accessing Nested Arrays</a></li>
</ul>
  
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

:clipboard: <strong>NOTES FOR CONTRIBUTIONS:</strong>
<ul>
<li>:warning: <strong>DO NOT</strong> add solutions that are similar to any existing solutions. If you think it is similar but better, then try to merge (or replace) the existing similar solution.</li>
  <li>Add an explanation of your solution.</li>
<li>Categorize the solution in one of the following categories — Basic, Intermediate and Advanced. :traffic_light:</li>
<li>Please add your username only if you have added any relevant main contents. (:warning: <em><strong>DO NOT</strong></em> remove any existing usernames)</li>
  </ul>
  
See :point_right: <a href="http://forum.freecodecamp.com/t/algorithm-article-template/14272"> Wiki Challenge Solution Template</a> for reference.



<!--stackedit_data:
eyJoaXN0b3J5IjpbNzEwMjEzMTc1LC02Mzk1MzU5MjAsNTc4Mj
UwMDAwLC0zNjE1MTMyMTgsLTE2Mjk1NjEwNTksLTE2MzU3MDc1
MzEsLTUxNzIyMzYzNSw2ODU2NzUxNDksLTgyNTMwNTQ4LC0xOT
M0ODkzMjUsMjA1Mjk5NTg2MCwxNTYxMDAxNzU3LDE4Mzc1NTIy
OTMsLTExNTAxMzMyNjcsMTUxMzg0NjIwNCwtMjE0Njc2NDQ0Ny
wtMjQwNjA3MDU1LDIxMzU2MDE2MjQsODE1MjM2OTU4LDgyMDgx
NTI4N119
-->