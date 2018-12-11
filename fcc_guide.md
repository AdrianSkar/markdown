---
title: Compare Scopes of the var and let Keywords
---

![:triangular_flag_on_post:](https://forum.freecodecamp.com/images/emoji/emoji_one/triangular_flag_on_post.png?v=3 ":triangular_flag_on_post:") Remember to use <a>**`Read-Search-Ask`**</a> if you get stuck. Try to pair program ![:busts_in_silhouette:](https://forum.freecodecamp.com/images/emoji/emoji_one/busts_in_silhouette.png?v=3 ":busts_in_silhouette:") and write your own code ![:pencil:](https://forum.freecodecamp.com/images/emoji/emoji_one/pencil.png?v=3 ":pencil:")

### Problem explanation:

We need to change `var` to `let` in our function scope and add `let` to our block scope.

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 1

*   Find `var` and replace with `let`.

> _try to solve the problem now_

*   Add `let` to the variable `i` inside of your if statement.

> _try to solve the problem now_

## Spoiler alert!

![warning sign](//discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif)

**Solution ahead!**

## ![:beginner:](https://forum.freecodecamp.com/images/emoji/emoji_one/beginner.png?v=3 ":beginner:") Basic Code Solution:
```javascript
    function checkScope() {
      "use strict";
      let i = "function scope";
      if (true) {
        let i = "block scope";
        console.log("Block scope i is: ", i);
      }
    console.log("Function scope i is: ", i);
    return i;
    }
```
![:rocket:](https://forum.freecodecamp.com/images/emoji/emoji_one/rocket.png?v=3 ":rocket:") [Run code at codepen.io](https://codepen.io/dylantyates/pen/wxwxRd)


# Code Explanation:

By using `let` you can declare variables in relation to their scope.

### Resources
- ["let" - *MDN Javascript reference*](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY1MzQ4NzQ2MSwtMTg1NDg1OTI1Myw1MT
Q2MzE0MDksLTE3NDg2Nzk5MjMsMTAxOTM4MjkyNSwtOTg5ODE5
NjQ3LC0xNTMxMTA4MzI5LC0xMTE4OTc5ODUyLDE0NjY3MDE1Nz
QsMTIyMTU4OTY2LDEyNzIwNDEwMjQsMTMwNjkxODM0NSw2MDY3
Mzc3NTMsODU4MTM4MDAsMTAxMTg4MTE5NSwxMDY1ODczMDk3LD
Q2MzMyMDI2OCwxOTEyNTM1NDQzLC01OTM4NzIwNTIsLTYzOTUz
NTkyMF19
-->