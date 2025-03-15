# Microsoft Certified: Azure Fundamentals (AZ-900)

## Microsoft Azure Fundamentals: Describe cloud concepts 

1. Introduction [here](https://learn.microsoft.com/en-gb/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/)


### Introduction
What is Cloud Computing? Cloud computing is where by you do not own/host/buy your own hardware but instead you loan out computing such as compute or storage to a third party cloud hosting platform provider. 
These providers manage the upkeep and costs of the hardware for you so you don't have to.
Because the hardware is part of the third party data centers, they allow you scale vertically as well as horizontally extremely easily by simply requesting more computing services at the touch of a button.

#### Shared Responsibility Model
Is where the cost of maintaining, upgrading, security, replacing of the hardware is shared between the consumer (you) and the cloud provider (Azure) 
- The cloud provider is responsible for physical security, powering and cooling of the hardware, network connectivity and minimum security in the data center itself and maintenance and upgrading of hardware.
- The consumer is responsible for the data within (your) services in the cloud, the security between (your) services and access from outside world .
- Responsibility is shared between the two for cases such as
  - Specific services
    - Using Cloud SQL, the provider is responsible for upkeep/security/versioning of the SQL server, the consumer is responsible for the data in the database.
    - Compared to just renting a Compute server and installing your own version of Oracle SQL on there, instead you are responsible for the upkeep/security/versioning of the SQL database on the server AND the data, but now the provider is only responsible for the upkeep/security of the server.

![img.png](responsibilityModels.png)

##### Infrastructure as a Service (IaaS)
Most responsibility is on the consumer, the provider just provides physical security, power, network connectivity, etc... And you as a consumer can just rent compute on the Infrastructure and do what you want with that.

##### Platform as a Service (PaaS)
Is a middle ground between IaaS and SaaS.

##### Software as a Service (SaaS)
Most responsibility is on the cloud provider, whereby the provider has full responsibility of the entire infrastructure and platform (physical security, power, network connectivity, service uptime, security, versioning, etc...). And you as a consumer just get access to a specific software service which you either pay as you go for or have a membership for.

### Cloud Models

#### Private Cloud
Is an offering by cloud providers to corporations in which corporations get their own private slice of cloud. A single entity will use a private cloud so that they can have greater control over what they will allow their own internal company use within the cloud platform such as services, outside network access, subscriptions, etc... and are able to handle costs at a wider corporate level much easier.
A private cloud can even be deployed onto a corporations own data center.
- Organizations have complete control over resources and security
- Data is not collocated with other organizations’ data
- Hardware must be purchased for startup and maintenance
- Organizations are responsible for hardware maintenance and updates

#### Public Cloud
Is the cloud platform built and controlled by the cloud provider (Azure) in which anyone can access, register, subscribe, pay, etc...
- No capital expenditures to scale up
- Applications can be quickly provisioned and deprovisioned
- Organizations pay only for what they use
- Organizations don’t have complete control over resources and security

#### Hybrid Cloud
Is an environment that uses both public and private cloud options in an interconnected environment.
One example of using a Hybrid cloud is if during running of applications in a private cloud a sudden spike in resources is required and your cloud is interconnected to a public cloud, you can temporarily deploy and make use of the public cloud resources.
A Hybrid cloud user can select what services they want in either the public and private cloud and can choose to reploy into either one depending on their use case.
- Provides the most flexibility
- Organizations determine where to run their applications
- Organizations control security, compliance, or legal requirements

#### Multi Cloud
Is where you use multiple cloud providers to meet your demands either in parallel or temporary for the purpose of migrating from one provider to another.

### Consumption based model
- Capital Expenditure (CapEx)
  - Is typically a one-time upfront cost to purchase some resource such as a building, datacenter, computer, etc...
- Operational Expenditure (OpEx)
  - Is spending money on services or products overtime, renting or leasing something, or purchasing a monthly/yearly membership.

Cloud computing is a form of Operational Expenditure. You're not making a one time payment for something but rather leasing/subscribing to something overtime.

The benefits of this kind of model:
- No upfront costs - so you can quickly and cheaply get started.
- No need to pay/manage infrastructure - so you can direct your costs directly to what it is you need immediately.
- You can pay for more resources when they're needed.
- You can stop paying for resources when they are no longer needed.

Cloud computing is essentially a pay-as-you-go computing service, you rent compute power and storage from someone else’s datacenter and when you're done you can just stop paying, close everything down and don't need to worry about datacenter costs or management.
- Plan and manage your operating costs.
- Run your infrastructure more efficiently.
- Scale as your business needs change.


### End
Now you should be able to answer the following questions:

- What is Cloud Computing
- What is a shared responsibility model
- What are each of these Cloud models
  - Public
  - Private
  - Hybrid
- What are some appropriate use-cases for each cloud model
- What is a consumption-based model
- Compare cloud pricing models

# Azure Products
## Cloud Models
- Azure Arc - A set of technologies that helps you manage your cloud environment. 
- Azure VMware Solution - allows running of VMware workloads in Azure.
## Compute (Processing power)
## Storage (Volume of data)
