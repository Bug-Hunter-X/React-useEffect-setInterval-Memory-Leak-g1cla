# React useEffect setInterval Memory Leak
This repository demonstrates a common error in React applications where a memory leak occurs due to a missing cleanup function in the `useEffect` hook when using `setInterval`. The `setInterval` function continues to run even after the component unmounts, leading to unnecessary resource consumption.
The `bug.js` file contains the problematic code, and `bugSolution.js` provides the corrected version with the cleanup function implemented.