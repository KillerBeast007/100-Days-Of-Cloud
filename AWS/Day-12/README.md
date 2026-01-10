# AWS Day 12: Attach Volume to EC2 Instance

## Objective
Connect a previously created EBS volume to a running EC2 instance to provide additional block storage.

## Services Used
- **AWS**: EC2 & EBS

## Key Learnings
- Confirmed that the Volume and the Instance must be in the same Availability Zone to connect.
- Learned that after attaching the volume in the AWS Console, I still need to log into the OS to mount and format the file system (e.g., using lsblk and mkfs).
- Understood the difference between the Root volume (where the OS lives) and Additional volumes (where data lives).