# [Class-37: Combined Reducers ](/README.md)

## [Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

## [Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)

## [Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)
<hr>






# Multiple Reducers Example

- Why create multiple reducers?
  - so you can modularize the reducers and have them in separate files. You don't want one big reducer.  
- How would you combine multiple reducers?
  - using combineReducer() method in redux 
- How will you manage state as an immutable object? why?
  - you set initial state then create a deep copy using the spread operator. this will allow you to change state with dispatch then return that state. 
  

# Redux Docs: Using Combined Reducers

- combineReducers is a utility function to simplify the most common use case when writing ___ _____ .
  - Redux reducers
- Explain how combineReducers assembles the new state tree.
  - `combineReducers` will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed
- How would you define initial state in an app using combineReducers?
  - initial state is either passed into a createStore function or returned in reducer function.
  

# Redux Docs: Combined Reducer Syntax

- Why will you want to split your reducing functions as your app becomes more complex?
  - Because as the app gets more complex testing and readability can decline. You don't want a giant reducer function when you can modularize it and combine them later. 
- The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
  - combineReducers, createStore
- What is a popular convention when naming reducers?
  - A popular convention is to name reducers after the state slices they manage, so you can use ES6 property shorthand notation.