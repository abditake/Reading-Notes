# [Class 06: Data Modeling](/README.md)

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

## [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

## [OWASP auth cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

<hr>





## Securing Passwords

- ### Explain to a non-technical friend how you would safely hash and store a password.
  - I would use an algorithm to change my password into strings and numbers. 
- ### What is Bcrypt?
  - a slow and powerful algorithm that uses key stretching 
- ### Why might you use something like Bcrypt?
  - has a work factor that display how expensive the hash function will be.

<hr>


## Basic Auth

- ### What is Basic Authentication?
  - a basic method for an http user agent to provide username and password when making a request.
- ### What properties are necessary in the header of a Basic Auth request?
  - authorization and credentials.
- ### How are username:password in Basic Auth encoded?
  - base64 encoded
## OWASP auth cheatsheet

- ### Define the authentication process to a non-technical recruiter.
  - the process of a verifying that an individual is who they claim to be. 
- ### How should your error messaging respond (both HTTP and HTML)? Why?

  - The user ID or password was incorrect.
  - The account does not exist.
  - The account is locked or disabled.
      -  this is to prevent attackers from mounting a user enumeration action against the application. 



```
Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.
```