# Programming Fundamentals: Functions 2

## Learning Objectives

- Use functions with objects to change data

## Introduction

In this exercise, you're going to give Phil an improved way to manage his cake baking!

## Setup

- Fork this repository and clone your forked version to your machine
- Install dependencies by running the command below while in the project's root directory:

`npm ci`

## Instructions

- Read through the numbered comments in `src/core.js` to understand the core requirements of this exercise.

- Write your code directly below the numbered comment.

- Add `console.log`'s to get visibility on your solution and run the file with the command `node src/core.js`

**Example**

```js
// 1. Create a variable named hello with the value 'Hello'
const hello = 'Hello'
console.log(hello)
```

## Running tests

- To verify your solutions, run the test suite by running the `npx jasmine` command followed by the path to the test file `spec/core.spec.js`:

`npx jasmine spec/core.spec.js`

- Alternatively, run `npm test`

- To begin with, all of the tests will fail. You'll see red `F`'s in your console, like the image below:

![](./img/test-fail.png)

- Your solution is complete when the red `F`'s have been replaced with green `.`'s in your console, like the image below:

![](./img/test-success.png)
