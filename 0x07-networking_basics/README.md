# Project: 0x07. Networking basics #0
## Search
* [Different types of network](https://intranet.alxswe.com/rltoken/XW3ZGm5Ya_a8XVDXcAKT_A)
1. Types of Area Networks

    Common types of area networks are:

    - LAN: Local Area Network
    - WAN: Wide Area Network
    - WLAN: Wireless Local Area Network
    - MAN: Metropolitan Area Network
    - SAN: Storage Area Network, System Area Network, Server Area Network, or sometimes Small Area Network
    - CAN: Campus Area Network, Controller Area Network, or sometimes Cluster Area Network
    - PAN: Personal Area Network
* [MAC address](https://intranet.alxswe.com/rltoken/j-Wp-YRvFTVP04SpIeRzHQ)
1. What is a MAC Address?

    A Media Access Control (MAC) address is a string of characters that identifies a device on a network. It’s tied to a key connection device in your computer called the network interface card, or NIC. The NIC is essentially a computer circuit card that makes it possible for your computer to connect to a network. A NIC turns data into an electrical signal that can be transmitted over the network.

    IP address ==> Address Resolution Protocol (ARP) ==> MAC address

2. How MAC Addresses Get Assigned

    Some well-known manufacturers of network adapters or NICs are Dell, Belkin, Nortel, and Cisco. These manufacturers all place a special number sequence (called the Organizationally Unique Identifier or OUI) in the MAC address that identifies them as the manufacturer. The OUI is typically right at the front of the address.
* [Private and public address](https://intranet.alxswe.com/rltoken/OPJCZYuWSEXLIZOqU9Uc0A)

    A public IP address is an IP address that can be accessed over the Internet. Like a postal address used to deliver postal mail to your home, a public IP address is the globally unique IP address assigned to a computing device. Your public IP address can be found at [What is my IP Address](https://www.iplocation.net/find-ip-address) page. A private IP address, on the other hand, is used to assign computers within your private space without letting them be directly exposed to the Internet. For example, if you have multiple computers within your home you may want to use private IP addresses to address each computer within your home. In this scenario, your router gets the public IP address, and each of the computers, tablets, and smartphones connected to your router (via wired or Wi-Fi) gets a private IP address from your router via [DHCP](https://www.iplocation.net/dhcp) protocol.
* [OSI model](https://intranet.alxswe.com/rltoken/k2uCsynicuNbu1cAQhXqVQ) - [vedeo](https://www.youtube.com/watch?v=0y6FtKsg6J4)

    The Open Systems Interconnection model (OSI model) is a conceptual model from the International Organization for Standardization (ISO) that "provides a common basis for the coordination of standards development for the purpose of systems interconnection. In the OSI reference model, the communications between systems are split into seven different abstraction layers:

    layer|..
    ---|---
    7 Application layer|SMTP HTTP HTTPS P2P DNS..
    6 Presentation layer| ..
    5  Session layer|..
    4  Transport layer|TCP UDP..
    3  Network layer|IP ICMP ..
    2  Data link layer|ARP VLAN SIP..
    1  Physical layer|Hubs Fiber..
## Resources

#### Read or watch:

* [OSI model](https://intranet.alxswe.com/rltoken/k2uCsynicuNbu1cAQhXqVQ)

* [LAN network](https://intranet.alxswe.com/rltoken/en370-Hrwgi_GUvFcg3bKg)
* [WAN network](https://intranet.alxswe.com/rltoken/Ah1EKqnINR85lM4P2WnLSw)
* [Internet](https://intranet.alxswe.com/rltoken/Lwh9xQxFD4dWh5sIApXI1g)

* [What is an IP address](https://intranet.alxswe.com/rltoken/HaZZvrmGaQ3U7ZLDYgZb6w)

* [IPv4 and IPv6](https://intranet.alxswe.com/rltoken/M8g-egWLlldTl6Y0QECdwA)
* [Localhost](https://intranet.alxswe.com/rltoken/7lj-zoZQ7xFTkj4MTyos_g)
* [TCP and UDP](https://intranet.alxswe.com/rltoken/uJbs8E9-FyATfsELpmtTIg)
* [TCP/UDP ports List](https://intranet.alxswe.com/rltoken/4PYkqDfOvIZZb9aUPGOOzQ)
* [What is ping /ICMP](https://intranet.alxswe.com/rltoken/3zBgO6r2M1Q8lUVt9g8aJw)
* [Positional parameters](https://intranet.alxswe.com/rltoken/U5CMxsErz85edWap3fNEoQ)
## Learning Objectives

### General

* What it is
* How many layers it has
* How it is organized
## Tasks

| Task | File |
| ---- | ---- |
| 0. OSI model | [0-OSI_model](./0-OSI_model) |
| 1. Types of network | [1-types_of_network](./1-types_of_network) |
| 2. MAC and IP address | [2-MAC_and_IP_address](./2-MAC_and_IP_address) |
| 3. UDP and TCP | [3-UDP_and_TCP](./3-UDP_and_TCP) |
| 4. TCP and UDP ports | [4-TCP_and_UDP_ports](./4-TCP_and_UDP_ports) |
| 5. Is the host on the network | [5-is_the_host_on_the_network](./5-is_the_host_on_the_network) |