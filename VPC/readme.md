**VPC**

![image](https://github.com/udaymurthy1319/AWS-DevOps-My-Understanding/assets/77770749/752ae1b9-aa74-4d64-a5a9-34e672168083)

**Simple Flow**:Internet-->Internet gateway--> public subnet--> nLoad Balancer (Create target of application)--> Route Table(will be in subnet)--> Security Group(particular IP address or port number)-->Private Subnet\
**Opposite flow** with the help of NAT Gateway(Mask private address of server/ application with load balancer(SNAT) or router(Nat Gateway)).

**VPC**: Virtual Private Cloud is a virtual network infrastructure used in cloud computing environments to provide a logically isolated section of the cloud where you can launch resources such as virtual machines, databases, and other services.

**Subnets** : Subnetworks, are divisions of an IP network that define a range of IP addresses. In the context of cloud computing and networking, subnets play a crucial role in organizing and segmenting an IP address space. 

**IP addressing**: 
IP addressing is a fundamental aspect of computer networking that involves assigning unique numerical addresses to devices connected to a network. The two main versions of IP addressing are IPv4 (Internet Protocol version 4) and IPv6 (Internet Protocol version 6). there are two types: IPV4 & IPV6. IPV4- 32 bit; IPV6- 128 bit.

**Network Access Control List (NACL)**:  Network Access Control List (NACL) is a set of rules that control traffic at the subnet level. NACLs act as stateless firewalls and are associated with subnets in a Virtual Private Cloud (VPC) on cloud platforms such as Amazon Web Services (AWS).

**Security Group**: Acts as a virtual firewall for your instances to control inbound and outbound traffic. 

**Routing**: Routing refers to the process of determining the path that data packets should follow to reach their destination in a computer network. This involves making decisions based on routing tables, which contain information about the network topology and the available paths to different destinations. Routing is a critical function in networking that enables communication between devices across local and wide-area networks.

**Gateways and endpoints**: A gateway is a network node that serves as an entry or exit point for data traffic between different networks. It acts as a bridge that connects networks with different communication protocols or architectures. An endpoint refers to a device or node that is a source or destination of data communication within a network. 

**VPC Flow Logs**: Flow logs capture information about the traffic flowing in and out of a VPC. Flow logs provide detailed data that can be useful for various purposes, including network monitoring, troubleshooting, security analysis, and compliance auditing.

**VPN connections**: VPC peering allows the connection of two VPCs within the same region, enabling them to communicate with each other as if they were on the same network. It's a one-to-one relationship, and traffic between peered VPCs stays within the AWS network.





