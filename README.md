# VLAN Network Setup with Inter-VLAN Routing

## Project Overview
This project demonstrates how to configure VLANs and enable inter-VLAN routing on a small office network. It includes configurations for network segmentation and basic access control rules.

## Objectives
- Set up VLANs to segment network traffic.
- Configure inter-VLAN routing for communication between departments.

## Tools Used
- Cisco Packet Tracer
- Cisco Switch model 2960 and Router model 2911

## Configuration
- **HR VLAN (ID: 10)**: `192.168.10.0/24`
- **IT VLAN (ID: 20)**: `192.168.20.0/24`
- **Sales VLAN (ID: 30)**: `192.168.30.0/24`

## Steps
1. Created a network topology with VLANs for HR, IT, and Sales departments.
2. Configured inter-VLAN routing on the router to enable communication between VLANs.
3. Set up basic security rules to restrict unnecessary traffic between VLANs.


## Testing
- Successfully pinged between VLANs, indicating inter-VLAN routing is active.


## Files
- `Diagrams/VLAN_Topology.png`: Diagram of the network setup.
- `Configurations/VLAN_Config.txt`: VLAN configuration commands.
- `Documentation/Project_Report.pdf`: Detailed project documentation.

## Lessons Learned
- The importance of network segmentation for security.
- How to troubleshoot VLAN and routing issues.

