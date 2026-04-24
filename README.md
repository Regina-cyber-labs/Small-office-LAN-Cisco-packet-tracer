# Small Office LAN Simulation using Cisco Packet Tracer

## Project Overview
This project simulates a small office Local Area Network (LAN) built in Cisco Packet Tracer to demonstrate basic network setup, IP addressing, and device communication.

The goal was to configure a simple office network where devices can communicate successfully through a switch and server.

## Network Topology
Devices used in this simulation:

- 2 PCs
- 2 Laptops
- 1 Server
- 1 Switch

The switch serves as the central connection point for all devices.

## Configuration Tasks Performed
### 1. Device Setup
- Added all end devices and connected them to the switch.
- Built a star topology for local communication.

### 2. IP Address Assignment
Assigned IP addresses manually to each device to enable connectivity.

Example structure used:

| Device | IP Address |
|--------|------------|
| PC0 | 192.168.1.10 |
| PC1 | 192.168.1.11 |
| Laptop0 | 192.168.1.12 |
| Laptop1 | 192.168.1.13 |
| Server | 192.168.1.50 |

## Connectivity Testing
Connectivity was verified using ping (ICMP).

Tests performed:
- PC0 → Laptop1 ✅ Successful
- PC1 → Laptop0 ✅ Successful
- PCs and Laptops → Server ✅ Successful

Sample evidence included for PC0 to Laptop1 ping success.
Additional device connectivity was tested but not all simulations were captured.


## Simulation Mode Analysis
Packet Tracer simulation mode was used with event filters for:
- ARP
- ICMP

Observed process:
1. ARP request resolved MAC addresses.
2. ICMP Echo Request sent.
3. ICMP Echo Reply received.
4. End-to-end communication confirmed.

## Challenges Encountered
- Simulation event filters sometimes displayed incomplete or excessive events when testing multiple devices.
- Some later pings did not show packet events clearly in simulation mode, though connectivity was still verified through successful pings.

## Skills Demonstrated
- Basic LAN Design
- Cisco Packet Tracer
- IP Addressing
- Switch-based Networking
- ARP and ICMP Troubleshooting
- Network Connectivity Testing

## Tools Used
- Cisco Packet Tracer

## Project Outcome
Successfully created a functioning small office LAN where all configured devices could communicate with one another and access the server.

## Future Improvements
Planned enhancements:
- Add DHCP configuration
- Add router for inter-network communication
- Implement VLAN segmentation
- Configure basic network security controls

## Files
- network-topology.jpeg 1
- network-topology.jpeg 2
