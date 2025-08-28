# AWS VPC Setup  

## Steps Performed
- Created a **custom VPC** (10.0.0.0/16 CIDR block)
- Added **public** and **private subnets**
- Configured **Internet Gateway** for public subnet
- Created **Route Table** and associated it with subnets
- Attached a **Network Security Group (NSG)** with SSH + HTTP allowed

## Learnings
- How custom VPC differs from default VPC
- Subnet IP ranges must not overlap
- Internet Gateway + Route Table = public internet access
