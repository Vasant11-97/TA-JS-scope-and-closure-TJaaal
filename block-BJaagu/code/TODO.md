Find the output of the code snippets below:

```js
console.log(numA + numB); // NAN Because both variables are declared after consoling the values.
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); // NAN Because the variable used numA is already used in colsole by declaring it with let.
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //51
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // Hello because both the function have the same name and the last one is considered and it is consoling hello.
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // Tyrion
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // Tyrion because it bubbles out for searching the variable username.
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // sayHello is not defined because we used let instead of var and it creates the box but does not innitiates the value in it.
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // SayHello is not defined because we used let instead of var and it creates the box but does not innitiates the value in it.
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // SayHello is not defined because we used let instead of var and it creates the box but does not innitiates the value in it and it is a function expression because of which it does not store in the memory of GEC.
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // SayHello is not defined because we used let instead of var and it creates the box but does not innitiates the value in it and it is a function expression because of which it does not store in the memory of GEC. and it used let which creates a box but does not initites any value to it.
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); // OUTPUT
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // John because the username which is declared in the function is consoling it out put so it is showing John as an output and the variable username which is declared outside is not called so it is not working. 
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // Cannot access username name before initialixation because inside the function the variable is declared with the same name as the variable declared in the global scope so the function will look inside the code and it founded the variable hich is declared after console log so it is showing this error.
```