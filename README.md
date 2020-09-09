![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)

# Declare And Call JavaScript Functions

## Objectives

By the end of this, developers should be able to:

- Understand the benefits of using Functions
- Declare And Call JavaScript Functions
- Define parameters and pass arguments
- Use return values

## Preparation

1. Fork and clone this repository
1. Create a new branch, `training`, for your work and change into it.

## Functions

`Function` holds encapsulated executable code.

## Why do we use functions?

- Avoid repetition of codes.
- Increases program readability.
- Divide a complex problem into simpler ones.

Basic syntax:
```js
function functionName () {}
```

### Demo: Functions

Let's write a function that will print a message for us!

```js
// declare function
function printHelloWorld () {
console.log('Hello World!');
}


// call function
printHelloWorld();

// call function as many times as we want
printHelloWorld();
printHelloWorld();
printHelloWorld();
printHelloWorld();
```

We can make our functions more useful by passing data into them.

```js
// declare function
function printHello (name){
console.log('Hello ' + name)
}

// call function
printHello("GA");

// invoke function as many times as we want
printHello("Hamza");
printHello("Sara");
printHello("Genius");

```

When we declare a function that accepts data, we call the key word that will represent the data a `parameter`.

```js
function myFunctionName (parameterName) {
console.log(parameterName);
}
```

When we pass the data into our function invocation, we call it an `argument`.

```js
function myFunctionName (parameterName) {
console.log(parameterName);
}

// arguments can be any data type
myFunctionName(1);

// arguments can also be variables
const argument = 1;
myFunctionName(argument);
```

### Think!

Can you expect the result of this code?
```js
let number =5;
console.log(Math.pow(number,2));
```

What about this ?
```js
function squareOf (number) {
console.log(Math.pow(number,2));
}

// call function as many times as we want
squareOf(1);
squareOf(2);
squareOf(5);
```
As we said `Function` will make your code more readable and understandable. 


### Lab: Functions

Create a file named `functions.js`.


1.  Declare a `fullName` function that will accept in a first name and last name to print a full name.
```js
cube(2) // 8
cube(3) // 27
```


2.  Declare a `cube` function that accepts a number argument and print that number raised to the third power.
```js
cube(2) // 8
cube(3) // 27
```



## Additional Resources

- [Functions Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions)
- [Function Basics JS Info](https://javascript.info/function-basics)


