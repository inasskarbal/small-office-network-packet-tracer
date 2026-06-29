🏢 Office Network Design using Cisco Packet Tracer
Overview
This project simulates a small office network using Cisco Packet Tracer.
The objective was to connect two departments (Accounts and Delivery) while assigning appropriate IP addresses, configuring network devices, and verifying end-to-end connectivity.

Objectives
Design a small office network
Connect the Accounts and Delivery departments
Configure routers and switches
Assign IPv4 addresses
Configure default gateways
Verify connectivity using ICMP (ping)

Network Topology
![Topology](Screenshots/topology.png)

NETWORK REQUIREMENTS
| Requirement                                 | Status |
| ------------------------------------------- | ------ |
| Two departments                             | ✅      |
| At least 2 PCs per department               | ✅      |
| Appropriate router and switch configuration | ✅      |
| IPv4 addressing                             | ✅      |
| Proper cabling                              | ✅      |
| End-to-end connectivity                     | ✅      |

IP Addressing
| Device | Interface | IP Address   |
| ------ | --------- | ------------ |
| Router0| G0/0      | 192.168.40.1 |
| Router0| G0/1      |192.168.40.129|
| PC0    | NIC       | 192.168.40.2 |
| PC1    | NIC       | 192.168.40.3 |
|Printer0| NIC       | 192.168.40.4 |
| PC2    | NIC       |192.168.40.130|
| PC3    | NIC       |192.168.40.131|
|Printer1| NIC       |192.168.40.132|

Connectivity Test
The network was tested using ICMP ping.
Successful communication was verified between the Accounts and Delivery department PCs.
![test](Screenshots/test.png)

Skills Demonstrated
Cisco Packet Tracer
Router configuration
Switch configuration
IPv4 addressing
Default gateway configuration
Basic network troubleshooting
CLI commands

Project Files
| File                                 | Description                 |
| ------------------------------------ | --------------------------- |
|small-office-network-packet-tracer.pkt| Cisco Packet Tracer project |
| topology.png                         | Network topology            |
| test.png                             | Connectivity verification   |
| router-cli.png                       | Router configuration        |

Future Improvements
VLAN implementation
DHCP server
Inter-VLAN Routing
ACLs
Dynamic Routing (OSPF)
