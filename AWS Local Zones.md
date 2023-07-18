For some of the [[AWS Availability Zones]] there are Local Zones options where, ideally, could bring the service closer to the user therefore reducing latency for sensitive applications. The user should extend their VPC to the Local Zone.

The user can apply this concept to a few AWS applications such as [[AWS EC2]], [[AWS RDS]], [[AWS ECS]], [[AWS EBS Volume]], [[AWS Amazon ElastiCache]] and so on.

Example:

1. [[AWS Region]] N.Virginia (us-east-I)
	1. AWS Local Zones are Chicago, Boston, Dallas, Houston, Miami and so on.

![[AWS Local Zones - VPC extension.png]]