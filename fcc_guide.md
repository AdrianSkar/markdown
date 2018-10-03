---
title: Golf Code
---
![:triangular_flag_on_post:](https://forum.freecodecamp.com/images/emoji/emoji_one/triangular_flag_on_post.png?v=3 ":triangular_flag_on_post:") Remember to use <a>**`Read-Search-Ask`**</a> if you get stuck. Try to pair program ![:busts_in_silhouette:](https://forum.freecodecamp.com/images/emoji/emoji_one/busts_in_silhouette.png?v=3 ":busts_in_silhouette:") and write your own code ![:pencil:](https://forum.freecodecamp.com/images/emoji/emoji_one/pencil.png?v=3 ":pencil:")

### ![:checkered_flag:](https://forum.freecodecamp.com/images/emoji/emoji_one/checkered_flag.png?v=3 ":checkered_flag:") Problem Explanation:

In the game of golf each hole has a **par** meaning the average number of **strokes** a golfer is expected to make in order to sink the ball in a hole to complete the play. Depending on how far above or below **par** your **strokes** are, there is a different nickname.

Your function will be passed **par** and **strokes** arguments. You've to return the correct string according to this table which lists the strokes in order of priority; top (highest) to bottom (lowest):

Strokes | Return  
:--------- | :-------------  
1 | "Hole-in-one!"  
<= par - 2 | "Eagle"  
par - 1 | "Birdie"  
par | "Par"  
par + 1 | "Bogey"  
par + 2 | "Double Bogey"
&gt;= par + 3 | "Go Home!"

**par** and **strokes** will always be numeric and positive.

*   Change the code below `// Only change code below this line` and above `// Only change code above this line`.
*   Ensure that you're editing the inside of the `golfScore` function.
*   You will have to make the function return exactly the same string as shown shown in the table, depending on the value of the parameters **par** and **strokes** that are passed to your function.

#### Relevant Links

*   <a href='https://en.wikipedia.org/wiki/Golf' target='_blank' rel='nofollow'>Golf</a>
*   <a href='http://www.freecodecamp.com/challenges/chaining-if-else-statements' target='_blank' rel='nofollow'>Challenge: Chaining If Else Statements</a>
*   <a href='http://www.freecodecamp.com/challenges/comparison-with-the-greater-than-equal-to-operator' target='_blank' rel='nofollow'>Challenge: Comparison with the Greater Than Equal To Operator</a>
*   <a href='http://www.freecodecamp.com/challenges/comparison-with-the-less-than-equal-to-operator' target='_blank' rel='nofollow'>Challenge: Comparison with the Less Than Equal To Operator</a>

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 1

`+number -number` can be used to increase or decrease a parameter in your condition.

> _try to solve the problem now_

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 2

You use `if / else if` chains to return different values in different scenarios.

> _try to solve the problem now_

## ![:speech_balloon:](https://forum.freecodecamp.com/images/emoji/emoji_one/speech_balloon.png?v=3 ":speech_balloon:") Hint: 3

Control the flow of your function based on the tables order of priority - top (highest) to bottom (lowest) to return matching string values.

> _try to solve the problem now_

## Spoiler Alert!

![warning sign](//discourse-user-assets.s3.amazonaws.com/original/2X/2/2d6c412a50797771301e7ceabd554cef4edcd74d.gif)

**Solution ahead!**

## ![:beginner:](https://forum.freecodecamp.com/images/emoji/emoji_one/beginner.png?v=3 ":beginner:") Basic Code Solution:

    function golfScore(par, strokes) {
      // Only change code below this line
      if (strokes == 1){
        return "Hole-in-one!";
      } else if (strokes <= par -2){
        return "Eagle";
      } else if (strokes == par -1) {
        return "Birdie";
      } else if (strokes == par) {
        return "Par";
      } else if (strokes == par +1) {
        return "Bogey";
      } else if (strokes == par +2) {
        return "Double Bogey";
      } else {
        return "Go Home!";
      }
      // Only change code above this line
    }
    // Change these values to test
    golfScore(5, 4);

### Code Explanation:

*   Compare the parameters **par** and **strokes** to return appropriate string values.
*   `if / else if` chain is used for flow control.
*   String "Go Home!" is returned for every condition where **strokes** is greater than or equal to **par + 3**.

<!--stackedit_data:
eyJoaXN0b3J5IjpbODIwODE1Mjg3LC0xMTU2NDMyNjI2LC01OT
g5MjU0MDYsLTk5MjM0NjI5NywtMTM2NTAwNzc1NSwzNTUxNDMw
NDcsLTEyNTM4ODIzNzgsLTE0NDQwODQyNDQsLTEwOTIwMTY2Mz
UsMjkxNDcwMTgsLTE5MzU0MTYyMzAsLTE3MDM0OTE0NjUsLTEz
MDcxNzk0NjUsMTUxNjQ3MjA4MiwtMzg5MTI0NTU0LC04OTcxOD
c2MTIsMjk4MDAyNTE5LDk5ODA4NTkyNywtMTMzNzI3MDU4Niwt
MTUwODkxMjMxNF19
-->