## Networking Concepts

### Chapter 3 - 
#### 1. VPC
#### 2. Components of VPC

### 1. VPC - 

An AWS VPC, or Virtual Private Cloud, is a logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network that you define. It functions like a traditional data center network but offers the scalability of AWS. Key features include control over your IP address ranges, subnets, and routing tables, and the ability to create layers of security. 

### 2. Key components - 

#### 1. IP Address Range (CIDR block):

When you create a VPC, you specify a private IP address range (CIDR block) from which you can assign addresses to subnets and resources within it.

#### 2. Subnets: 

A subnet is a range of IP addresses within your VPC. You can create public-facing subnets (with internet access) and private-facing subnets (without internet access) for your resources, such as EC2 instances.

#### 3. Route Tables: 

These define rules for how network traffic is routed to and from your subnets.

#### 4. Internet Gateway: 

An internet gateway is a component that you attach to a VPC to enable communication with the internet.

#### 5. Security Groups and Network ACLs:

These act as virtual firewalls to control inbound and outbound traffic to your resources at the instance and subnet levels, respectively.

#### 6. VPN Connection: 

You can use AWS Site-to-Site VPN to create a secure, private connection between your corporate data center and your VPC, extending your network into the AWS cloud. 

### How it works
You start by creating a VPC within an AWS Region, defining its IP address range.

Inside the VPC, you create subnets, each of which must reside in a single Availability Zone.

You deploy your resources, like EC2 instances, into these subnets.

You configure route tables to direct traffic, such as an internet gateway for public subnets or a NAT gateway for private subnets to allow outbound internet access.

You use security groups and network ACLs to control access to your instances and subnets. 

<img width="611" height="481" alt="vpc" src="https://github.com/user-attachments/assets/42913dd0-3be1-4f56-b177-b75472992771" />

