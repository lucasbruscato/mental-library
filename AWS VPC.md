VPC stands for Virtual Private Cloud, which is a private network the user can deploy their resources.

### Subnets

Inside a VPC there can be Subnets, which allow to partition the network inside the VPC (shown below) in an [[AWS Availability Zones]], with two types:
1. Private Subnets is a subnet not available from the internet
2. Public Subnets is a subnet available from the internet

For defining the accesses to the subnets it's used the Route Tables.

![[AWS VPC - subnets.png|300]]

Important functionalities:
- **Internet Gateways** allow the VPC to connect to the internet
- **NAT Gateways** allow the private subnets to access the internet while remaining private
