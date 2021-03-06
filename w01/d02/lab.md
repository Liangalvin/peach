#### Exercise: Grabbing input from the user in the browser

**Cheatsheet**

```
var color = prompt(“What is your favorite color?”)
```
**Steps**:
 1. Create an html file with a script tag in it to write some Javascript code
 2. Prompt the user for their name using the ```prompt``` function
 3. Use ```document.write``` to print to the browser window a message including their name

####FizzBuzz

**Cheatsheet**

In javascript there exists the remainder operator ```%``` to grab the remainder when one number is divided by another.

For instance ```12 % 5``` is ```2```, because ```5``` goes into ```12``` twice with one remainder of two.

Note: the remainder operator is sometimes called the modulo operator.

Use these references as your guides:

- [MDN guide]( https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Arithmetic_Operators#Remainder_%28.25%29)
- [IE guide](http://msdn.microsoft.com/en-us/library/ie/9f59bza0%28v=vs.94%29.aspx)

**Challenge**:

Write a program in javascript that takes one integer as an argument. If the argument is divisible by 3 return "Fizz", if the argument is divisible by 5 return "Buzz", and if the argument is divisible by both 3 AND 5 return "FizzBuzz". Otherwise return just the argument itself.  

Hint: if a number is perfectly divisible by another number it has a remainder of zero.


#### The Vegan Test

*On the menu tonight: Steak, fruit salad, tofurkey, pork chops.*

  - Write a program in javascript that takes one menu item as an argument.
    - If a vegan can eat it, return "This cuisine is vegan friendly."
    - Otherwise, return "Vegans beware!"
  - For the sake of this exercise. Tofurkey is definitely vegan friendly.

**Hint**: Two identical strings are considered to be equal to each other.
