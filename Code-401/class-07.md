# [Class 06: Data Modeling](/README.md)

## [Intro to JWT](https://jwt.io/introduction/)

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

## [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

<hr>

## Intro to JWT

- ### What is a JSON Web Token (JWT)?
    - an open standard that defines a compact and self-contained way for securely transmitting information as json. 

- ### When should we use JSON Web Tokens?
    - authorization and information exchange.
- ### Claims are expected in which structural component of a JWT?
    - the payload.
        - registered claims
        - public claims 
        - private claims

## Are JWTs Secure?

- ### If I get a JWT and I can decode the payload, how can we call that secure?
- It's really not secure however an added part to a jwt is the private key. if a 
jwt isn't encrypted anybody can read its contents but wont be able to change it
without a private key. 

- ### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
      - The must know the private key or the secret.
- ### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
  ```
    you can send the Jwt over an encrypted channel an added layer to this would be 
  verifying the Jwt signature with a public key and matching it with the private key.
  every user that visits the site has a public key and they have to have that match 
  the private key and no other person can impersonate that.

  
  ```
## JWTs Explained

- ### Why use JWT?
      - securely transfer between two bodies
      - digitally signed- information is verified and trusted
      - compact can be sent via url, post request, http header
      - self-contained
          - avoids querying the database more than once
- ### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
  ```
    when a user signs in you have all your information stored. and this is done quickly 
  since Jwt can be sent via url, post, etc...Anytime the user now request any 
  information he no longer needs to verify or sign in the Jwt that was created in the 
  server just keeps being checked.

  
  ```

- ### What are the three components (the structure) of a JWT signature?
      - header
      - payload
      - signature