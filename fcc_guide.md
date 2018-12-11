---
title: Compare Scopes of the var and let Keywords
---

![:triangular_flag_on_post:](https://forum.freecodecamp.com/images/emoji/emoji_one/triangular_flag_on_post.png?v=3 ":triangular_flag_on_post:") Remember to use <a>**`Read-Search-Ask`**</a> if you get stuck. Try to pair program ![:busts_in_silhouette:](https://forum.freecodecamp.com/images/emoji/emoji_one/busts_in_silhouette.png?v=3 ":busts_in_silhouette:") and write your own code ![:pencil:](https://forum.freecodecamp.com/images/emoji/emoji_one/pencil.png?v=3 ":pencil:")

### Problem Explanation:

We need to change `var` to `let` in our function scope and add `let` to our block scope.

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 1

*   Find `var` and replace with `let`.

> _try to solve the problem now_

*   Add `let` to the variable `i` inside of your if statement.

> _try to solve the problem now_

## Spoiler Alert!

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
![:rocket:](https://forum.freecodecamp.com/images/emoji/emoji_one/rocket.png?v=3 ":rocket:") <a href='https://codepen.io/dylantyates/pen/wxwxRd' target='_blank' rel='nofollow'>Run Code</a>


# Code Explanation:

By using `let` you can declare variables in relation to their scope.

### Resources
- ["let" - *MDN Javascript reference*](https://developer.mozilla.org/en-US/docs/Glossary/Boolean)


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4NTQ4NTkyNTMsNTE0NjMxNDA5LC0xNz
Q4Njc5OTIzLDEwMTkzODI5MjUsLTk4OTgxOTY0NywtMTUzMTEw
ODMyOSwtMTExODk3OTg1MiwxNDY2NzAxNTc0LDEyMjE1ODk2Ni
wxMjcyMDQxMDI0LDEzMDY5MTgzNDUsNjA2NzM3NzUzLDg1ODEz
ODAwLDEwMTE4ODExOTUsMTA2NTg3MzA5Nyw0NjMzMjAyNjgsMT
kxMjUzNTQ0MywtNTkzODcyMDUyLC02Mzk1MzU5MjAsNTc4MjUw
MDAwXX0=
-->