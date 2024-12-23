# Express.js Route Handler Error Handling Bug

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  The `bug.js` file contains code that attempts to retrieve a user based on their ID. However, it fails to handle cases where the ID is not a valid integer, potentially leading to unexpected behavior or crashes.

The `bugSolution.js` file provides a corrected version of the code that includes robust error handling to address this issue.

## How to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `node bug.js`.  Attempt to access a route with an invalid user ID (e.g., `/users/abc`).
4. Observe the error.
5. Run `node bugSolution.js` and observe the improved error handling.