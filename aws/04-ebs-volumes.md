# AWS EBS Volumes  

## Steps Performed
- Created additional EBS volume (20GB)  
- Attached to running EC2  
- Mounted new volume under `/mnt/data`  
- Tested persistence after reboot  

## Commands
```bash
lsblk
sudo mkfs -t ext4 /dev/xvdf
sudo mkdir /mnt/data
sudo mount /dev/xvdf /mnt/data
```

##Learnings

Newly attached EBS volumes must be formatted & mounted

Volumes can move between instances in the same AZ
