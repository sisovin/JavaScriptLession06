# Booleans and if-Statement in JavaScript

## Table of Contents
1. [Introduction](#introduction)
2. [Booleans in JavaScript](#booleans-in-javascript)
3. [if-Statement in JavaScript](#if-statement-in-javascript)
4. [Examples](#examples)
   - [Simple if statement](#simple-if-statement)
   - [if-else statement](#if-else-statement)
   - [if-else if-else statement](#if-else-if-else-statement)
5. [Exercises](#exercises)
   - [Sample Project](#sample-project)
   - [Exercise 6abc - 6cdefg - 6hijk](#exercise-6abc---6cdefg---6hijk)

## Introduction
This lesson covers Booleans and if-Statements in JavaScript. Booleans are a data type that can only have two values: `true` or `false`. They are often used in conditions to decide which code should be executed.

## Booleans in JavaScript
Booleans in JavaScript are a fundamental data type that represent truth values. They can only be one of two values: `true` or `false`. These values are often the result of comparisons or conditions and are crucial for control flow in programming, such as in if statements, loops, and any other place where a decision needs to be made based on whether something is true or false.

### Overview:
- **true**: This represents something that is correct, on, or affirmative. In logical operations, true often represents a condition that has been met or an affirmative decision.
- **false**: Conversely, this represents something that is incorrect, off, or negative. In logical operations, false often represents a condition that has not been met or a negative decision.

## if-Statement in JavaScript
An `if` statement in JavaScript is used to execute a block of code only if a specified condition is true. If the condition is false, the code inside the block is not executed.

### Syntax:
```javascript
if (condition) {
  // code to be executed if condition is true
}
```

### Extended Syntax with else if and else:
```javascript
if (condition1) {
  // code to be executed if condition1 is true
} else if (condition2) {
  // code to be executed if condition2 is true
} else {
  // code to be executed if none of the conditions are true
}
```

## Examples

### Simple if statement:
```javascript
let score = 75; // Set the score to 75

if (score > 70) {
  console.log("Pass");
}
// Output: Pass
```

### if-else statement:
```javascript
let score = 60; // Set the score to 60

if (score > 70) {
  console.log("Pass");
} else {
  console.log("Fail");
}
// Output: Fail
```

### if-else if-else statement:
```javascript
let score = 60; // Set the score to 60

if (score > 70) {
  console.log("Pass");
} else if (score >= 50) {
  console.log("Resit");
} else {
  console.log("Fail");
}
// Output: Resit
```

## Exercises

### Sample Project
- [Rock Paper Scissors](src/rock-paper-scissors.html)

### Exercise 6abc - 6cdefg - 6hijk
- [6abc](src/6abc.html)
- [6de](src/6de.html)
- [6fghij](src/6fghij.html)
- [Cart Quantity](src/cartquantity.html)
