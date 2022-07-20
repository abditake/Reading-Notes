
# [Class-28: Component Lifecycle / `useEffect` Hook](/README.md)

## [effects hook](https://reactjs.org/docs/hooks-effect.html)
<hr>

# effects hook

- What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?
  - allows you to add side effects inside the functional component instead needing to use componentDidmoint for classes.
- When using the useEffect Hook:
    - What does useEffect do?
      - you can dictate react to do something after render 
    - Why is useEffect called inside a component?
      - you have access to any props and the count variable right from effect
    - Explain the importance of properly implementing effects with Cleanup
       - we might want to set up a subscription to some external data source. In that case, it is important to clean up so that we don’t introduce a memory leak!
