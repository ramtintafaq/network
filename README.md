  
**COMPUTER NETWORKS QUIZ**

   
Bot version on Telegram: [https:	//t.me/networks\_quiz\_bot](https://t.me/networks_quiz_bot)  
Additional quizzes (unofficial and unverified): [Drive 02 Dttrip](https://www.dropbox.com/sh/6oezv9540vc7tf6/AAA9ZUenTKvzFQlOQ3dQeELAa?dl=0)  
At the bottom of the file you will find the questions from Reti's oral exams. Together with the questions for the final exam **Do not modify the file for personal purposes, you will break the bot\!** Edit it only to contribute to the quizzes respecting the correct formatting, thanks\! **Before editing answers check it out compare yourself on the group of networks connected to the telegram bot [t.me/inginf\_bot](http://t.me/inginf_bot)**   
to allow others to evaluate whether the previous answer is wrong or not\!

SLIDE CHAPTERS  
3\) Fundamentals of data transmission  
4\) Audio and video  
5\) Reti TLC  
5\) Reti TLC 2  
6\) Network architectures and protocols

                  **Thatrcizio 1\.** Common channel signaling provides that

1) The control equipment of the switching exchanges yes they exchange signaling information in packet switching                                                                                          
2) Each channel dedicated to the transmission of user data is associated with a different reporting channel   
3) The signaling between the switching centers occurs by sharing a single channel via satellite  
     
   null verified.  
   Comment: In common channel signaling the user information travels on separate channels but with a single signaling channel used to control the signaling of all user channels. The signaling channel works on a packet basis.

     
   **Exercise 2\.** The characteristics of a fully connected mesh topology are  
       A) High number of channels, good fault tolerance, easy routing  
       B) High number of channels, good fault tolerance, difficult routing  
       C) Low number of channels, poor fault tolerance, difficult routing  
     
   null verifyfacing.  
   Comment: see transparencies “Meshed topology”. NoIn a fully connected mesh there is always a direct path between each node.  
     
   **Exercise 3.** Conversational interactive telecommunications services are characterized by

       A) Low probability of error in the transfer of information  
       B) Transfer of information in real time  
       C) Storage of information online and delivery to the recipient in a deferred time  
     
   null verified.   
   Comment: In conversational interactive services, communication occurs with the transfer of information from end to end in real time. See “Conversational Interactive Services” transparencies.

   **Exercise 4\.** In packet switching networks the factors that lead to the choice of small packet sizes are  
1) Lower incidence of control information, greater efficiency in the transfer of SDU large in size  
2) Better parallelization possibility, lower transfer delay, lower probability of bit error  
3) Better parallelization possibility, lower packetization delay, lower probability of packet error

 

null verified.  
Comment: The length of the packets is determined by: possibility of parallelization (pipeline), packetization delay, percentage of control information. Short packets favor the parallel transmission on different channels of packets of the same communication, short packets reduce the packetization delay (important for voice traffic on packet networks), long packets reduce the percentage of control information.  

**Exercise 5.** In the OSI model, the transport layer provides services  
    A) Based on services from the application layer  
    B) Based on the services provided by the network layer  
    C) Building on the services provided by the session layer

null verified.  
Comment: Think about the ISO/OSI stack. See transparencies on the OSI model.

**Exercise 6\.** Which of the following statements conforms to the ISO/OSI reference model?  
    A) One (N)-entity and one (N-1)-entity can have the same address.  
    B) One (N)-entity can be associated with two different (N-1)-addresses.  
    C) Two (N)-entities can be associated with the same (N-1)-address.

null verified.  
Comment: Each entity is characterized by the acronym (address) of its layer, so A and C are wrong and by exclusion the correct answer is B. Internet source.  
	  
**Exercise 7\.** In a Go-Back-N window protocol it may be convenient to increase the size of the transmission window (measurement in number of data)  
 A) When the transmission speed increases with the same size of the data units and equal transfer delays of the data units between transmitter and receiver  
  B) When the transmission speed decreases with the same size of the data units and equal transfer delays of the units between transmitter and receiver  
  C) When the distance between transmitter and receiver decreases, therefore the transfer delays of the data units, without changing the transmission speed  
   D) When the probability of error on the channel increases

null verified.  
Comment: Efficiency of a window protocol. Assuming you have *n=k*, we have Wt=k(1+2\*(tp/tx)). As the transmission speed increases, the tx transmission time decreases, imposing an increase in Wt to ​​maintain the efficiency equal to k.

**Exercise 8\.** A Go-Back-N window protocol **non** requires an increase in complexity compared to a Stop-And-Wait relatively  
    A) Amount of memory required from the transmitter  
    B) Minimum amount of sequence numbers required to distinguish data units  
    C) Amount of memory required from the receiver

null verified.  
Comment: Go-Back-N does not require an increase in complexity with respect to the reception window at the receiver. Per lo Stop and Wait INR=1 and for the Go-Back-N INR=1.

**Exercise 9\.** I protocolli Aloha ed S-Aloha

  A) To avoid interference between the transmissions of users who share a broadcast channel, assign each user a fixed time interval in which to transmit  
   B) They do not implement any preventive controls to avoid interference between user transmissions 	that share a broadcast channel; only in the case of interference (collision) is action taken, repeating the transmission after a delay fixed  
 C) They do not implement any preventive control to avoid interference between the transmissions of users sharing a broadcast channel;   
only in the case of interference (collision) is action taken, repeating the transmission after a delay random

null verified.  
Comment: Aloha has low efficiency because the nodes transmit without coordinating with each other, only in case of collision a backoff: The two (or more) stations that collided wait a random time before retransmit the PDU. The random time serves to break determinism and if the two (or more) stations waited the same time, there would again be a collision with probability 1\. In this case the   
maximum random wait time.

**Exercise 10\.** The architecture of Internet protocols is organized  
    A) In seven levels  
    B) In four levels  
    C) In six levels  
    D) In ​​a completely non-stratified way

null verified.  
Comment: The Internet today is based on the ARPA architecture composite from 4 levels. The levels are: application, service, internetwork, network. Source: “Layered Architecture” transparencies, see also video lesson.

**Exercise 11\.** The TCP receiver  
    A) Send cumulative acknowledgments (ACKs).  
    B) Send an acknowledgment (ACK) for each segment received  
    C) Does not send feedback

null verified.  
Comment: By definition TCP uses window protocols that make use of cumulative ACKs. See “TCP” transparencies.

**Exercise 12\.** The header of the TCP segment, i.e. the PCI of the TCP protocol  
    A) It is always a fixed size of 20 bytes  
    B) It is of variable size depending on the options present  
    C) It has a fixed size of 40 bytes

null verified.  
Comment: Exists in the TCP header   
a variable-sized Options field. See “TCP” transparencies.

**Exercise 13\.** Logical addresses on the Internet are  
    A) Determined completely freely by the system administrators of each subnet  
    B) Organized into domains  
    C) Completely free format

null verified.  
Comment: See transparencies on IP.

**Exercise 14\.** The routing protocol can be used between AS (Autonomous System).  
    A) EGP (Exterior Gateway Protocol)  
    B) RIP (Routing Information Protocol)  
    C) OSPF (Open Shortest Path First)

null verified.  
Comment: The exchange of information between routers belonging to different ASs occurs through the EGP type routing protocol. (Source Wikipedia)

**Exercise 15\.** In the OSI model, one (N)-connection  
    A) It can be achieved using one or more (N-1) connections  
    B) It is terminated by two (N-1)-CEPs  
    C) It can be achieved using one or more (N+1)-connections  
    D) It can only be achieved using multiple (N-1)-connections

null verified.  
Comment: By definition an (N)-layer provides services to (N+1)-layers. This means that its user (the N+1 layer) will have to request a connection before being able to use the service. An N layer can correspond to several N-1 connections.

**Exercise 16\.** Compared to the 10 Mbit/s Ethernet standard, in the definition of 100Mbit/s Ethernet the MAC protocol  
    A) AND' has been modified to allow for more efficient collision detection  
  B) AND' has been modified by introducing a mechanism to avoid collisions, improve performance and support real-time services  
    C) It was kept unchanged, accepting the reduction by a factor of ten (approximately) called "collision domain"  
   D) It was kept unchanged, keeping the maximum size unchanged by increasing the minimum size of the plot by a factor of ten

null verified.  
Comment: See transparencies on MAC.

**Exercise 17\.** The metric (cost) in a routing algorithm  
    A) Expresses the weight to be assigned to a (channel) link in path selection  
    B) Expresses the calculation complexity of the algorithm	  
    C) Expresses the probability that the shortest path will be used

null verified.  
Comment: See transparencies.

**Exercise 18\.** The advantages of virtual circuit-type services over datagram-type services in a packet-switching network are  
 A) Less packet delay, routing calculation for each packet  
 B) Less variability in packet delays, maintaining packet sequence, routing for each packet  
 C) Less variability in packet delays, maintenance of packet sequence, routing only when opening the connection

 null verified.  
Comment: The advantages of virtual circuit services compared to datagram services are: maintenance of the sequence (I always take the same route), less variability in delays (processing delay only), routing only during the connection opening phase. See “Virtual circuit service” transparencies.  
Learning

**Exercise 19\.** Which of the following statements is true regarding IEEE 802.1d Transparent Bridges?  
    A) The routing follows "backward learning" and flooding criteria  
    B) Routing is based on the exchange of routing tables between bridges	  
    C) Routing always occurs in flooding mode

null verified.  
Comment: (Internet source). Local networks standards, page 41

**Exercise 20\.** Compared to 100 Mb/s Fast Ethernet (100Base T), 1 Gb/s Ethernet allows you to meet time constraints on collision recognition  
    A) Decreasing the distance between nodes  
    B) By imposing optical fiber as the transmission medium  
    C) Increasing the minimum size of PDUs

null verified.  
Comment: by switching to 1Gb/s to maintain Transmission Time \> RTT by acting on propagation times there would be a need for minimum distances between the hosts (a few tens of metres), the only solution is to increase the minimum size of the PDUs so as to increase Transmission Time.,  
By increasing the minimum size of PDUs, the time required to transmit a packet increases, allowing for a greater ability to detect and handle collisions in the network.

**Exercise 21\.** Compared to CBR (Constant Bit Rate) type sources, VBR (Variable Bit Rate) type sources  
    A) They have greater difference between maximum and minimum transmission speed  
    B) They have more stringent requirements on maximum delay  
    C) They have more stringent requirements on average delay

null verified.  
Comment: CBR is used in video conferences (speed of 64kb/s). VBR is used for streaming and file transfer (for first order Mb/s for second order Mb/s kb/s a Gbps).

**Exercise 22\.** End-to-end error recovery in the Internet environment, when present,  
    A) It is always carried out only by application processes  
    B) It is carried out at the Transport level  
    C) It is carried out at the Internet (network) layer  
    D) It is not foreseen for any type of service

null verified.  
Comment: End-to-end is one of the principles of computer network design and is applied on 	different network protocols such as in the UDP protocol (Layer 4 protocol, transport layer). (Source Wikipedia).

**Exercise 23\.** The POP3 protocol  
    A) It is used to block pop-ups in a web browser  
    B) It is used to exchange email messages between mail servers  
  C) It can be used to transfer email messages from a server to an email client installed on a PC  
    D) Use messages that always include encrypted authentication

null verified.  
Comment: The Post Office Protocol (POP) is a client-server application level protocol which has the task of allowing a client to access an email account present on a server host and download e-mails. \-email of the account itself. The B refers to the SMTP protocol.

**Exercise 24\.** What is meant by collision domain in Ethernet?  
    A) The portion of the network within which the same collision is detected  
    B) The number of packet header bits that can be corrupted by a collision    
    C) The set of nodes that interrupt transmission due to a collision

null verified.  
Comment: Collision domain: portion of the network in which two frames collide. See “Collision Domain” transparency. 

**Exercise 25\.** In una sottorete IP (Logical IP Subnet)  
    A) The hosts share the same network prefix  
    B) The network prefix always consists of the first three bytes of the address  
    C) Hosts always communicate by going through the router

     
null verified.  
Comment: In a network all the subnets created must have the same network address. B is incorrect since the network prefix does not necessarily consist of the first 3 bytes.    
   
**Exercise 26\.** In the OSI reference model one (N)-PCI can contain  
    A) (N)-addresses  
    B) (N+1)-addresses  
    C) (N-1)-addresses

null verified.  
Comment: This is the header of that level which can only contain level N addresses. The N-SDU will contain (N+1) addresses.

**Exercise 27\.** The TCP protocol  
    A) It provides error detection on each segment's data using a checksum  
    B) Provides error detection only on the segment header  
    C) It does not provide data error detection and recovery

null verified  
Comment: TCP offers error control functionality on received packets thanks to the checksum field contained in its PDU. See transparencies “TCP” (Source Wikipedia).

A) It provides error detection on each segment's data using a checksum.

The reason behind this answer is that TCP provides error detection on each segment's data using a checksum. The checksum is a value calculated on the segment data, which allows you to detect any transmission errors or data corruption during transfer. When the recipient receives the segment, it calculates the checksum again and compares it to the received checksum value. If the values ​​do not match, it is assumed that an error occurred during transmission.

C) Does not provide data error detection and recovery: This option is incorrect because TCP provides an error detection mechanism using the checksum. Additionally, TCP also includes error recovery mechanisms, such as acknowledgment and resending of lost or damaged segments.

Therefore, the correct answer is option A) Provides error detection on each segment's data using a checksum.  
 

**Exercise 28\.** The P/F(Poll/Final) bit of frames in the LaPB layer 2 protocol  
    A) Provides implicit confirmation on plots not yet confirmed  
    B) Allows you to request the sending of a confirmation by the receiver  
    C) Speeds up the transmission of information

null verified.  
Comment: The Poll and Final field is a single bit and has two uses. It is called Poll if it is used by the primary station to ask for a response from the secondary stations, while Final when it is used by a secondary station to indicate a response at the end of the transmission. It has meaning only if set to 1\. (Source Wikipedia).

**Exercise 29\.** Which of the following protocols does not perform data unit delimitation functions?  
    A) LaPB (Link access Procedure Balanced), used in ISDN channel B  
    B) LaPF (Link access Producer to Frame-mode bearer services), used in Frame Relay networks  
    C) PPP (Point-to-Point Protocol), used in domestic Internet access  
    D) IEEE 802.2 LLC (Logical Link Control), used in local networks

null verified.  
Comment: The delimiters are inserted later by the MAC protocol. See “IEEE 802.2 Logical Link Control” transparencies.

**Exercise 30\.** What is essential for Ethernet in full-duplex mode?  
   A) The ability to simultaneously receive and transmit packets  
   B) The availability of fault protection techniques through two disjoint paths between each pair of nodes  
   C) Full support for both 10 Mbit/s and 100 Mbit/s speeds

null verified.  
Comment: A full-duplex physical medium has the characteristic that transmission and reception occur on separate cables. This means I can simultaneously receive and transmit packets.

**Exercise 31.** The characteristics of a tree topology are  
    A) Low channel count, bad fault tolerance, easy routing  
    B) Low channel count, good fault tolerance, easy routing  
    C) High number of channels, good fault tolerance, difficult routing

null verified.  
Comment: See “Tree topology” slides.

**Exercise 32\.** Version 4 IP addresses are:  
    A) Of fixed total length, composed of a part of variable length that identifies the network and a part of variable length that identifies the host  
    B) Of fixed total length, composed of a fixed-length part that identifies the network and a fixed-length part that identifies the host  
    C) Of a variable length, composed of a part of variable length that identifies the network and a part of variable length that identifies the host

null verified.   
Comment: IPV4 definition. See “IPV4” transparencies.

**Exercise 33\.** In Store-And-Forward packet-switched networks, the use of large PDUs (packets):  
    A) It reduces the probability of losing information by error on the bits received  
   B) Minimizes the transfer delay because, as there is less overhead due to the control information present in each PDU, the total amount of information to be sent is smaller  
  C) Requires a larger header to allow management of all the information contained in the PDU  
   D) Increases the overall information transfer delay because each node must receive the entire PDU before it can send it on the next channel

null verified.  
Comment: Sending large packets on Store-And-Forward nodes leads to a non-negligible delay in information transfer. For this reason it is preferable to send small packets in order to minimize the storage time (Store).

