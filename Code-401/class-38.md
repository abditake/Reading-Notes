# [Class-37: Combined Reducers ](/README.md)

## [async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)

## [thunk middleware](https://github.com/reduxjs/redux-thunk)

<hr>

# async actions
- Why use Redux middleware?
  - to make synchronous calls or async logic to our redux reducers. 
- Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
  - redux reducers changes state from a click on the ui which triggers an event handler that needs to preform an action and send that to middleware for an http request. The middleware becomes a step before reaching the store so that we can properly call to the api. 
- How are we accommodating async in our Redux app?
  - adding event handlers with dispatch

# thunk middleware
- Why would you need redux-thunk middleware?
  - allows writing async logic within redux 
- Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
  - function
- Describe how any return value from the inner thunk function will be made available.
  - it will be available as the return value of the dispatch. for example in the diagram there was a dispatch from the event handler to middleware with an action; that actions return is in the dispatch. 



# Async Redux Data flow

 ![async redux data flow](https://d33wubrfki0l68.cloudfront.net/08d01ed85246d3ece01963408572f3f6dfb49d41/4bc12/assets/images/reduxasyncdataflowdiagram-d97ff38a0f4da0f327163170ccc13e80.gif)