# TCP-Implement
Northeastern University - Scalable Distributed System (CS 6650) - Fall 2024


Java Socket Programming implementation
The goal of this assignment is to implement a TCP client and server. You can use Java. Your TCP or UDP
client/server will communicate over the network and exchange data.
The server will start in passive mode listening for a transmission from the client. The client will then start
and contact the server (on a given IP address and port number). The client will pass the server a string (eg:
“network”) up to 80 characters in length.
On receiving a string from a client, the server should: 1) reverse all the characters, and 2) reverse the
capitalization of the strings (“network” would now become “KROWTEN”).
The server should then send the string back to the client. The client will display the received string and exit.
Example
Starting the server:
Assume that you started a server on machine 128.111.49.44, listening to port number 32000. The syntax
should look like the following:
csil-machine1> server 32000 <enter>
(in this line, “server” will be replaced by one of the names given below in the Submission Section)
Starting the client:
csil-machine2> client 128.111.49.44 32000 <enter>
(in this line, “client” will be replaced by one of the names given below)
Enter text: This is my text to be changed by the SERVER <enter>
Response from server: revres EHT YB DEGNAHC EB OT TXET YM SI SIHt
csil-machine2>
At this point (after receiving one line to be reversed), the server and client should both exit.
[Credits: Prof. K. C. Almeroth UCSB]
