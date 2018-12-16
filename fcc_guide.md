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

## Spoiler alert!

![warning sign](//discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif)

**Solution ahead!**

## ![:beginner:](https://forum.freecodecamp.com/images/emoji/emoji_one/beginner.png?v=3 ":beginner:") Code solution:
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
![:rocket:](https://forum.freecodecamp.com/images/emoji/emoji_one/rocket.png?v=3 ":rocket:")[Run code at codepen.io](https://codepen.io/dylantyates/pen/WyWoYJ)
# Code explanation:

Uses the operator `filter()` and `map()` functions to square all positive integers in a given array.


## Alternative code solution:
```javascript

  // change code below this line
  const squaredIntegers = arr.filter((param) => Number.isInteger(param) && param >= 0).map(x => x * x);
  // change code above this line

```
- [Run code at repl.it](https://repl.it/@AdrianSkar/ES6-Write-higher-order-arrow-functions)

Remember that _"When there is no function body, and only a return value, arrow function syntax allows you to omit the keyword `return` as well as the brackets surrounding the code."_


### Resources

- ["Array.prototype.map()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)
- ["Array.prototype.filter()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
- ["Array.prototype.reduce()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)
- ["Number.isInteger()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number/isInteger)
- ["Math.pow()" - *MDN JavaScript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/pow)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTYxMjAzMjkwMSwxOTQ3MDE5NTM3LDE2MT
U5NTIxMDEsMjExNzE3NzkwOCwtMTIwMzE1MTI5OSwtOTQ4Nzc0
NTgwLC04MTk1OTgwODUsMjI5NzM0NjcwLC0xMTIzMTkxODYsMT
k3MzQ3ODE1NywtMTg1NDg1OTI1Myw1MTQ2MzE0MDksLTE3NDg2
Nzk5MjMsMTAxOTM4MjkyNSwtOTg5ODE5NjQ3LC0xNTMxMTA4Mz
I5LC0xMTE4OTc5ODUyLDE0NjY3MDE1NzQsMTIyMTU4OTY2LDEy
NzIwNDEwMjRdfQ==
-->