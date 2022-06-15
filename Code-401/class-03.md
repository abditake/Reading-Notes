# [Class 03: Express REST API](/README.md

## [Review if helpful: An Introduction to Node.js on sitepoint.com](https://www.sitepoint.com/an-introduction-to-node-js/)

## [Using Express Routing](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

  ## [Express Routing](https://www.digitalocean.com/community/tutorials/learn-to-use-the-new-router-in-expressjs-4)

<hr>

# Review: ES6 Classes

- ### Classes are a template for creating ____.
    - objects

- ### Can a class declaration be hoisted?

    - class declarations need to be defined before an object is constructed
- ### How would you describe a constructor and contextual “this” to a non-technical friend?

    - a constructor is the blueprint for creating object types

<hr>

# Using Express Routing

- ### Within Express, what does routing refer to?

    - routing refers to how an application's endpoints respond to client requests. 
- ### What is the difference between a route path and a route method?
    - a route method is from one http methods attached to an instance of the express class.
    - a route path is the endpoint that requests can be made

- ### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
    - when routing methods have multiple callback functions. you must pass next as an argument to the callback function and then call next within the body of the function to had off control.


<hr>

# Express Routing

- ### What is an Express Router?
    - small express application with only routing stuff.

- ### By what mean do we initialize express.Router() in an express server?
    - get an instance of express.router so that we can apply routes to it.
- ### What do we use route middleware for?
    - doing something before a request is processed 