**Exercise 34\.** A Selective Repeat protocol with a transmit window of size Wt and a receive window of size Wr  
    A) It can only work if, k being the number of numbering bits, we have INT+INR2k \-- Wt \+ Wr \<= 2^k  
    B) It can only work if, k being the number of numbering bits, we have INT2k \-- Wt \<= 2^k  
    C) It can only work if, k being the number of numbering bits, we have INR2k \-- Wr \<= 2^k

null verified.  
Comment: See “Selective Repeat” transparencies.

**Exercise 35\.** Il PPP(Point-to-Point Protocol)  
    A) Use a Go-Back-N window protocol for recovering lost data drives  
    B) Use the address field in data units to distinguish commands from responses  
    C) Uses the sequence 01111110 to delimit the data units in a similar way to LaPB (ISDN channel B)

null verified.  
Comment: See transparencies “PPP PDU Encapsulation”.

**Exercise 36\.** Il PPP(Point-to-Point Protocol)  
    A) Use a Go-Back-N window protocol for recovering lost data drives  
    B) Use the address field in data units to distinguish commands from responses  
2 C) Use the sequence 01111110 to delimit the data units in a similar way to LaPB (ISDN channel B)

null verified.  
Comment: Duplicate quiz see 35\.

**Exercise 37\.** Which of the following performances are possible thanks to Store-And-Forward operation in a packet network?  
  A) The possibility of having different transmission speeds between the different channels certificates to the same switch.   
    B) The reduction of information transfer delays through a switching node.  
    C) Reducing the size of packet headers.  
    D) The possibility of using Forward Error Correction channel coding

null verified.  
Comment: Ability to adapt to channels with different capacities. 

**Exercise 38\.** The difference between teleservices, carrier services and supplementary services lies in the fact that  
    A) While bearer services only offer the transfer of information between user-network interfaces, teleservices involve the functions of user equipment according to pre-established protocols; supplementary services, on the other hand, modify or integrate a carrier service and a teleservice  
    B) While teleservices only offer the transfer of information between user-network interfaces, carrier services involve the functions of user equipment according to pre-established protocols; supplementary services are special services for data transfer   
    C) While bearer services only offer the transfer of information between user-network interfaces, teleservices involve the functions of user equipment according to pre-established protocols; supplementary services are special services for data transfer

null verified.  
Comment: Bearer services are the services offered by the telephone line. It is called carrier because it is an essential service without which we cannot perform all other teleservices. It provides the possibility of transmitting signals between user interface and network. Teleservices are services enabled by bearer services. They provide the complete possibility of communication between users according to pre-established protocols. Supplementary services integrate or modify one or more basic services. See transparencies “Classification of telecommunications services”.

**Exercise 39\.** According to the OSI model, the functions in a telecommunications network are  
    A) Operations available on a service interface  
    B) The rules of interaction between entities belonging to the same architectural layer  
    C) Operations carried out within an architectural layer

null verified.  
Comment: See “Network Architecture” slides.  B is the definition of communication protocol: In a network, the rules that define the interaction between elements of a network are called *communication protocols.*

**Exercise 40\.** Consider a transmitter host that uses the TCP protocol and a receiver with infinite speed, i.e. one that always declares the maximum available value as the reception window. Given a current transmitter window of size equal to 10 segments, with a maximum receiver window equal to 20 segments, when the transmitter receives a segment containing an ACK from the receiver, which of the following situations is possible?  
    A) The current window at the transmitter becomes 3 segments  
    B) The current window at the transmitter becomes 51 segments   
    C) The current window at the transmitter becomes 11 segments  
    D) The current window at the transmitter becomes 13 segments

null verified.  
Comment: Assuming that the ACK received is the tenth of that transmission and assuming a TCP with Slow Start, then the cwnd increases by \+1 segments upon receipt of each ACK.

**Exercise 41\.** Il Domain Name System (DNS)  
    A) It allows you to assign an Ethernet address to a host based on its IP address  
    B) Create a mapping function between (3)-addresses and (2)-addresses in OSI terms  
    C) Allows an application to know the IP address of a website whose logical name is known  
    D) It allows you to know the physical location of an Internet host

null verified.  
Comment: DNS application layer protocol composed of 2 fundamental elements: the hierarchical structure and the application protocol to interact with this hierarchical structure. DNS is a system that allows us to convert a logical name of a website into an IP address. 

**Exercise 42\.** Given a number of nodes and a number of channels, a T1 topology for which the average distance between nodes is smaller than another T2 topology, in the presence of uniformly distributed traffic,  
    A) It allows the same amount of traffic to be distributed on the channels  
    B) It allows a smaller amount of traffic to be distributed on the channels  
    C) It allows a greater quantity of traffic to be distributed on the channels

null verified.  
Comment: If the average distance decreases, the Throughput increases. “For uniform traffic and	regular topologies, the traffic that can be disposed of is inversely proportional to the average distance.” Slide 53 General Concepts.

**Exercise 43\.** The piggybacking technique in window protocols consists of the possibility of  
    A) Send any data units that have experienced transmission errors back to the transmitter  
    B) Concatenate multiple hits into a data unit  
    C) Transport feedback information and user data in the same data unit  
    D) Have the receiver explicitly report any data unit losses to the transmitter

null verified.  
Comment: Piggybacking allows, in the case of bidirectional information flows, the possibility of writing the feedback information (ACK) in the header of the PDU traveling in the opposite direction. This allows a saving of ACKs. 

 **Exercise 44\.** Distinguishing commands and responses in layer 2 protocol frames LaPB aims to  
    A) Understand whether a Poll bit or a Final bit was sent  
    B) Understand who the recipient of the plot is  
    C) Distinguish supervision frames from information frames

null verified.    
Comment: The LAPB protocol belongs to the HDLC protocol family. It presents a supervision frame used for error and flow control, for example when only commands, responses and confirmations (no data) need to be sent. This frame by definition does not have a data field.

**Exercise 45\.** In a local area network (LAN) on a bus topology with protocol of access CSMA, the amount of time that various nodes detect a collision between the transmissions of two particular nodes  
    A) It is higher for nodes near the ends of the bus and lower for nodes in the center of the bus  
    B) It is the same for all nodes in the network  
    C) It depends on the position of the nodes with respect to the transmitters of the packets that generate the collision  
    D) depends on the speed of propagation of the signal

null verified.  
Comment: See “CSMA” transparencies.

**Exercise 47\.** The header of a data packet in a packet-switched network with datagram service contains  
    A) The source and destination node addresses  
    B) The address of the destination node and a connection identifier  
    C) A connection identifier  
    D) The address of the source node and a connection identifier,

null verified.  
Comment: See transparencies “IP datagram format”.

**Exercise 48\.** Compared to the 10 Mbit/s Ethernet standard, in the definition of 100 Mbit/s Ethernet, the MAC protocol **(duplicate quiz)**  
    A) It has been modified by introducing a collision avoidance mechanism, which improves performance and supports real-time services.  
    B) It was kept unchanged, accepting the reduction of the maximum size of the “collision domain” by a factor of ten (approximately).   
   C) It was kept unchanged, keeping the maximum size of the "collision domain" unchanged, but increasing the minimum size of the frame by a factor of ten.  
     D) It has been modified to allow collisions to be detected more efficiently.

null verified.  
Comment: See transparencies. 

**Exercise 49\.** Il PPP(Point-to-Point Protocol) **duplicate quiz**  
    A) It uses a go-back-n window protocol for recovering data drive losses  
    B) Makes use of the address field in data units to distinguish those sent by the user from those 		sent by the operator  
    C) It uses a known sequence of bits to delimit data units

null verified.  
Comment: See transparencies “PPP PDU Encapsulation”.

**Exercise 50\.** An IP router after calculating the route  
    A) Change the source and destination IP addresses of the datagram  
    B) Edit the Time To Live and Header Checksum fields in the datagram header  
    C) Only modify the Time To Live field in the datagram header

null verified.	  
Comment: If I modify the Time To Live I must therefore also modify the Header Checksum otherwise I would be given an error. This leads me to exclude C, while A makes no sense as an answer. (Source: Marchetto)  
   
**Exercise 51\.** An Ethernet card in a switch processes (i.e. reads and decides whether and how to route)  
    A) Only packets with broadcast destination MAC address  
    B) All packets, regardless of destination address  
    C) Only packets with a unicast destination MAC address equal to that of the switch  
    D) Only packets with multicast destination MAC address

null verified.   
Comment: See switch operation.

**Exercise 52\.** Which of the following statements is true? A host connected to the Internet, when it wants to transmit/receive data to/from any other host on the Internet, must know.  
    A) Your IP address and mask, your MAC address, the IP address of the default router,   
the IP address of a DNS  
    B) Just your MAC address  
    C) Only your IP address  
   
null  verified.  
Comment: Source Marchetto.

 **Exercise 53.** By switching we mean  
    A) The transfer of information from one point to one or more other points  
    B) The exchange of information regarding the control and management of a telecommunications network  
    C) The process of interconnecting resources for the time necessary for communication

null verified.  
Comment: See transparencies “Function: switching”. A represents TRANSMISSION and B represents SIGNALING. 

**Exercise 54 duplicated**. In the OSI model, the transport layer provides services  
    A) Based on services from the application layer  
    B) Based on the services provided by the network layer  
    C) Building on the services provided by the session layer

null verified.  
Comment:Layer 4 uses the services of layer 3 (network) to provide its services to higher layers.

**Exercise 54\.** In the OSI model, the network layer provides services  
    A) Based on the services provided by the application layer  
    B) Based on the services provided by the transport layer  
    C) Based on the services provided by the link layer

null verified.  
Comment: The network layer is above the link layer.

**Exercise 55\.** In a real mobile radio channel, the fading phenomenon consists of:  
    A) Decrease in received power, caused by the distance between transmitter and receiver  
    B) Rapid variation in received power, caused by sources operating at the same frequency  
    C) Decrease in received power, caused by atmospheric sources such as rain and snow   
    D) Rapid variation in the power received, caused by the presence of moving obstacles

null verified.  
Comment: See transparencies “Channel radio (mobile) real".

**Exercise 56\.** They are obligatorily contained in the IP header, i.e. in the PCI of the IP protocol  
    A) The IP address of a source and destination  
    B) The port of a source and destination  
   C) The Window field which allows the receiver to report the current size of the receiving window to the transmitter  
    D) The source and destination MAC address

null verified.  
Comment: See transparencies “IP datagram format”.

**Exercise 57\.** The IP protocol  
    A) It guarantees error detection only on the datagram header  
    B) It guarantees error detection on the header and content of the datagram  
    C) It does not provide any type of error protection  
    D) It guarantees error detection only on the content of the datagram

null verified.  
Comment: The Header Checksum field (16 bit) is used to verify that the IP header arrived at the destination intact. If the header undergoes modifications during transport, the checksum is different and the IP protocol understands that there has been an error. Note that the checksum verifies the integrity of the header only, and not of the transported data. 

**Exercise 58\.** The greater complexity of the Go-Back-N protocol compared to the Stop-And-Wait protocol is due   
    A) To the greater complexity of the transmitter  
    B) To the greater complexity of the receiver  
    C) To the greater complexity of both the receiver and the transmitter  
    D) To the management of timeout of the receiver

null verified.  
Comment: Since Go-Back-N and Stop-And-Wait have almost the same complexity at the receiver, at the transmitter it is larger, and is due to the fact that for the former the transmission window is greater than one while for the second is equal to one.

**Exercise 59\.** The use of cookies in the HTTP protocol allows you to  
    A) Associate multiple requests made by the same browser or user  
    B) Cache the responses received  
    C) Download all the objects contained in a page by opening a single TCP connection  
    D) Send the response to the client using several fragments (Chunked Transfer)

null verified.  
Comment: See “cookies” transparencies.

**Exercise 60\.** In a fully connected mesh topology with N nodes, the number of bidirectional channels is equal to  
    A) N(N-1)/2  
    B) 2N  
    C) N-1  
    D) N

null verified  
Comment: See “Meshed Topology” transparencies.

**Exercise 61\.** The IP protocol provides a service  
    A) Unreliable (i.e. without guarantee of delivery) and connectionless  
    B) Reliable (i.e. with delivery guarantee) and connectionless  
    C) Unreliable (i.e. without delivery guarantee) and connection oriented

null verified.  
Comment: IP is a connectionless and best effort packet protocol, which does not guarantee any reliable form of communication in terms of error control, flow control and congestion control. (Source Wikipedia)  

**Exercise 62\.** Compared to the IP protocol, the UDP protocol  
    A) It adds nothing  
    B) Adds the ability to carry messages while distinguishing between different application processes on the same host  
    C) It allows reliable transport of information

null verified  
Comment: By definition UDP is unreliable (connectionless), it performs multiplexing and demultiplexing. 

**Exercise 63\.** CIDR (Classless Inter Domain Routing), based on the use of netmasks in IP addresses, is a technique used to  
    A) Decrease the convergence time of routing protocols  
    B) Use IP address space efficiently  
    C) Avoid the formation of 

routing loop in routing 

null verified  
Comment: Quora source: “A **CIDR IP address** looks like a normal IP address except that it ends with a slash followed by a number, called the IP network prefix (e.g.-255.255.255.240/24) CIDR addresses reduce the size of routing tables and make more IP addresses available within organizations.”

**Exercise 64.** Which of the following line encodings is more efficient, i.e. requires a lower bit rate at the physical level for the same information rate transmitted?  
    A) Coding 4B5B  
    B) Encodes 64B66B  
    C) 8B10B coding

null verified.  
Comment: If every 4B I send 5B, to maintain a constant Throughput I have to increase the transmission speed by a factor of 5/4, same thing for the others. A 64/66 encoding allows me to scale up by a very small factor of 66/64, so it requires a lower bit rate. (1.03 times the initial bit rate, compared to 1.25 for the other 2 encodings.)

**Exercise 66.** The DSL access network separates data and voice on the same transmission medium between user equipment and exchange equipment using:  
    A) Time multiplexing   
    B) Frequency division multiple access  
    C) Time division multiple access  
    D) Frequency multiplexing

null verified.  
Comment: An ADSL filter is in fact used both on the user side and on the exchange side precisely to divide voice and data into frequency and not give yourself disturbance between them. If you look, an ADSL filter is made up of a low-pass filter for voice.

**Exercise 67\.** The Stop-And-Wait protocol  
    A) It can only work using more than one numbering bit  
    B) It can work using a number of numbering bits greater than or equal to 1  
    C) It can only work using a single numbering bit  
   D) It can only work using a number of numbering bits smaller than the size of the transmission window

null verified.  
Comment: By definition, in the Stop-And-Wait protocol the possibilities of malfunction are reduced by using a greater number of bits for numbering or a maximum lifetime for PDUs and ACKs.

**Exercise 68.** In a tree topology with N nodes, the number of bidirectional channels is equal to  
    A) N  
    B) N-1  
    C) 2N  
    D) N(N-1)/2

null verified.  
Comment: See “Tree Topology” slides.  
   
**Exercise 69\.** They are obligatorily contained in the UDP header, i.e. in the PCI of the UDP protocol  
    A) The value of the Maximum Segment Size negotiated between transmitter and receiver    
    B) The checksum field, for error detection  
    C) Some flags (in the CODE field) for opening and closing the connection

null verified.  
Comment: UDP only provides basic transport layer services, namely: connection multiplexing and error checking via a checksum inserted in the packet header. (Source Wikipedia)

**Exercise 70\.** The transport layer in the Internet  
    A) Provides reliable transport of information if the UDP protocol is used  
    B) It provides only unreliable transportation  
    C) It always provides reliable transport of information  
    D) Provides reliable transport of information if the TCP protocol is used

null verified.  
Comment: TCP is a transport layer packet network protocol belonging to the suite of the protocols   
internet which deals with transmission control or making data switching on the network between sender and recipient reliable. (Source Wikipedia)

**Exercise 71\.** In a routing table of an IP router there is a mask in which the first 24 bits (the most significant) are 1 and the last 8 bits (the least significant) are 0\. Which of the following statements is true?  
    A) The mask can be associated with a "subnetted" class B address  
    B) The mask is certainly associated with a "subnetted" class A address  
    C) The mask cannot be associated with a class C address

