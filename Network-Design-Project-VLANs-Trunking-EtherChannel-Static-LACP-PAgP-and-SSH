Technologies Implemented

## VLANs (Virtual LANs)

VLANs were created to segment the network into multiple broadcast domains.

PCs were assigned to specific VLANs for isolation and traffic control.

## Trunking

Configured trunk links between switches to carry multiple VLAN traffic.

Used 802.1Q encapsulation for VLAN tagging.

## EtherChannel (Link Aggregation)
Implemented EtherChannel to provide redundancy and bandwidth aggregation between switches. Three methods were configured:

Static (ON mode): Ports manually bundled into a channel without negotiation.

LACP (Link Aggregation Control Protocol): Used channel-group … mode active for IEEE standard negotiation.

PAgP (Port Aggregation Protocol): Used channel-group … mode desirable for Cisco proprietary negotiation.

Remote Access (SSH & Telnet)

SSH (Secure Shell): Configured for secure encrypted remote access.

Telnet: Configured to demonstrate legacy access methods.

VTY lines were configured to allow both SSH and Telnet.

##  Network Topology

The topology consists of:

2 Switches connected with trunk and EtherChannel links.

4 PCs assigned to different VLANs.

SSH- and Telnet-enabled switch for remote login.

## Configuration Highlights

VLAN creation and assignment to switchports.

Trunking configuration using switchport mode trunk.

## EtherChannel setup:

Static: channel-group 1 mode on

LACP: channel-group 2 mode active

PAgP: channel-group 3 mode desirable

Remote access configuration:

Domain name configured.

RSA keys generated for SSH.

Local user accounts with privilege levels.

Enabled both SSH version 2 and Telnet on VTY lines.

## Results

VLAN segmentation successfully isolated broadcast domains.

Trunking allowed inter-VLAN traffic across switches.

EtherChannel (Static, LACP, and PAgP) increased throughput and redundancy.

Remote access worked through both SSH (secure) and Telnet (legacy).
