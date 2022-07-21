# [Class-29: Advanced State with Reducers](/README.md)

## [useReducer hook](https://reactjs.org/docs/hooks-effect.html)
## [Ultimate Guide to useReducer](https://reactjs.org/docs/hooks-effect.html)
<hr>

# useReducer hook

- Name an alternative to the useState Hook.
  - useReducer
- Why might the useReducer Hook be preferable to the useState Hook?
  - complex state logic involving multi-sub levels
- What are two ways to set the initial state?
  - Pass initial state as second argument
  - Pass an init function as the third argument

# Ultimate Guide to useReducer
  - In terms of state, what does useReducer expect to receive as a parameter?
    - reducer function
    - initial state
  - What does useReducer return?
    - an array that holds the current state value and a dispatch function
  - Explain dispatch to a non-technical recruiter.
    - is a placeholder for what we want to do with the reducer function. the dispatch function will be called later and the reducer function will update state based on dispatch object.