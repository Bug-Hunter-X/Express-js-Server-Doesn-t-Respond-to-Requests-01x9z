# Express.js Server Doesn't Respond to Requests

This repository demonstrates a common error in Express.js applications where the server fails to respond to incoming requests due to a missing response-sending function within the request handler.

## Bug

The `bug.js` file contains the erroneous code. The server starts successfully, but it doesn't send any response to client requests.

## Solution

The `bugSolution.js` file shows the corrected code. The `res.send()` function is added to the request handler to send a response to the client.

## How to reproduce

1. Clone the repository.
2. Navigate to the repository's directory.
3. Run `node bug.js`.
4. Attempt to access the server (e.g., via a web browser or `curl`). You'll observe no response.
5. Run `node bugSolution.js`.  You will now receive a response from the server.
