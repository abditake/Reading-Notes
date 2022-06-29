 # [Class 12: Socket.io](/README.md)

## [Socket.io Chat Example](https://socket.io/get-started/chat/)
## [Rooms](https://socket.io/docs/v4/rooms)
## [Namespaces](https://socket.io/docs/v4/namespaces/)

<hr>










## Socket.io Chat Example

- ### Explain to a non-technical recruiter what the Chat Example (above) does.
    - allows for communication between server and all connected devices

- ### What proof of life are we getting on the backend from the above app?
    - if User connected is seen on the console

- ### Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
    - `broadcast.emit`
## Rooms

- ### What is a room and how might a room be useful?
    - a space/channel that sockets can join and leave. it is useful because it can allow communication to only specific parties and not the entire server.

- ### How do you join a room?
  - `socket.join('some room)`
- ### how do you leave a room?
  - `socket.join('some room)`
## Namespaces

- ### What is a Namespace and what does it allow you to do?
    - a namespace is a single shared connection
- ### Each namespace potentially has its own what? (hint: 3 things)
    -  each namespace has its own event handlers,rooms, and middleware.

- ### Discuss a possible use case for separate namespaces
    - create individual special namespaces that only authorized users have access to like for example client and supplier while separating that from the rest of the application. 