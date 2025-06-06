🟢 What is JavaScript?
```
Ans: JavaScript is a lightweight, interpreted programming language primarily used to make web pages interactive.
```
🟢 What are the data types in JavaScript?
```
Primitive: string, number, boolean, null, undefined, symbol, bigint

Non-Primitive: object, array, function
```
🟢 What is the difference between var, let, and const?
```
var: Function-scoped, can be redeclared

let: Block-scoped, cannot be redeclared

const: Block-scoped, cannot be reassigned or redeclared
```
🟢 What is typeof in JavaScript?
```
 Returns the data type of a variable.
```
🟢 What are truthy and falsy values?
```

Falsy: false, 0, "", null, undefined, NaN
```
🟢 What is a function?
```
A reusable block of code that performs a specific task.
```
🟢 What are arrow functions?
```
 A shorter syntax for writing functions:

js
Copy
Edit
const add = (a, b) => a + b;
```
🟢 What is a callback function?
```
Ans: A function passed as an argument to another function to be executed later.
```
🟢 What is the difference between function declaration and function expression?
```
Declaration: Hoisted

Expression: Not hoisted

function greet() {} // Declaration
const greet = function() {}; // Expression
```
🟢 What is lexical scope?
```
Ans: Inner functions have access to variables defined in outer functions.
```
🔹 3. Hoisting & Closures
🟢 What is hoisting?
```
Ans: JavaScript moves variable and function declarations to the top of their scope before execution.
```
🟢 What is a closure?
```
Ans: A function that remembers its outer variables even after the outer function has finished execution.

function outer() {
  let count = 0;
  return function inner() {
    return ++count;
  };
}
```
🔹 4. Objects & Arrays
🟢 How to clone an object in JS?
```
Shallow copy: Object.assign({}, obj) or {...obj}

Deep copy: JSON.parse(JSON.stringify(obj))
```
🟢 What are object destructuring and array destructuring?
```
Ans: Extract values from objects or arrays easily:

const { name } = obj;
const [first, second] = arr;
```

🟢 What is the difference between == and ===?
```
==: Loose equality (converts types)

===: Strict equality (no type conversion)
```
🔹 5. Asynchronous JavaScript
🟢 What is the event loop?
```
Ans: It's how JavaScript handles asynchronous code using a queue and call stack.

🟢 What is the difference between synchronous and asynchronous code?
Ans:

Synchronous: Executes in sequence

Asynchronous: Executes without blocking the main thread (e.g., using setTimeout, fetch, Promise)
```

🟢 What is a Promise?
```
Ans: An object representing the eventual completion or failure of an asynchronous operation.

const promise = new Promise((resolve, reject) => {});
```
🟢 What are async and await?
```
Syntactic sugar over Promises to write cleaner asynchronous code.
```
🟢 What is callback hell and how to avoid it?
```
Ans: Multiple nested callbacks; avoid using Promises or async/await.
```
🔹 6. DOM Manipulation
🟢 What is the DOM?
```
Ans: Document Object Model – a tree structure of the HTML page used by JavaScript to access and manipulate elements.
```
🟢 How to select elements in DOM?
```
getElementById, getElementsByClassName, querySelector, querySelectorAll
```
🟢 How to create and append elements?
```
let div = document.createElement('div');
document.body.appendChild(div);
```

🔹 7. ES6+ Features
🟢 What are template literals?
```
Ans: Strings with embedded expressions using backticks:

`Hello, ${name}`
```
🟢 What is the spread operator?
```
Ans: Expands arrays or objects:

let arr2 = [...arr1];
```
🟢 What is the rest parameter?
```
Ans: Collects all remaining arguments into an array:

function sum(...args) {}
```

🟢 What are default parameters?
```
Ans: Function parameters with default values:

function greet(name = "Guest") {}
```
🟢 What is destructuring?
```
Ans: Extract values from arrays or objects into variables.
```
🔹 8. Error Handling
🟢 What is the try-catch block?
```
Ans: Used to handle runtime errors:

try {
  // code
} catch (error) {
  console.log(error);
}
```
🟢 What is the purpose of finally?
```
Ans: Executes after try or catch, regardless of the result.
```
🔹 9. Memory Management
```
🟢 What is a memory leak in JS?
Ans: When memory is not released properly, leading to performance issues.
```
🟢 How does garbage collection work in JS?
```
Ans: JavaScript automatically frees memory that is no longer used (mark-and-sweep algorithm).
```
🔹 10. Advanced Topics
🟢 What is event delegation?
```
Ans: Using a parent to handle events of dynamically added child elements.
```
🟢 What is debounce and throttle?
```
Debounce: Delay function execution until a pause

Throttle: Limit function execution to once in a time interval
```
🟢 What are higher-order functions?
```
Ans: Functions that take or return other functions (e.g., map, filter, reduce).
```
🟢 What is currying?
```
Ans: Breaking a function into a series of functions, each taking one argument.

function add(a)(b) => a + b;
```
🟢 What is the this keyword in JavaScript?
```
Ans: Refers to the object from which a function is called.
```
🟢 What are arrow functions and how do they handle this?
```
Ans: Arrow functions don’t bind their own this, they inherit it from the parent scope.
```

🔹 11. Browser APIs
🟢 What is localStorage vs sessionStorage vs cookies?
```
localStorage: Persistent data

sessionStorage: Data per session

cookies: Small data, sent with HTTP requests
```
🟢 What is the Fetch API?
```
Ans: Used for making network requests: 
fetch(url).then(res => res.json());
```
🟢 How to make an API call in JavaScript?
```
Using fetch or axios.
```