# AWS VPC Setup  

## Steps Performed  
- Created a **custom VPC** with `10.0.0.0/16` IPv4 CIDR block  
- Added **public** and **private subnets** with non-overlapping CIDR ranges  
- Attached an **Internet Gateway** and associated it with the public subnet  
- Created and associated a **Route Table** with proper routes for internet access  
- Configured a **Network Security Group (NSG)** allowing inbound SSH (22) and HTTP (80) traffic  

## Learnings  
- Understood how a **custom VPC** provides granular control compared to the default VPC  
- Learned that **subnet CIDR blocks must not overlap** within a VPC  
- Realized that **Internet access requires both Internet Gateway and Route Table configurations**  
- Gained hands-on exposure to **network isolation** and securing resources with NSGs  

## Usage  
- This **custom VPC** was later used for provisioning **EC2 instances** and experimenting with other AWS services.  