null verified.   
Comment: A mask of 24 can be associated with a class A, B or C IP address. If it were class C, the subnet would be as long as the class subnet: it would not create subclasses but would still be admissible (since the mask would still be \>= to the class subnet).

**Exercise 72\.** A Go-Back-N protocol with transmission window of size Wt  
    A) It can only work using a number of numbering bits greater than or equal to log2(Wt)     
    B) It can only work using a number of numbering bits greater than or equal to log2(Wt-1)    
    C) It can only work using a number of numbering bits greater than or equal to log2(Wt+1)  

null verified.  
Comment: By definition Go-Back-N allows Wt\<2^k as transmission window. That is, Wt \<= 2^k-1 ;  Wt+1 \<= 2^k ;   k\>=log2(Wt+1)

**Exercise 73\.** ADSL (Asymmetric Digital Subscriber Line) technology  
    A) It was mainly designed to provide a voice/data access service to a residential user who mainly accesses the Web as a client  
    B) It was designed primarily to allow the interconnection of local networks over large distances  
    C) It was designed primarily to provide a purely data access service to a Web service provider that has one or more Web servers

null verified.  
Comment: See “ADSL” transparencies.

**Exercise 74\.** The quality characteristics required by a telephone service are:  
    A) Information transfer with maximum delay in the order of hundreds of milliseconds and extremely low delay jitter; bit rate of the order of tens of kbit/s; probability of error not exceeding a few percentage units; probability of blocking not exceeding a few percentage units  
    B) Transfer of information with a maximum delay of the order of tens of seconds; negligible probability of error; negligible blocking probability  
    C) Transfer of information with a maximum delay of the order of hundreds of milliseconds and extremely low delay jitter; bit rate in the order of tens of Mbit/s; probability of error not exceeding a few percentage units; probability of blocking not exceeding a few percentage units

null verified.  
Comment: See “Quality indexes (telephony)” transparencies.

**Exercise 75\.** In original IP routing, i.e. without the use of masks, the choice of the output interface on which to forward a packet is based   
    A) On the full IP address (net\_id \+ host\_id) of the recipient  
    B) On the subnet(net\_id) part of the recipient's IP address  
    C) Only on the host side (host\_id) of the recipient's IP address

null verified.  
Comment: To choose where to forward the packet it is sufficient to know the net\_id (network id) of the recipient.

**Exercise 76\.** Il DNS (Domain Name Service):  
    A) To increase the reliability and response speed of the system, it uses a set of caches, but each resolution must always reach the authoritative server for the domain to which the name belongs  
    B) It is used by operators to sell domain names to their customers who need to create public servers  
    C) It is based on a system of hierarchical servers, each responsible for the naming of a particular zone  
    D) Represents a product for distributing the load across multiple routers within the local network

null verified.  
Comment: DNS (Domain Name Service) is a system used to resolve the names of network nodes (hosts) into IP addresses. The service is created via a distributed database, made up of DNS servers. 

**Exercise 77\.** Which of the following statements in comparing the Aloha and Slotted-Aloha protocols is false?  
    A) Slotted-Aloha allows for better exploitation of the capabilities of the transmission medium  
    B) Aloha's performance is less dependent than Slotted-Aloha on propagation delays  
    C) Aloha is easier to implement as it does not require slot synchronization 

null verified.  
Comment: The Slotted Aloha protocol adds a further characteristic to the Aloha protocol from which it derives, namely that time is divided into discrete intervals called slots. The consequence of this characteristic is that two transmissions either collide completely within the same slot or do not collide at all; the partial collision problem present in Aloha results eliminated. (Source Wikipedia) 

**Exercise 78\.** In the case of packet switching  
    A) The switching function allocates to the interlocutors a subset of the network resources with which one or more circuits are established for connecting the user terminals; the resources must be released if they are necessary for the establishment of other circuits  
    B) The switching function allocates to the interlocutors for exclusive use a subset of the network resources with which one or more circuits are established for connecting the user terminals; the resources are released only at the end of the communication  
    C) The switching function does not allocate a subset of the network resources to the interlocutors for exclusive use; all network resources are always available for packet transmission; the packages wait in special queues for the necessary resources to become available

null verified.  
Comment: See “Packet switching” transparencies.

**Exercise 79\.** They are obligatorily contained in the UDP header, i.e. in the PCI of the UDP protocol  
    A) The TTL (Time To Live) field which allows packets that have crossed an excessive number of routers to be eliminated from the network  
    B) The source and destination port  
    C) The source and destination IP address

null verified.  
Comment: See transparencies “UDP: segment header”.

**Exercise 80\.** Internet routing tables  
    A) They indicate the sequence of routers to pass through to reach a certain arp destination  
    B) They only indicate the next router to pass through to reach the destination  
    C) They indicate the sequence of autonomous systems to pass through to reach a certain destination

null verified.  
Comment: See “IP routing (next hop)” slides.

**Exercise 81.** Data transfer between two application processes in the OSI model occurs by involving  
    A) Only two application layer entities, one for each of the two systems  
    B) At least one entity for each of the seven levels in both systems  
    C) An entity in each system, independent of the level to which they belong

null verified.  
Comment: Since the application level is the highest in the ISO-OSI stack, the transmitter must first pass through all 6 lower levels and then the receiver must go up all the levels up to the last one.

**Exercise 82\.** Consider two LANs   
Ethernet A and B, connected by a switch B1 and a router R1 (B1 and R1 are in parallel between the two LANs). Assume that the switch and the router have both active ports and know all the addresses (MAC and IP respectively) of the hosts connected to the two LANs. When a host connected to LAN A transmits an ARP packet to obtain the MAC address of router R1, which of the following statements is true?  
    A) The packet is forwarded on LAN B only by router R1  
    B) The packet is forwarded on LAN B only by switch B1  
    C) The packet is forwarded on LAN B either by the switch or by the router, depending on the value of the destination MAC address contained in the packet  
    D) The packet is forwarded on LAN B by both router R1 and switch B1

null verified.  
Comment: The router receives the ARP and recognizes that it is intended for it via the payload. So it doesn't forward it but responds to the host that requested the MAC. The switch, being the ARP packet sent in broadcast, forwards it to all its ports except the one from which it received it.

**Exercise 83\.** The SMTP protocol  
    A) It operates on the UDP protocol, since email messages are usually short  
    B) It is based on messages that always include encrypted authentication  
C) It is used for the delivery of outgoing email messages from a client to a given server  
D) It is used to transfer e-mail messages from a server to a client installed on a PC

null verified.  
Comment: SMTP is the protocol used to send and receive emails from email servers. Clients use SMTP only to send the message to the mail server which takes care of sending the message itself.

**Exercise 84\.** In the case of using a Stop-And-Wait protocol on a non-sequential channel  
    A) It is always handled smoothly  
    B) It can give rise to malfunctions of the protocol, to the point of causing loss of information and blocking of the algorithms  
    C) It can give rise to malfunctions of the protocol, to the point of causing loss of information, but not the blocking of the algorithms

**Answer**:  B verified.  
Comment: On the slides there is an example of block of the algorithm and loss of information, happens with numbering bits k \= . 

**Exercise 85\.** An (N-1)-protocol allows the interaction  
    A) Between an (N+1)-entity and an (N-1)-entity  
    B) Between two (N-1)-entities  
    C) Between any two entities, regardless of the level, as long as belonging to different systems  
    D) Between two (N)-entities

null verified  
Comment: By definition protocols work with entities of the same level as the protocol

**Exercise 86\.** In the case of circuit switching   
    A) The switching function allocates to the interlocutors a subset of the network resources with which one or more circuits are established for connecting the user terminals; the resources must be released if they are necessary for the establishment of other circuits  
    B) The switching function allocates to the interlocutors for exclusive use a subset of the network resources with which one or more circuits are established for connecting the user terminals; the resources are released only at the end of the communication  
    C) The switching function does not allocate a subset of the network resources to the interlocutors for exclusive use; all network resources are always available for packet transmission; the packages wait in special queues for the necessary resources to become available

null verified.  
Comment: See “Circuit switching” transparencies.

**Exercise 87\.** Class C version 4 IP addresses feature:

1) Multicast communications  
2) (Few) networks with a large number of hosts  
3) (Many) networks with a small number of hosts  
4) Broadcast communications   
     
   null verified.  
   Comment: Class C addresses are similar to classless addresses with a /24 mask. This indicates a high number of networks and a low number of hosts (256 hosts per network).  
     
   **Exercise 88\.** The CSMA and CSMA-CA protocols  
       A) They try to avoid interference between the transmissions of users sharing a broadcast channel by preventively listening to the channel status; the transmission can only start if the channel is listened to freely  
       B) They do not implement any preventive control to avoid interference between the transmissions of users sharing a broadcast channel; only in the case of interference (collision) is action taken, repeating the transmission after a random delay  
       C) They try to avoid interference between the transmissions of users sharing a broadcast channel by preventively listening to the channel status; transmission can only start if the channel is actually free  
     
   null verified.  
   Comment: See “CSMA” transparencies.

   **Exercise 89.** By reporting we mean  
       A) The transfer of information from one point to one or more other points  
       B) The exchange of information regarding the control of a telecommunications network  
       C) The process of interconnecting resources for the time necessary for communication  
     
   null verified.  
   Comment: See transparencies on “Reporting”. 

   **Exercise 90\.** The MIME protocol allows  
       A) To have data encoded differently within the email message  
       B) To reserve online resources so that an email message with a multimedia file attachment can reach its destination  
    with guaranteed quality  
       C) To transmit useful information to the recipients of the email to monitor the quality of the transmission  
       D) Control playback of a media file downloaded from the network  
     
   null verified.  
   Comment: See transparencies “Message format: multimedia extensions”.

   **Exercise 91\.** Statistical multiplexing means  
       A) A fixed frequency multiplexing scheme in which the bandwidth assigned to the different information flows is proportional to the transmission speed  
       B) A multiplexing scheme that involves a random choice between frequency multiplexing and time multiplexing  
       C) A multiplexing scheme that does not provide for a predetermined assignment of transmission resources to information flows  
     
   null verified  
   Comment: C corresponds to the definition of statistical multiplexing.  
     
   **Exercise 92\.** What is the order of magnitude of the maximum transmission speed on an optical fiber?  
       A) 1 Tbit/s  
       B) 1 kbit/s  
       C) 1 Mbit/s  
       D) 1 Gbit/s  
       E) 1 bit/s  
     
   null verified.  
   Comment: See transparencies “Optical fibre”.

   **Exercise 93\.** If a router receives a correct TCP packet, encapsulated in an IP header packet destined for a non-existent TCP port (for which there is no application process waiting)  
       A) Discards it and sends an ICMP packet to the destination  
       B) Passes it to a default application process that handles all TCP packets for which there is no available application process  
       C) Ignore the TCP port value and send the packet  
       D) Discards it and sends an ICMP packet to the source  
     
   null verified  
   Comment: Since the TCP packet is encapsulated in an IP packet, the latter will not be able to detect the TCP port error, so the correct answer is C.   
     
     
   **Exercise 94\.** The increment of the current TCP transmitter window  
       A) It is regulated only by the receiver  
       B) It is regulated only by the slow-start congestion control phase  
       C) It is regulated by the congestion control phase called slow-start and congestion avoidance  
     
   null verified.  
   Comment: See “TCP congestion control” transparencies.

   **Exercise 95\.** The CSMA and CSMA-CD protocols allow 1-persistent and non-persistent versions  
       A) In the case of the 1-persistent version, if listening to the channel indicates that it is busy, the attempt is proposed with a random delay; in the case of non-persistent versions, if listening to the channel indicates that it is busy, the transmission begins as soon as the current transmission ends   
       B) In the case of the non-persistent version, if listening to the channel indicates that it is busy, the attempt is proposed with a random delay; in the case of the 1-persistent versions, if listening to the channel indicates that it is busy, the transmission begins as soon as the current transmission ends   
       C) In both cases, if listening to the channel indicates that it is busy, the transmission attempt is postponed with a random delay  
     
   null verified.  
   Comment: See “CSMA” transparencies.

   **Exercise 96\.** Assume that between a transmitter and a receiver that implement a Go-Back-N type ARQ (Automatic repeat request) scheme, the time between the start of transmission of a data unit and the end of reception of the corresponding acknowledgment is constant and greater than the time necessary to transmit the information that can be stored in the transmission window. In this situation, the transmission speed increases on the channels that connect the transmitter to the receiver  
       A) It decreases the quantity of information transferred on average in the unit of time between the transmitter and the receiver  
       B) It fails to increase the quantity of information transferred on average in the unit of time between   
   transmitter and receiver  
       C) Increases the quantity of information transferred on average in the unit of time between the transmitter and the receiver  
     
   null verified.  
   Comment: n \= Wt / (1+2(Tp/Tx)) \=\> at higher speeds, If Tx decreases, the denominator of n increases → n decreases

   **Exercise 97\.** In the OSI model, frame delineation, i.e. the ability to identify the end of a packet on a channel, is a function:  
       A) Performed by all OSI layers  
       B) Typical of the level or sublevel adjacent to the physical level   
       C) Exclusive to the network layer  
     
   null verified.  
   Comment: Level 2 deals with this.  
     
   **Exercise 98\.** If segment loss is identified by receiving three acknowledgments, the current window size of the reno TCP transmitter  
       A) It is brought to half the size of the receiver window  
       B) It is brought back to the initial value, equal to one segment  
       C) It is placed at half of the current value (to be precise at half of the current value plus a segment)  
     
   null verified.  
   Comment: This is how TCP reno works.

   **Exercise 99\.** Frame Relay technology provides   
       A) Transferring fixed-size data units in a non-connection-oriented manner  
       B) The transfer of fixed-size data units over virtual circuits  
       C) The transfer of data units of variable size over virtual circuits  
     
   null verified.  
   Comment: See “Frame Relay” transparencies.

   **Exercise 100\.** The Network Address Translation (NAT) mechanism  
       A) Implement a mapping function between (3)-addresses and (2)-addresses in OSI terms  
       B) It can change the IP addresses of packets  
       C) Allows you to associate the logical address of a host with the IP address  
       D) Changes the path of packets on the Internet  
     
   null verified.  
   Comment: See “NAT” transparencies.  
     
   **Exercise 101\.** In the absence of other packets, the minimum time required for a packet to pass through the switch operating in store-and-forward mode  
       A) It increases as the packet transmission speed increases  
       B) It increases as the distance between the source and destination of the packet increases  
       C) It grows as the number of bits of which the packet is composed increases  
     
   null verified.  
   Comment: See “Store and forward” transparencies.

   **Exercise 102\.** The PING application program  
       A) It uses ICMP protocol messages to determine the path followed to reach a host belonging to the Internet  
       B) Use an option of the TCP protocol to verify the connectivity of a host belonging to the Internet network  
       C) Use ICMP protocol messages to verify the connectivity of a host belonging to the Internet  
     
   null verified.   
   Comment: See transparencies of the “PING” command.

   **Exercise 103\.** A network topology with N nodes and M unidirectional channels is given. Each channel has C Mbit/s capacity. The routing algorithm is such as to uniformly distribute traffic over the network channels. The average number of channels crossed by a packet on the path from the source to the destination is equal to D. The maximum amount of traffic handled by the network increases if:   
   	A) Decreases C to equal N, M, and D  
   	B) Decreases M to equal N, D, and C  
      	C) Decrease D to equal N, M and C  
       	D) Decreases N to equal D, M, and C  
         
   null verified.  
   Comment: if the average distance decreases, with the same channel capacity, the traffic handled should increase.dv   
     
   **Exercise 104\.** Statistical multiplexing   
   **A)** It can only be used in connectionless networks  
   **B)** It is used in telephone networks because it is closely associated with the use of constant speed channels  
   **C)** It consists in the sharing of the same resource (transmission channel, memory device, etc.) by traffic sources that use it based on instantaneous needs  
   **D)** It can only be used in connection-oriented networks, but not circuit-switched ones  
     
   null check.  
   Comment: By definition in statistical multiplexing you can make multiple sources use the same resource in frequency or time by betting on the fact that they will not use them at the same time. See explanation of video lesson 5\.

   **Exercise 105\.** In a packet-switched network operating in store-and-forward mode, a larger data unit size   
   **A)** Increases the complexity of routing each data unit  
   **B)** Increases the time from when a data unit reaches the input of a switch to when it leaves the switch  
   **C)** Increases the number of operations that must be performed by a switch to transfer the same total amount of user information  
     
   null verified.  
   Comment: Long packets lead to a longer store time on the part of the receiving node.

   **Exercise 106\.** Congestion control in the TCP protocol   
       A) It is not available  
       B) Occurs with duplicate ACKs and when the time-out expires  
       C) It is based on the receiver reporting the available reception window  
     
   null verified.  
   Comment: Congestion control decreases the CWND by a value that depends on the type of congestion detected, i.e. whether Timeout was detected or whether duplicate ACKs were received.

   **Exercise 107\.** Window protocols are also called ARQ (Automatic Retransmission reQuest) Why  
       A) In case of arrival of an incorrect packet the receiver he asks retransmission  
       B) In case of failure to return an ACK the receiver he asks retransmission  
       C) The expiration of the timeout at the transmitter corresponds to an automatic retransmission request  
   	  
   null verified.  
   Comment: see slide “Window Protocols”

   **Exercise 108\.** In the case of common channel signaling   
       A) Each channel for the transfer of user information corresponds to a signaling channel  
     B) A single signaling channel is used to control numerous channels that transfer user information; the signaling channel operates in package mode  
     C) A single signaling channel is used to control numerous channels that transfer user information; the signaling channel operates in circuit mode  
     
   null verified.   
   Comment: In common channel signaling, user information travels on separate channels but with a single signaling channel used to control the signaling of all user channels. The signaling channel works on a packet basis.

   **Exercise 109\.** At the current state of technology, it is possible to transmit information without amplification along the transmission route over longer distances using  
       A) The canal hertziano (radio, satellite)  
       B) Optical fibers  
       C) Telephone twisted pairs  
       D) Coaxial cables  
     
   null verified.  
   Comment: B is wrong, optical fibre: total immunity from electromagnetic disturbances, low attenuation (\~0.1dB/km), dependent on wavelength, requires cables with redundant optical amplifiers every 30/50 km. The right answer is TO.  
     
   **Exercise 110\.** The (N+1)-directory function associates  
       A) An (N+1)-address to an (N)-address  
       B) One (N+1)-title to one (N)-address  
       C) One (N+1)-title to one (N+2)-address   
     
   **Answer:**  B verified.  
   Comment: There is a level N function called (N)directory which establishes a correspondence between the (N)titles and the (N-1)addresses of the (N-1)SAPs through which the (N)entities access the (N- 1\) services. Since it is the (N+1) directory, the answer should therefore be B. Source: https://www.docsity.com/it/appunti-di-reti-telematiche-modello-osi/496/  
     
   **Exercise 111\.** The preamble that is placed before the IEEE 802.3 (Ethernet) data units is necessary for  
       A) Allow you to keep the network synchronous	  
       B) Allow synchronization of repeaters and receivers encountered on the local network  
       C) Allow repeaters to retransmit drives data at the same rate at which it was received  
     
   null verified.  
   Comment: Preamble (of 7 bytes): each of these first 7 bytes has the value 10101010 and they are needed to “wake up” the receiver adapters and synchronize the oscillators with those of the transmitter. Source: “Wikipedia”. 

   **Exercise 112\.** If a router detects an incorrect checksum on an IP packet, and therefore a potential error on the IP addresses contained in the packet, during routing  
      	A) Discards it and sends an ICMP packet to the source only  
       	B) Discards it and sends an ICMP packet to both the source and the destination  
       	C) Discards it without reporting it to any other network entity  
      	D) It forwards it to the destination anyway, however sending an ICMP packet to the source to report the error  
   	  
   null  verified.  
   Comment: The IP header checksum is a field used for header error checking.

   **Exercise 113\.** In the OSI model, which of the following functions is performed by session layer entities?  
       A) Routing of data units in a type that is not fully connected  
       B) The choice of data representation syntax for a work session  
       C) The definition of synchronization points in a stream of data units  
     
   null verified  
   Comment: The tasks of the session level are: possibility of intervening on dialogue between peers, if there are errors in the connection the session is restored using synchronization points, activity management.

   **Exercise 114\.** The complexity of the routing procedures used, within a node, to forward information has a greater influence on the performance of a network in the case of  
       A) Packet switching without virtual circuits (datagram mode)  
       B) Packet switching with virtual circuits   
       C) Circuit switching  
     
   null  verified.  
   Comment: In the case of datagrams (no virtual circuits) it is necessary to identify the source/destination pair in each packet, which entails greater complexity in the performance of a network node. In the case of virtual circuits it is sufficient to identify the virtual circuit. The source/destination pair is used only during the opening phase of the circuit. See “Addressing information” transparencies. 

   **Exercise 115\.** The LLC SNaP (SubNetwork access Protocol) format of the IEEE 802.2 LLC protocol  
       A) It allows the sharing of a broadcast transmission medium  
       B) It allows the coexistence of a large number of protocols higher than level 2  
       C) It is required in the Internet for transfer of data units in subnets  
       D) It guarantees the recognition of transmission errors   
     
   null verified.   
   Comment: SNAP indicates the higher layer protocol. See “Private/Local Networks LLC Logical Link Control”.  
     
   **Exercise 116\.** In the CSMA and CSMA-CD protocols the concept of “persistence” refers to:  
