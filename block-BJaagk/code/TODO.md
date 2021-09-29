1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let result = (marks, total) => {
  return (marks * 100) / total;
}
let result = function(marks, total) [
  return (marks * 100) / total;
]
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

let result = (marks, total) => {
  return (marks * 100) / total;
}
// Your answer
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

let result = (marks, total) => {
  return (marks * 100) / total;
}
```


```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, total) => {
  return (marks * 100) / total;
}
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

A function which is created with out storing in a variable is known as function defination and when we store a function in a variable 
it is known as function expression. We can store a function in a variable because function acts like an object in javascript.

example : let dummyFunction = function(marks, total) {
  return (marks * 100) / total;
}

4. Why is a function call an expression in JavaScript?

Because we can call the function in a variable with the arguments.

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Valid
five = add; // Valid
five = five(10, 11); // Valid
five = function () {
  return 'Hello';
}; // Invalid
```

6. What is the difference between function definition and function call? Explain with an example.

When we create a function with some logic in it it is called the function defination and when we call that function with the arguments having values is known as function call.

example : function dummyExample(first, second) {
  return first * second;
} 
dummyExample(10, 12);

7. What is the similarities between function definition and function call?

A function defination is a procedure to achieve the particular result while function call is a procedure to achieve or execute the task.

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid
```

9. What is higher order function explain with an example.

A function that accepts the function or return a function is called higher order function.
example : let plusFive = (number) => {
  return number + 5;  
};
// f is assigned the value of plusFive
let f = plusFive;

10. Explain what is callback function. Why you can pass a function inside a function?

In JavaScript, a callback is a function passed into another function as an argument to be executed later.

Because a function acts as an object in javascript so it can be called in another function as a reference.
