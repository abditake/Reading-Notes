# [Class 15:  Authentication](/README.md)

- ## What is OAuth
- ## Authorization and Authentication flows
<hr>

# What is OAuth


- ## What is OAuth?
    - an open-standard authorization protocol for access delegation.

- ## Give an example of what using OAuth would look like.
    - when you go onto a website and it allows multiple ways of logging in for example
    if i made a website and gave you and option to login through google. 

- ## How does OAuth work? What are the steps that it takes to authenticate the user?
    - connects to other website on behalf of user
    - the other website creates a one-time token 
    - the first site gives this token to the site the user is login into
    = the clients software presents the request token to the authorization provider
    - client is to approve the authorization to the second site
    - the user approves the transaction
    - the user gets an approved token 
    - the user gives the approved token to the first website
    - the second website lets the first website access their site on behalf of the user
    - the user successfully completed the transaction occurring

- ## What is OpenID?
    - openID is an authentication protocol (not authorization)


<hr>


# Authorization and Authentication flows

- ## What is the difference between authorization and authentication?
      - authentication is verifying who the user is and authorization is verifying what 
      they have access to. 

- ## What is Authorization Code Flow?
      - exchanges an authorization code for a token 

- ## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
      - uses Code verifier  to send a value of https to retrieve authorization code.
- ## What is Implicit Flow with Form Post?
      - uses OIDC to do the token request without having to manage it in the backend.
- ## What is Client Credentials Flow?
      - the system authenticates and authorizes the app rather than a user
- ## What is Device Authorization Flow?
      - rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.
- ## What is Resource Owner Password Flow?
      - user inputs user and password into the website and exchange that for a token.




