# [Class 01: Introduction to React and Components](/README.md)

- ## Component-Based Architecture
- ## What is Props and How to Use it in React
<hr>

# Component-Based Architecture

- ## what is a Component?
   - A component piece of code that fills in a certain part of the user interface.

```
A component is a software object, intended to interact with other components, 
encapsulating certain functionality or a set of functionalities. It has an obviously 
defined interface and conforms to a recommended behavior common to all components within an architecture.

```
- ## What are the advantages of using component-based architecture?
    - a component has six characteristic
      - `Reusability`: being able to be used in different situations in different applications
      - `Replaceable`: Switching components with other similar components freely
      - `Not context specific`: Components being able to work in different environments and contexts.
      - `Extensible`: extending a component to have a new behavior.
      - `Encapsulated`: a component covers the interface while not exposing the internal state, variables or process.
      - `Independent`: little to no dependency on other components

- ## What are the advantages of using component-based architecture?
     - `Ease of deployment`: Easily change and replacing components to newer versions
     - `Reduced cost`: The use of third-party components allows you to spread the cost of development and maintenance.
     - `Ease of development`: components being independent allows development without major problems to other parts of the system.
     - `Reusable`: Using components through multiple applications and systems which brings overall costs down.
     - `Modification of technical complexity`:A component modifies the complexity through the use of a component container and its services.
     - `Reliability`: Reusing components makes the system more consistent which in turn makes it more reliable
     - `System maintenance and evolution`: easy to update/change components without changing other parts of the system
     - `Independent`: Components are such that different groups could work on other parts of the same application without affecting each other boosting overall productivity.
<hr>

# What is Props and How to Use it in React?

- ## What is “props” short for?
    - Props is a keyword in React, which is short for Properties.
- ## How are props used in React?
    - In react props is a way for components to pass data to one another. Props in react are used in three steps by...
        1. Defining an attribute and its value.
        2. passing it to the child component by using props.
        3. then, Rendering the props data.
- ## What is the flow of props?
    - When asked what is the flow of props, it's the same as being asked what is the flow of data in React. The flow of props(data) in react is unidirectional or one way.

    ```
    parent ----> data ----> child

    parent <---- data <---- child(using a callback-function)

    ```  

## Things I want to know more about
    - How do components interact while on different pages that need to interact with 
    each other. Does passing data from one component to the other get tricky when dealing with login and stuff?


