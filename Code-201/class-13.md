# [Class 13: - Local Storage](/README.md)

- ## Local Storage- The past, present & future of local storage for web applications

<hr>

# Local Storage

- ## `cookies`: they send data from the browser to the server constantly.
    - they send data over and over needlessly
    - send unencrypted data 
    - the data they send is limited to 4kb 


- ## `userdata`: allows a certain amount of data for web pages to store.
- ## `html5 storage`: a way to store key/value pairs locally on the client/users web browser.  
    - unlike cookies the data isn't transmitted to a remote server

```
However, the data is actually stored as a string. If you are storing and 
retrieving anything other than strings, you will need to use functions like 
parseInt() or parseFloat() to coerce your retrieved data into the expected 
JavaScript datatype.(local Storage)
```

- ## `setitem*()`: calling with a key that has a value pair rewrites the value of the named key that already exists. 
- ## `getitem()`: calling with a key that has been declared will return null rather than throw an error.

### With html storage you can implement that in your code and not lose data that has been changed within your code. for example when making a game without using html storage you lose progress as soon as the page is closed. 

- ## `object store`: databases with records and fields, with each field with a specific datatype. 
  - Changes to the object store are called transactions
