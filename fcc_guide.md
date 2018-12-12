---
title: Prevent Object Mutation
---
![:triangular_flag_on_post:](https://forum.freecodecamp.com/images/emoji/emoji_one/triangular_flag_on_post.png?v=3 ":triangular_flag_on_post:") Remember to use <a>**`Read-Search-Ask`**</a> if you get stuck. Try to pair program ![:busts_in_silhouette:](https://forum.freecodecamp.com/images/emoji/emoji_one/busts_in_silhouette.png?v=3 ":busts_in_silhouette:") and write your own code ![:pencil:](https://forum.freecodecamp.com/images/emoji/emoji_one/pencil.png?v=3 ":pencil:")

### Problem Explanation:

We need to prevent `MATH_CONSTANTS` value from changing.

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 1

*   Use Object.freeze(obj) to prevent object from being changed.

> _try to solve the problem now_

## Spoiler Alert!

![warning sign](//discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif)

**Solution ahead!**

## ![:beginner:](https://forum.freecodecamp.com/images/emoji/emoji_one/beginner.png?v=3 ":beginner:") Basic Code Solution:
```javascript
    function freezeObj() {
      "use strict";
      const MATH_CONSTANTS = {
        PI: 3.14
      };

      Object.freeze(MATH_CONSTANTS);
      
      try {
        MATH_CONSTANTS.PI = 99;
      } catch( ex ) {
        console.log(ex);
      }
      return MATH_CONSTANTS.PI;
    }
    
    const PI = freezeObj();
```
![:rocket:](https://forum.freecodecamp.com/images/emoji/emoji_one/rocket.png?v=3 ":rocket:") <a href='https://codepen.io/dylantyates/pen/OwVxYB' target='_blank' rel='nofollow'>Run Code</a>

# Code Explanation:

By using Object.freeze() on `MATH_CONSTANTS` we can avoid manipulating it.


### Resources
- ["Object.freeze()" - *MDN Javascript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5NzA5NzMzNzAsMTk3MzQ3ODE1NywtMT
g1NDg1OTI1Myw1MTQ2MzE0MDksLTE3NDg2Nzk5MjMsMTAxOTM4
MjkyNSwtOTg5ODE5NjQ3LC0xNTMxMTA4MzI5LC0xMTE4OTc5OD
UyLDE0NjY3MDE1NzQsMTIyMTU4OTY2LDEyNzIwNDEwMjQsMTMw
NjkxODM0NSw2MDY3Mzc3NTMsODU4MTM4MDAsMTAxMTg4MTE5NS
wxMDY1ODczMDk3LDQ2MzMyMDI2OCwxOTEyNTM1NDQzLC01OTM4
NzIwNTJdfQ==
-->