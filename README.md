# React Router Dom v6 Catch-All Route Issue

This repository demonstrates a common issue encountered when using catch-all routes ("/*") in React Router Dom v6.  The catch-all route, intended to handle any unmatched routes, is unexpectedly ignored when placed after more specific routes.

## Problem

The provided `App.js` shows a simple React application using React Router. The catch-all route (`/*`) is designed to display a "404 Not Found" message if the user navigates to an invalid route.  However, this route is ineffective in its current position.

## Solution

The solution, in `AppSolution.js`, demonstrates how to correctly position the catch-all route. By placing it *before* more specific routes, React Router correctly handles unmatched paths.  This ensures the catch-all route functions as expected. 