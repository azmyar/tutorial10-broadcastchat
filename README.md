# Module 10
> M Azmy Arya Rizaldi M - 2206081704

## Original Code of Broadcast Chat
<img src="img/async-1.png">
Clients and server interact via WebSocket. So, when one client sends a message, the server forwards it to all connected clients. This results in a broadcast effect where a message sent by one client is received by all connected clients.

## Modifying Port
<img src="img/async-2.png">
To ensure proper functioning, we need to modify both ports (in `client.rs` and `server.rs`). If either of them has a different port from the other, the client won't be able to connect to the server.
