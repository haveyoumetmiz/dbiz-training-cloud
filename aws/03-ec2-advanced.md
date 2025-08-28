# AWS EC2 Advanced  

## Steps Performed
- Tried running 2 EC2 instances  
- Stopped one, **detached its EBS volume**  
- Attached the same volume to second instance  
- Verified data persistence  
- Launched **10 EC2s at once** using Launch Template

## Learnings
- Volumes can be re-attached → useful for backup/recovery  
- Launch Templates save **AMI + instance config** for mass deployment
- Cost optimization: multiple small instances vs single large
