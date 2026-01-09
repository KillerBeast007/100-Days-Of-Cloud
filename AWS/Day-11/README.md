# AWS Day 11: Attach Elastic Network Interface (ENI) to EC2 Instance

## Objective
Add a secondary network interface to an EC2 instance to enable multi-homing or network isolation.

## Services Used
- **AWS**: EC2 (Network Interfaces)

## Key Learnings
- Learned that an ENI represents a virtual network card.
- Discovered that the ENI must be in the same Availability Zone as the EC2 instance to be attached.
- Understood that adding a second ENI allows an instance to connect to two different subnets simultaneously.