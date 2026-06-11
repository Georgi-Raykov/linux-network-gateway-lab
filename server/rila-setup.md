# RILA Server Setup

## Role
Gateway server for internal network.

## Interfaces

### enp0s3 (external - NAT)
- Internet access via VirtualBox NAT

### enp0s8 (internal LAN)
- IP: 192.168.50.101/24
- Network: 192.168.50.0/24

## Services
- DHCP Server (dhcpd)
- NAT (firewalld masquerade)
- Routing enabled (ip_forward)

## Firewall Zones
- external → enp0s3
- internal → enp0s8

## Notes
This machine acts as a Linux router between internal network and internet.
