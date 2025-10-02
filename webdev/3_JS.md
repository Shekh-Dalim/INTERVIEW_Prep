1: What is JavaScript?
```
Ans: JavaScript is a programming language mainly used to make web pages interactive.
For example: animations, form validation, dynamic content.
```
2: What are the data types in JavaScript?
```
Primitive: string, number, boolean, null, undefined, symbol, bigint

Non-Primitive: object, array, function
```
3: What is the difference between var, let, and const?
```
var: Function-scoped, can be redeclared , Reassignment

let: Block-scoped, cannot be redeclared bu we can Reassignment

const: Block-scoped, cannot be reassigned or redeclared
```
4: What is typeof in JavaScript?
```
 Returns the data type of a variable.
```
5: What are truthy and falsy values?
```

Falsy: false, 0, "", null, undefined, NaN
```
6: What is a function?
```
A reusable block of code that performs a specific task.
```
7: What are arrow functions?
```
 A shorter syntax for writing functions:

js
Copy
Edit
const add = (a, b) => a + b;
```
8: What is a callback function?
```
Ans: A function passed as an argument to another function to be executed later.
```
9: What is the difference between function declaration and function expression?
```
Declaration: Hoisted

Expression: Not hoisted

function greet() {} // Declaration
const greet = function() {}; // Expression
```
10: What is lexical scope?
```
Ans: Inner functions have access to variables defined in outer functions.
```
🔹 3. Hoisting & Closures
11: What is hoisting?
```
Ans: JavaScript moves variable and function declarations to the top of their scope before execution.
```
12: What is a closure?
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
13: How to clone an object in JS?
```
Shallow copy: Object.assign({}, obj) or {...obj}

Deep copy: JSON.parse(JSON.stringify(obj))
```
14: What are object destructuring and array destructuring?
```
Ans: Extract values from objects or arrays easily:

const { name } = obj;
const [first, second] = arr;
```

15: What is the difference between == and ===?
```
==: Loose equality (converts types)

===: Strict equality (no type conversion)
```
🔹 5. Asynchronous JavaScript
16: What is the event loop?
```
Ans: It's how JavaScript handles asynchronous code using a queue and call stack.
```
17: What is the difference between synchronous and asynchronous code?
```
Ans:
Synchronous: Executes in sequence
Asynchronous: Executes without blocking the main thread (e.g., using setTimeout, fetch, Promise)
```

18: What is a Promise?
```
Ans: An object representing the eventual completion or failure of an asynchronous operation.

const promise = new Promise((resolve, reject) => {});
```
19: What are async and await?
```
Syntactic sugar over Promises to write cleaner asynchronous code.
```
20: What is callback hell and how to avoid it?
```
Ans: Multiple nested callbacks; avoid using Promises or async/await.
```
🔹 6. DOM Manipulation
21: What is the DOM?
```
Ans: Document Object Model – a tree structure of the HTML page used by JavaScript to access and manipulate elements.
```
22: How to select elements in DOM?
```
getElementById, getElementsByClassName, querySelector, querySelectorAll
```
23: How to create and append elements?
```
let div = document.createElement('div');
document.body.appendChild(div);
```

🔹 7. ES6+ Features
24: What are template literals?
```
Ans: Strings with embedded expressions using backticks:

`Hello, ${name}`
```
25: What is the spread operator?
```
Ans: Expands arrays or objects:

let arr2 = [...arr1];
```
26: What is the rest parameter?
```
Ans: Collects all remaining arguments into an array:

function sum(...args) {}
```

27: What are default parameters?
```
Ans: Function parameters with default values:

function greet(name = "Guest") {}
```
28: What is destructuring?
```
Ans: Extract values from arrays or objects into variables.
```
🔹 8. Error Handling
29: What is the try-catch block?
```
Ans: Used to handle runtime errors:

try {
  // code
} catch (error) {
  console.log(error);
}
```
30: What is the purpose of finally?
```
Ans: Executes after try or catch, regardless of the result.
```
🔹 9. Memory Management
```
34: What is a memory leak in JS?
Ans: When memory is not released properly, leading to performance issues.
```
35: How does garbage collection work in JS?
```
Ans: JavaScript automatically frees memory that is no longer used (mark-and-sweep algorithm).
```
🔹 10. Advanced Topics
36: What is event delegation?
```
Ans: Using a parent to handle events of dynamically added child elements.
```
37: What is debounce and throttle?
```
Debounce: Delay function execution until a pause

Throttle: Limit function execution to once in a time interval
```
38: What are higher-order functions?
```
Ans: Functions that take or return other functions (e.g., map, filter, reduce).
```
39: What is currying?
```
Ans: Breaking a function into a series of functions, each taking one argument.

function add(a)(b) => a + b;
```
40: What is the this keyword in JavaScript?
```
Ans: Refers to the object from which a function is called.
```
41: What are arrow functions and how do they handle this?
```
Ans: Arrow functions don’t bind their own this, they inherit it from the parent scope.
```

🔹 11. Browser APIs
42: What is localStorage vs sessionStorage vs cookies?
```
localStorage: Persistent data

sessionStorage: Data per session

cookies: Small data, sent with HTTP requests
```
43: What is the Fetch API?
```
Ans: Used for making network requests: 
fetch(url).then(res => res.json());
```
44: How to make an API call in JavaScript?
```
Using fetch or axios.
```
