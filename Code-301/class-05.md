# [Class 05: React and Forms](/README.md)

- ## React Docs - Thinking in React
- ## Higher-Order Functions
<hr>

# React Docs - Thinking in React

- ## What is the single responsibility principle and how does it apply to components?

     - the idea that a component should do only one thing and if it deviates from that it should be decomposed into smaller components.



- ## What does it mean to build a ‘static’ version of your application?
      - creating  your app without any interactivity by using just props.props. this is build out your component before dealing with the meat and potatoes.

- ## Once you have a static application, what do you need to add?
      - identify and complete the minimal representation of the UI state. writing dry code.

- ## What are the three questions you can ask to determine if something is state?
```
1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.

3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

```

- ## How can you identify where state needs to live?
```
1. Identify every component that renders something based on that state.

2. Find a common owner component (a single component above all the components that need the state in the hierarchy).

3. Either the common owner or another component higher up in the hierarchy should own the state.

4. If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

```
<hr>


# Higher-Order Functions

- ## What is a “higher-order function”?
        -  higher-order functions are functions that operate on other functions either by taking them as arguments or by returning them.

- ## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
        - it is returning a true or false on if the input received in the greatherthan function is higher or lower than 10.

- ## Explain how either map or reduce operates, with regards to higher-order functions.
        - Map and reduce would allow you to mutate arrays and since they are higher-order methods they can be applied to functions that manipulate the array. For example during our code challenge we would have a function that took in an input and with that input which was stored in an array we used map and reduce to manipulate it to get our tests passing.

