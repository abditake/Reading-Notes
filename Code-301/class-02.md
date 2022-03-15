# [Class 02: State and Props](/README.md)

- ## React lifecycle
- ## React State Vs Props
<hr>

# React lifecycle

- ## Based off the diagram, what happens first, the `render` or the `componentDidMount`?
    - Based on the diagram the render happens before the componentDidMount.

- ## What is the very first thing to happen in the lifecycle of React?
    - In the first thing to happen in the lifecycle of a component is Mounting.


- ## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
    1.constructor
    2.render
    3.react updates
    4. componentDidMount
    5. componentWillUnmount



- ## What does componentDidMount do?

  - allows us to execute React code when the component is already placed in the Dom; load anything using network or initializing Dom.

<hr>

# React State vs Props

- ## What types of things can you pass in the props?
    - You can pass through any data types from strings,functions,objects etc.


- ## What is the big difference between props and state?
  - props are handled outside of the component and state is handled inside the component.

- ## When do we re-render our application?
  - we re-render our application based on something the user has done on the webpage. storing things in state will allow you to re-render based on input whereas passing it into props won't change anything. 




- ## What are some examples of things that we could store in state?
  - counter application
  - any function or piece of code that changes
  


 ## Things I want to know more about.

    - I want to fully grasp event handlers and being able to 
    update not just part of text on a webpage but major sections of a page. 
    like for example creating a click that changes maybe the header and nav not just header or nav.