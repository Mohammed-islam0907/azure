# Azure


## Benefits of High Availability and Scalability in the Cloud

- High availablility - multiple instances spread over different blast radiuses
- elasticity: 
    - vertically scale: "making bigger" - adding more memory, CPU etc. - means you'd have to stop services = downtime 
    - horizontally scale: Adding/removing instances - no downtime 

## Resource Groups

- Azure doesn't manage components 
- Anything created in Azure portal = Azure resource 


## Subscriptions 

- Hierarchial permissions

## Compute Services

- Made up of CPU & memory 

 - Fault domains distribute VM's within **availability sets**

 ## Azure Networking Services

 - **Virtual networks**: Isolated, secure environments to run VM's and apps
 - **Virtual network peering**: 2 or more virtual networks connect in Azure
 - Azure VPN Gateway: ensures secure connections between on site infastructure & Azure VN
 - Azure Expressroute: Connection between on site infastructure and Azure datacentre, **without** going over the internet