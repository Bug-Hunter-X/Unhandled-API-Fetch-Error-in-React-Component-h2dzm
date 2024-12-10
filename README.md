# Unhandled API Fetch Error in React Component

This repository demonstrates a common error in React applications:  failing to properly handle errors during asynchronous operations, specifically API calls.

The `bug.js` file contains a React component that fetches data from an API.  The issue is that while it displays a loading indicator and catches errors, it doesn't elegantly handle cases where the API request itself fails (e.g., a 404 or 500 error).

The `bugSolution.js` file provides a corrected version that addresses this issue by explicitly checking the response status and handling non-2xx status codes gracefully.