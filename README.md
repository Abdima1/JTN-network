# JTN-network
Worked on this freelencing projects  for a construction company . The project depicts the entire companies topology.

📌 Project Overview

This project simulates a 4-router enterprise WAN topology built in Cisco Packet Tracer.
The design represents multiple branch offices connected through a redundant ring WAN, with each site supporting its own local LAN.
The network demonstrates structured IP addressing, WAN subnetting, dynamic routing, and scalable hierarchical design.

Network Architecture

The topology follows a ring-based WAN core design:

4 routers interconnected via serial point-to-point links

Each router connects to an access switch

End-user PCs connect to the switches

Full inter-site communication enabled through dynamic routing

🔁 WAN Core (Ring Topology)

Each router connects to two neighboring routers

Redundancy ensures traffic can reroute if a link fails

Serial links use /30 subnetting for efficient IP utilization

This design prevents a single point of failure in the WAN.

🖥️ LAN Structure

Each router serves as the default gateway for its local LAN:

Dedicated /24 subnet per site

Switch-based access layer

End devices configured with proper gateway addressing

This structure supports scalability and easy expansion.

🌍 IP Addressing Strategy
🔹 WAN Links

Subnet mask: /30 (255.255.255.252)

Used for point-to-point serial connections

Minimizes IP address waste

🔹 LAN Networks

Subnet mask: /24 (255.255.255.0)

One subnet per site

Simple and scalable addressing plan

🔄 Routing

Dynamic routing is implemented to ensure:

Automatic route advertisement

Full network reachability

Redundant path utilization

Faster convergence in case of failure

  🛠️ Technologies & Concepts Demonstrated

IP subnetting and VLSM

WAN serial configuration

Dynamic routing protocols (OSPF / RIP)

Hierarchical network design

Redundant topology implementation

Troubleshooting overlapping networks

Enterprise-level IP planning

  🎯 Project Purpose

This lab simulates a real-world scenario such as:

Multi-branch enterprise network

School district WAN

Hospital multi-building infrastructure

Government branch offices

The goal was to design a scalable, redundant, and well-structured routed network.

  🚀 Key Takeaways

Efficient use of /30 for WAN links

Proper separation of WAN and LAN addressing

Redundant ring topology for high availability

Clean hierarchical design ready for future enhancements

Practical routing and subnetting implementation


      **NETWORK DIAGRAM**
<img width="473" height="333" alt="image" src="https://github.com/user-attachments/assets/30e3827d-5054-41ca-b374-6d837e88c7a5" />
<img width="697" height="152" alt="Screenshot 2026-02-22 135012" src="https://github.com/user-attachments/assets/c8d95b34-a5dc-4880-bc78-bb4b407015c6" />





