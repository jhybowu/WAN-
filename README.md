
Project Title:
Design and Implementation of a Secure WAN Connection Between Ghana and Cape Verde Branch
Offices
Project Objective:
To design and simulate a secure Wide Area Network (WAN) connection between two branch offices
— the Ghana Office and the Cape Verde Office - using Cisco Packet Tracer. The aim is to ensure connectivity for essential services (HTTP and ICMP) while strictly restricting all other traffic, using appropriate IP addressing and access control measures.
Project Requirements:
1. Topology Design:
o Create two separate branch networks:
Ghana Office
• Cape Verde Office
o Each branch must have exactly four end-user systems (PCs).
o Include a router at each site and connect them using a WAN link.
2. IP Addressing:
o Use CIDR (Classless Inter-Domain Routing) to subnet the IP address space.
• Allocate IP addresses without any excess beyond the number of devices required.
Clearly label IP addresses used at each site (e.g., network ID, broadcast address, and usable host IPs).
3. Connectivity & Services:
Ensure that end-user systems from both branches can communicate with each other using:
•НТТР (TCP Port 80)
• ICMP (Ping)
• Demonstrate connectivity using Ping and a Web Browser (HTTP server must be configured).
4. Security Requirements:
• All traffic other than HTTP and ICMP must be explicitly denied across the WAN.
• Implement and apply Access Control Lists (ACLs) on the routers to enforce this policy.
