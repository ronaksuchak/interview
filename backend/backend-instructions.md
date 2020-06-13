# Luhn Checksum Exercise

## Overview

Create a PHP program that outputs the validity of a number by applying the [Luhn Checksum](http://en.wikipedia.org/wiki/Luhn_algorithm).

**Input:**

The program should accept a single number to validate.
 
**Output:**

The program should output the input along with the validity of the number.
 
**Examples:**

Given an input of `79927398713`, the output should be:

```
79927398713 is valid.
```
 
Given an input of `79927398710`, the output should be:

```
79927398710 is not valid.
```

## Guidelines
1. There are many solutions and code snippets online implementing the Luhn Checksum. Please resist using those. We want to see your coding style and approach to problem solving.
1. Please treat this as you would any other task you'd encounter during your daily work. This will show us how you currently code and not how you coded 6, 12, or 18 months ago.
1. Your code should be suitably tested. This means including a few automated tests with your work as well as instructions on how to run them (a simple README is fine).
    - We recommend a simple PHP script that loads your Luhn Checksum class and compares its output to known good/bad values.
    - Or, feel free to use [PHPUnit](https://phpunit.de) or something similar.
    - In the end, use whatever will get you a few automated tests to include with your code as quickly and painlessly as possible.
1. Your code should gracefully handle invalid input and errors.
1. Please do not feel that you need to spend a great deal of time working on a solution. Hopefully completing this exercise won't take more than an hour or two.


## Credits

Adapted from: https://gist.github.com/tomharris/bc9a942bcd25e029e746