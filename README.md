Revised: 3/12/2025
A simulated network with the following features:
WAN Connectivity: Simulates a realistic ISP connection using DHCP services and NAT Overload for "internet" access.
Network Segmentation: VLANs isolate Management, Parent, and untrusted (Child) traffic to reduce attack surface.
Inter-VLAN Routing: Configured Router on a Stick with 802.1Q trunking to manage traffic between vlan segments.
Access Control: Extended ACLs to act as an internal firewall and prevent unneceesary lateral movement from kids to parents devices.
Layer 2 Hardening: Switch ports secured with Port Security + Sticky MAC addresses for physical security.
