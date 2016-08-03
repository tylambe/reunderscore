# Overview

Underscore is an expansive JavaScript library that abstracts dozens of incredibly useful processes into easy-to-use functions. By nature, these functions are stored as methods in an object saved as the _ property on the global window object.

While being able to use underscore will make you a stronger programmer, knowing exactly how each of these functions are put together will enhance your understanding not just of functions, but also the objects, Booleans, and other data types you use already. This is a library complete with a testing suite to help you hone your chops.

## Installation
======
Almost none! Here are two different ways to get started:

#### Git
======
Go to your command line and enter `git clone https://github.com/tylambe/reunderscore`

#### Download as a .zip file
======
Scroll up on this page to the green 'Clone or download' button, click 'Download as Zip', and find the folder titled 'reunderscore' wherever your browser usually downloads files. Unzip and you will have access to the project folder.

## Usage
======
```
reunderscore
  |-lib                 # Contains testing libraries and SpecRunner styling
  |-spec
    |---part1.js        # Tests for Part 1
    |---part2.js        # Tests for Part 2
  |-src
    |---reunderscore.js # Complete the functions in this file to make the tests pass.
  |-SpecRunner.html     # Open this file in your browser to check your progress.
```
As you complete the functionality for each function in reunderscore.js, refresh the SpecRunner.html file in your browser to see if your functions pass each test. If you are failing a test, consider the assertion provided by a specific test and write the proper functionality.