1) The way in which the transmission attempt occurs, if listening to the channel indicates that it is busy  
2) The calculation of the time for which a station is allowed to occupy the channel  
3) How the retransmission attempt occurs if a collision has occurred  
4) The time during which two transmissions overlap on the channel, a necessary condition Why the collision is detected  
     
   null verified.  
   Comment: see the transparencies “Access Protocols for LAN Networks”, it is not B because the 'Carrier Sense' phase where the channel is listened to is carried out already at the first transmission and not following a failed transmission (i.e. only when there is retransmission is necessary).  
     
   **Exercise 117\.** They are contained in the IP header, i.e. in the PCI of the IP protocol  
1) The 16-bit Checksum field for checking the correctness of the header and data contained in the packet  
2) The Sequence Number field for segment numbering  
3) The Identification and Fragment Offset fields which allow the management of packet fragmentation  
     
   null verified.  
   Comment: Answer A is wrong, since the header checksum does not check the correctness of the data but only the correctness of the header. B is also wrong since the 'Sequence Number' field is introduced in the header of the TCP protocol (therefore Transport Layer and not Network Layer where IP operates) to guarantee the arrival of the packets in the correct order.  
     
   **Exercise 118\.** Why does VDSL technology have high performance only if the distance between the street cabin and the user's home is less than a hundred metres?  
1) Because the end-to-end delay between the user's home and the operator's exchange is reduced    
2) Because the costs of laying cables are reduced  
3) Because the shorter length of the copper cable allows the use of higher bit rate modulation  
4) Because connections must pass through fewer intermediate nodes  
     
   null verified.  
   Comment: See “VDSL” transparencies. 

   **Exercise 119\.** Point-to-Point Protocol (PPP) does not use address fields because

1) Leverages underlying MAC addresses  
2) Take advantage of top-level addresses  
3) It must operate on point-to-point connections  
4) It has no space in the plot header  
     
   null verified.  
   Comment: See transparencies on the “PPP”.  
     
   **Exercise 120\.** The DHCP protocol provides that  
1) A client uses an IP address as soon as it receives it from the server in a DHCP Offer message.  
2) A customer can disconnect from the network without communicating this to the server.  
3) If a server exists, it is unique in the client's local network.  
4) The server never provides the IP address of a DNS server in its response.  
     
   null verified.   
   Comment: Answer A is wrong, since after the DHCP Offer I only have proposals and the IP has not yet been assigned. Only after the DHCP ACK can the client make use of the IP address offered by the DHCP server. C is incorrect since there can be multiple DHCP servers in a client's local network. D is wrong, in fact the DHCP server provides the DHCP client with IP addresses of one or more DNS servers. By exclusion, the right answer is B. Source “Wikipedia”.  
     
   **Exercise 121.** The fundamental functions of the link layer in the OSI model are  
1) Flow control and transmission error recovery  
2) Data drive routing  
3) Transferring binary digits to the channel  
     
   null verified.  
   Comment: See “Connection Level” transparencies. B is false because routing is the responsibility of the Network Layer, while C is false because the only layer that interfaces with the channel is the Physical Layer.  
     
   **Exercise 122\.** During the slow-start phase of TCP congestion control, the current transmitter window  
1) It is halved for each missing acknowledgment (ACK).  
2) It grows by one segment for each acknowledgment (ACK) received  
3) Doubles for each acknowledgment (ACK) received  
4) It remains constant over time  
     
   null verified.  
   Comment: If there has been a time-out, by definition and to remain conservative, TCP Reno/Tahoe bring the cwnd to 1 (they enter the slow-start phase). Here the cwnd increases by 1 MSS for each ACK received. See TCP Reno transparencies.  
     
   **Exercise 123**. What is the order of magnitude of the maximum transmission speed over coaxial cable?  
1) 1 Tbit/s  
2) 1 Mbit/s  
3) 1 bit/s  
4) 1 kbit/s  
5) 1 Gbit/s  
     
   null verified.  
   Comment: Coaxial cable: transmission speeds around hundreds of Mbit/s. See transparencies “Coaxial cable”.  
     
     
   **Exercise 124\.** Window protocols can be used   
1) Only for communications using a connection  
2) Both for communications that use a connection and for those that do not  
3) Only for communications that do not use a connection  
     
   null  
   Comment: Window protocols require an initial handshake and then a connection  
     
   **Exercise 125\.** L’Address Resolution Protocol (ARP)  
1) Allows you to obtain an Ethernet address to assign to the card of the machine that made the ARP request  
2) It allows a host to know the IP address of its DNS server  
3) Implements a mapping (translation) function between (3)-addresses and (2)-addresses in OSI terms  
     
   null verified in an exam correction with a similar question.  
   Comment: ARP allows you to know the MAC address of another host by knowing its IP address.  
   The A is wrong because the MAC address that is returned is not that of the machine that made the request. B is wrong because that is the job of a DNS Discover and not an ARP Request.  
     
   **Exercise 126\.** In the OSI model, the segmentation performed by a level entity (N+1)  
1) Create many (N+1)-PDUs from a single (N+1)-SDU  
2) Create one (N+1)-PDU ​​from many (N)-SDUs  
3) It combines many (N+1)-PDUs into a single (N)-SDU  
4) Create as many (N+1)-PCIs for the same (N+1)-PDU  
     
   null verified.  
   Comment: Segmentation can occur by building multiple (N)-PDUs from one (N)-SDU, or by generating multiple (N-1)-SDUs from one (N)-PDU. Therefore, replacing N with N+1 gives the answer A. See “PDU Creation” slides.  
     
   **Exercise 127\.** Let's be WT \> 1 by WR \> 1 the size, respectively, of the transmit window and the receive windows in a window protocol. Both also *N* the total amount of sequence numbers available to distinguish data units. Which of the following constraints is a necessary and sufficient condition to avoid malfunctions on a channel that does not reverse the order of the data units?  
1) N=INT+1 \-- N \=  Wt \+ 1  
2) N=(INT+INR)2 \-- N \= (Wt \+ Wr) / 2  
3) N=INR+1 \-- N \= Wr \+ 1  
4) NINT+INR \-- N \>= Wt \+ Wr  
      
   null verified.  
   Comment: Assuming N=2^k (since N=total quantity of n°seq) the formula to be respected is Wt+Wr\<=2^k , i.e. Wt+Wr\<=N , i.e. N \>= Wt+Wr   
     
   **Exercise 128\.** The three fundamental elements that define a protocol are:  
1) Algorithms, formats, timings  
2) Algorithms, formats, entities  
3) Algorithms, services, timings   
     
   null verified.  
   Comment: By definition a protocol is defined as semantics, syntax, timing. See “Protocols” transparencies.  
     
   **Exercise 129\.** An Ethernet card in a Bridge reads and decides whether and how to route  
1) All packets, regardless of destination address  
2) Only packets with a unicast destination MAC address equal to that of the bridge  
3) Only packets with broadcast destination MAC address  
4) Only packets with multicast destination MAC address  
     
   **Answer**: A verified.  
   Comment: By definition, a Bridge's Ethernet reads and routes all packets.  
     
   **Exercise 130\.** Which of the following statements is false?  
1) An IP router can use the ARP (Address Resolution Protocol) protocol to know the MAC address of the router or host to which it must deliver an IP packet  
2) A host can use ICMP messages to verify another host's connectivity to the Internet.  
3) An IP router, which does not perform a NAT (Network Address Translator) function, does not modify the IP addresses of the packets it must re-transmit  
4) An IP host always only makes direct deliveries  
     
   null verified.  
   Comment: A B and C are correct as they are the definitions of ARP, ICMP, and NAT respectively. By exclusion the answer is D.  
     
   **Exercise 131\.** To avoid blocking or losing data units in a window protocol due to non-sequential channels, it is useful  
1) Number PDUs to a number of bits greater than 1 and do not limit the lifetime of PDUs in the network  
2) Number PDUs to a number of bits greater than 1 and limit the lifetime of PDUs in the network  
3) Number PDUs on a single bit and limit the lifetime of PDUs in the network  
     
   null verified.  
   Comment: By definition in window protocols it is necessary to number the PDUs on a number of bits greater than 1\. It is necessary that the packets have a minimum TTL (Time To Live) lifetime otherwise it would lead to congestion (i.e. blocking) of the intermediate nodes.  
     
   **Exercise 132\.** Constraints on the maximum extension of an IEEE 802.3 local area network (CSMA/CD) arise  
1) Both from the propagation delay of signals from one end of the network to the other, and from the attenuation of signals on the transmission media.  
2) Is from attenuation of signals on transmission media, and the maximum delays tolerated by users of the MAC service  
3) By the number of bits that would be needed to increase data units in the case of large propagation delays  
4) From the limited number of level 3 addresses  
     
   null  
   Comment: with a network that is too large the probability of collision increases (a host does not notice in time that someone else has already started transmitting)

   **Exercise 133\.** In the case in which a window protocol is used on a channel that does not allow inversions in the sequence order of the data units transmitted (i.e. on a sequential channel), assuming that a non-cyclic progressive numbering is used, the transmission and reception windows *they never can* find yourself in the following situation:

1) No sequence number included in the receive window is also included in the transmit window  
2) The smallest sequence number in the transmit window is smaller than the smallest sequence number in the receive window  
3) The smallest sequence number in the receive window is smaller than the smallest sequence number in the transmit window.  
4) The largest sequence number in the receive window is larger than the largest sequence number in the transmit window  
     
   null verified.  
   Comment: A is possible in the case where all packets have been received but no ACK has yet arrived at the transmitter. B and D are both the case where the receiver window has advanced but the transmitter has not yet received the ACK. C cannot occur because the transmission window can advance only following the reception of ACKs which must be sent by the receiver after receiving a packet, but the reception would necessarily involve a forward slide of the receiver, therefore the receiver would not never remains “behind” the transmitter.  
     
   **Exercise 134\.** Medium Access Control (MAC) sublayer protocols have purpose  
1) To allow the sharing of a broadcast channel using a distributed algorithm  
2) To allow the sharing of a broadcast channel using a centralized algorithm  
3) To allow sharing of a point-to-point channel  
     
   null verified.  
   Comment: In the MAC sublayer the random access protocols are: Aloha, CSMA, CSMA/CD and CSMA/CA. In random access protocols, all peer stations implement a distributed algorithm to access the medium, there is no centralized element. Source: “Internet”.  
     
   **Exercise 135\.** The IEEE 802.3 (CSMA/CD) standard provides data units (also including layer 2\)  
1) Variable in size between 10 and 4500 octets  
2) Variable in size between 64 and 1518 octets  
3) Fixed size equal to 53  
     
   null verified.  
 


   **Exercise 136\.** Which of the following statements is true?

1) In the Ethernet commercial standard (CSMA/CD access protocols), a minimum packet size has been defined to ensure correct collision identification  
2) In the commercial Ethernet standard (CSMA/CD access protocol), a minimum packet size has been defined to distinguish packets from those of the IEEE 802.3 standard  
3) In the Ethernet commercial standard (CSMA/CD access protocol), a minimum packet size has been defined to guarantee better performance, in terms of traffic disposed of, to the access protocol compared to that which would be obtained with packets of maximum size  
     
   null verified.  
   Comment: On Ethernet the collision is a function of the length of the packet.  
     
   **Exercise 137\.** They are obligatorily contained in the TCP header, i.e. in the PCI of the TCP protocol  
