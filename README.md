# example_tcp
The example_tcp folder contains a simple example of a server and a client
which They communicate together using the TCP communication channel.
The server works in Loopback on port 8080. A client that knows the IP address
server and the port number on which the server is listening will connect to the server
The client sends the data entered from the command line.
The server provides a service that translates lowercase letters in the text
sent to the client in capital letters (with toupper())
and sent back to the client.
The client displays the received data on the screen.

No socket multiplexing, it is possible to operate only one  
duplex communication without creating other new connections.

Windows /Linux 
bat file for Linux: https://www.linux.org/threads/running-windows-batch-files-on-linux.11205/