1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
```

// Your code goes here

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

let percentage = (marks, totoal) => {
  return (marks * 100) / total;
};
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
```

Function Declaration

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

function Expression

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

Function Expression

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

Function Expression(Arrow)

```js
let percentage = (marks, total) => (marks * 100) / total;
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

4. Why is a function call an expression in JavaScript?

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid
five = add; // valid
five = five(10, 11); // valid
five = function () {
  return "Hello";
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.

7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}

hello.user = "Sam"; // valid
```

9. What is higher order function explain with an example.

10. Explain what is callback function. Why you can pass a function inside a function?
