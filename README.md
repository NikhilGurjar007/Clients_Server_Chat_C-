# Clients_Server_Chat_C++
Socket programming is a way of connecting two nodes on a network to communicate with each other. One socket(node) listens on a particular port at an IP, while another socket reaches out to the other to form a connection. The server forms the listener socket while the client reaches out to the server.
1.Client and server communication
The client sends a request, and the server returns a response. This exchange of messages is an example of inter-process communication. To communicate, the computers must have a common language, and they must follow rules so that both the client and the server know what to expect.
2.Client-server socket programming
Socket programming is a way of connecting two nodes on a network to communicate with each other. One socket(node) listens on a particular port at an IP, while other socket reaches out to the other to form a connection. Server forms the listener socket while client reaches out to the server.
3.Sequence of function for client-server communication
create a client server socket connection  
Create a socket with the socket() system call.
Connect the socket to the address of the server using the connect() system call.
Send and receive data. There are a number of ways to do this, but the simplest is to use the read() and write() system calls
Send data from client to server in socket programming 
Create a socket with the socket() system call.
Bind the socket to an address using the bind() system call. ...
Listen for connections with the listen() system call.
Accept a connection with the accept() system call. ...
Send and receive data.
