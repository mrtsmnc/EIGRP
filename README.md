# EIGRP

**EIGRP Features Enhanced Interior Gateway Routing Protocol (EIGRP) is a classless, advanced distance-vector protocol used by Cisco. It is an extended version of Cisco's previous protocol, IGRP. Like IGRP, EIGRP uses the concept of an autonomous system to describe a group of routers that run the same routing protocol and share routing information. However, unlike IGRP, EIGRP sends subnet mask information in routing updates. This allows us to use Variable Length Subnet Masks (VLSM) and summarization when designing our networks.

EIGRP is a hybrid routing protocol that combines both distance-vector and link-state protocol features. EIGRP synchronizes routing tables between neighbors and then updates the information containing any changes in the topology. This feature enables EIGRP to be used in large networks. EIGRP can reach up to a maximum of 255 hops. Normally, EIGRP's administrative distance (AD) is 90, but this is only applicable for internal EIGRP routes. The other type of route, the external EIGRP route, has an AD of 170.

EIGRP, some of the features that set it apart from other protocols are:

It supports both IPv4 and IPv6 through protocol-independent modules. It is considered a classless protocol (like RIPv2 and OSPF). It supports Variable Length Subnet Masks (VLSM) and Classless Inter-Domain Routing (CIDR). It supports summarization and non-contiguous networks. It has efficient neighbor discovery. It uses Reliable Transport Protocol (RTP) for communication. It uses the Diffusing Update Algorithm (DUAL) to select the best path.

**One of the most distinct features of EIGRP is its support for routing different network layer protocols such as IP, IPX, Apple Talk, and IPv6.

*There are two modes in which EIGRP commands are entered: router configuration mode and interface configuration mode.

*Router configuration mode: It allows for enabling protocols, specifying which networks will run EIGRP, and setting global properties.

*Interface configuration mode: It enables adaptation of summary, metric, timer, bandwidth, and other interface-level settings.

*EIGRP uses three different tables: Neighbor Table, Topology Table, and IP Routing Table.

*There are five EIGRP packets: Hello, Update, Query, Reply, and ACK.

1- Hello Packet: This packet is used to establish neighbor relationships between routers.

2- Update Packet: It is sent when there is a change in routing information.

3- Query Packet: This packet is sent when a router needs new information.

4- Reply Packet: It is sent in response to Query packets.

5- ACK Packet: It is sent to confirm that a packet has been sent correctly
