**Source**

Cerf, Vincent and Robert Kahn. 1974. "A Protocol for Packet Network Intercommunication.'' IEEE Transactions on Communications 22.5: 637-648

https://www.cs.princeton.edu/courses/archive/fall06/cos561/papers/cerf74.pdf



**Summary**

Kahn and Cerf talk about the development of the Transmission Control Protocol/Internet Protocol, also known as TCP/IP, and its impact on computer networking.


The concept of packet switching is hugely important in computer networking, the authors break down packet switching and explain how it works. 

They explain communication between processes. Using packet switching and TCP/IP, two things that have a connection can communicate with each other.

The TCP/IP protocols aims to solve some of the issues with interconnection in packet switching networks






**Key Quotes**


"In practice, a GATEWAY between two networks may be composed of two halves, each associated with its own network. It is possible to implement each half of a GATEWAY so it need only embed internetwork packets in local packet format or extract them. We propose that the GATEWAY handle internetwork packets in a standard format, but we are not proposing any particular transmission procedure between GATEWAY halves."


"A newly created port could apply to the central registry for an address which the central registry would guarantee to be unused by any HOST system in the network. Each TCP could maintain tables matching external names with internal ones, and use the external ones for communication with other processes."