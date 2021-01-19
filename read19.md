# What does it mean that web sockets are bidirectional? Why is this useful?
-it means that it is a two way communication . This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.


# Does socket.io use HTTP? Why?
- a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js


# What happens when a client emits an event?
-the client automatically reconnects and sends its buffered events
connect.

# What happens when a server emits an event?
-the server send emits , it make it on fire , the server runs

# What happens if a client “misses” an event?
# How can we mitigate this?
he socket receives the msg and doesn't find a handler for it so nothing happens with it.
-You make it listen.

--------------------------------------------

# Document the following Vocabulary Terms

### Web Socket :
is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

### Socket.io :
is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

### Client :
means that the JavaScript code is run on the client machine, which is the browser.

### Server :
 Server-side JavaScript means that the code is run on the server which is serving web pages.
 