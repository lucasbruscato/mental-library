Amazon EC2 is one of the most popular services from AWS, it provides infrastructure as a service.

It mainly consists of:
- Renting virtual machines (EC2 per se)
- Storing data on virtual drives (EBS)
- Distributing load across machines (ELB)
- Scaling the services using auto-scaling group (ASG)

There are a few options for sizing ([[AWS EC2 Instance Types]]) and settings:
1. A few options for Operating System (OS): Linux, Windows and MacOS
2. Flexible computing power (CPU)
3. Flexible random-access memory (RAM)
4. Flexible storage space:
	1. EBS / EFS
	2. EC2 Instance store
5. Network card: speed of the card, public IP address
6. Firewall rules: [[AWS Security Groups]], [[SSH connection]]
7. Bootstrap script (EC2 user data)
8. Access management is done at Security linking to an [[AWS IAM Roles]]

Regarding billing, there are a few [[AWS EC2 Instances Purchasing Options]].