# React Router Dom: Handling of Non-Matching Routes

This repository demonstrates a common error in React Router v6 and its solution.

## Problem

The provided `App.js` initially lacks a catch-all route (`*`) to handle unmatched paths. This results in unexpected behavior when attempting to navigate to a route not explicitly defined. The application might break or simply show nothing.

## Solution

The solution (`bugSolution.js`) adds a catch-all route (`/*`) which provides a fallback rendering component for handling any other unmatched path in the application.

## How to run

1. Clone the repository
2. Install the dependencies: `npm install`
3. Run the application: `npm start`