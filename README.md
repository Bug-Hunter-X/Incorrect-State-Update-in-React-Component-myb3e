# Incorrect State Update in React Component

This repository demonstrates a common error in React applications involving incorrect state updates. The `bug.js` file shows a React component with a flawed state update mechanism using the `useState` hook. The `bugSolution.js` file provides the corrected implementation.

## Bug Description
The `bug.js` component attempts to update state incorrectly by directly modifying the state variable instead of using the update function provided by the `useState` hook. This causes no state change and potentially unexpected behavior. The solution showcases the correct way to utilize `useState` for updating state.