*This project has been created as part of the 42 curriculum by oait-si-.*

## Description 

This project is a general practical exercise designed to introduce the basics of computer networking. The goal is to learn how to configure IP addresses, connect devices through routers, and understand the role of a gateway within a network by solving 10 non-functioning network levels.

## Instructions 1. 

**Execution:** Download the project files, extract them, and run the index.html file in a web browser. 2. **Browser Requirement:** Use Google Chrome or a Chromium-based browser; Firefox is known to block usage. 3. **Usage:** Enter your intranet login to practice with your personal configuration in the "Training" tab. 4. **Exporting:** Use the **[Get my config]** button to download your configuration once a level is successfully completed.

## Submission Details

To complete the assignment, 10 exported configuration files (one per level) must be placed at the root of the Git repository.


## What I Learned

## Networking Concepts Learned

### TCP/IP
TCP/IP is the fundamental communication model used in modern networks. In NetPractice, IP addresses are used to uniquely identify hosts, while TCP/IP concepts help understand how data is routed between devices across different networks.

### IP Addressing and CIDR
An IP address identifies a device on a network. CIDR notation (e.g. /20, /24) defines how many bits belong to the network and how many to hosts. This was essential to correctly determine network ranges, valid hosts, and broadcast addresses.

### Subnet Mask
The subnet mask separates the network part of an IP address from the host part. Understanding subnet masks allowed proper configuration of devices so they belonged to the same subnet and could communicate.

### Default Gateway
The default gateway is the router interface that allows a host to communicate with devices outside its local network. In NetPractice, incorrect gateway configuration often caused communication failures between networks.

### Routing Table
Routing tables define how packets are forwarded between networks. Routers use them to decide the next hop for a packet. In NetPractice, correct routing entries were required to allow traffic to flow between multiple subnets.

### Routers and Switches
Switches operate at Layer 2 and forward frames within a local network, while routers operate at Layer 3 and connect different networks together. This distinction was crucial when designing functional network topologies.

### OSI Model
The OSI model provides a layered approach to networking. NetPractice mainly focuses on Layer 3 (Network layer), helping reinforce how IP addressing and routing work in practice.


## Resources

* **Networking Concepts Studied:** TCP/IP addressing, subnet masks, default gateways, routers, switches, and the OSI layers.


* **AI Usage:** AI was used as a thought partner to explain complex subnetting logic, troubleshoot "KO" errors (such as "No reverse way" and "Multiple destination hosts match"), and clarify the binary mathematics required for CIDR masks. 

* **References:** 
* [42sp-cursus-netpractice](https://github.com/caroldaniel/42sp-cursus-netpractice): Visual guides and logic for project levels. 
* [NetPractice Walkthrough](https://medium.com/@imyzf/netpractice-2d2b39b6cf0a): Technical breakdown of routing and subnetting. 
* [OSI Model Guide](https://www.imperva.com/learn/application-security/osi-model/): Standard reference for network layer theory.

