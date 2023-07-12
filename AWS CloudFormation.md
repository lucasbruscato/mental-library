It's a tool for writing [[infrastructure as code]].

For example, you create a **stack template** (with a yaml file) in CloudFormation stating:
1. the creation of a [[AWS Security Groups]]
2. the creation of two [[AWS EC2 - Elastic Compute Cloud]] using the security group created in 1.
3. the creation of an [[AWS S3]] bucket
4. and the creation of a [[AWS Elastic Load Balancer]] controlling the flow for these EC2 instances

Some of the advantages of using CloudFormation:
- Enables the user to destroy and re-create an infrastructure
- Provides the generation of a diagram for your templates (example below)
- It uses declarative programming, no need to figure out ordering and orchestration
- Supports (almost) all AWS resources

![[AWS CloudFormation diagram.png]]