1) The TTL (Time To Live) field which allows packets that have passed through an excessive number of routers to be eliminated from the network  
2) The sequence number and the ack number, for segment and acknowledgment numbering (ACK)  
3) The fragmentation field for managing segment fragmentation  
     
   null verified.  
   Comment: A is wrong because the TTL field is introduced in the Network Layer header by the IP protocol and not by TCP to the Transport Layer. C is wrong because fragmentation (i.e. the division of a PDU into several parts) is managed by the Network Layer and not by the Transport Layer.  
       
     
   **Exercise 138\.** A protocol  
1) It is a set of semantic and syntactic rules to allow communication between two entities of the same level  
2) It is a set of semantic and syntactic rules to allow communication between two entities of the same system  
3) It is a set of semantic and syntactic rules to allow communication between two systems that are connected to each other  
4) It is a set of semantic and syntactic rules to allow communication between two entities of different systems  
     
   null verified.  
   Comment: By definition, a protocol allows a (N) entity to communicate with other (N) entities, therefore of the same level.  
     
   **Exercise 139\.** In a Store-and-Forward packet network the increase in the number of nodes between source and destination  
1) It leads to an increase in delivery time, directly proportional to the size of the package  
2) It leads to an increase in delivery time, directly proportional to the average channel speed  
3) It leads to an increase in delivery time, inversely proportional to the size of the package  
     
   null verified.  
   Comment: In Store-and-Forward mode each node must first store each package and only then can it forward it to the next node, so if the number of nodes increases by a value N, this procedure will have to be repeated N more times. Therefore, increasing the number of intermediate nodes increases the delivery time, directly proportional to the size of the packet.  
     
   **Exercise 140\.** The UDP protocol provides a service  
       A) Unreliable (i.e. without guarantee of delivery) and connectionless  
       B) Reliable (i.e. with delivery guarantee) and connectionless  
       C) Unreliable (i.e. without delivery guarantee) and connection oriented  
     
   null verified.  
   Comment: By definition UDP: it only implements multiplexing and demultiplexing functions, it does not communicate to the receiver that it is about to receive a packet (i.e. it is connectionless) and is unreliable as it does not implement a mechanism that allows it to understand if the packet has arrived or not to the destination. See “UDP” transparencies.  
     
   **Exercise 141\.** The TCP protocol provides a service  
       A) Unreliable (i.e. without guarantee of delivery) and connectionless  
       B) Reliable (i.e. with delivery guarantee) and connectionless  
       C) Unreliable (i.e. without delivery guarantee) and connection oriented  
       D) Reliable (i.e. with delivery guarantee) and connection oriented  
     
   null verified.  
   Comment: TCP provides multiplexing and demultiplexing, flow and congestion control functions, communicates to the receiver that it is about to receive a packet by establishing a connection with it (i.e. it is connection oriented) and is reliable because, through the use of Window Protocols (and therefore ACKs and Timeouts), has the means to understand whether the packet has arrived at the destination or not. See “TCP” transparencies.  
     
   **Exercise 142\.** Il PPP(Point-to-point-Protocol)  
       A) Use the byte-stuffing technique to ensure data transparency  
       B) Use the bit-stuffing technique to ensure data transparency  
       C) It does not guarantee the transparency of the data  
     
   null verified.  
   Comment: See transparencies on the PPP. Inserts an escape byte (01111101) before each 01111110 that appears in the PDU to ensure transparency.  
     
   **Exercise 143\.** When comparing 100 Mb/s Fast Ethernet (100Base T) to 10 Mb/s Ethernet, which of the following statements is false?  
       A) The distance constraints between nodes are more stringent  
       B) A different access protocol is used  
      C) A different physical layer is used  
     
   null verified.  
   Comment: A is true because from Ethernet to Fast Ethernet the size of the network decreased by a factor of 10\. C is true because Base T indicates twisted pair, while Ethernet at 10Mb/s was on coaxial. The only false one is B.  
     
   **Exercise 144\.** Which of the following protocols does not perform error detection functions on data drives?  
       A) LaPB (Link access Protocol Balanced)  
       B) IEEE 802.2 LLC (Logical Link Protocol)  
       C) PPP (Point-to-Point Protocol)  
       D) LaPF (Link access Procedure to Frame-mode bearer services)  
     
   null verified.  
   Comment: Slide “Link layer (Layer 2)” page 48, clearly states that LLC does not do error checking (there is no CRC field).   
     
    **Exercise 145.** Which of the following statements is true?  
       A) A T1 topology, with N nodes, C channels and average distance M1, always allows for the disposal of a smaller amount of traffic than a T2 topology, with N nodes, C channels and average distance M2\>M1, only with traffic uniformly distributed between knots.  
       B) A T1 topology, with N nodes, C channels and average distance M1, always allows for the disposal of a smaller amount of traffic than a T2 topology, with N nodes, C channels and average distance M2\>M1, regardless of the traffic distribution.  
       C) The amount of traffic handled in a T1 topology, with N nodes, C channels and average distance M1, compared to that handled in a T2 topology, with N nodes, C channels and average distance M2\>M1, depends on the traffic distribution between nodes  
     
   null verified.  
   Comment: With the same capacity available on the channels, the amount of traffic that can be handled by a network depends on the average of the distances between each pair of nodes on the network (slide: Topology and performance).  
     
   **Exercise 146\.** Among the main differences between a Frame Relay network and an IP Internet network are:  
       A) The use or non-use of ARQ (automatic Retransmission reQuest) in every section of the network  
       B) The transfer of information in a connection-oriented rather than a non-connection-oriented manner   
       C) Transferring data units of variable size instead of fixed size  
     
   null verified.  
   Comment: Frame relay uses virtual circuit and not datagram (as IP does). Both use variable size packets.  
     
   **Exercise 147\.** Consider a network LAN Ethernet with 10 knots. The network is partitioned into two networks interconnected by transparent bridges. Which of the following statements is false?  
1) The bridge separates the collision domains of the two interconnected networks  
2) Network performance in terms of traffic cleared improves in any traffic condition, i.e. completely independently of the distribution of traffic between nodes  
3) Bridging introduces additional delay in transmissions between bridged nodes  
4) It is not necessary to change the configuration of the nodes connected to the LAN to allow correct operation after the network partition  
     
   null verified.  
   Comment: to be defined  
     
   **Exercise 148\.** Consider two LANs (Ethernet 10BaSE) A and B, connected by a bridge B1 and a router R1 (B1 and R1 are in parallel between the two LANs). Assume that the bridge and the router have both active ports and know all the addresses (MAC and IP respectively) of the hosts connected to the two LANs. When a host connected to LAN A transmits an IP packet to a host connected to LAN B  
1) The packet is forwarded on LAN B either by the bridge or by the router, depending on the value of the destination MAC address contained in the packet  
2) The packet is forwarded on LAN B by both router R1 and bridge B1  
3) The packet is forwarded on LAN B only by router R1  
4) The packet is forwarded on LAN B only by bridge B1  
     
   null verified.  
   Comment: to be defined  
     
   **Exercise 149\.** The size of the current TCP transmitter window during a connection  
1) It is regulated exclusively on the basis of the signal from the receiver of the size of the reception window to carry out flow control  
2) It varies as the congestion in the network varies and due to the flow control exercised by the receiver  
3) It's fixed  
     
   null verified.  
   Comment: TWND \<= min{CWND, RWND} therefore the transmission window depends both on the variation of the network congestion (CWND) and on how much Buffer is available on the receiver (RWND)  
     
   **Exercise 150\.** If segment loss is identified by receiving three acknowledgments, the current window size of the reno TCP transmitter  
1) It is brought to a value equal to half the threshold  
2) It is brought to a value equal to the threshold value	  
3) It is brought back to the initial value, equal to one segment  
     
   null verified.  
   Comment: The 3 hits correspond to the receipt of 3 duplicate ACKs, I remain in the Congestion Avoidance phase with the halving of the CWND, so A is the right answer (TCP reno).  
     
   **Exercise 151\.** What is the order of magnitude of the maximum transmission speed on a twisted pair?  
       A) 1 Tbit/s  
       B) 1 kbit/s  
       C) 1 Mbit/s  
       D) 1 Gbit/s  
       E) 1 bit/s  
     
   null verified.  
   Comment: See “Doppino” transparencies.  
     
   **Exercise 152\.** An IP router  
1) Performs both fragmentation and reassembly of the datagram  
2) Performs datagram fragmentation, but not reassembly  
3) Does not perform datagram fragmentation  
4) Performs datagram fragmentation, and reassembly only if an appropriate bit is set in the IP header  
     
   null verified.  
   Comment: Reassembly is the responsibility of the final destination. Source “Marchetto”.  
     
   **Exercise 153\.** Common channel signaling  
1) Requires the use of signaling messages that contain the identifier of the connection to which they refer  
2) It is used only in packet-switched networks, because the associated-channel signaling technique is used in circuit-switched networks.  
3) It cannot be used in cell- or packet-switched networks because it is too difficult to identify connections in these networks without associating a signaling channel to them  
4) It uses common transmission channels that are associated with each connection when the connection is opened  
     
   null verified.  
   Comment: A is the definition of common channel signaling: a separate channel managed by packet switching, where each packet contains the signaling information regarding a specific controlled channel and the connection identifier. B: Common channel signaling is typically used in telephone networks (circuit switching). C: meaningless. D: associated channel definition. Source: video lessons.  
     
   **Exercise 154\.** Code division multiplexing  
1) it is a special case of time division alone  
2) it is a special case of frequency division only  
3) allows you to use multiplexing and switching on the same physical medium  
4) it does not necessarily require to be coupled with time or frequency multiplexing  
     
   null verified.  
   Comment: A and B are false, C is incorrect because switching is the sharing of the node, not the physical medium, while multiplexing is the way in which the physical medium is divided. Source: video lessons.  
     
   **Exercise 155.** An (N)-protocol governs the interactions  
1) between an (N)-entity and an (N-1)-SAP  
2) between (N)-entities of the same system or different systems  
3) between an (N)-entity and all entities below it in the protocol stack  
4) between an (N)-entity and the (N-1)-entity  
     
   null verified.  
   Comment: protocol definition. Source: video lessons.  
     
   **Exercise 156\.** A Go-Back-N window protocol provides that:  
1) The moment a package is received with an error they are retransmitted the last N data units  
2) The transmitter receives acknowledgments for the last N data units transmitted before it can begin transmitting additional data units  
3) The transmitter cannot send more than N data units before receiving one or more acknowledgements  
4) Every time a time-out expires it is retransmitted the data unit whose sequence order is equal to the sequence number of the last data unit transmitted minus N  
     
   null verified.  
   Comment: A: retransmission occurs with timeout and not with packets received with errors. B: just receive an ACK that advances the window. Q: The timeout can expire during window transmission and the rule is not to retransmit by going backwards, but to retransmit the contents of the window. Source: video lessons.  
     
   **Exercise 157\.** Which of these statements about HTTP is false?  
1) HTTP is an application-level protocol that allows you to transfer objects on a web page  
2) HTTP is a language that allows you to define the format of web pages  
3) HTTP is based on a client-server architecture  
4) Without additional solutions, HTTP is a stateless protocol  
     
   **Answer:**  B verified during the marking of the exam.  
   Comment: HTTP (Hypertext Transfer Protocol) is not a language, but a communication protocol. It is used for data transfer, especially for retrieving resources such as web pages. The definition of the format of web pages is usually handled by markup languages ​​such as HTML (Hypertext Markup Language) and style sheets such as CSS (Cascading Style Sheets).  
     
   **Exercise 158\.** Using the piggybacking technique in window protocols gives the advantage of:  
1) Confirm the receipt of more than one data unit with a single acknowledgment  
2) Transmit data units even outside the transmission window  
3) Increase the probability that an ACK is received by the transmitter  
4) Reduce the percentage of control information that is transported over the network  
     
   **Answer:**  D verified during the marking of the exam.  
   Comment: by definition, Piggybacking is used in the case of bidirectional data flows (Full-Duplex) and allows the ACK to be included in the headers of packets traveling in the opposite direction.  
     
    **Exercise 159\.** The DHCP Discover message is sent via UDP using the IP destination address:  
1) Il limited broadcast IP address 255.255.255.255  
2) The loopback address 127.0.0.1  
3) The IP address of the local DNS server  
4) The IP address of the DHCP servers on the local network  
     
   **Answer:**  A verified during the marking of the exam.  
   Comment: DHCP Discover is transmitted with destination IP address 255.255.255.255 (Broadcast) and port address 67 (added by UDP). Only DHCP servers (which can be more than one within the same network) have an active receive service on port 67, so all other hosts that receive the DHCP Discover ignore it.  
     
   **Exercise 160\.** What disadvantage does datagram-style packet switching have compared to circuit switching?  
1) Source routing calculation  
2) Variability of data delays  
3) Calculation of the route when opening the communication  
4) High communication opening time  
     
   **Answer:**  B verified during the marking of the exam.  
     
   **Exercise 161\.** In the absence of errors, the efficiency of a Stop and Wait protocol:  
1) is always higher than the efficiency of a Go-Back-N protocol  
2) is less than the efficiency of a Go-Back-N protocol only if the transmission time of a packet plus the round trip time on the channel is less than the time needed to send the entire transmission window of the Stop and Wait protocol  
3) is lower than the efficiency of a Go-Back-N protocol only if the transmission time of a packet is greater than the round-trip propagation time on the channel  
4) is always lower than the efficiency of a Go-Back-N protocol  
     
   **Answer:**  D verified during the marking of the exam.  
     
   **Exercise 162\.** What is the playout buffer for?  
1) To avoid network congestion situations  
2) Access multimedia content faster thanks to local caching  
3) To compensate for network delays in streaming multimedia content  
4) To manage the retransmission window for multimedia contents  
     
   **Answer:**  C verified during the marking of the exam.  
     
   **Exercise 163\.** In a virtual circuit packet switching network the number of labels used for routing is proportional:  
1) To the number of possible destinations  
2) To the average number of channels output from each node  
3) To the number of active connections  
4) To the average number of nodes to cross  
     
   **Answer:**  C verified during the marking of the exam.  
     
   **Exercise 164\.** How are ARP protocol messages encapsulated?  
1) In the body of an HTTP message  
2) Directly into an Ethernet frame  
3) In one or more TCP segments  
4) Directly into an IP datagram  
     
   **Answer:**  B verified during the marking of the exam.  
     
   **Exercise 165\.** What happens when the TCP transmission timeout is set to a value significantly lower than the round-trip time?  
1) The time required to recover from segment loss situations becomes longer  
2) Unnecessary segment retransmissions may occur  
3) There is never any visible effect  
4) The receiver no longer guarantees that the process listening on the socket is provided with correct data  
     
   **Answer:**  B verified during the marking of the exam.  
     
   **Exercise 166\.** The instability of the Aloha and Slotted Aloha protocols is caused by:  
1) The increase in propagation delay when the traffic offered exceeds a certain threshold  
2) The decrease in traffic disposed of when the traffic offered exceeds a certain threshold  
3) The increase in traffic disposed of when the traffic offered exceeds a certain threshold  
     
   **Answer:**  B verified during the marking of the exam.  
     
   **Exercise 167\.** Consider a host that is transmitting data using the TCP protocol. Given a current transmitter window of size equal to 10 segments, with a maximum receiver window of 40 segments, when the transmitter receives a segment containing an ACK from the receiver, which of the following situations is impossible?  
1) The current window at the transmitter becomes 1 segment  
2) The current window at the transmitter becomes 51 segments  
3) The current window at the transmitter becomes 9 segments  
4) The current window at the transmitter becomes 5 segments  
     
   **Answer:**  B verified during the marking of the exam.  
   Comment: The transmission window must always respect the constraint TWND \<= min{CWND, RWND}.  
     
   **Exercise 168\.** Which of these fields is not contained in the header of an IPv4 datagram?  
