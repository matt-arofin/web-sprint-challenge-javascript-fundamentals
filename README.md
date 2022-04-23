# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks. 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results. 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 
.map() is a built-in higher order function that takes a callback as an argument when it is invoked on an array using dot notation. It returns a new array when invoked without altering the data in the original array. It is useful when you want to manipulate a dataset without changing the source - for example, when .

.reduce() is a built-in higher order function that takes a callback as an argument when it is invoked on an array using dot notation. Using the callback function, it reduces (adds/multiplies/concatenates) the contents of an array and returns a single value. This is particularly useful when dealing with an array of values that need to be summed.

.filter() is a built-in higher order function that takes a callback as an argument when it is invoked on an array using dot notation. This function returns a new array without manipulating the original. The callback function should return a boolean, which if true will then result in that item being added onto the new array. This is useful when trying to get 


2. Explain the difference between a callback and a higher order function.
A higher order function is a function which passes other functions as arguments when run, while a callback function is a function that is executed by a higher order function.

3. Explain what a closure is.
A closure is the combination of a function and the environment in which it operates - it is formed when an inner function reaches into the scope of the outer function that houses it to search for a variable that is defined there.

4. Describe the four principles of the 'this' keyword.
Window binding is the default binding of all functions - when a function is freely invoked (ie. without dot syntax), "this" is automatically bound to the global object window in node or simply returns "undefined" in strict mode.

Implicit binding is when a function (method) is invoked using dot notation - in such instances, "this" becomes whatever object or variable is to the left of the dot.

Explicit binding is when uses method invocation to bind "this" to a specific object context - when .apply(), .call(), or .bind() are invoked, the first parameter passed through the function's bracket becomes the context for "this". While .call() immediately invokes the function with arguments passed to it individually, .apply() does the same thing but takes arguments in the form of an array instead, and .bind() creates a new function which is not immediately invoked but also takes individual arguments.

New binding (Keyword binding) specifically involves using the "new" keyword when calling constructor functions - in this case, "this" points to the new object that is about to be created.

5. Why do we need super() in an extended class?
super() replaces the functionality of the .call(), .apply() and .bind() methods of pseudclassical inheritance and is used to pass the properties of the child class through to the parent class.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your repo to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/master; your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://bloomtech.notion.site/bloomtech/BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) (see part 2, submitting an assignment with codegrade).
