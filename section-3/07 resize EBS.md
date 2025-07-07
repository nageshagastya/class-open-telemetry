### Resize the EBS

Go to AWS > EC2 > Volumes > Modify > Increase the size

Wait for the 'volume state' to become 'In-use'
```
df -h

lsblk

sudo apt install cloud-guest-utils

sudo growpart /dev/xvda 1

lsblk

sudo resize2fs /dev/xdva1

df -h
```
![image](https://github.com/user-attachments/assets/ec8c7f39-f98d-4256-9239-613424d2e6a7)
