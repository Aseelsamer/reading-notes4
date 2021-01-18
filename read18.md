# What is the benefit of transforming data into packets?
- to meet the demands of pervasive data-centric applications and services.

# UDP is often refereed to as a connectionless protocol. Why is this?
-UDP is a connectionless protocol. No connection needs to be established between the source and destination before you transmit data. UDP does not have a mechanism to make sure that the payload is not corrupted.


# Can a socket server application have multiple socket connections?
-Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it .


# Can a socket connection application be connected to multiple socket servers?

-Yes it can . 

# Can an application be both a socket server and a socket connection?
-Yes you can , but you have to make thread for the server and thread for the connection.


# Document the following Vocabulary Terms


Term
### OSI Model :
 Open Systems Interconnection (OSI) model, a conceptual framework that describes the functions of a networking or telecommunication system.


### TCP Model :
The TCP/IP model includes specifications for translating the network addressing methods used in the Internet Protocol to link-layer addresses.


### TCP:
 is one of the main protocols of the Internet protocol suite.


### UDP:
 is one of the core members of the Internet protocol suite.


### Packets:
 is a small amount of data sent over a network, such as a LAN or the Internet. Similar to a real-life package, each packet includes a source and destination as well as the content (or data) being transferred.


### Socket:
 is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to.