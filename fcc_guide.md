---
title: Explore Differences Between the var and let Keywords
---
![:triangular_flag_on_post:](https://forum.freecodecamp.com/images/emoji/emoji_one/triangular_flag_on_post.png?v=3 ":triangular_flag_on_post:") Remember to use **`Read-Search-Ask`** if you get stuck. Try to pair program ![:busts_in_silhouette:](https://forum.freecodecamp.com/images/emoji/emoji_one/busts_in_silhouette.png?v=3 ":busts_in_silhouette:") and write your own code ![:pencil:](https://forum.freecodecamp.com/images/emoji/emoji_one/pencil.png?v=3 ":pencil:")

### Problem Explanation:

We need to change each `var` to `let` in our code.

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 1

*   Find each `var` and replace with `let`.

> _try to solve the problem now_

## Spoiler Alert!

![warning sign](//discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif)

**Solution ahead!**

## ![:beginner:](https://forum.freecodecamp.com/images/emoji/emoji_one/beginner.png?v=3 ":beginner:") Basic Code Solution:
```javascript
    let catName;
    let quote;
    function catTalk() {
      "use strict";

      catName = "Oliver";
      quote = catName + " says Meow!";

    }
    catTalk();
```
![:rocket:](https://forum.freecodecamp.com/images/emoji/emoji_one/rocket.png?v=3 ":rocket:") <a href='https://codepen.io/dylantyates/pen/eKqoGY' target='_blank' rel='nofollow'>Run Code</a>

# Code Explanation:

By using `let` instead of `var` we can avoid overriding `catName` and `quote`.

#### Relevant Links

*   <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/var' target='_blank' rel='nofollow'>var</a>
*   <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let' target='_blank' rel='nofollow'>let</a>


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5NzU0MzU5OTMsLTE1MzExMDgzMjksLT
ExMTg5Nzk4NTIsMTQ2NjcwMTU3NCwxMjIxNTg5NjYsMTI3MjA0
MTAyNCwxMzA2OTE4MzQ1LDYwNjczNzc1Myw4NTgxMzgwMCwxMD
ExODgxMTk1LDEwNjU4NzMwOTcsNDYzMzIwMjY4LDE5MTI1MzU0
NDMsLTU5Mzg3MjA1MiwtNjM5NTM1OTIwLDU3ODI1MDAwMCwtMz
YxNTEzMjE4LC0xNjI5NTYxMDU5LC0xNjM1NzA3NTMxLC01MTcy
MjM2MzVdfQ==
-->