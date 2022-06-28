
 # [Class 12: Socket.io](/README.md)

## [Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
## [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
## [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)
## [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
## [TCP](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

<hr>


## Web Sockets

- ### What is a Web Socket?
    - Computer communication protocol, providing full-duplex communication channels over a single TCP connection. 

- ### Describe the Web Socket request/response handshake and what happens once the connection is established.
    - The client sends a WebSocket handshake request, then the server returns  a websocket handshake response. Once this is established the connection becomes bidirectional protocol which allows the WebSocket to send real time updates without requiring the client to submit a request each time. 

- ### Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
    - requested from the client 

Socket.io Tutorial

- ### What does the event handler io.on() do?
    - Whenever someone connects to which port the code is listening to, anything inside io.on gets executed. 

- ### Describe some possible proof of life or proof that the code works as expected
  - Creating a listen on the route 3000 and a sample html file. then hitting that route on your browser. if the io.on is configured right it should display either on the console whether the the user is connected or disconnected. of course you will need to import the Script in the html file for this to work as well. 

- ### What does socket.emit() do?
    - causes call callbacks registered to the event to fire. more specifically to this tutorial it sends an object.

Socket.io vs Web Sockets

- ### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
  - WebSocket doesn't support broadcasting and Socket.io does.
  - Socket.io has fallback options and WebSocket doesn't 
  - load balancers and proxys are not supported in WebSocket but are in Socket.io 
  - WebSocket is the protocol which is established over the TCP connection whereas Socket.io is the library to work with WebSocket. 

- ### When would you use Socket.IO?
  - If you want automatic reconnects and smaller additional features

- ### When would you use WebSockets?
  - If you want a clean piece of code that connects directly to TCP. It isn't as bloated as Socket.io.

Videos
OSI Model Explained

- ### What are a couple of key takeaways from this video?
  - All People Seem To Need Data Processing.
    - APSTNDP 
  - Time division multiplexing
    - every conversation has a single moment in time to send it's data. 
  
TCP Handshakes Explained

- ### Translate the gist of this video to a non-technical friend
    - TCP needs to be established by a three-way handshake.
      - this is done by synchronization acknowledgment
  - the client asks if it can shake the servers hand. The server replies yes before reaching out and shaking the client's hands. then finally they shake each others hand. 