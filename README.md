# React useEffect Missing Dependency
This repository demonstrates a common bug in React 18 and 19 involving the `useEffect` hook and missing dependencies.  The `useEffect` hook is not correctly specifying its dependencies leading to unexpected behavior.  The solution shows how to correct this. 

## Bug
The `bug.js` file contains a React component with a `useEffect` hook that's missing a key dependency, causing infinite re-renders.

## Solution
The `bugSolution.js` file provides the corrected code, where the `count` variable is added to the dependency array of useEffect, fixing the issue.