This section is focused on [[Global Application]]: tools, infrastructure and strategies.

The tools covered in this section were:
1. [[Amazon Route 53]]
2. [[Amazon CloudFront]]
3. [[Amazon S3 Transfer Acceleration]]
4. [[AWS Global Accelerator]]
5. [[AWS Outposts]]
6. [[AWS WaveLength]]
7. [[AWS Local Zones]]

With the tools described above there are some global applications architectures that can be created, such as:

1. Single [[AWS Region]], Single [[AWS Availability Zones]] - e.g., only one EC2 instance in only one availability zone
	1. No high availability
	2. No global latency protection
	3. Low difficulty
2. Single [[AWS Region]], Multi [[AWS Availability Zones]] - e.g., two EC2 instances in two different availability zones
	1. High availability
	2. No global latency protection
	3. Medium difficulty
3. Multi [[AWS Region]], Multi [[AWS Availability Zones]], Active-Passive relation - e.g., one of the EC2 instances is passive, i.e., read-only by the users
	1. High availability
	2. Global latency protection for reading
	3. No global latency protection for writing
	4. High difficulty
4. Multi [[AWS Region]], Multi [[AWS Availability Zones]], Active-Active relation - e.g., both of the EC2 instances are active, i.e., read/write by the users
	1. High availability
	2. Global latency protection for reading
	3. Global latency protection for writing
	4. Very high difficulty

