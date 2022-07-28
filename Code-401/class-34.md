# [Class-34: API Integration ](/README.md)

## [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)
## [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

<hr>


# Review API Server Build
  
- Explain the different between a query string parameter and a path parameter.
  - path parameters is resource identification and query parameters is resource sorting or filtering.
- What would our API URL with a path id parameter be given the following information:
  - Domain: http://our-site.com
  - v3
  - model name: stuff
  - id: things
    - `http://our-site.com/v3/stuff/things`
- We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
  - it's an endpoint or url that allows you to get, create, update and delete data. although when creating, updating and deleting you would use something like postman or thunderClient to make a proper request to the api.

<hr>

# Review Auth Server Build
  
  - Describe how you would use middleware to implement basic and bearer auth.
    - create middleWare that requires tokens for bearer, and hashed keys for basic to authenticate then authorize the user to first all the user the access to see the data but then allow the user to create, update and delete the data. If the tokens and hashed keys don't match to the access you are given then you can only read.
  - Describe the handshake necessary to implement OAuth.
    - You need some token that is unique associated to the users ID. this token is what verifies you as a person then based on that you are given authorization to view and access resources based on your role. youtube won't give you access to moderate other peoples channels but since you logged in and verified yourself, you have access to your own account. 
  - Describe how Role Based Access Control works to a non-technical friend.
    - A system that works based on roles and depending on that role you have specific access to resources and information. It's designed to control issues between projects, teams, also to maintain a streamlined system where an employee can just have his role changed to either give him/her access to more resources or less. 