# Enterprise-Network-project[README.md](https://github.com/user-attachments/files/27305149/README.md)
# Enterprise VLAN Network Project

## Overview

This project demonstrates a multi-VLAN enterprise network built in Cisco Packet Tracer.

## Features

* VLAN segmentation (10, 20, 30, 40)
* Inter-VLAN routing (Router-on-a-Stick)
* DHCP configuration for all VLANs
* DNS server implementation
* SSH secure remote management
* ACL restricting management access to IT VLAN only

## VLAN Structure

* VLAN 10 – Servers → 192.168.1.0/24
* VLAN 20 – Sales → 192.168.2.0/24
* VLAN 30 – HR → 192.168.3.0/24
* VLAN 40 – IT → 192.168.4.0/24

## Security

* SSH enabled on all switches and router
* Access Control Lists restrict administrative access to VLAN 40 only

## Diagram

![Network Diagram](network-diagram.png)

## Files

* `enterprise-vlan-network.pkt` – Packet Tracer project file
* `network-diagram.png` – Network diagram
