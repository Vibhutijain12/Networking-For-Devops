
# Networking Concepts

#### Chapter 1 - 
###### 1. IP Address
###### 2. Subnets
###### 3. Ports 
###### 4. CIDR




#### 1️⃣ IP Address:  
An IP address is a unique numerical label for a device on a network, like a digital home address, that enables communication and data exchange.

It identifies your device and helps route data in small packets across the internet or a local network. There are two main versions, IPv4 and the newer IPv6, and types such as public, private, static, and dynamic. 


#### How an IP address works

#### 1. Unique Identification: 
Every device, from a computer to a smartphone or smart toy, is assigned an IP address to be uniquely identified on a network.

#### 2. Communication: 
The Internet Protocol (IP) defines how data is transmitted. When you send information, it's broken into packets, and each packet includes the source and destination IP addresses, allowing it to be correctly routed.

#### 3. Data Routing: 
Routers use these addresses to ensure that packets of data reach their destination. 


#### Types of IP addresses

#### 1.Public IP: 
Your network's main gateway to the internet, typically assigned by your Internet Service Provider (ISP).

#### 2.Private IP: 
An address assigned to devices within a private network, like your home or office, and managed by the router.

#### 3. Static IP: 
An address that is manually configured and remains constant.

#### 4. Dynamic IP: 
An address that is automatically assigned by a router and can change over time. 

#### 2️⃣  Subnets: 

1. A subnet (subnetwork) is a smaller, logical section of a larger network.
2. It is created by dividing an IP network into multiple parts using a subnet mask.

#### Purpose:

1. Reduce broadcast traffic
2. Organize network logically
3. Improve security

#### Types of Subnets:

#### ✅ 1. Public Subnet:
A subnet that has a route to the internet through an Internet Gateway (IGW)

Example:
An EC2 instance with a public IP in a public subnet can be accessed from the Internet.

#### ✅ 2. Private Subnet
A subnet without direct internet access.
It does not route traffic to an Internet Gateway.

#### 3️⃣ CIDR (Classless Inter-Domain Routing):

CIDR, or Classless Inter-Domain Routing, is a method of IP address allocation that provides a more flexible and efficient way to assign IP addresses and manage network routing.

#### 4️⃣ Ports:

Ports are virtual endpoints used by devices to send and receive data, identified by unique numbers that direct traffic to specific applications or services.

Range: 0 – 65535

Well-known: 0–1023 (HTTP, HTTPS, FTP, SSH)

#### Purpose:
Allows multiple services to run on same IP.
