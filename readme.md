# Dinosaur Museum Project

The _Dinosaur Museum_ is opening! You've been tasked with building some challenging functionality for the automated systems recently installed at the museum.

To complete this project, you will need to write a number of difficult functions that will support attendees in finding out information about dinosaurs, finding the dinosaur's location, and calculating their entry fees.

## Project setup

### Getting started

1. Fork and clone this repository.

1. Navigate to the cloned repository's directory on your command line. Then, run the following command:

   ```
   npm install
   ```

   This will install the libraries needed to run the tests.

1. Open up the repository in VSCode. Follow the instructions below to complete the Lab.

### Tests

To run the tests, you can run the following command from the command line. You will need to be in the root directory of your local directory.

```
npm test
```

This will run the test output once.

### Test watcher

If you'd like, you can have the tests run constantly. 
This means that each time you save your file, your tests will re-run. 
To do so, you can run the following:

```
npm run watch
```

Follow the on-screen prompts to exit out of the constant runner.

### Run test files individually

There are a lot of tests that are contained in this project. 
You can run a single test file individually by putting the name of the file after `npm test`. 
You can even only put part of the file name.

```
npm test facts
```

Keep in mind that the testing framework, Jest, will attempt to match as many files as possible. So, for example, the following command will run all of the tests because all of the tests are inside of the `dinosaur-museum-project/` folder.

```
npm test dinosaur
```

### Run tests individually

_After choosing a specific file to run,_ you can also specific which test you want to run, specifically. Add `.only` after either `test` or `describe` for the specific test you'd like to run.

```js
test.only("should return an array of everyone's name who is in the line, in order", () => {
```

This will either run the specific `test` or, in the case of adding `.only` to a `describe`, all of the tests for a specific function.

> **NOTE:** Don't forget to remove this after you get the test to pass!

### Run file

If you want to manually test out your file, you can do so by running the following command.

```
node index.js
```

The output will be printed to your terminal.

## Instructions

### Project overview

Each file under the `src/` directory contains two or three functions that you will need to complete. Follow the JSDoc comments and tests to understand what needs to be completed.

Each of these functions is quite challenging. You will need to apply everything you've learned to solve each one.

Before you start coding, remember Polya's problem solving methodology; begin by _understanding the problem,_ then _devise a plan._ Only after accomplishing those two steps should you start writing your code.
"Polya's problem solving methodology"
"Understand the problem, make a plan, execute the plan, and look back and reflect"

### Tips

- `\n` represents a new line in text. For example, take a look at the following code.

  ```js
  console.log("Each\nNew\nLine!");
  ```

  This will output in the following way:

  ```
  Each
  New
  Line!
  ```

- Start small for each of the functions. Many of the functions require you to solve for some edge-case. First, design a function that works for a single case and then expand outwards. It is likely that you will incrementally have more and more tests passing, as opposed to all of them passing at once.
