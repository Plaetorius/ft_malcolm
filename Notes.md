# ft_malcom
- Man In the Middle attack (MITM):
- Address Resolution Protocol (ARP): 
- ARP Spoofing / Poisoning:
- Network: group of devices connected together. Includes computers, servers, cameras... anything connected with something else.
- Vulnerability: weakness (misconfiguration, logic flaw, overlook...) in an information system, system security procedures, internal controls, or implementations that could later be **exploited** by a threat source
- Exploit: program, or piece of code, designed to find or take advantage of a **vulnerability** in an application, network, computer system... typically for malicious purposes, such as installing a malware (payload). An exploit is a way to deliver a malware into the target system
- MAC Address: Medium Access Control. Unique and permeable identifier of a device (like human fingerprints). 

# Basics


## Network Addresses
Network Addresses can be all kind of addresses, but here we mainly need to look at **IP and MAC Addresses**.
IP Address used to temporarly identify a host on a network. It is composed of 4 groups of 8 bits (8 bits being an octet):
0b`11111111.11111111.11111111.11111111` is `255.255.255.255`.
The IP address is calculating using **IP Addressing & Subnetting**. 

### Types
- Broadcast address: transmit to all addresses on the network. Message sent on it may be received by all addresses
    - Network Layer communication: may be a specific IP Address (often `255.255.255.255` (all-one value))
    - Data Link Layer on Ethernet netowrks: may be a specific MAC Address  
- Multicast address: transmit to a certain group of addresses on the network. 
- Unicast address: transmit to a single address on the network

# Sources
[Exploit definition](https://www.cisco.com/c/en/us/products/security/advanced-malware-protection/what-is-exploit.html)

[Vulnerability definition](https://csrc.nist.gov/glossary/term/vulnerability)

[RFC 826 - ARP](https://datatracker.ietf.org/doc/html/rfc826)

[THM Network Fundamentals](https://tryhackme.com/module/network-fundamentals)

[MAC Table / Forwarding information base](https://en.wikipedia.org/wiki/Forwarding_information_base)

[OSI Model](https://en.wikipedia.org/wiki/OSI_model)

[OSI Model - Level 2 Data Link](https://en.wikipedia.org/wiki/Data_link_layer)

[Network switch](https://en.wikipedia.org/wiki/Network_switch)

[THM L2 Mac Flooding & ARP Spoofind](https://tryhackme.com/r/room/layer2)

[MAC Address](https://en.wikipedia.org/wiki/MAC_address)

[UID](https://en.wikipedia.org/wiki/Unique_identifier)

[Network Interface Controller](https://en.wikipedia.org/wiki/Network_interface_controller)

[Network Address](https://en.wikipedia.org/wiki/Network_address)

[Network Segment](https://en.wikipedia.org/wiki/Network_segment)

[IP Addressing & Subnetting](https://www.techopedia.com/6/28587/internet/8-steps-to-understanding-ip-subnetting#:~:text=IP%20Address%3A%20A%20logical%20numeric,floor%2C%20building%20or%20geographical%20location)