# AWS EC2 Basics  

## Steps Performed
- Launched EC2 with Amazon Linux + Ubuntu AMIs  
- Used **t2.micro** instance (Free Tier)  
- Connected via **SSH key pair** and **EC2 Instance Connect**  
- Attached 8GB EBS volume  
- Configured **Security Group** for SSH (22) + HTTP (80)

## Commands
```bash
chmod 400 my-key.pem
ssh -i "my-key.pem" ec2-user@<public-ip>
