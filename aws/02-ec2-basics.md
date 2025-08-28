# AWS EC2 Basics  

## Steps Performed  
- Launched **EC2 instances** using both **Amazon Linux** and **Ubuntu AMIs**  
- Selected **t2.micro** instance type (Free Tier)  
- Connected via:  
  - **SSH key pair** (`.pem` file)  
  - **EC2 Instance Connect** (browser-based)  
- Attached the default **8 GB EBS volume**  
- Configured **Security Group** with inbound rules for **SSH (22)** and **HTTP (80)**  
- Created a **Launch Template** from a configured EC2 instance for easier replication  

## Commands Used  
```bash
# Fix permissions for SSH key
chmod 400 my-key.pem  

# Connect to EC2 instance
ssh -i "my-key.pem" ec2-user@<public-ip>  
```

Learnings

EBS volumes persist even after EC2 termination (unless deleted on termination)

Understood the difference between Running, Stopped, and Terminated states

Learned how to take Snapshots and reuse them for recovery/backup

Got familiar with Launch Templates for replicating consistent environments