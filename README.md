# Basic Labs for AZ-700 Preparation

## Design and Implement Core Networking Infrastructure

### Create and Configure a Virtual Network (VNet)
**Objective**: Understand the creation and configuration of VNets, subnets, and IP addressing.

**Steps**:
1. Create a VNet with multiple subnets.
2. Configure IP addressing and subnet delegation.
3. Verify connectivity between VMs in different subnets.

**Documentation**: Include VNet and subnet configurations, and test results.

### Configure Name Resolution Using Azure DNS
**Objective**: Learn to configure DNS settings for VNets.

**Steps**:
1. Create a private DNS zone.
2. Link the DNS zone to a VNet.
3. Create DNS records and verify resolution.

**Documentation**: Document DNS zone setup, linking process, and resolution tests.

### Implement VNet Peering
**Objective**: Enable connectivity between VNets using VNet peering.

**Steps**:
1. Create two VNets.
2. Set up VNet peering between the two VNets.
3. Verify connectivity between VMs in different VNets.

**Documentation**: Include steps for setting up peering and connectivity tests.

### Implement a NAT Gateway
**Objective**: Understand how to configure and use a NAT gateway for outbound internet access.

**Steps**:
1. Create a NAT gateway.
2. Associate the NAT gateway with a subnet.
3. Test outbound internet access from a VM in the subnet.

**Documentation**: NAT gateway configuration, subnet association, and test results.

### Monitor Network Health Using Azure Network Watcher
**Objective**: Learn to use Network Watcher for network diagnostics and monitoring.

**Steps**:
1. Enable Network Watcher.
2. Use tools like Connection Monitor, IP Flow Verify, and Network Security Group (NSG) flow logs.

**Documentation**: Steps for enabling and using Network Watcher, sample outputs.

## Design, Implement, and Manage Connectivity Services

### Set Up a Site-to-Site VPN Connection
**Objective**: Configure a secure VPN connection between an on-premises network and an Azure VNet.

**Steps**:
1. Create a virtual network gateway.
2. Configure a local network gateway.
3. Establish a site-to-site VPN connection.
4. Verify connectivity.

**Documentation**: Detailed steps for setting up and verifying the VPN connection.

### Implement a Point-to-Site VPN Connection
**Objective**: Enable secure remote access to an Azure VNet.

**Steps**:
1. Create a virtual network gateway.
2. Configure point-to-site VPN settings.
3. Download and configure VPN client.
4. Verify remote access connectivity.

**Documentation**: Steps for creating and configuring the VPN, client setup, and test results.

### Configure Azure ExpressRoute
**Objective**: Establish a private connection between an on-premises network and Azure using ExpressRoute.

**Steps**:
1. Create an ExpressRoute circuit.
2. Configure private and Microsoft peering.
3. Connect a VNet to the ExpressRoute circuit.
4. Verify connectivity.

**Documentation**: ExpressRoute configuration details, peering setup, and connectivity tests.

## Design and Implement Application Delivery Services

### Set Up an Azure Load Balancer
**Objective**: Distribute network traffic across multiple VMs.

**Steps**:
1. Create an Azure Load Balancer.
2. Configure backend pools and health probes.
3. Create load balancing rules.
4. Test traffic distribution.

**Documentation**: Load Balancer setup, backend pool configuration, and test results.

### Configure Azure Application Gateway
**Objective**: Implement an Application Gateway for HTTP(S) traffic.

**Steps**:
1. Create an Application Gateway.
2. Configure backend pools, HTTP settings, listeners, and rules.
3. Implement WAF policies.
4. Test HTTP(S) traffic and WAF rules.

**Documentation**: Application Gateway setup, configurations, and test outcomes.

## Design and Implement Private Access to Azure Services

### Implement Azure Private Link and Private Endpoints
**Objective**: Securely connect to Azure services using Private Link.

**Steps**:
1. Create a private endpoint for an Azure service.
2. Configure DNS settings for the private endpoint.
3. Verify private connectivity to the service.

**Documentation**: Steps for creating and configuring private endpoints, DNS setup, and connectivity tests.

### Configure Service Endpoints
**Objective**: Enable secure access to Azure services using service endpoints.

**Steps**:
1. Enable service endpoints on a subnet.
2. Configure service endpoint policies.
3. Test access to Azure services.

**Documentation**: Service endpoint configuration, policy setup, and test results.

## Design and Implement Azure Network Security Services

### Create and Configure Network Security Groups (NSGs)
**Objective**: Control inbound and outbound traffic to Azure resources.

**Steps**:
1. Create an NSG.
2. Define and associate NSG rules.
3. Apply NSG to a subnet or network interface.
4. Verify traffic filtering.

**Documentation**: NSG creation, rule configuration, and test outcomes.

### Implement Azure Firewall
**Objective**: Secure network traffic with Azure Firewall.

**Steps**:
1. Create an Azure Firewall.
2. Configure firewall rules and policies.
3. Test traffic filtering and logging.

**Documentation**: Azure Firewall setup, rule configurations, and test results.

### Deploy a Web Application Firewall (WAF)
**Objective**: Protect web applications using WAF.

**Steps**:
1. Create a WAF on Azure Application Gateway.
2. Configure WAF policies and rules.
3. Test protection against web attacks.

**Documentation**: WAF setup, policy configuration, and test outcomes.

## Additional Tips for Documenting Labs

- **Step-by-Step Instructions**: Provide clear and detailed steps for each lab. Include screenshots and commands where applicable.
- **Diagrams**: Use network diagrams to illustrate the architecture and flow of each lab.
- **Test Cases**: Document test cases and expected outcomes to verify the configurations.
- **Troubleshooting**: Include common troubleshooting tips and how to resolve potential issues.