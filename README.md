# React Router v6 Catch-All Route Issue

This repository demonstrates a bug in React Router v6 where the catch-all route (`path="*"`) doesn't correctly handle all unmatched routes, leading to unexpected rendering behavior.  The issue is observed when navigating to paths not explicitly defined, particularly with dynamic segments.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Navigate to a route that doesn't exist (e.g., `/invalid-path`, `/users/123`).

You will observe that the `NotFound` component is not rendered as expected.  This demonstrates the issue with the catch-all route.

## Solution

The provided solution demonstrates how to resolve this issue.  See `AppSolution.js` for the corrected implementation.