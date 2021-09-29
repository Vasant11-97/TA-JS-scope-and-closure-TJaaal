1. What does thread of execution means in JavaScript?

Thread in JavaScript is the execution of running multiple tasks or programs at the same time. Each unit capable of executing code is called a thread

2. Where the JavaScript code gets executed?

Everything in JavaScript happens inside an "Execution Context”. Whenever a JavaScript program is run an execution context is created. 

3. What does context means in Global Execution Context?

The environment in which your code is running is Execution context . It is created when your code is executed

4. When do you create a global execution context.

The Global Execution Context gets created when we load the JavaScript file, even when it is empty.

5. Execution context consists of what all things?

 variable scope (and the scope chain, variables in closures from outer scopes), function arguments, and the value of the this object.

6. What are the different types of execution context?

Global Executional Context and Functional Execution Context

7. When global and function execution context gets created?

The Global Execution Context gets created when we load the JavaScript file, even when it is empty. It creates two special things for us in its creation phase, that is the window object and this . In Global Execution context, the window object and this are equal. There is nothing to execute as the script file is blank.

8. Function execution gets created during function execution or while declaring a function.

while declaring a function.


9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)