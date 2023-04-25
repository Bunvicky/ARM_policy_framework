Policy definition:
IPaddy_control
 This ARM template creates a policy definition that prohibits the creation of public IP addresses for virtual machines in a specific resource group.

Compliance
policy definitions:
 no-public-ip-vm, secure-connection, and restricted-ports. These policy definitions enforce compliance with regulatory requirements related to network security and access control.
 
 powershell 
 the policy definition requires that storage accounts use encryption for data at rest. The policy is assigned to a specific storage account, but it can also be assigned at the subscription or resource group level to enforce compliance across all resources.