# Azure Day 11: Change Azure Virtual Machine Size Using Console

## Objective
Manually scale a virtual machine's CPU and RAM to handle changing workloads.

## Services Used
- **Azure**: Azure Virtual Machines (Size settings).

## Key Learnings
- Realized that changing the size (e.g., from Standard_B1s to Standard_B2s) triggers a restart of the VM.
- Learned that not all sizes are available in every region or for every hardware series.
- Compared this to AWS Day 7; the process is conceptually identical (Vertical Scaling), but Azure’s interface lists hundreds of specific "Sizes" to choose from.
