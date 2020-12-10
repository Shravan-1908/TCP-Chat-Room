# TCP-Chat-Room

This is a simple chat room created in python. This chat room contains two files, **server** and **client**.

### Server
The **server** file acts as a server for the chat room. It handles all the client messages and broadcasts it to the different clients. It may also close connection with a client due to some exception.

### Client
The **client** file is a client which sends messages to other clients through the server. Multiple instances of clients can be opened to
experience a real chatting experience.


*Note: The server is created on local host, at IP address*  ```127.0.0.1``` *, thus the clients can chat only on the local machine. Although, one can host it on a cloud service to make it a real life chat application.*