1) Destination IP address  
2) Time to live (TTL)  
3) Protocol  
4) Destination port  
     
   **Answer:**  D verified during the marking of the exam.  
   Comment: the Source Port and the Destination Port are added by the Transport Layer protocols, i.e. by both TCP and UDP, as both provide the multiplexing and demultiplexing service which allows the incoming traffic to be differentiated and distributed to the various applications ( i.e. to the various Sockets) and to unify the outgoing data flow.  
     
   **Exercise 169\.** In the DNS hierarchy for resolving uncached names, which level is immediately below the Root DNS Server?  
1) Top-level domain (TLD) DNS server  
2) DHCP server locali  
3) Local DNS server  
4) authoritative DNS servers  
     
   **Answer:**  A verified during the marking of the exam  
   Comment: hierarchically, under the Root DNS Servers there are the 1st Level Domains (.com, .it, .net, etc), also called Top-Level-Domain (TLD), which are managed by the Top-Level-Domains (TLD) DNS Server.  
     
   **Exercise 170\.** The current congestion window at the TCP transmitter at the start of the connection:  
1) It has a size negotiated with the receiver and equal to half the receiver's window  
2) It has a size equal to a segment of maximum size (MSS)  
3) It has a size negotiated with the receiver and equal to the maximum value of the receiver's window  
4) It has a random size chosen during the connection opening phase

   **Answer:**  B verified during the marking of the exam.

   

   **Exercise 171\.** In a packet-switched network operating in store-and-forward mode, a smaller size of data units:

1) Decreases the number of operations that must be performed by a switch to transfer the same total amount of user information  
2) Increases the probability of losing the packet given the same bit error probability  
3) Decreases the complexity of routing each data unit  
4) Decreases the time from when a data unit reaches the input of a switch to when it leaves the switch  
     
   **Answer:**  D verified during the marking of the exam.  
      
   **Exercise 172\.** In a one-way ring topology, with 10 nodes and uniform unicast traffic (all nodes transmit the same amount of traffic to all others), the average number of channels traversed by a packet is equal to:  
1) 20  
2) 10  
3) 5  
4) 1  
     
   **Answer:**  C verified during the marking of the exam.  
     
   **Exercise 173\.** Transmission Control Protocol (TCP) congestion control is based on:  
1) On the variation of the number of parity bits inserted in the transmitted segments  
2) On the trend of the size of the segments transmitted to the network state  
3) On adapting the transmitter window to the memory availability of the receiver  
4) On the dynamics of the transmitter window size  
     
   **Answer:**  D verified during the marking of the exam.  
     
   **Exercise 174\.** The minimum time necessary to send a 100 Kbyte packet between two stations separated by 300 meters, using a wired network with UTP (Unshielded Twisted Pair) and crossing 3 interconnection devices operating in store and forward mode, is of the order of:

1) A few seconds  
2) It can only be calculated by knowing the transmission bit rate on the channels  
3) A few milliseconds  
4) Hundreds of milliseconds  
     
   **Answer:**  B verified during the marking of the exam.  
     
   **Exercise 175\.** What are the source and destination port fields for in TCP and UDP?  
1) To implement a multiplexing/demultiplexing mechanism for processes on hosts  
2) To manage the allocation of resources on the router on the path from source to destination  
3) To indicate the network interfaces over which packets will be forwarded by IP  
4) To indicate the physical interfaces on which the frames will be transmitted by Ethernet  
     
   **Answer:**  A verified during the marking of the exam  
     
   **Exercise 176.** Among the fundamental functions of the transport layer in the OSI model we find:  
1) Label switching in circuit switching  
2) Reading data from a terminal device  
3) Transmission error recovery  
4) Data drive routing  
     
   **Answer:**  C verified during the marking of the exam.  
     
   **Exercise 177.** Given the same information rate transmitted, which of the following line encodings requires a lower bitrate at the physical level?  
1) Code 12B15B  
2) Coding 4B5B  
3) They all require the same bit rate  
4) Coding 8B10B  
     
   **Answer:**  C verified during the marking of the exam.  
     
   **Exercise 178\.** If a router receives an IP packet, with correct checksum, with the same source and destination IP address and TTL field=9  
1) Routes it to the destination  
2) It forwards it to the destination anyway, but sends an ICMP packet to the source to report the error  
3) It discards it and sends an ICMP error packet to the source  
4) Unwrap the package  
     
   **Answer:**  A verified during the marking of the exam.  
     
   **Exercise 179\.** The preamble in the Ethernet package:  
1) It allows you to recognize transmission errors  
2) It allows you to identify the type of protocol carried in the data field of the Ethernet packet  
3) It allows you to identify the application process to which the package is delivered  
4) It is necessary to allow the receiver node to tune its clock with the transmitter node's clock  
     
   null verified during the marking of the exam.

   **Exercise 180\.** Two IP stations 130.192.40.1/24 and 130.192.40.200/24  
1) They do not have valid IP addresses  
2) They can exchange IP packets directly  
3) They can only exchange IP packets via a router  
4) They cannot exchange IP packets  
     
   null verified during the marking of the exam.  
     
   **Exercise 181\.** SMTP  
1) it is used by a mail client to fetch an email message from a server  
2) allows a mail server to communicate to another mail server who the sender of a message is  
3) allows a mail server to verify the identity of a user who wants to send a message  
4) it is based on the telnet protocol  
     
   null verified during the marking of the exam.  
     
   **Exercise 182\.** TCP messages contain a sequence number that indicates  
1) the next byte the receiver expects to receive  
2) the message number in the sequence of messages transmitted over the TCP connection  
3) the sequence number of the message in a set of fragments produced by fragmenting a larger message  
4) the position of the first byte of the message in the sequence of bytes transmitted over the TCP connection  
     
   null verified during the marking of the exam.  
     
   **Exercise 183\.** Congestion control in TCP  
1) imposes a maximum number of TCP connections that a station can open  
2) it is based on information received from routers on the route  
3) it is only present for some types of connections  
4) limits the size of the transmission window  
     
   null verified during the marking of the exam.  
     
   **Exercise 184\.** In the WI-FI protocol with DCF and handshaking  
1) sending RTS and CTS packets reduces the probability of collisions on data packets  
2) Collisions are completely avoided thanks to the carrier sense mechanism  
3) sending RTS and CTS packets allows two terminals, one of which is hidden, to send their frames simultaneously  
4) Collisions on any type of data transmitted are completely avoided  
     
   null verified during the marking of the exam.  
     
   **Exercise 185\.** The HEAD method of the HTTP protocol is used to:  
1) get the header of a web page  
2) send only the header of an HTTP request  
3) change the header, or home page, of a web server  
4) receive only the HTTP response header  
     
   null verified during the marking of the exam.  
     
   **Exercise 186\.** Receipt on node A of an ICMP Echo Reply packet sent by node B indicates that  
1) A and B are able to exchange IP packets  
2) A is able to send IP packets to B but not vice versa  
3) B is able to send IP packets to A but not vice versa  
4) B is able to send IP packets to A but vice versa is not guaranteed  
     
   null verified during the marking of the exam.    
     
   **Exercise 187\.** The ARP Request frame is used to learn  
1) the MAC address of a station connected to an IP network different from that of the source  
2) the IP address of an Ethernet node directly connected to the source node  
3) the IP address of a station given its internet name  
4) the MAC address of an IP node directly connected to the source node  
     
   null verified during the marking of the exam.  
     
   **Exercise 188\.** The DHCP protocol  
1) is used for automatic configuration of an IP station  
2) provides IP stations only with private addresses  
3) provides stations with the IP address corresponding to a given domain name  
4) does not allow a station to reuse the same IP address already used during a previous connection to the local network  
     
   null verified during the marking of the exam.  
     
   **Exercise 189\.** Given a topology (nodes, channels and associated costs), the optimal path between a source and a destination  
1) it never changes even if a channel becomes unavailable  
2) changes depending on the node running the link state algorithm  
3) it is the same whether you use a link state algorithm or a distance vector algorithm  
4) it never changes even if the cost of the channels changes  
     
   null verified during the marking of the exam.  
     
   **Exercise 190\.** When an Ethernet switch receives an ARP Request packet  
1) it forwards it only to the port to which the network's DHCP server is connected  
2) forwards it on all ports except the one from which the packet was received  
3) forwards it only on ports on which multicast traffic has been enabled  
4) forwards it only on the port to which the destination node/host is connected  
     
   null verified during the marking of the exam.  
     
   **Exercise 191\.** Version 4 IP addresses are:  
1) randomly assigned to the various stations connected to the internet, regardless of their position  
2) assigned by the network card manufacturers  
3) generally assigned on a geographical and topological basis, in order to facilitate aggregation  
     
     
   null verified during the marking of the exam.  
     
   **Exercise 192\.** The slow start phase in TCP  
1) It expects the congestion window to remain at a very low value for the entire duration of the connection  
2) it is one of the phases that achieve flow control  
3) allows the congestion window to grow quickly starting from a very low initial value     
4) allows the congestion window to grow slowly to avoid congestion situations  
     
     
   null verified during the marking of the exam.  
     
   **Exercise 193\.** The minimum packet size in the CSMA/CD protocol of the Ethernet network  
1) is necessary to ensure collision recognition  
2) it is preferable to maximize performance in terms of traffic disposed of  
3) It is necessary to ensure that we avoid causing multiple consecutive collisions on the same packet  
4) it does not depend in any way on the maximum size (in metres) allowed of the network  
     
   null verified during the marking of the exam.  
     
   **Exercise 194\.** A ring topology may be preferable to a mesh topology because:  
1) it can carry data and voice communications simultaneously  
2) routing is simpler  
3) it is more robust to failures  
4) allows bidirectional routes  
     
   null verified during the marking of the exam.  
     
   **Exercise 195\.** Two stations in the same collision domain in an Ethernet network  
1) they can create a collision only in the case of exactly simultaneous transmission  
2) they can never create a collision thanks to the carrier sense operation typical of the CSMA-CD protocol  
3) they identify the collision thanks to a NACK frame sent by the switch to which they are connected  
4) they can create a collision when transmitting a packet  
     
   null verified during the marking of the exam.  
     
   **Exercise 196\.** The TCP segments sent from host A to host B contain an Acknowledgment number that indicates:  
1) the next byte that host B expects to receive  
2) the next byte that host A expects to receive in the segments sent by host B  
3) the position of the segment in the sequence of segments transmitted on the TCP connection  
4) the position of the first byte of the segment in the sequence of bytes transmitted over the TCP connection  
     
   null verified during the marking of the exam.  
     
   **Exercise 197\.** A node that uses a Selective Repeat window protocol with cumulative ACK semantics to receive data from another node is delivered a duplicate PDU. Assuming no data was lost, which of the following is most likely the cause of this behavior?  
1) The receiver window is too small  
2) Transmitter timeout is too short  
3) Transmitter timeout is too long  
4) The transmitter window is too small  
     
   null verified during the marking of the exam.  
     
   **Exercise 198\.** A node that uses a Go-Back-N window protocol with cumulative ACK semantics to receive data from another node is delivered a duplicate PDU. Which of the following actions do you take?  
1) Always send an ACK relative to the expected sequence number  
2) if the PDU is within the receive window, it always sends an ACK relating to the sequence number of the duplicate PDU  
3) Send an ACK for the expected sequence number only if the transmitter timeout has not yet expired  
4) Always send an ACK for the sequence number of the duplicate PDU  
     
   null verified during the marking of the exam.  
     
   **Exercise 199\.** The IP protocol  
1) Implements the transport layer of the Internet  
2) It makes a large network more scalable thanks to the aggregability of addresses  
3) It is not used in local networks as Ethernet technology is adequate  
4) Provides access mechanisms to a shared medium  
     
   null verified during the marking of the exam.  
     
   **Exercise 200\.** A routing protocol  
1) involves the exchange of information on the state of the network to build routing tables  
2) defines the operations to be performed to forward individual packets to the output port  
3) defines the operations to be performed to choose the route to the destination  
4) uses routing tables but only in the case of circuit switching  
     
   null verified during the marking of the exam.  
     
   **Exercise 201\.** In the ATM protocol of the B-ISDN network, the data units, called cells, are small (48 bytes \+ 5 header bytes)  
1) to segment the IP protocol data units into cells in order to reduce the probability of data loss  
2) to improve the relationship between headers and user data in the cell  
3) to reduce packetization (package creation) time to transfer voice for real-time applications  
4) to increase the transfer speed of a large file thanks to the efficient segmentation and reassembly process  
     
   null verified during the marking of the exam.  
     
   **Exercise 202\.** It DNS  
1) is a system used for the automatic configuration of the domain name on hosts on the Internet  
2) is a distributed database which, given a search key, allows you to identify, within a hierarchy of servers, a record of a specified type  
3) it is a system used by the IANA to delegate the assignment of domain names (Top Level Domain)  
4) it is a server that is installed within a corporate network and contains the correspondence between the name and address of any host on the internet routing network  
     
   null verified during the marking of the exam.  
     
   **Exercise 203\.** Simultaneous sharing of the same physical channel between different sources can occur  
1) through frequency multiplexing  
2) through circuit multiplexing  
3) through circuit switching  
4) through virtual circuit packet switching  
     
   null verified during the marking of the exam.  
     
   **Exercise 204\.** An Ethernet network containing 200 stations can be assigned the IP network  
1) 130.192.2.0/24  
2) 130.192.0.0/25  
3) 130.192.2.0/25  
4) 130.192.2.0/26  
     
   null verified during the marking of the exam.  
     
   **Exercise 205\.** I TCP segments  
1) they have a fixed size negotiated when the connection is established  
2) they have a fixed size specified by the TCP standard  
3) they have variable size which is decided based on the level of congestion in the network  
4) they have variable size which does not depend on the level of congestion in the network  
     
   null verified during the marking of the exam.  
     
   **Exercise 206\.** To reduce packetization delay it is advisable  
1) increase the size of the header  
2) choose a nearby destination  
3) reduce the size of the PDU data field  
4) use a contention access protocol  
     
   null verified during the marking of the exam.  
     
   **Exercise 207\.** In a UTP (Unshielded Twisted Pair) cable the signal transmission occurs using  
1) the difference between the voltages of different pairs of conductors  
2) the difference between the voltages on the components of a pair of conductors  
3) the difference between the voltage of a single conductor and “ground”  
4) the difference between the voltage of a single conductor and the metal braid  
     
   null verified during the marking of the exam.  
     
     
     
     
   **Exercise 209\.** Flow control  
1) it is offered by UDP using a special field in the header  
2) it is offered by both TCP and UDP as it is fundamental in the creation of end-to-end communication  
3) it is not offered by either TCP or UDP as it is already present in lower level protocols  
4) is offered by TCP using a special field in the header  
     
   null verified during the marking of the exam.  
     
     
   **Exercise 210\.** An example of multiple access is represented by  
1) base station that transmits to mobile terminals in a cellular network  
2) local landline telephone exchange  
3) television broadcasts radiated by satellite  
4) mobile terminals that transmit to a base station in a cellular network  
     
   null  
   Comment: Mobile terminals potentially access from different points  
     
   **Exercise 211\.** Which of the following functions is not performed by the Transmission Control Protocol (TCP)?  
1) Congestion control  
2) Maintenance of byte sequence  
3) Multiplexing/demultiplexing through the door mechanism  
4) Choice of packet routing  
     
   null  
   Comment: Routing is the responsibility of the network layer  
     
   **Exercise 212\.** For a transmitter implementing an ARQ (Automatic Retransmission reQuest), receiving a succession of hits containing the same sequence number is a symptom of  
1) an increase in the duration of time  
2) a loss of acknowledgment data unit (ACK)  
3) an increase in bandwidth availability between transmitter and receiver  
4) a loss of one data unit of information  
     
   null  
     
   **Exercise 213\.** Which of the following functions **non** Is it characteristic of the second architectural level of the OSI model?  
1) delimitation of data units  
2) addressing on the local network  
3) error control on data drives  
4) end-to-end routing of data drives  
     
   null verified   
   Comment: see slide 02-Architectures pp45-46: routing is the responsibility of level 3  
     
   **Exercise 214\.** Which of the following statements applies to Fast Ethernet in full-duplex (bidirectional) mode?  
