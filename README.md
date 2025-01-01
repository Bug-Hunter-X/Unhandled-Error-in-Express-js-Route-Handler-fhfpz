# Express.js Route Handler Error

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  Specifically, the `/users/:id` route attempts to parse the `id` parameter as an integer but fails to handle cases where the `id` is not a valid integer, resulting in a potential crash or unexpected behavior.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides a corrected version with appropriate error handling.