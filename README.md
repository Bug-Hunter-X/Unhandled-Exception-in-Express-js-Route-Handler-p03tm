# Unhandled Exception in Express.js Route Handler

This repository demonstrates a common yet easily overlooked error in Node.js Express.js applications: unhandled exceptions within route handlers.  Failure to properly handle these exceptions can lead to server crashes and unexpected behavior. 

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a robust solution using async/await and try...catch blocks.  The solution ensures graceful error handling and prevents server crashes.