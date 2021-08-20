# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

.map is a method used on an array to create a new array, with all items in the array altered in some way. For example if you have an array of numbers like [1,2,3,4,5] but want to multiply all the values by 2 you can use the .map method to convert that array to [2,4,6,8,10].

.reduce is a method used on arrays that returns a result, typically an answer from an addition or multiplication computation. Let's say you have an array that holds the populations of individual cities but you want the total population amount, .reduce would be a great use case to get that single value. 

.filter is a method used on an array to create a new array that is smaller and filters out certain items by a set condition. A use case for this method would be wanting to create a new array that only has certain items. Let's say you have an array of cities but you only want to see which ones have a population greater than 1 million residents, .filter would be a great way to create that new array of large cities. 

2. Explain the difference between a callback and a higher order function.

A callback function gets passed through a higher order function as an argument. A higher order function is the one that receives the callback as their argument. 

3. Explain what a closure is.

Closure is when an inner function reaches outside of it's scope to access another function or variable. 

4. Describe the four principles of the 'this' keyword.

A. global/window

When used in the global scope the 'this' keyword will refer to the window object.

B. Implicit

When creating a method as an objects key the 'this' keyword is used to reference that specific object

C. Explicit

Explicit use of the keyword 'this' is used when creating new functions using methods like .call or .bind

D. New

When creating a constructor function you use the 'this' keyword to refer to the new object that has yet to be made. 

5. Why do we need super() in an extended class?

You need super() to inherit the attributes of the Parent class, it replaces the .call method. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


X 1. Fork the repo
X 2. Clone your forked version of the repo
X 3. cd into your repo and create a branch with your first and last name
X 4. open the terminal in your vs code and type `npm install`
X 5. next type `npm run test` in your terminal
X 6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

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
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

