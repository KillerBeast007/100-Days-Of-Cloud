# AWS Day 15: Create Volume Snapshot

## Objective
Capture a point-in-time backup of an EBS volume to ensure data can be restored if the original volume is lost or corrupted.

## Services Used
- **AWS**: EBS (Snapshots)

## Key Learnings
- Learned that snapshots are incremental backups; only the blocks that have changed since the last snapshot are saved, which saves storage costs
- Realised that while EBS volumes are tied to a specific Availability Zone, snapshots are stored in Amazon S3, making them highly durable and accessible across the entire region.
- Understood the security value: Snapshots allow for "Disaster Recovery" (DR) by providing a clean state to roll back to after a security incident.