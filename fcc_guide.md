---
title: Write Higher Order Arrow Functions
---
![:triangular_flag_on_post:](https://forum.freecodecamp.com/images/emoji/emoji_one/triangular_flag_on_post.png?v=3 ":triangular_flag_on_post:") Remember to use <a>**`Read-Search-Ask`**</a> if you get stuck. Try to pair program ![:busts_in_silhouette:](https://forum.freecodecamp.com/images/emoji/emoji_one/busts_in_silhouette.png?v=3 ":busts_in_silhouette:") and write your own code ![:pencil:](https://forum.freecodecamp.com/images/emoji/emoji_one/pencil.png?v=3 ":pencil:")

### Problem Explanation:

We need to compute and square values from the `realNumberArray` and store them in the variable `squaredIntegers` using the `map()`, `filter()`, and/or `reduce()` functions.

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 1

*   You will need to `filter()` the `realNumberArray` for positive integers (decimals are not integers).

> _try to solve the problem now_

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 2

*   You will need to `map()` the values from your `filter()` function to the variable `squaredIntegers`.

> _try to solve the problem now_

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 3

*   Remember the magic of chaining functions.

> _try to solve the problem now_

## Spoiler Alert!

![warning sign](//discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif)

**Solution ahead!**

## ![:beginner:](https://forum.freecodecamp.com/images/emoji/emoji_one/beginner.png?v=3 ":beginner:") Basic Code Solution:
```javascript
    const squareList = (arr) => {
      "use strict";
      const squaredIntegers = arr.filter( (num) => num > 0 && num % parseInt(num) === 0 ).map( (num) => Math.pow(num, 2) );
      return squaredIntegers;
    };

    // test your code
    const squaredIntegers = squareList(realNumberArray);
    console.log(squaredIntegers);
```
![:rocket:](https://forum.freecodecamp.com/images/emoji/emoji_one/rocket.png?v=3 ":rocket:") <a href='https://codepen.io/dylantyates/pen/WyWoYJ' target='_blank' rel='nofollow'>Run Code</a>

# Code Explanation:

Uses the operator `filter()` and `map()` functions to square all positive integers in a given array.

#### Relevant Links

*   <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map' target='_blank' rel='nofollow'>map()</a>
*   <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter' target='_blank' rel='nofollow'>filter()</a>
*   <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce' target='_blank' rel='nofollow'>reduce()</a>


## Alternative code solution:
```javascript
const myConcat = (arr1, arr2) => arr1.concat(arr2);
```
- [Run code at repl.it](https://repl.it/@AdrianSkar/ES6-Write-arrow-functions-with-params)

Remember that _"When there is no function body, and only a return value, arrow function syntax allows you to omit the keyword `return` as well as the brackets surrounding the code."_


### Resources

- ["Array.prototype.map()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
- ["Array.prototype.filter()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- ["Array.prototype.filter()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)
- ["Array.prototype.filter()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg5OTk5MTE0LDE2MTU5NTIxMDEsMjExNz
E3NzkwOCwtMTIwMzE1MTI5OSwtOTQ4Nzc0NTgwLC04MTk1OTgw
ODUsMjI5NzM0NjcwLC0xMTIzMTkxODYsMTk3MzQ3ODE1NywtMT
g1NDg1OTI1Myw1MTQ2MzE0MDksLTE3NDg2Nzk5MjMsMTAxOTM4
MjkyNSwtOTg5ODE5NjQ3LC0xNTMxMTA4MzI5LC0xMTE4OTc5OD
UyLDE0NjY3MDE1NzQsMTIyMTU4OTY2LDEyNzIwNDEwMjQsMTMw
NjkxODM0NV19
-->