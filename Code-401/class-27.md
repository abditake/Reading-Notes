# [Class-27: `useState()` Hook](/README.md)


## [react hello world](https://reactjs.org/docs/hooks-intro.html#motivation)
## [introducing JSX](https://reactjs.org/docs/hooks-overview.html)
## [rendering elements](https://reactjs.org/docs/hooks-state.html)
<hr>



# Introducing Hooks

- **What was the motivation for introducing Hooks?**
  - It’s hard to reuse stateful logic between components
  - Complex components become hard to understand
- **What changes are important regarding implementing Hooks versus Component Classes.**
  - Hooks let you use more of React’s features without classes.
  - Hooks let you split one component into smaller functions based on what pieces are related (such as setting up a subscription or fetching data)
- **Hooks allow you to reuse stateful logic without changing _ _____.**
  - component hierarchy

# hooks api

- **Name two rules imposed by React Hook usage.**
  - Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)
  - Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
- **How would you identify a custom Hook and why might you create one?**
  - If a function’s name starts with ”use” and it calls other Hooks, we say it is a custom Hook. 

# the state hook

- **What is a Hook?**
  - A Hook is a special function that lets you “hook into” React features
- **When would I use the useState Hook?**
  - If you write a function component and realize you need to add some state to it.
- **If you were to add React state to a function** component by declaring a state variable:
    - **What does calling useState do?**
      - it declares a state variable. allows you to preserve some values between function calls.
    - **What do we pass to useState as an argument?**
      - object, number or string as the initial state. 
    - **What does useState return?**
      - returns a pair of values
