
## Networking Concepts

### Chapter 4 - 
##### 1. Security Groups
##### 2. NACLs
##### 3. NAT Gateway

Security groups and NACL both act as virtual firewalls which control the traffic from Inbound and Outbound of the resources. 

#### 1. Security Groups
It performs the function of a virtual firewall, managing the inbound and outbound traffic for one or more Amazon EC2 instances or other AWS services within a VPC.

#### a. Inbound Rules: 
These outline the types of traffic that are permitted to use the resources. It serves as a virtual firewall, controlling the traffic going in and coming out of a VPC for one or more Amazon EC2 instances or other AWS services.

#### b. Outbound Rules: 
It control the traffic that originates from AWS resources, like EC2 instances, and is sent to external destinations. 

They function similarly to inbound rules, specifying the destination IP address, protocol, and port. By default, security groups allow all outbound traffic, but you can create specific rules to restrict or permit outgoing connections to certain IP addresses or services.  

#### c. Protocol: 
A protocol is a collection of guidelines that controls how two devices communicate with one another.

#### 2. NACLs:
Network Access Control List is also a virtual firewall for subnets, which controls the Inbound and Outbound traffic of Subnets. After the creation of VPC, a Default NACL will be associated and allow all Inbound and Outbound Traffic.

In NACL just like Security Groups, it contains set of Inbound and Outbound Rules , that can either allow or deny Traffic into or out of subnets. Since we have option to allow or deny traffic the order of the rules becomes important so that AWS uses a concept of rule number.

#### 3. NAT Gateway: 
NAT Gateway - stands for Network Address Translation. It is a managed AWS service that is scaled based on your usage. 

NAT Gateway will help you to access the internet which instances are configured in the private subnet but without proper routing, no one can access that instance from outside.

### Types of NAT Gateway

#### a. Public: 
NAT Gateway that resides in a public subnet. You can access the internet from the instance which is residing in the private subnet but others cant access this instance which is in the private subnet through the internet without proper routing to the subnets.

#### b. Private: 
Private NAT Gateways are mostly used for communication between VPCs or between VPCs and Transit Gateway. You can't access Elastic IP with the private NAT Gateway.

The main use case of NAT Gateway is to allow you to have Internet access in private subnets of your Virtual Private Cloud. This way your instances still can't be accessed from the Internet but the instances themselves can access the Internet. 
