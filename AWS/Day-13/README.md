# AWS Day 13: Create AMI from EC2 Instance

## Objective
Create a reusable Amazon Machine Image (AMI) from an existing EC2 instance to simplify scaling and backups.

## Services Used
- **AWS**: EC2 (Images & AMIs)

## Key Learnings
- Learned that an AMI captures the state of the root volume and any attached EBS volumes.
- Understood that when creating an AMI, the instance usually reboots to ensure data consistency (though this can be disabled).
- Realized that AMIs are the foundation for Auto Scaling Groups; once you have a "Gold Image," you can launch 100 identical servers in minutes.