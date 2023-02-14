# fortinet-in-2-tiers-architecture-bank

Our network topology architectures (2-tiers) on which I worked with Imane Mallach.

The most important tasks performed for this topology are:

*** Access Layer Switches:
-VLAN, Portfast, Trunk and access ports.

***reduce main switches:
-Per VLAN Spanning Tree (pvstp)
- Virtual Routing and Forwarding (VRF)
-VLAN Interfaces
-IP subnet
- Hot Standby Router Protocol (Hsrp)
-static routing to connect between vrfs
-VLAN, Portfast, Trunk ports, static EtherChannel and lacp.

***FortiGate:
-VLAN Interfaces
- port management
-sd-wan interfaces
-Performance SLA
- static route
- high availability
-firewall policy.

***windows server:
-DHCP Server

