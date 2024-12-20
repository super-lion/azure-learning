**Capital Expenditure (CapEx):** Here we have the concept of being able to completely understand the direction in which a 
company is moving and investing in something that we know will pay out over time. Unfortunately, usually it requires
big investments and large amounts of experience in the industry!

**Operational Expenditure (OpEx):** This is the concept of only paying for what you need, reducing initial investments. 
This is made possible by cloud services that are bordering the concept of infinite resources, which means that we can
easily up or down scale the amount of resources we use and pay for.

**Shared Responsibility Model:** Customer responsibility vs Provider responsibility

|                                             | On Premise |              IaaS              |   Paas   |
|---------------------------------------------|:----------:|:------------------------------:|:--------:|
| Date<br/>Application                        |  Customer  | Customer with tools from Azure | Customer |
| Runtime<br/>OS                              |  Customer  | Customer with tools from Azure |  Azure   |
| H/V -VM<br/>Compute<br/>Network<br/>Storage |  Customer  |             Azure              |  Azure   |

**Cloud Computing Types:** Public, Private, Hybrid

**Reliability:**
 - Auto Healing - redeploying a VM onto a new node upon node failure, etc.
 - Storage x3 - replicas on different racks or even availability zones
 - Auto Scaling - maintaining a level of performance to meet expected user performance
 - SLA (Service Level Agreement) - financially backed commitment from Azure
 - Design for Failure - multiple region design
 - Monitor - application insights

**Predictability:**
 - SKU
   - ACU (Azure Compute Unit) - defined performance units and storage unit that we get
 - Behaviour - known tools and services available
 - Use Templates - to have repeatable actions 
   - Automation
   - DevOps

Some regions are paired and some services will use that pairing automatically: [pairing table](https://learn.microsoft.com/en-us/azure/reliability/cross-region-replication-azure#azure-paired-regions)
![AzurePairingTable.png](AzurePairingTable.png)

