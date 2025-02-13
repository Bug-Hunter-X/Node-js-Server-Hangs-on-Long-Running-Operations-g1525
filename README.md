# Node.js Server Hangs on Long-Running Operations

This repository demonstrates a common issue in Node.js applications where long-running operations can cause the server to hang and become unresponsive.  The `server.js` file contains a simple HTTP server that simulates a 5-second delay. During this delay, the server is unable to handle new requests.

The solution, provided in `serverSolution.js`, utilizes asynchronous programming techniques to prevent the server from blocking while handling the long-running task.  This ensures that the server remains responsive even during lengthy operations.