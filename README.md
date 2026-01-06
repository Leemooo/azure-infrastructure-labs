# Azure Infrastructure Labs

## Purpose
Hands-on Azure labs documenting IaaS, Networking, Identity, Security, and Operations. 

## Azure is not:
- A VM hosting platform
- A single datacenter
- Someone else's computer

## Azure is: 
- A global pool of compute, storage, networking
- controlled by software-defined infrastructure
- charged by usage. 
- Operated through APIs first, UI second 

In cloud everything is disposable. If you build something and can't delete then build it again, you don't understand it.

## On-Prem vs Azure

| On-Prem | Azure Environment|
| ------ | ------ |
| DataCenter | Azure Region |
| Rack | Resource Group |
| Physical Server | Virtual Machine |
| VLAN | Virtual Network |
| Firewall | NSG |
| AD | Entra ID |
| Backup Appliance | Azure Backup |

## Definitions

Tenant = Identity boundary

Subscription = Billing and access boundary 

Resource Group = Logical container for related resources

If resources live and die together they belong in the same RG.

