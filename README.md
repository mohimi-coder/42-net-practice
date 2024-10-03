# 42-net-practice

NetPractice 42


![preview](https://github.com/user-attachments/assets/72f695d7-cbe0-4d62-942c-cce7f02b4ab4)


1 – Use  flsm (Fixed length subnet mask) 
How flsm works ?

192.168.1.0 255.255.255.0   --------> subnetwork=2
192.168.1.0/24

2^n ==> N 		n=number of bits to get from host id 

N = number of subnetwork

We have 2 subnetworks

2^n ==> 2

2^1 ==> 2

----------------------
192.168.1.0/25
1111 1111.1111 1111. 1111 1111.1000 0000 255.255.255.128


------------------------------
192.168.1.0/24 ==> 8 subnetworks

2^n => N	2^n => 8	2^3 => 8

 n = 3.  N = 8 
 
192.168.1.0/24 + n = / 27   1111 1111.1111 1111.1111 1111.1110 0000

Hop count = 2^n ==-> 2^5 = 32 

192.168.1.0/27 		|	192.168.1.128/27
192.168.1.32/27		|	192.168.1.160/27
192.168.1.64/27		|	192.168.1.192/27
192.168.1.96/27		|	192.168.1.224/27

# What is tcp/ip ?

TCP stands for Transmission Control Protocol. It is a communications standard that enables application programs and devices to exchange messages over a network. It is used to send packets across the internet.
TCP guarantees the integrity of the data being communicated over a network. Before it transmits data, TCP establishes a connection between a source and its destination, which remains active until communication begins. It then breaks large amounts of data into smaller packets, while ensuring end-to-end delivery without loss of any data.
TCP: Transport Layer


https://www.simplilearn.com/tutorials/cyber-security-tutorial/what-is-tcp-ip-model

🟢Application Layer

<img width="683" alt="Screen Shot 2024-10-03 at 8 47 21 PM" src="https://github.com/user-attachments/assets/383d40cd-b413-472f-96bf-252d4e2e552d">

This is the topmost layer which indicates the applications and programs that utilize the TCP/IP model for communicating with the user through applications and various tasks performed by the layer, including data representation for the applications executed by the user and forwards it to the transport layer.
Some of the protocols used in this layer are:
	✅HTTP: Hypertext transfer protocol is used for accessing the information available on the internet.
	✅SMTP: Simple mail transfer protocol, assigned the task of handling e-mail-related steps and issues.
	✅FTP: This is the standard protocol that oversees the transfer of files over the network channel.
 
🟢Transport Layer

<img width="683" alt="Screen Shot 2024-10-03 at 8 47 45 PM" src="https://github.com/user-attachments/assets/d23bda85-1673-451e-b34d-01f9868a5aff">


This layer is responsible for establishing the connection between the sender and the receiver device and also performs the task of dividing the data from the application layer into packets, which are then used to create sequences.
The protocols used in this layer are:
	•	TCP: Transmission Control Protocol is responsible for the proper transmission of segments over the communication channel. It also establishes a network connection between the source and destination system.
	•	UDP: User Datagram Protocol is responsible for identifying errors, and other tasks during the transmission of information.
 
🟢Internet Layer

<img width="683" alt="Screen Shot 2024-10-03 at 8 48 04 PM" src="https://github.com/user-attachments/assets/ef92e9a0-3b01-4284-8002-fa2e8ab41b70">


The Internet layer performs the task of controlling the transmission of the data over the network modes and enacts protocols related to the various steps related to the transmission of data over the channel, which is in the form of packets sent by the previous layer.
This layer performs many important functions in the TCP/IP model, some of which are:
	•	It is responsible for specifying the path that the data packets will use for transmission.
	•	This layer is responsible for providing IP addresses to the system for the identification matters over the network channel.
 
Some of the protocols applied in this layer are:
	•	IP: This protocol assigns your device with a unique address; the IP address is also responsible for routing the data over the communication channel.
	•	ARP: This protocol refers to the Address Resolution Protocol that is responsible for finding the physical address using the IP address.
 
🟢Network Access Layer

<img width="683" alt="Screen Shot 2024-10-03 at 8 48 21 PM" src="https://github.com/user-attachments/assets/d9b684fa-f1d9-4840-bdf5-0139c6626ee9">


This layer is the combination of data-link and physical layer, where it is responsible for maintaining the task of sending and receiving data in raw bits, i.e., in binary format over the physical communication modes in the network channel.

# OSI Model vs. TCP IP Model

<img width="529" alt="Screen Shot 2024-10-03 at 8 48 52 PM" src="https://github.com/user-attachments/assets/31513759-3592-4eae-8cf9-bbf0e62ee9d0">


<img width="1260" alt="Screen Shot 2024-10-03 at 8 28 27 PM" src="https://github.com/user-attachments/assets/8e20e78f-239f-4870-b82f-9f4020dcd10a">

# Functions of TCP/IP Layers

The TCP/IP model is a four-layer model that divides network communications into four distinct categories or layers. The model is often referred to as the TCP/IP stack. The four important layers are the application layer, the transport layer, the network layer, and the link layer.
	•	The Application Layer: The application layer is closest to the end user. And this is the layer that users interact with directly, including protocols such as HTTP, FTP, and SSH. This layer is responsible for providing applications with access to the network.
	•	The Transport Layer: The transport layer ensures that data is delivered reliably and efficiently from one point to another. This layer handles data transmission between hosts, including protocols like TCP and UDP.
	•	The Internet Layer: The network layer is responsible for routing data through the web. This layer delivers data packets from one host to another, including the IP protocol.
	•	The Link Layer: The link layer provides reliable data links between the two nodes — for example, protocols like ethernet and Wi-Fi.

# What is routing table ?

A routing table is a set of rules, often viewed in table format, that's used to determine where data packets traveling over an Internet Protocol (IP) network will be directed. This table is usually stored inside the Random Access Memory of forwarding devices, such as routers and network switches.


# What is router?

A router is a device that connects two or more packet-switched networks or subnetworks.

# What is switch ?

The Switch is a network device that is used to segment the networks into different subnetworks called subnets or LAN segments. It is responsible for filtering and forwarding the packets between LAN segments based on MAC address.

# Router vs switch 


![switch-vs-router-chart](https://github.com/user-attachments/assets/371adfe6-679a-40a0-b4d9-e02a1fddf0fe)


# What is the usage of this ip address 127.0.0.0 ?

https://www.pubconcierge.com/blog/subnetting-101-free-ipv4-cheat-sheet/

https://www.solarwinds.com/resources/it-glossary/network-protocols





