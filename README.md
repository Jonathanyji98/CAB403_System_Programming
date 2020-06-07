# CAB403
The is a chatbox client and server program 

To compile the program (make sure the make file, client.c and server.c file are all in the same folder)
1. Run “make clean” command to clear all the outputs. 
2. Run “make” command to compile the files. This make file compiles server.c and client.c. 

Starting the server and client:
To run the server, type in the command “./Server <port number>”. 
To run the client, type in the command “./Client <server_ip_address> <port_number>”.
  
Functions
1. SUB<Channelid>
2. CHANNELS
3. UNSUB<channelid>
4. NEXT<channelid>
5. LIVEFEED<channelid>
6. NEXT
7. SEND<Channelid><message>
8. BYE


