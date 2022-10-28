# Unit 2 - JavaScript Foundations

## Making the Test Pass
* The Unit Tests are located in `answers.test.js`. You can look inside that file. It's not magic. 🧙🏾‍♂️
* In order for me to accept your submission, all of my tests must pass.
    1. From this project's **root directory** (not this current directory), install the test with `npm install`. (Do this only one time)
    2. Run your test with `npm test`. (Run this command often to see if your functions are passing)

## Coding Exercises

1. Write a function that takes a name and **returns** a greeting with `"Good morning"` and the person's name.

    Example:
    ```javascript
    greet("Carmen"); // "Good morning, Carmen!"
    greet("Devonte"); // "Good morning, Devonte!"
    greet("Reuben Ogbonna"); // "Good morning, Reuben Ogbonna!"
    ```

2. Write a function that returns the [area of a rectangle](https://www.khanacademy.org/math/cc-third-grade-math/imp-geometry/imp-multiply-to-find-area/a/area-rectangles-review), given a length and width:

    Examples:
    ```javascript
    area(5, 7); // 35
    area(15, 10); // 150
    area(25.75, 42); // 1081.5
    ```

3. You are given two angles (in degrees) of a triangle. Write a function to find and return the [3rd degree](https://www.aaamath.com/geo612x5.htm) **Note:** only positive integers will be tested.
    Examples:
    ```javascript
    otherAngle(30, 60); // 90
    otherAngle(60, 60); // 60
    otherAngle(43, 78); // 59
    otherAngle(10, 20); // 150
    ```

4. Write a function that returns the [diameter of a cicle, given its area](https://socratic.org/questions/how-do-you-find-diameter-of-a-circle-with-area):

    Examples:
    ```javascript
    diameterFromArea(10); // 3.5682482323055424
    diameterFromArea(100); // 11.283791670955125
    ```

5. Write a function that calculates the total price of the bill, after tax. The function should take two arguments, a price and a percentage, and it should return the total price.

    Examples:
    ```javascript
    totalPrice(100, 5); // 105;
    totalPrice(250, 20); // 300;
    totalPrice(1, 18); // 1.18;
    ```

6. Write a function that takes two strings as arguments, determines the longer of the two strings, and then returns the result of concatenating the shorter string, the longer string, and the shorter string once again. You may assume that the strings are of different lengths.

    Examples:
    ```javascript
    shortLongShort('abc', 'defgh');    // "abcdefghabc"
    shortLongShort('abcde', 'fgh');    // "fghabcdefgh"
    shortLongShort('', 'xyz');         // "xyz"
    ```

7. Write a function that takes one argument, a positive integer, and returns a string of alternating `'1'`s and `'0'`s, always starting with a `'1'`. The length of the string should match the given integer.

    Examples:
    ```javascript
    stringy(6);    // "101010"
    stringy(9);    // "101010101"
    stringy(4);    // "1010"
    stringy(7);    // "1010101"
    ```

8. Write a describeAge function that takes a parameter age (which will always be a positive integer) and does the following:

    If the age is 12 or lower, it returns `"You're a kid."`
    If the age is anything between 13 and 17 (inclusive), it returns `"You're a teenager."`
    If the age is anything between 18 and 64 (inclusive), it return `"You're an adult."`
    If the age is 65 or above, it return `"You're an elderly."`
    **Bonus:** write this function using as few lines of code as possible. Up for a challenge? This function can be written in one-line using ternary operator(s) 😳.

    Examples:
    ```javascript
    describeAge(11); // "You're a kid."
    describeAge(13); // "You're a teenager."
    describeAge(19); // "You're an adult."
    describeAge(64); // "You're an adult."
    describeAge(64); // "You're an adult."
    describeAge(99); // "You're an elderly."
    ```


9. Leap years occur in every year that is evenly divisible by 4, unless the year is also divisible by 100. If the year is evenly divisible by 100, then it is not a leap year, unless the year is also evenly divisible by 400.

    Assume this rule is valid for any year greater than year 0. Write a function that takes any year greater than 0 as input, and returns true if the year is a leap year, or false if it is not a leap year.

    Examples:
    ```javascript
    isLeapYear(2016); // true
    isLeapYear(2015); // false
    isLeapYear(2100); // false
    isLeapYear(2400); // true
    isLeapYear(1900); // false
    isLeapYear(1752); // true
    isLeapYear(1700); // false
    ```



As always, when you are done, commit and push.
