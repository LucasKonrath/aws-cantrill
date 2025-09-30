### Virtual Private Clouds

- Virtual network inside AWS
- Created at region level on an AWS account
- By default is private and isolated, not accessible from outside AZ
- Two types - default VPCs and custom vpcs
- Default VPC max 1 per region, custom VPCs can have many
- Some services assume default VPC is always present
- CIDR is always 172.31.0.0/16
- Each AZ SN is /20
- Has IGW, allows access to/from internet
- Security Group - limit data transfer
- ACL - access control list
- Subnets assign public IPV4 addresses

![alt text](image-1.png)