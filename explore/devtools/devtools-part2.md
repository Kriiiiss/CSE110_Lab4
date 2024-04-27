# Devtools-part2

1. What was the bug?

The bug is that `document.getElementById("num1").value;` and `document.getElementById("num2").value;` methods retrieve the user input as strings. When `num1` and `num2` are passed to the `calculateSum()` function, they are concatenated rather than being mathematically added. For example, if num1 is "3" and num2 is "4", the function outputs "34" instead of performing the expected sum, which should be 7.

2. How would you fix it?
 
Since the type of `num1` and `num2` are string, I convert the type from string to number by using method Number(). In the function `calculateSum()`, I change the type of `num1` and `num2` so that they can be mathematically added. Finally, the result will return the output and get and expect output. 
