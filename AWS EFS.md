EFS stands for Elastic File System, it's a managed network file system that can be mounted over several EC2 instances.

EFS works with Linux EC2 instances in multiple [[AWS Availability Zones]], it's highly available, scalable, expensive, pay per use and has no capacity planning.

Also, there is the EFS-IA which stands for Infrequent Access and is a storage class, some key points about it:

- It's cost-optimized for files not accessed every day
- Up to 92% lower cost compared to EFS Standard
- One can implement a lifecycle policy and move files that are not accessed for X days to EFS-IA