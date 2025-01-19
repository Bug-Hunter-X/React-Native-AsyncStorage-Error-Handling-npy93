# React Native AsyncStorage Error Handling

This repository demonstrates a common error in React Native applications involving AsyncStorage and provides a solution with improved error handling.

The original code lacks proper error handling for asynchronous operations, potentially leading to crashes or unexpected behavior. The solution includes `try...catch` blocks to handle potential errors and ensures that cleanup actions (e.g., setting loading states) are performed regardless of success or failure.

## Bug

The `bug.js` file shows the problematic code.  The primary issue is the absence of error handling when using `AsyncStorage.setItem` and `AsyncStorage.getItem`. 

## Solution

The `bugSolution.js` file presents a corrected version with comprehensive error handling.  The `try...catch` blocks handle potential exceptions, providing more resilient code and a better user experience.