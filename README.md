# branch-office-network-pt

Packet Tracer Project: Multi-Branch Network with Head Office
This project demonstrates a multi-branch network connected to a head office using Cisco Packet Tracer. The network is designed with essential technologies and configurations, making it suitable for understanding enterprise-level networking.

# Project Description

A compact Packet Tracer project featuring two branch offices connected to a head office. It includes VLANs, inter-VLAN routing, OSPF, trunk ports, DHCP, and secure remote management via SSH and SVI. Built for simplicity and scalability, it’s perfect for understanding and practicing enterprise network setups.

## Key Features
1. DHCP: Centralized IP address allocation for devices.
2. OSPF: Dynamic routing protocol for efficient inter-branch communication.
3. VLANs: Logical segmentation of networks within Head Office
4. Inter-VLAN Routing: Communication between VLANs using Layer 3 devices.
5. Trunk Ports: VLAN tagging for inter-switch connections.
6. Static Routing: Manual routing configuration for specific paths.
7. Console and VTY Access: Device management via CLI.
8. SSH: Secure remote management.
9. SVI: Switch Virtual Interface for remote management.
    
## Network Topology
- Branches: Two branches connected to the head office via routers.
- Head Office: Acts as the central hub for communication.

## Technologies Used

| Technology          | Purpose                                          |
|---------------------|--------------------------------------------------|
| DHCP                | Automates IP address assignment.                |
| OSPF                | Enables dynamic and scalable routing.           |
| VLANs               | Enhances security and reduces broadcast.        |
| Inter-VLAN Routing  | Facilitates communication between VLANs.        |
| Trunk Ports         | Supports VLANs across switches.                 |
| Static Routing      | Provides manual routing for specific paths.     |
| Console/VTY Access  | CLI-based device management.                    |
| SSH                 | Secure remote management.                       |
| SVI                 | Remote management for switches.                 |

## Configuration Highlights
### Router Configuration:
- OSPF setup for dynamic routing.
- Static routing for specific paths.
- DHCP server configuration for IP assignment.
### Switch Configuration:
- VLAN creation and inter-VLAN routing.
- Trunk port configuration.
- SVI setup for remote management.
### Management Security:
- SSH enabled for secure VTY access.
- Console and VTY password configurations.

## Files Included
- branch-office-network-pt.pkt: Packet Tracer file for the project.
- Configurations.txt: Device configurations for reference.

## How to Use
1. Open the project file in Cisco Packet Tracer.
2. Simulate network operations by testing DHCP, inter-VLAN communication, and OSPF routing.
3. Access devices remotely using SSH or via console connections.

## Future Improvements
- Integrate more advanced protocols like BGP for larger networks.
- Enhance security with ACLs (Access Control Lists) and port security.
- Implement QoS (Quality of Service) for better traffic management.

## Contributing
Feel free to contribute to this project by submitting pull requests or reporting issues.

## License
This project is licensed under the [MIT License]







