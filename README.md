# network-vlan-project
VLAN network design and inter-VLAN routing project using Cisco Packet Tracer

- Overview - 
This project demonstrates the design and implementation of a segmented network using VLANs in Cisco Packet Tracer. The network simulates a small enterprise environment where different departments are separated into distinct VLANs to improve organization and security.

- Technologies Used - 
Cisco Packet Tracer
VLAN Configuration
Subnetting
Inter-VLAN Routing (Router-on-a-Stick)

- Key Features - 
Created multiple VLANs for network segmentation
Configured trunk links between switch and router
Implemented inter-VLAN routing using subinterfaces
Assigned IP addresses based on subnetting scheme
Verified connectivity across all VLANs

- Testing & Results - 
All devices across different VLANs were able to communicate successfully using ICMP (ping), confirming proper configuration of routing and VLAN segmentation.

- Challenges - 
Initially, an incorrect router model was selected, which caused issues when configuring VLANs through the CLI. To resolve this, I researched the differences between available routers in Cisco Packet Tracer and determined that the Cisco 2911 was the most suitable option for this configuration. Replacing the router allowed for proper VLAN and subinterface configuration.

- Files Included - 
Packet Tracer file (.pkt)
Project documentation
