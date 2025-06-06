1. What is Node.js?
```
Node.js is a JavaScript runtime built on Chrome’s V8 engine that lets you run JavaScript on the server side.
```
2. What are the key features of Node.js?
```
    Non-blocking I/O
    Event-driven
    Single-threaded
    Fast execution using V8 engine
```
3. What is the difference between require() and import?
```
    require() is CommonJS (used in Node.js).
    import is ES6 (modern JavaScript).
    import needs "type": "module" in package.json.
```
4. What is an event loop?
```
    It’s a loop that handles asynchronous operations in Node.js using events and callbacks.
```
5. What is npm?
```
    Node Package Manager — used to install and manage packages (libraries) in Node.js.    
```
6. What is a module in Node.js?
```
   A file containing reusable code. You can export and import functions, objects, etc.
```
7. How to export and import a module?  
```  
   // myModule.js
   module.exports = function() { console.log("Hello"); };

   // main.js
   const greet = require('./myModule');
   greet();
```
🔹 Asynchronous Programming
8. What is a callback?
```
   A function passed to another function to run after the task completes.
```
9. What is a Promise?
```
    An object that represents the result of an async operation. It can be:
        Pending
        Resolved
        Rejected
```
10. What is async/await?
```
    A cleaner way to work with Promises. Makes async code look like synchronous.

    async function run() {
        const data = await fetchData();
    }
```

🔹 Core Concepts
11. What is the Event Loop?
```
    A mechanism that allows Node.js to handle non-blocking I/O using events and callbacks.
```
12. What is the difference between synchronous and asynchronous?
```
    Sync: blocks the code
    Async: doesn’t block; uses callbacks/promises
```
13. What are streams?
```
    Streams allow reading/writing large data in chunks. Types: Readable, Writable, Duplex, Transform.
```
14. What is the use of process?
```
    Gives info/control over the current Node.js process (e.g., process.env, process.exit()).    
```
🔹 Express.js & APIs
15. What is Express.js?
```
    A minimal and flexible web framework for Node.js to build servers and APIs.
```
16. What is middleware in Express?
```
    Functions that process requests before reaching the route handler.
```
17. How to create a simple server in Express?   
``` 
        const express = require('express');
        const app = express();
        app.get('/', (req, res) => res.send('Hello World'));
        app.listen(3000);
```
18. How to handle errors in Express?
```
    Use error-handling middleware:

    app.use((err, req, res, next) => {
      res.status(500).send('Something broke!');
    });
```

🔹 Advanced Topics
19. What is clustering in Node.js?
```
    It allows running multiple Node.js instances to take advantage of multi-core CPUs.
```
20. What is the difference between spawn() and fork()?
```
    spawn() runs a new process.

    fork() is used for child processes (IPC with parent).
```
21. What is a memory leak in Node.js?
```
    When memory that is no longer needed is not released. Causes performance issues.
```
22. How to secure a Node.js app?
```
    Validate input
    Use HTTPS
    Avoid eval
    Use Helmet.js
    Sanitize data
```
23. How does Node.js handle concurrent requests?
```
    Using the event loop, callbacks, and the async nature of I/O operations.
```
24. What is CORS?
```
    Cross-Origin Resource Sharing – allows/disallows access from other domains.
```
25. What is the role of package.json?
```
    Stores project metadata and dependencies.
```
26. How to update or uninstall an npm package?
```
    Update: npm update package-name
    Uninstall: npm uninstall package-name
```


 