1) Full-duplex mode can be used between a user station and a switch port, or between the ports of two switches  
2) Full-duplex mode does not allow for a greater distance between a user station and a switch  
3) Full-duplex mode allows you to interconnect switches in a ring topology  
4) Full-duplex mode does not increase the amount of information that can be exchanged between a user station and a switch, compared to half-duplex mode  
     
   null   
      
   **Exercise 215\.** The TCP transmitter window control algorithm switches from the slow-start phase to the congestion avoidance (AIMD) phase  
1) upon notification by the receiver  
2) when the current window reaches a threshold value  
3) when a timeout expires  
4) as soon as you receive an out-of-sequence response  
     
   null to check  
   Comment: see slide 04-Transport Level  
     
     
   **Exercise 216\.** In a virtual circuit packet switching network, the routing algorithm is applied in the switching nodes  
1) to all received packets  
2) to virtual circuit opening and closing request packages only  
3) to data packets only  
4) to virtual circuit opening request packets only  
     
   null to check  
   Comment: see slide 01-General Concepts pp.146-147 all packets route otherwise the packet would not move from the intermediate nodes  
     
   **Exercise 217\.** Which of these statements about peer-to-peer architectures is false?  
1) They are autoscaling, meaning performance does not change drastically as the number of peers varies  
2) The peers are located in large data centers and are managed by the same administrator  
3) Resources usually remain accessible even if some peers are turned off  
4) Peers can change their IP address over time  
     
   null verified.  
     
   **Exercise 218\.** Which of these statements regarding datagram routing in IP networks is true?  
1) It is carried out by routers based on the destination IP address  
2) It is carried out by routers based on the source IP address  
3) It is done by routers based on the virtual-circuit (VC) identifier   
4) IP is based on circuit switching, so no routing is done  
     
       null

		    Comment: see IP slide 

**Exercise 219\.** The fact that the PPP protocol (Point-to-Point Protocol) operates on point-to-point connections entails, among other things:

1) That PPP should use MAC layer addresses to distinguish sender and recipient  
2) That it is not necessary to use addresses in the PPP header  
3) That PPP must send the identity of the recipient to the higher levels  
4) That PPP frames have a fixed length  
     
   null to check.  
   Comment: It is not necessary to explicitly identify the sender and recipient via header addresses because it is implicit that each frame sent is destined for the directly connected device. Furthermore, D is wrong as the length is configured by preliminary agreement between the two devices.  
     
   **Exercise 220\.** Which of the following measures is necessary to make the operation of a window protocol more robust in the case of a non-sequential channel between transmitter and receiver?  
1) Use of cumulative confirmations  
2) Increasing the bits in the address fields of the data units  
3) Choice of equally sized transmit and receive windows  
4) Increase in bits used for data unit numbering  
     
   null verified during the marking of the exam.  
     
   **Exercise 221\.** Which of these statements about TCP's retransmission mechanism is false?  
1) Receiving a duplicate triple ACK causes the older segment to be retransmitted while awaiting acknowledgment	  
2) A timeout causes the oldest segment to be retransmitted while waiting for confirmation  
3) A timeout causes all segments awaiting acknowledgment to be retransmitted  
4) Receiving an ACK also cumulatively confirms all previous segments  
     
   null verified.  
   Comment: In case of timeout the transmission window is reduced, so C is definitely false as it cannot retransmit them all.  
     
   **Exercise 222\.** Which of these statements about DASH is false?  
1) It is based on the availability of versions of the same multimedia content encoded at different bit rates  
2) It produces messages that are packaged in RTP to create internet telephony  
3) Makes a compromise between available network bandwidth and quality of multimedia content  
4) It is used for streaming multimedia content over HTTP  
     
   null verified during the marking of the exam.  
     
   **Exercise 223\.** Datagram-type packet switching provides:  
1) An assignment of transmission resources for the duration of the packet transmission only  
2) A statistical choice between frequency multiplexing and time multiplexing  
3) A preventive assignment of transmission resources based on the activity statistics of the sources  
4) A permanent assignment of transmission resources to different information flows  
     
   null To be verified  
     
   **Exercise 224\.** The TCP protocol dynamically varies the size of the current window at the transmitter to achieve:  
1) The window does not change  
2) Both flow control and congestion control  
3) Only congestion control  
4) Just flow control  
     
   null verified during the marking of the exam.  
     
   **Exercise 225\.** Which of the following is NOT an example of multiple access?  
1) A switch that transmits packets on an interface output in a packet switching network  
2) Aloha Stations to Master Station  
3) Smartphones transmitting to a base station in the access network of a cellular network  
4) Transmissions from computers equipped with a WIFI card to an Access Point  
     
   null verified during the marking of the exam.  
     
   **Exercise 226.** There is at least a tree topology with 5 nodes and 4 channels in which, if you add a channel between two nodes not directly connected to each other, the topology:  
1) It becomes a ring topology  
2) It remains a tree topology  
3) It becomes a star topology  
4) It becomes a fully connected topology  
     
   null verified  
     
     
   **Exercise 227\.** Which of these statements about DHCP is false?  
1) DHCP dynamically provides an IP address to a requesting host  
2) Among the information provided by the DHCP server there is also the default gateway address  
3) DHCP messages are packaged in broadcast UDP datagrams  
4) There can be at most one DHCP server in a network  
     
   null verified during the marking of the exam.  
     
   **Exercise 228\.** The following is mandatory in the IP header, i.e. in the PCI of the IP protocol:  
1) The Time To Live field which allows packets that have passed through an excessive number of routers to be eliminated from the network  
2) The source MAC address, useful for sending replies to received packets  
3) The ACK Number field for acknowledgment numbering (ACK)  
4) The CODE field, which contains the SYN, FIN and ACK flags for opening and closing the connection  
     
   null verified.  
     
   **Exercise 229\.** A link state routing algorithm predicts that:  
1) Each node of the network communicates to all the nodes of the network the information on the cost of transmission towards the nodes adjacent to it  
2) Each node in the network generates its own routing tables and then distributes them only to adjacent nodes  
3) Each node in the network communicates information on the cost and direction of the roads leading to each possible destination to the nodes adjacent to it  
4) Each node in the network generates its own routing tables and then distributes them to all other nodes in the network  
     
   null verified.  
   Comment: Slide “Layer 3: Routing” page 11  
     
   **Exercise 230\.** In an Ethernet network where terminals are connected in full-duplex mode to switch ports using a UTP cable:  
1) The CSMA/CD access protocol is effectively useless because the switch separates collision domains between its ports  
2) The CSMA/CD access protocol is effectively useless because the switch works at bit rates greater than or equal to 1GB/s, making frames short-lived  
3) The CSMA/CD access protocol is still used for bit rates below 100Mb/s  
4) The CSMA/CD access protocol is still used, but only in the case of two transmissions let's get started at the same time  
     
   null verified during the marking of the exam.  
     
   **Exercise 231\.** In a time interval T, a transmitter node using a Go-Back-N window protocol with a window of 5 PDUs transmits PDUs numbered 9, 10, 11 and receives ACK (cumulative) 8\. Assuming the timeout has not expired and that ACK 8 is the highest sequence number received up to this point, which of the following actions is allowed by the protocol rules in this situation?  
1) Send PDU 12  
2) Send PDU 8  
3) Send PDUs 12 and 13  
4) No action until more ACKs are received  
     
   null verified during the marking of the exam.  
     
   **Exercise 232\.** A (N)-PDU ​​(Protocol Data Unit), passing to level (N-1) transforms into:  
1) One or more (N)-SDU (Service Data Unit)  
2) One or more (N-1)-SDU (Service Data Unit)  
3) Una (N-1)-PCI (Protocol Control Information)  
4) One or more (N-1)-SDUs (Service Data Unit) to which N-PCIs are added  
     
   null verified during the marking of the exam.  
     
     
   **Exercise 233\.** The ARP (Address Resolution Protocol) protocol allows you to:  
1) Obtain an unknown IP address of a host from a domain name  
2) Send error messages between routers  
3) Obtain an unknown MAC address of a host from an IP address  
4) Obtain an unknown IP address of a host from a MAC address  
     
   null verified.  
     
     
   **Exercise 234\.** Which of these statements regarding Web cookies is false?  
1) A browser in possession of a cookie includes it in subsequent requests to the relevant HTTP server  
2) The browser creates a different cookie every time it accesses the same HTTP server  
3) The cookie is created by the HTTP server when a browser logs in for the first time  
4) The cookie is stored by the browser in the file system of the client host  
     
   null verified.  
     
   **Exercise 235\.** Which of the following statements about the comparison between the Aloha and Slotted-Aloha protocols is true?  
1) Collisions in Aloha can occur at any time, while in Slotted-Aloha they coincide with the start of plots  
2) Broadcasts in Aloha can start at any time, while in Slotted-Aloha they must be preceded by a channel reservation slot  
3) The broadcast in Slotted-Aloha must be preceded by listening to the channel, while in Aloha it can take place as soon as the plot is available  
4) Unlike Slotted-Aloha, Aloha's performance depends on propagation delays  
     
   null verified during the marking of the exam.  
     
   **Exercise 236\.** In the case where an error in the configuration of the forwarding tables on the routers generates a closed path in the network, which of these statements is true?  
1) A datagram traveling on this path is sooner or later discarded by routers based on the TTL field  
2) The spanning tree protocol prevents these problems before they arise  
3) A datagram can travel along this path infinitely  
4) A datagram circulating on this path is sooner or later eliminated by routers, which identify it by comparing the content with the copies kept in the local cache  
     
   null verified during the marking of the exam.  
     
   **Exercise 237\.** The transmission delay of a PDU in a packet switching network:  
1) It depends on the size of the PDU and the distance between the transmitter and receiver  
2) It just depends on the bit rate of the transmitter   
3) It depends on the bit rate of the transmitter and the distance between transmitter and receiver  
4) It depends on the bit rate of the transmitter and the size of the PDU  
     
   null verified during the marking of the exam.  
     
   **Exercise 238\.** Consider an extended LAN network in Ethernet technology whose nodes are interconnected by transparent switches. Which of the following statements is **false**?  
1) The switches can support the creation of Virtual LANs  
2) Switches introduce additional delay in transmissions between nodes connected via the switches themselves  
3) It is necessary to modify the configuration of the nodes connected to the LAN to allow correct routing of the MAC frames between the switches  
4) Switches separate the collision domains of interconnected network portions  
     
   null verified during the marking of the exam.  
     
   **Exercise 239\.**  Regarding receiving an out-of-sequence segment in TCP, which of these statements is true?  
1) The reordering of the segments is the responsibility of the RTP protocol  
2) The receiver immediately delivers the segment to the higher protocol layers  
3) The receiver always discards the segment that needs to be transmitted again  
4) The receiver returns an acknowledgment number referring to the next expected byte  
     
   null To be verified  
      
   **Exercise 240.** Given the same number of bits of information transmitted, which of the following line encodings requires a bit rate higher on a physical level?  
1) Coding 4B5B  
2) Polar coding NRZ  
3) Manchester coding   
4) Unipolar coding   
     
   null verified during the marking of the exam.  
* Comment: 4B5B requires a bit rate of 1.25, NRZ and unipolar require a bit rate of 1, Manchester requires a bit rate of 2\. Physical layer \- pages 28-32  
    
  **Exercise 241\.** During the slow-start phase of the TCP protocol management control, the current window of the transmitter:   
1) It grows by one segment for each acknowledgment (ACK) received  
2) Doubles for each acknowledgment (ACK) received  
3) It is halved for each missing acknowledgment (ACK).  
4)  It remains constant over time  
   null verified.   
   Comment: Duplicate quiz (see Ex. 122\)   
     
   **Exercise 242\.** Which of the following features are possible thanks to Store & Forward operation in a packet network?  
1) The possibility of having different transmission speeds between the different channels connected to the same switch  
2) The reduction of information transfer delays through a switch node  
3) The possibility of using forward error correction channel coding  
4) Reducing the size of packet headers  
     
   null verified.   
   Comment: Duplicate quiz (see Ex. 37\)    
     
   **Exercise 243\.** The IP protocol  
1) It does not provide any type of error protection  
2) It guarantees error detection only on the contents of the datagram  
3) Provides error detection on the header and content of the datagram  
4) It guarantees error detection only on the datagram header	  
     
   null verified.   
   Comment: Duplicate quiz (see Ex. 57\) routing  
     
   **Exercise 244\.** An IP router after calculating the route:  
1) Change the source and destination IP addresses in the datagram header  
2) Only changes the Time To Live (TTL) field in the datagram header  
3) Edit exclusively in the Header Checksum field in the datagram header  
4) Edit the Time To Live and Header Checksum fields in the datagram header  
     
   null verified.   
   Comment: Duplicate quiz (see Ex. 50\)   
     
   **Exercise 245\.** The Stop & Wait protocol  
1) It can work using a number of numbering bits greater than or equal to 1  
2) It can only work using more than one numbering bit   
3) It can only work using a number of numbering bits smaller than the size of the transmission window  
4) It can only work using a single numbering bit  
     
   null verified.   
   Comment: Duplicate quiz (see Ex. 67\)   
     
   **Exercise 246\.** The TCP transmission window control algorithm switches from the slow-start phase to the congestion avoidance (AIMD) phase  
1) Upon notification by the SIP receiver  
2) When the timeout expires  
3) As soon as you receive out-of-sequence feedback  
4) The moment the current window reaches a threshold value  
     
   null to check.   
   Comment: Duplicate quiz (see Ex. 215\)   
     
   **Exercise 247\.** Which of the following is a consequence of increasing the number of numbering bits in the data units of a window protocol  
1) Increased number of possible virtual circuits  
2) Increase in malfunctions due to non-sequential channel between transmitter and receiver  
3) Potential increase in protocol throughput  
4) Failure to detect collisions on broadcast channel

   null verified.

   Commento: default gateway

   

   **Exercise 248\.** Which of these statements regarding TCP slow start is false?

1) When a threshold (sstresh) is reached, it switches to congestion avoidance mode.  
2) It is based on an exponential increase of the congestion window (cwnd)  
3) Constantly keeps TCP throughput low to avoid network congestion  
4) It runs following a timeout event that occurs on the connection

   null to check

   

   **Exercise 249\.** Flow control in TCP

1) It bases its operations on the receive window (rwnd) field in the TCP segment header  
2) It is managed by the default gateway which limits the throughput of datagrams sent over the network  
3) It bases its operations on TCP timeouts and receiving duplicate ACKs  
4) Requires the establishment of a virtual circuit through intermediate routers

   null to check 

   

   **Exercise 250\.** Which of these statements related to the Real Time Protocol is **false**?

1) It can be used to convey multimedia flows in IP telephony  
2) It is an application layer protocol that normally relies on UDP  
3) It offers guarantees on internet transmission times  
4) Allows you to specify the codec used for the multimedia stream

   null to check

   

   **Exercise 251.** One line coding and one digital modulation

1) Both can be used for radio transmission  
2) They can only be used for transmission on electric vehicles  
3) They can only be used for transmission on electric vehicles (the first) and radio vehicles (the second)  
4) Both can be used for fiber optic transmission 

   null verified

   

   **Exercise 252\.** In a Selective Repeat protocol with a reception window equal to 2 PDUs, and initially positioned on sequence numbers 0 and 1, the following reception of PDUs in the indicated order does not cause PDU rejection

1) 0,3,1,2  
2) 2,0,1,3  
3) 0,2,3,1  
4) 1,0,3,2

   null to check

   

   **Exercise 253\.** A routing table contains all four of the following entries simultaneously. Identify the entry selected following the forwarding procedures of a datagram with destination 130.192.15.200

1) 0.0.0.0/0  
2) 130.192.14.128/25  
3) 130.192.0.0/16  
4) 130.192.15.128/25

   null to check

   

   **Exercise 254\.** The term “Roaming” in a cellular network refers to

1) The overlap of multiple cells in a given area of ​​the territory  
2) The ability to track a terminal regardless of the cell in which it is located  
3) The persistence of the connection even when passing into an adjacent cell  
4) The speed at which a terminal moves from one cell to another

   null to check

   

   **Exercise 255\.** A packet begins reception at a switching node at time t=15ms and ends reception at t=35ms. Assuming that there are no other packets in the queue and that the processing time is negligible, its forwarding on an output channel having quadruple speed compared to the of entry it is completed in time

