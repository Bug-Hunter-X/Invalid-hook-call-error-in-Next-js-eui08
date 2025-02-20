# Next.js Invalid Hook Call Error

This repository demonstrates a common error in Next.js applications: the "Invalid hook call" error. This error occurs when using React Hooks outside of a functional component.

## Bug

The `bug.js` file contains a Next.js component that incorrectly uses a hook outside of a functional component, leading to the error. This can often occur when refactoring code or when integrating third-party libraries that use hooks internally.

## Solution

The `bugSolution.js` file provides a corrected version of the component. This solution ensures that all hooks are called within the body of a functional component.