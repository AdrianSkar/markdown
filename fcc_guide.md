---
title: Prevent Object Mutation
---
![:triangular_flag_on_post:](https://forum.freecodecamp.com/images/emoji/emoji_one/triangular_flag_on_post.png?v=3 ":triangular_flag_on_post:") Remember to use <a>**`Read-Search-Ask`**</a> if you get stuck. Try to pair program ![:busts_in_silhouette:](https://forum.freecodecamp.com/images/emoji/emoji_one/busts_in_silhouette.png?v=3 ":busts_in_silhouette:") and write your own code ![:pencil:](https://forum.freecodecamp.com/images/emoji/emoji_one/pencil.png?v=3 ":pencil:")

### Problem explanation:

_You need to freeze the `MATH_CONSTANTS` object so that no one is able to alter the value of `PI`, add, or delete properties ._

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 1

*   _Use `Object.freeze()` to prevent mathematical constants from changing._

> _try to solve the problem now_

## Spoiler alert!

![warning sign](//discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif)

**Solution ahead!**

## ![:beginner:](https://forum.freecodecamp.com/images/emoji/emoji_one/beginner.png?v=3 ":beginner:") Basic code solution:
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
![:rocket:](https://forum.freecodecamp.com/images/emoji/emoji_one/rocket.png?v=3 ":rocket:")[Run code at codepen.io](https://codepen.io/dylantyates/pen/OwVxYB)

# Code explanation:

By using Object.freeze() on `MATH_CONSTANTS` we can avoid manipulating it.


### Resources
- ["Object.freeze()" - *MDN Javascript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMjI5NzM0NjcwLC0xMTIzMTkxODYsMTk3Mz
Q3ODE1NywtMTg1NDg1OTI1Myw1MTQ2MzE0MDksLTE3NDg2Nzk5
MjMsMTAxOTM4MjkyNSwtOTg5ODE5NjQ3LC0xNTMxMTA4MzI5LC
0xMTE4OTc5ODUyLDE0NjY3MDE1NzQsMTIyMTU4OTY2LDEyNzIw
NDEwMjQsMTMwNjkxODM0NSw2MDY3Mzc3NTMsODU4MTM4MDAsMT
AxMTg4MTE5NSwxMDY1ODczMDk3LDQ2MzMyMDI2OCwxOTEyNTM1
NDQzXX0=
-->