# Azure Day 15: Create and Configure Network Security Group (NSG)

## Objective
Create a virtual firewall to filter network traffic to and from Azure resources in a virtual network.

## Services Used
- **Azure**: Azure Networking (NSG)

## Key Learnings
- Learned that NSG rules are processed based on priority (lower numbers are processed first).
- Discovered that NSGs contain default security rules that cannot be deleted, but can be overridden by higher-priority custom rules.
- Practiced the "Principle of Least Privilege" by only opening Port 22 (SSH) for specific IP ranges rather than the entire internet.