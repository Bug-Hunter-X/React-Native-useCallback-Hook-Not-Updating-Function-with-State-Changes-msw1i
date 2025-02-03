# React Native useCallback Hook Not Updating Function with State Changes

This repository demonstrates a common error when using the `useCallback` hook in React Native: failure to update a function when its dependencies change. Specifically, if a function within `useCallback` relies on a state variable, and that state variable is not listed in the dependency array, the function will not re-render even if the state changes. This can lead to unexpected behavior and bugs in your application.

The `bug.js` file contains code exhibiting this problem. The `bugSolution.js` file provides a corrected implementation.

## How to reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run the application using a React Native emulator or physical device.