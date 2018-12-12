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

#### Relevant Links

*   <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze' target='_blank' rel='nofollow'>Object.freeze()</a>

## ![:clipboard:](https://forum.freecodecamp.com/images/emoji/emoji_one/clipboard.png?v=3 ":clipboard:") NOTES FOR CONTRIBUTIONS:

*   ![:warning:](https://forum.freecodecamp.com/images/emoji/emoji_one/warning.png?v=3 ":warning:") **DO NOT** add solutions that are similar to any existing solutions. If you think it is **_similar but better_**, then try to merge (or replace) the existing similar solution.
*   Add an explanation of your solution.
*   Categorize the solution in one of the following categories — **Basic**, **Intermediate** and **Advanced**. ![:traffic_light:](https://forum.freecodecamp.com/images/emoji/emoji_one/traffic_light.png?v=3 ":traffic_light:")
*   Please add your username only if you have added any **relevant main contents**. (![:warning:](https://forum.freecodecamp.com/images/emoji/emoji_one/warning.png?v=3 ":warning:") **_DO NOT_** _remove any existing usernames_)

> See ![:point_right:](https://forum.freecodecamp.com/images/emoji/emoji_one/point_right.png?v=3 ":point_right:") <a href='http://forum.freecodecamp.com/t/algorithm-article-template/14272' target='_blank' rel='nofollow'>**`Wiki Challenge Solution Template`**</a> for reference.

### Resources
- ["let" - *MDN Javascript reference*](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let)
 - [Rauschmayer, Axel. "Variables and scoping in ECMAScript 6". *2ality.com*, 2015-02-07.](http://2ality.com/2015/02/es6-scoping.html) Accessed 11 Dec 2018. 
  - [Bos, Wes. "Quick Tip: Use let with for Loops in JavaScript". *wesbos.com*, 16 Aug 2016.](https://wesbos.com/for-of-es6/) Accessed 11 Dec 2018. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1ODMxMjE0MjQsMTk3MzQ3ODE1NywtMT
g1NDg1OTI1Myw1MTQ2MzE0MDksLTE3NDg2Nzk5MjMsMTAxOTM4
MjkyNSwtOTg5ODE5NjQ3LC0xNTMxMTA4MzI5LC0xMTE4OTc5OD
UyLDE0NjY3MDE1NzQsMTIyMTU4OTY2LDEyNzIwNDEwMjQsMTMw
NjkxODM0NSw2MDY3Mzc3NTMsODU4MTM4MDAsMTAxMTg4MTE5NS
wxMDY1ODczMDk3LDQ2MzMyMDI2OCwxOTEyNTM1NDQzLC01OTM4
NzIwNTJdfQ==
-->