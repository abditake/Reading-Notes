# [Class-39: Combined Reducers ](/README.md)

## [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

## [MobX](https://mobx.js.org/getting-started.html)

## [Tutorial](https://redux-toolkit.js.org/tutorials/overview)

<hr>


# Redux Toolkit (RTK)

- What concerns are addressed by Redux Toolkit?
  - Configuring a Redux store is too complicated
  - I have to add a lot of packages to get Redux to do anything useful
  - Redux requires too much boilerplate code
- What does configureStore() do?
  - configureStore(): wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.
- How would I use createSlice()?
  - createSlice(): accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.

# MobX

- What is Mobx?
  - mobx is a scalable state management solution 
- How does MobX make it “impossible” to produce an - inconsistent state?
  - The strategy to achieve that is simple: Make sure that everything that can be derived from the application state, will be derived. Automatically.
- How would we build a reactive user interface?
  - The observer HoC wrapper from the mobx-react-lite package fixes that by basically wrapping the React component in autorun. This keeps the component in sync with the state.


# Tutorial

- What take-away(s) did this tutorial provide?
  - redux toolkit uses a library called immer
    - Immer is a library that simplifies the process of writing immutable update logic.