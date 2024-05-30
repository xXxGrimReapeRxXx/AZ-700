# Lab 1: Create and Configure a Virtual Network (VNet)

## Objective

Understand the creation and configuration of Azure Virtual Networks (VNets), including subnets and IP addressing.

## Steps

1. **Create a VNet with Multiple Subnets**
    - Sign in to the Azure portal: [Azure Portal](https://portal.azure.com/)
    - Navigate to Virtual Networks: In the left-hand menu, select "Create a resource" > "Networking" > "Virtual Network".
    - Create a Virtual Network:
        - **Basics:**
            - Subscription: Select your subscription.
            - Resource group: Create a new resource group or select an existing one.
            - Name: Enter a name for your VNet (e.g., MyVNet).
            - Region: Select the region where you want to create the VNet.
        - **IP Addresses:**
            - IPv4 address space: Enter the address space (e.g., 10.0.0.0/16).
            - Subnets:
                - Subnet 1: Name: Subnet1, Address range: 10.0.1.0/24
                - Subnet 2: Name: Subnet2, Address range: 10.0.2.0/24
        - **Security:** Leave defaults or configure as needed.
        - **Tags:** Optionally add tags for organization.
        - **Review + create:** Review the settings and click "Create".

2. **Configure IP Addressing and Subnet Delegation**
    - Navigate to the VNet: Go to "Virtual networks" in the left-hand menu, then select your VNet (MyVNet).
    - **Subnets:**
        - Add Subnet: Add additional subnets if needed.
        - Configure subnet delegation: Select a subnet and configure delegation for specific services (e.g., Azure SQL, Azure Container Instances).

3. **Verify Connectivity Between VMs in Different Subnets**
    - **Create Virtual Machines:**
        - Create two VMs, one in each subnet (Subnet1 and Subnet2).
        - Ensure both VMs are in the same resource group and VNet.
    - **Test Connectivity:**
        - Use SSH (Linux) or RDP (Windows) to connect to one of the VMs.
        - Ping the other VM using its private IP address to verify connectivity.

## Documentation

Include the following details in your documentation:

- **VNet and Subnet Configurations:**
    - Screenshots of the VNet creation process.
    - Configuration details of subnets.
- **IP Addressing:**
    - CIDR blocks used.
- **Subnet Delegation:**
    - Screenshots and details of subnet delegation settings.
- **Test Results:**
    - Output of ping tests between VMs.
    - Screenshots or command outputs verifying connectivity.
