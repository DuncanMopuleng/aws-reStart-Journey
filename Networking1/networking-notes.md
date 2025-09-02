# NETWORKING
Networking is described as a way of computers to communicate with each other and share resources of the network
### How do they communicate
Computers share resource differently; They use differerent modes such as LAN, WAN, MAN, PAN and WLAN to communicate and share resources over a defined medium. This medium can be defined as layouts or shapes, this is show how they are physically and logically connected. They are called **Topologies** in networking field. They can be listed as bus, star, ring, mesh, hybrid. Further more there is what we call **Management models**. This is to show how devices interact and share resources (client–server vs peer-to-peer).

### Internet Protocol (IP)
Defined as rules for sending data across networks.<br>
IP Address: Unique number for each device; written in dotted-decimal (e.g., 192.168.1.1).<br>
**IP Classes:**<br>
Class A → Large networks <br>
Class B → Medium networks<br>
Class C → Small networks<br>
**Binary Conversion:** Change each decimal part (0–255) into 8-bit binary.<br>
**Port Numbers:** Identify specific apps/services (e.g., HTTP → 80, HTTPS → 443).<br>
**In short:** IP identifies devices, classes organize them, binary shows bits, ports connect apps.

## AWS VPC
In Amazon Web Services, there is what we call a VPC for networking. VPC allows users to create a private, isolated section of the AWS Cloud where you can launch and run your resources securely.

AWS VPC has services that allows networking and content delivery services; 
Categorize them like this


### Key Features

Isolation → Your VPC is separate from other customers. <br>

Subnets → Divide your VPC into smaller networks (public and private).

IP Addressing → You choose your own IP range (IPv4/IPv6).

Routing → Control traffic flow with route tables.

Security → Use Security Groups (stateful) and Network ACLs (stateless).

Connectivity → Connect VPCs to the internet, other VPCs, or on-premises networks (via VPN or Direct Connect).

## Why Use VPC?

1. Host web apps (public subnet) and databases (private subnet) securely.

2. Control who can access what with firewall rules.

3. Extend your company’s data center into the cloud.

In AWS, there are services allows networking and content delivery services. <br>

### **Categorize them like this;**
AWS Networking & Connectivity Services

**VPC-related & Network Monitoring:** Flow Logs, Peering, Endpoints, Transit Gateway, PrivateLink.<br>
**Connectivity to On-Premises:** VPN, Direct Connect <br>
**Traffic & Load Management:** Elastic Load Balancing, Global Accelerator <br>
**DNS & Domain Services:** Amazon Route 53 <br>

## AWS Content Delivery

**CDN & Acceleration:** CloudFront, Content Delivery Network

### Defination of VPC Service

Flow Logs: Track VPC network traffic. <br>
Peering: Connect two VPCs privately. <br>
Endpoints: Private access to AWS services. <br>
Virtual Private Network (VPN): Secure connection to AWS over internet. <br>
Direct Connect: Dedicated private network to AWS. <br>
PrivateLink: Private service access without internet. <br>
Transit Gateway: Central hub connecting multiple VPCs. <br>
Global Accelerator: Improve global app performance. <br>
Content Delivery Network (CDN): Fast content delivery worldwide. <br>
CloudFront: AWS CDN service. <br>
Elastic Load Balancing (ELB): Distribute traffic across servers. <br>
Amazon Route 53: Domain registration & DNS service. <br>
