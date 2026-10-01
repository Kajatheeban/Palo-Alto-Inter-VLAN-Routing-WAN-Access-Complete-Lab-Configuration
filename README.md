## 🎥 YouTube Tutorial

Watch the full lab tutorial on YouTube:

[▶️ Watch the Video on YouTube](https://youtu.be/x3fYjc25J5g?si=qnKjJmg6i3k0d6Hc)


# Palo-Alto-Inter-VLAN-Routing-WAN-Access-Complete-Lab-Configuration
Palo Alto Firewall lab with 3 PCs in 3 VLANs. Learn VLANs, Inter-VLAN routing, security policies, WAN connectivity, and Source NAT. Includes connectivity testing between VLANs and the WAN using EVE-NG. A practical lab for networking, firewall, and cybersecurity learners.  #PaloAlto #VLAN #Networking #CyberSecurity #EVE-NG

# Palo Alto Firewall – Inter-VLAN Routing & WAN Connectivity Lab

A practical **Palo Alto Networks firewall lab** built in **EVE-NG** to demonstrate VLAN segmentation, Inter-VLAN routing, security policies, Source NAT, and WAN connectivity.

## 📌 Lab Overview

This lab consists of **3 PCs connected to 3 separate VLANs**, with a Palo Alto firewall performing Layer 3 routing and security enforcement.

The main objectives are:

* Configure multiple VLANs
* Configure Palo Alto Layer 3 subinterfaces
* Implement Inter-VLAN routing
* Allow communication between different VLANs
* Configure security policies
* Configure Source NAT
* Provide WAN connectivity
* Allow internal PCs to access the external WAN
* Test and troubleshoot network connectivity

## 🗺️ Lab Topology

```text
                    WAN / Internet
                          |
                          |
                    [Palo Alto]
                          |
                    802.1Q Trunk
                          |
                       [Switch]
                    /      |      \
                   /       |       \
               VLAN 101   VLAN 102   VLAN 103
                  |         |         |
                PC-1      PC-2      PC-3
```

## 🔧 Lab Components

| Device             | Purpose                          |
| ------------------ | -------------------------------- |
| Palo Alto Firewall | Routing, Security Policies & NAT |
| Layer 2 Switch     | VLAN configuration and trunking  |
| PC-1 / VPCS        | VLAN 101 client                   |
| PC-2 / VPCS        | VLAN 102 client                   |
| PC-3 / VPCS        | VLAN 103 client                   |
| EVE-NG             | Network emulation platform       |


