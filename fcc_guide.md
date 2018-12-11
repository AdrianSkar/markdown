---
title: Compare Scopes of the var and let Keywords
---

![:triangular_flag_on_post:](https://forum.freecodecamp.com/images/emoji/emoji_one/triangular_flag_on_post.png?v=3 ":triangular_flag_on_post:") Remember to use <a>**`Read-Search-Ask`**</a> if you get stuck. Try to pair program ![:busts_in_silhouette:](https://forum.freecodecamp.com/images/emoji/emoji_one/busts_in_silhouette.png?v=3 ":busts_in_silhouette:") and write your own code ![:pencil:](https://forum.freecodecamp.com/images/emoji/emoji_one/pencil.png?v=3 ":pencil:")

### Problem explanation:

_Fix the code so that `i` declared in the if statement is a separate variable than `i` declared in the first line of the function._

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 1

*  _Be certain not to use the `var` keyword anywhere in your code._

> _try to solve the problem now_

*   Remember that `let`'s scope is limited to the block, function or statement in which you declare it.
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
 - [Rauschmayer, Axel. "Variables and scoping in ECMAScript 6". *2ality.com*, 2015-02-07.](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839) Accessed 11 Dec 2018. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MjkzODM5ODksLTE4NTQ4NTkyNTMsNT
E0NjMxNDA5LC0xNzQ4Njc5OTIzLDEwMTkzODI5MjUsLTk4OTgx
OTY0NywtMTUzMTEwODMyOSwtMTExODk3OTg1MiwxNDY2NzAxNT
c0LDEyMjE1ODk2NiwxMjcyMDQxMDI0LDEzMDY5MTgzNDUsNjA2
NzM3NzUzLDg1ODEzODAwLDEwMTE4ODExOTUsMTA2NTg3MzA5Ny
w0NjMzMjAyNjgsMTkxMjUzNTQ0MywtNTkzODcyMDUyLC02Mzk1
MzU5MjBdfQ==
-->