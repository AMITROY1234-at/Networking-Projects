# Modern Hotel Network Design and Implementation

## Project Overview

This project presents the design and implementation of a three-floor hotel network using Cisco Packet Tracer. The network connects different departments across all three floors and provides communication between all devices.

## Network Design

The network consists of three routers, one switch per floor, wireless networks, PCs, laptops, phones, printers, and a dedicated IT department.

### Departments & VLANs

| Floor | Department | VLAN | Network |
|------|------------|------|---------|
| 1st Floor | Reception | 80 | 192.168.8.0/24 |
| 1st Floor | Store | 70 | 192.168.7.0/24 |
| 1st Floor | Logistics | 60 | 192.168.6.0/24 |
| 2nd Floor | Finance | 50 | 192.168.5.0/24 |
| 2nd Floor | HR | 40 | 192.168.4.0/24 |
| 2nd Floor | Sales | 30 | 192.168.3.0/24 |
| 3rd Floor | Admin | 20 | 192.168.2.0/24 |
| 3rd Floor | IT | 10 | 192.168.1.0/24 |

## Technologies & Concepts

- Cisco Packet Tracer
- VLAN
- IPv4 Addressing
- OSPF
- DHCP
- Wireless Networking
- SSH
- Port Security
- Sticky MAC
- Serial DCE Connections

## Key Features

- Three routers connecting three floors
- Serial DCE connections between routers
- Department-based VLAN segmentation
- OSPF dynamic routing
- DHCP configured on the respective routers
- Wireless connectivity for laptops and phones
- Printer for each department
- SSH remote login on all routers
- Port security on the IT department switch
- Sticky MAC address learning
- Shutdown violation mode
- Network-wide device communication

## Testing & Verification

- Tested communication between different departments
- Verified OSPF routing
- Verified DHCP address assignment
- Tested SSH remote login using Test-PC
- Tested port security on the IT department switch

## Network Topology

![Modern Hotel Network Topology](modern-hotel-topology.png)

## Project File

Open the `.pkt` file using Cisco Packet Tracer to explore the complete network topology and configurations.

## Tools Used

- Cisco Packet Tracer 9.0
- Cisco Routers & Switches
- PCs
- Laptops
- Smartphones
- Servers
- Wireless Access Points
- Printers
