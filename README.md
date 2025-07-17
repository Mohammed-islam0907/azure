# Azure


## Benefits of High Availability and Scalability in the Cloud

- High availablility - multiple instances spread over different blast radiuses
- elasticity: 
    - vertically scale: "making bigger" - adding more memory, CPU etc. - means you'd have to stop services = downtime 
    - horizontally scale: Adding/removing instances - no downtime 


## Different Cloud Computing Types

- Public 
- Private (on prem)
- Hybrid (both)

## Differences Between Types of Cloud Computing

- revisit 

## Benefits and Usage of Resource Groups

- Azure doesn't manage components 
- Anything created in Azure portal = Azure resource 
- Resources share lifecycle - provisioned/deprovisioned together  
- RBAC - Role based access control - can give permissions to a certain 
- IAM - access control - resources inherit permissions
- Tags - Key value pairs

## Benefits and usage of region and region pairs
- Different countries have different rules so having seperate regions allows to adapt to regulations
- Using diferent regions supports in the case of a disaster 
- Region pairs have same regulatory boundaries but 100's miles apart  
- Ensures failiure of one data centre doesn't effect the service running


## Benefits and usage of subscriptions 
- every subscription trusts 1 and only one azure ad tenant
- can apply budget, RBAC, policy - gets inheritied into resource groups and into resources
- can have one or more resource groups in each subscrcritpion


- Hierarchial permissions

## Azure Resource Manager (ARM)
- Used to interact with Azure
- Management and deployment construction for Azure 
- JSON template can be used to define resources - can be run as many times

## Azure Arc
- extends control plane of Azure to services outside of Azure


## Compute Services

- Made up of CPU & memory 

 - Fault domains distribute VM's within **availability sets**

 ## Azure Networking Services

 - **Virtual networks**: Isolated, secure environments to run VM's and apps
 - **Virtual network peering**: 2 or more virtual networks connect in Azure
 - Azure VPN Gateway: ensures secure connections between on site infastructure & Azure VN
 - Azure Expressroute: Connection between on site infastructure and Azure datacentre, **without** going over the internet

 ## 

 - Saas - users pay on a subscription basis 