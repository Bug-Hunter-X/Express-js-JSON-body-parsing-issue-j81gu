This repository contains a demonstration of a common issue encountered when working with JSON request bodies in Express.js applications.  The bug arises from a missing or incorrectly set `Content-Type` header in the request, preventing the `express.json()` middleware from properly parsing the request body.  The solution demonstrates the correct way to handle JSON requests and avoid this error.