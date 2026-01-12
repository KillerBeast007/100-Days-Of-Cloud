# AWS Day 13: Terminate EC2 Instance

## Objective
Permanently delete an EC2 instance to stop incurring costs and clean up the environment.

## Services Used
- **AWS**: EC2

## Key Learnings
- Learned that "Termination" is different from "Stopping"; stopping is like turning off a PC, while termination is like throwing it in a shredder—it cannot be undone.
- Observed that by default, the Root EBS volume is deleted upon termination, but additional data volumes can be preserved if configured otherwise.
- Realised that if "Termination Protection" (which we set on Day 9) is enabled, I must manually disable it before I can successfully delete the instance.