1) t=40ms  
2) t=45ms  
3) It depends on the propagation time to the destination  
4) t=50ms

   null verified

   Comment: 35 \+ (35-15)/4 \= 40 ms

   

   **Exercise 256\.** In a WiFi network the sending of an ACK for a unicast frame by the receiver is 

1) Not necessary if the channel was booked through RTS/CTS  
2) Mandatory only if the receiver is the Access Point  
3) Required after waiting a NAV time  
4) Required if plot reception is correct

   null to check

   

   **Exercise 257\.** A source sends 12 PDUs using a Go-Back-N protocol with a transmission window of 5 PDUs, numbering them starting from 1\. The first ACK is received after the transmission of packet 5 has finished and is ACK 2\. Knowing that it is not after any timeout expires, what action follows

1) The source sends packet 3  
2) The source sends packet 6  
3) No action  
4) The source retransmits the package 2

   null verified

   Comment: From Kourse, Due to window width limitations, the sender sends packets 0 to 3, but then has to wait for notification of receipt of one of them before it can proceed when subsequent ACKs arrive (for example, ACK0 and ACK1), the window slides forward and the sender can transmit a new packet (pkt4 and pkt5 respectively)., 

   

   **Exercise 258\.** By eliminating a bidirectional channel from a ring topology, the resulting topology

1) It becomes a tree topology  
2) It becomes a passive star topology  
3) It remains a ring topology  
4) It becomes an active star topology

   null verified

   **Exercise 259.** When transmitting data over a radio channel, it is preferable to use 

1) A polar line encoding such as Manchester encoding to facilitate synchronization recovery   
2) An nBmB type line coding to reduce bandwidth occupation  
3) A unipolar line coding to guarantee the continuous component necessary for transmission  
4) A digital modulation like 64-QAM to be able to transmit in the appropriate frequency band 

   null to check

   

   **Exercise 260\.** A host must send a 4800 byte file using 800 byte PDU with 100 byte PCI. What size is the last PDU sent?

1) 900 byte  
2) 100 byte  
3) 700 byte  
4) 800 byte

   null verified

   Comment: 800 byte PDU, of which 100 bytes for the header and then 700 bytes for the data.  700\*6 \= 4200\. 4800-4200 \= 600 → 600+100 \= 700 bytes

   

   **Exercise 261\.** IP datagram segmentation is an example of 

1) Generation of more 3-SDUs from a 3-PDU  
2) Generation of more 2-SDUs from a 3-SDU  
3) Generation of more 3-PDUs from a 3-SDU  
4) Generation of more 2-SDUs from a 3-PDU  
     
   null verified  
   Comment: see slide 33 Protocol architectures  
   Many N-PDU from one N-SDU  
   Many (N-1)-SDU from one N-PDU  
     
   **Exercise 262\.** In a virtual circuit packet switching network, the number of labels used by a node for routing is proportional  
1) To the number of possible sources  
2) To the sum of the average number of channels entering and exiting each node   
3) To the number of active connections  
4) To the number of possible destinations

   null verified  
     
   **Exercise 263\.** Which of the following protocols does not provide some form of error detection  
1) Ethernet  
2) IEEE 802.2 LLC (Logical Link Control)  
3) PPP (Point-to-point Protocol)  
4) IEEE 802.3

   null verified

   

   **Exercise 264\.** In the case where an error in the configuration of the forwarding tables on the routers generates a closed path in the network, which of these statements is true?

1) A datagram can travel along this path infinitely   
2) The spanning protocol trand and avoid these problems before they arise  
3) A datagram circulating on this path is sooner or later eliminated by the routers, which identify it comparing them the content with copies held in the local cache  
4) A datagram traveling on this path is sooner or later discarded by routers based on the TTL field

   null verified

   

   **Exercise 265\.** A 2 second playout delay

1) It is compatible with streaming stored content but not for VoIP  
2) It is compatible with both streaming of stored content and VoIP  
3) It is not compatible with streaming stored content or VoIP  
4) It is compatible with VoIP but not for streaming stored content  
     
   null verified  
     
   **Exercise 266\.** Which of these statements about UDP is true?  
1) UDP automatically retransmits datagrams for which an acknowledgment has not been received  
2) UDP implements flow control but not congestion control  
3) UDP implements both flow and congestion control   
4) UDP allows multiplexing/demultiplexing thanks to the port concept

   null verified

   

   **Exercise 267\.** In the byte stuffing procedure 

1) The receiver discards each byte that matches the delimiter used by the protocol  
2) The receiver discards the delimiter used by the protocol that precedes the escape byte  
3) The receiver discards the escape byte preceding the delimiter used by the protocol  
4) The receiver discards any byte that matches the escape byte used by the protocol

   null verified

   

   **Exercise 268\.** In the case of stations all within radio range of each other, which of the following statements regarding the comparison between the Aloha and CSMA protocols is true?

1) Unlike CSMA, a station transmitting using Aloha needs acknowledgment  
2) Unlike Bye bye, a station using CSMA never collides with a transmission initiated longer than the maximum propagation delay  
3) Aloha broadcasts can start at any time, whereas in CSMA they must be preceded by a channel reservation slot  
4) Unlike Bye bye, in CSMA a station never collides with other stations 

   null to check

   

   **Exercise 269\.** Which of the following statements is true, considering the classic operations of an IP router (thus excluding firewalls, NAT, etc.)?

1) A router changes at least one IP address of the packets it must transmit   
2) A router uses ICMP messages to determine the path to follow to reach a host belonging to the Internet  
3) An IP router uses the address resolution protocol (ARP) to know the IP address of the router to write as the destination address in the IP packet  
4) A router changes at least one MAC address of packets containing IPs, but not IP addresses

   null to check

   	

   **Exercise 270\.** How many hosts can be managed at most in a network with netmask 255.255.255.128?

1) 254  
2) 255  
3) 126  
4) 64

   null to check

   Comment: the first 25 bits are dedicated to the network, 32 \- 25 \= 7 bits available for hosts. 2^7 \= 128\. Not all are available, 2 are occupied by default. 128-2 \= 126\. The answer is C

   

   **Exercise 271\.** If a node using a window protocol receives a PDU out of sequence and with incorrect parity bits:

1) It discards the PDU and does not send any ACK  
2) Sends an ACK for the sequence number contained in the PDU but discards the PDU  
3) Discards the PDU and sends an ACK of the expected sequence number  
4) Inserts the PDU into memory if it is within the receive window, without sending any ACK  
     
   null verified during correction  
     
   **Exercise 272\.** A frame received from an Ethernet card of one switch is elaborated for deciderne the routing   
1) Only if the destination MAC address is broadcast   
2) Only if the unicast destination MAC address matches that of the switch  
3) Always, whatever the destination address  
4) Only if the destination MAC address is multicast and the switch belongs to the corresponding multicast group

   null to check

   

   **Exercise 273\.** Compared to the 1-persistent CSMA, the non-persistent CSMA predicts that 

1) After a collision, wait a random time before trying to transmit  
2) Relistening to the channel, if found busy, occurs after a random time  
3) Wait a random time and then send the plot to the channel  
4) The transmission occurs as soon as the channel becomes live  
     
   null to check  
     
   **Exercise 274\.** The ICMP (Internet Control Message Protocol) protocol allows  
1) The exchange of error messages between routers ed host  
2) To transfer emails between host and host  
3) The exchange of error messages between the TCP protocol and the IP protocol  
4) To transfer a web page from a server to a client

   null verified

   

   **Exercise 275\.** They are obligatorily contained in the TCP header, i.e. in the PCI of the TCP protocol

1) Some flags used for opening and closing the connection  
2) The current value of the congestion window  
3) The header checksum field, for the revelation of the error on the header only  
4) The value of the Maximum Segment Size negotiated between the transmitter and receiver

   null verified

   **Exercise 276\.** In uno schema ARQ (Automatic Retransmission reQuest) with non-cyclic numbering, with window Wt \> 1, the number of the first packet in the transmission window, can be referred to:

1) To none of the other answers  
2) To a packet transmitted by the transmitter, received by the receiver, and for which the transmitter received the corresponding ACK  
3) To a packet for which the receiver has no buffer space  
4) To a packet transmitted by the transmitter, received by the receiver and for which the transmitter has not yet received the corresponding ACK

   null verified

   

   **Exercise 277\.** In the CSMA-CD protocol a station completes the transmission of a frame

1) Only if it has the highest priority compared to the station it collides with.  
2) Only if, when listening to the channel, you cannot detect it an eventuality simultaneous reception with the transmission in progress  
3) Always after starting it  
4) Only if it receives an ACK frame from the receiver

   null verified

   

   **Exercise 278\.** If a node using a Selective Repeat protocol receives a sequence number PDU within the receive window with incorrect parity bits:

1) It discards the PDU and does not send any ACK  
2) Discards the PDU and sends an ACK of the expected sequence number  
   **has**  
   null verified  
   Comment: The packet is completely ignored. With incorrect parity bits it is as if it was never received  
     
   **Exercise 279\.** Which of these CANNOT be a network ID:  
1) 130.192.55.0/16  
2) 130.192.55.0/24  
3) 130.192.16.0/20  
4) 130.192.16.0/24

   null verified during correction

   

   **Exercise 280\.** A source must send 6 PDUs using a Go-Back-N protocol with cumulative ACKs and a transmission window of 3 PDUs, numbering them starting from 1\. After the transmission of the first window, and before the timeout expires, the only confirmation received is ACK 3\. Which of the following actions is likely to be performed by the source:

1) The source retransmits the PDU 2  
2) The source sends PDUs 3 and 4  
3) The source sends PDUs 4 and 5  
4) The source no longer sends anything and waits for the timeout to expire  
     
   null verified during correction   
   Comment: ACK 3 advances the window by 2 positions

   **Exercise 281\.** Which field in the IP header is used to prevent a packet from being forwarded by more than N routers?

1) Destination address  
2) Version  
3) None of the answers

   null verified during correction 

   Comment: the field that is used is the TTL

   

   **Exercise 282\.** In a WiFi network the use of RTS/CTS messages

1) Eliminates collisions with other stations  
     
   null  
   Comment: Collisions are never eliminated, at most they are reduced  
     
   **Exercise 283\.** Which of the following statements about NAT is true?  
1) NAT uses an IP address/port combination to create associations between internal hosts and destinations on the Internet   
2) Port forwarding is necessary to allow communication between hosts on the internal network towards the internet  
3) NAT assigns IP addresses dynamically to hosts on the internal network that request them  
4) It is always possible to contact the hosts of the internal network from the internet, without any particular additional solutions

   null verified during correction

   **Exercise 284\.** Which of the following is not a network ID?

1) 192.168.16.0/24  
2) 130.192.36.128/25  
3) 13.0.0.0/8  
4) 192.168.16.0/16

   null to check

   

   **Exercise 285\.** Routers have IP addresses

1) Always and only one  
2) more than one  
   null   
     
   **Exercise 286\.** Aloha protocol begins broadcasting  
1) after listening to the channel, feeling it free  
     
   null  
   Comment: Aloha broadcasts regardless without listening to the channel  
     
   **Exercise 287\.** The byte stuffing technique in the PPP protocol is used to  
1) separate the header from the data field  
2) correctly detect the beginning and end of the plot

   null verified during correction 

   Comment: serves to identify that the delimiter is unique in the message 

			  
**Exercise 291\.** Which of these statements regarding the HTTP 1.1 protocol is true?

1) HTTP 1.1 is based on a client-server paradigm  
2) HTTP 1.1 uses UDP at the transport layer  
3) HTTP 1.1 is natively stateful (not stateless)  
4) HTTP 1.1 messages use binary encoding  
     
   null  
   Comment: Http uses TCP, is stateless and uses ascii encoding  
     
   **Exercise 292\.** The fragmentation operation carried out by IPv4 routers is an example of:   
1) Generation of more 2-SDUs from a 3-SDU  
2) Generation of more 3-SDUs from a 3-PDU  
3) Generation of more 3-PDUs from a 3-SDU  
4) Generation of more 2-SDUs from a 3-PDU

   null

   

   **Exercise 293\.** Associate a dynamic cost (for example the load on the channel) with a transmission channel instead of a static cost (for example equal to 1 for all transmission channels)

1) It can cause frequent changes of the chosen path from a source to a destination  
2) Avoid possible fluctuations in the choice of routes caused by variations in cost over time  
3) It is preferable in the case of packet switching but not in circuit switching  
4) Reduces variations in route selection from a source to a destination

   null

   

   **Exercise 294\.** Consider a network consisting of a transmitter, an intermediate node and a receiver. There are 2 packets, each lasting 10 ms, which begin to arrive at the intermediate node at time t \= 20 ms. The channel that connects the intermediate node with the receiver has double the speed compared to the channel that connects the transmitter with the intermediate node. Assuming that there is no time gap between the 2 packets, that there are no other packets in the queue, and that the processing time is negligible, at what instant of time does the transmission complete?

1) 40ms  
2) 50ms  
3) 45ms  
4) 70ms  
   null to check  
     
   **Exercise 295\.** A node must send 2200 bytes of data, using 900 byte PDU with 100 byte PCI, over a channel with a transmission rate of 4Mbit/s. How long does it take for the last packet to be transmitted?  
1) 1.4ms  ✅ 
2) 1.8ms  
3) 1ms  
4) 5ms  
   null to check  
     
   **Exercise 296\.** Let a 100Mbit/s channel share 2 30Mbit/s TCP connections and 2 40Mbit/s UDP connections. Which of the following statements is correct?  
1) UDP connections block TCP connections  
2) TCP connections have a transmission speed of 25Mbit/s, due to TCP Fairness.  
3) UDP connections have a transmission speed of 30Mbit/s, due to TCP congestion control  
4) TCP connections have a transmission speed of 10Mbit/s  
   null to check  
   150  
   **Exercise 297\.** Il bluetooth:  
1) Use Modulation *frequency hopping spread spectrum* short range radio transmission ISM band connected to a Master node with star center topology  ✅
2) Use Modulation *frequency hopping spread spectrum* High band long range radio transmission.  
3) It is only used by mobile phones to transmit.

   null verified
   Comment: (Local Network Standard 2022 \- Bluetooth ) The exam answers were similar

   

**Exercise 298\.** Which of these is false for the VoIP?
1) RTP provides mechanisms to ensure real-time delivery  ✅
2) RTP can be used for audio/video transfer  
3) SIP can be used to open and close a session  
4) SIP provides mechanisms for determining the address of the called party
null verified
**Exercise 299\.** Selective repeat with Wt=Wr=4 and cumulative ACK semantics, where the window transmission time is much less than RTT, only PDUs 0,1,2,3 need to be transmitted. 
After the first transmission of the entire window the receiver receives PDUs 0,2,3. Assuming that no packets are subsequently lost, 
what is the correct sequence that the receiver sees arriving after the first reception of PDU 3?

1) 1  
2) 1,2,3  ✅
3) 0,1  
4) 0,1,2,3  
     
   null verified  
   Comment: Not receiving PDU 1, the receiver will only send ACK equal to 1\. The transmitter, as soon as the timeout expires, will send back the entire window not yet confirmed, therefore PDUs 1,2,3; since RTT \> window transmission duration, the 3 PDUs will have already been transmitted before an ACK is received by the transmitter.  
   Under the assumption that subsequent packets after those in the first window cannot be lost, the receiver will receive PDUs 1,2,3. 

**Exercise 300\.** How fast is WiFi technology nowadays?  
1) Hundreds of Gigabit/s  
2) On the order of Tbit/s  
3) Some Gigabit/s  ✅
4) Tens of Mbit/s  
   null verified  
   **Exercise 301**. The FTTx residential access network consists of  
1) A passive fiber optic distribution network and, optionally, a copper terminal segment ✅
2) Always entirely from an active fiber optic distribution network  
3) A passive copper distribution network and, optionally, a fiber optic terminal segment  
4) From an optical distribution network based on IEEE 802.3 Gigabit Ethernet technology	
	null to check
**Exercise 302**. A 16-QAM digital modulation
1) It involves sending 16 bits each symbol time  
2) It involves sending 4 bits each symbol time ✅  
3) It involves sending 4 symbols every bit time  
4) It involves sending 16 symbols each bit time    
	null to check
   
