# [Class-36: Redux ](/README.md)

## [Dan Abramov Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)
<hr>



# Dan Abramov Redux Tutorials

- What is the first principle of Redux?
    -  The first principle of Redux is whether your app is a really simple one like this counter example, or a complex application with a lot of UI, and change of state, you are going to represent the whole state of your application as a single JavaScript object.

- what is a store and what do we use our reducers for within that store?
    -  the store combines the three principles of redux; holds the state object. the reducer tells how the state is updated with actions.

- Name three Redux store methods given to us by createStore and describe their use.
    - getState(): retrieves current state of redux store
    - dispatch(): dispatch actions to change the state
    - subscribe():lets register a callback the redux store will call anytime an action has been dispatched
- Explain to a non-technical recruiter what combineReducers() does and why it is useful.
    - combineReducer does exactly what it says adds all reducer functions that are passed through it together so that you can update them easily. alows you to update state at different parts at one place. 