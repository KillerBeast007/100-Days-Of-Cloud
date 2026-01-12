# Azure Day 14: Create and Attach Managed Disks in Azure

## Objective
Provision a new Managed Disk and attach it to an existing VM to increase storage capacity.

## Services Used
- **Azure**: Azure Managed Disks & Virtual Machines.

## Key Learnings
- Learned that Managed Disks are the preferred storage solution because Azure handles the underlying hardware availability and scaling for you.
- Confirmed that a disk must be in the same Region as the VM to be attached.
- Understood that after attaching a disk in the Portal, it appears as "Raw" storage to the OS; I still need to use Linux commands (like fdisk and mount) to make it usable for files.