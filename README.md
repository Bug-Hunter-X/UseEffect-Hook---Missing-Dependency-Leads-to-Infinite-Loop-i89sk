# React useEffect Hook - Missing Dependency

This repository demonstrates a common error in React's `useEffect` hook: missing dependencies in the dependency array.  This can lead to unexpected behavior, often an infinite render loop.

## The Bug
The `bug.js` file contains a component with a `useEffect` hook that's missing a crucial dependency.  Observe the infinite loop that occurs in the console.