# Azure Day 13: SSH into an Azure Virtual Machine

## Objective
Establish a secure shell (SSH) connection to a Linux VM in Azure using a private key.

## Services Used
- **Azure**: Azure Virtual Machines & OpenSSH.

## Key Learnings
- Practiced using the ssh -i <private_key_path> user@public-ip command.
- Learned that the Network Security Group (NSG) must have an inbound rule allowing Port 22 for the connection to succeed.
- Confirmed that the private key file (.pem or .key) must have restricted permissions (chmod 400) on the local machine to be accepted by the SSH client.

test