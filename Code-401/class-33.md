# [Class-33: Login and Auth](/README.md)

## [What is Role Based Access Control](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)
## [react-cookie library](https://www.npmjs.com/package/react-cookie)
## [react-cookies component](https://www.npmjs.com/package/react-cookies)
<hr>

# What is Role Based Access Control (RBAC)?

- What is Role Based Access Control (RBAC)?
  - Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.
- Share some an example of RBAC including all possible CRUD operations and correlating roles.
  -  Management role group – you can add and remove members.
  -  Management role scope – it limits what objects the role group is allowed to manage.
  -  In these two examples you would able to alter the RBAC system for specific roles so that you can easily change someones access in the system whenever they go to another department or even leave the company instead of removing them by name. 
- What are the Benefits of RBAC?
  - RBAC offers a streamlined approach that is logical in definition. Instead of trying to administer lower-level access control, all the roles can be aligned with the organizational structure of the business and users can do their jobs more efficiently and autonomously.

Compare and Contrast the following two Libraries and the following questions. Yes, they are similarly named.

# react-cookie library

# react-cookies component

  1. Describe some react-cookie features.
     - functional component land  
     - uses withCookies method to provide access to your cookies everywhere 
     - cookies props must be instantiated with new cookie or set using req.universalCookies 
  2. Describe some react-cookies features.
     - class component land 
     - if your website is setup with a login you can track cookies specific to the user until they logout.
     - returns object with cookie name as key 
     - create / route if you want access to cookies everywhere
  3. Which library would you prefer would you prefer? Why?
     - react-cookie library only because it is the functional component implementation and I need to get functional components down. 
