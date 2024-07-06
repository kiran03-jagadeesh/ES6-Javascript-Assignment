# ES6-Javascript-Assignment
## Exercise 1: Let and Const
## Problem Statement:

Create two variables using let and const. The let variable should be named age and set to 30. The const variable should be named name and set to "Alice". Try to reassign the name variable and observe what happens.

## Hint/Explanation:

ES6 introduced let and const for declaring variables. let is used for variables that can change, while const is for variables that should remain constant.

## Solution:

let age = 30;

const name = "Alice";

// Uncomment the line below to see the error

// name = "Bob"; // This will throw an error

## Exercise 2: Arrow Functions
## Problem Statement:

Convert the following function into an arrow function.

function add(a, b) {

return a + b;

}

## Hint/Explanation:

Arrow functions provide a concise syntax and lexically bind the this value.

## Solution:

const add = (a, b) => a + b;

## Exercise 3: Template Literals
## Problem Statement:

Use a template literal to print "Hello, Alice! Your age is 30." using the variables name and age.

## Hint/Explanation:

Template literals allow embedded expressions and multi-line strings.

## Solution:

console.log(`Hello, ${name}! Your age is ${age}.`);

## Exercise 4: Destructuring Objects
## Problem Statement:

Given an object { firstName: "Alice", lastName: "Johnson" }, use object destructuring to extract firstName and lastName into variables.

## Hint/Explanation:

Destructuring allows you to unpack values from arrays or properties from objects.

## Solution:

const person = { firstName: "Alice", lastName: "Johnson" };

const { firstName, lastName } = person;

## Exercise 5: Destructuring Arrays
## Problem Statement:

Given an array [1, 2, 3, 4, 5], use array destructuring to create variables first and second for the first two elements.

## Hint/Explanation:

Array destructuring works similarly to object destructuring but with array elements.

## Solution:

const numbers = [1, 2, 3, 4, 5];

const [first, second] = numbers;

## Exercise 6: Spread Operator
## Problem Statement:

Combine two arrays [1, 2, 3] and [4, 5, 6] into a new array using the spread operator.

## Hint/Explanation:

The spread operator allows an iterable (like an array) to be expanded in places where zero or more arguments or elements are expected.

## Solution:

const arr1 = [1, 2, 3];

const arr2 = [4, 5, 6];

const combined = [...arr1, ...arr2];

## Exercise 7: Rest Parameters
## Problem Statement:

Write a function that takes multiple arguments and returns their sum using rest parameters.

## Hint/Explanation:

Rest parameters allow us to represent an indefinite number of arguments as an array.

## Solution:

const sum = (...numbers) => numbers.reduce((acc, current) => acc + current, 0);

## Exercise 8: Default Parameters
## Problem Statement:

Create a function greet(name, greeting = "Hello") that greets a person. If no greeting is provided, it should default to "Hello".

## Hint/Explanation:

Default function parameters allow named parameters to be initialized with default values if no value or undefined is passed.

## Solution:

const greet = (name, greeting = "Hello") => ${greeting}, ${name}!;

## Exercise 9: Classes and Inheritance
## Problem Statement:

Create a class Animal with a constructor setting the name property. Then, create a subclass Dog that extends Animal and adds a bark method.

## Hint/Explanation:

ES6 classes are syntactical sugar over JavaScript's existing prototype-based inheritance. The extends keyword is used for class inheritance.

## Solution:

class Animal {

constructor(name) {

this.name = name;

}

}

class Dog extends Animal {

bark() {

return Woof! My name is ${this.name};

}

}
