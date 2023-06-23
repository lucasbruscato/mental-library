There are different storage options for EC2 instances, such as:

1. [[AWS EBS Volume]] - a type of storage
	1. network drives attached to one EC2 instance at a time
	2. mapped to an Availability Zone
	3. can use EBS snapshots for backups and transferring across AZ
2. [[AWS AMI]] - a type of image / snapshot of EC2 instances with your customizations
3. [[AWS EC2 Instance Store]] - a type of storage
	1. high performance hardware disk attached to your EC2 instance
	2. lost if your instance is stopped or failed
4. [[AWS EFS]] - a type of storage
	1. network file system, can be attached to 100s of instances in a region
	2. has the Infrequent Access to cost-optimize
5. [[AWS FSx]] - a type of storage for fully managed file systems
	1. FSx for Windows: network file system for Windows servers
	2. FSx for Lustre: high performance computing Linux file system

An illustration comparing EBS and EFS:

![[AWS EC2 - Instance Storage (EBS vs EFS).png]]