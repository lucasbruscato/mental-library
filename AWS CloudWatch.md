CloudWatch is a tool that contains several functionalities, such as:

1. CloudWatch Metrics
	1. It provides metrics for almost all services in AWS, metrics like CPU Utilization, EBSByteBalance, Memory and so on
	2. Those metrics have timestamp
	3. One can use the dashboards there in custom times
2. CloudWatch Alarms
	1. It provides triggers to alarms if a certain condition occurs, e.g., CPU Utilization >= 80%, and those messages can be sent via [[AWS SNS]] topics
	2. Also, it can be associated with actions, for example:
		1. Auto scaling: increase/decrease EC2 instances count
		2. EC2 actions: stop, terminate, reboot, etc
	3. Can also create a billing alarm on the CloudWatch Billing metric
3. CloudWatch Logs
	1. It can collect logs from several services such as:
		1. [[AWS Elastic Beanstalk]]: logs from the application
		2. [[AWS ECS]]: logs from the containers
		3. [[AWS Lambda]]: function logs
		4. Also can run an agent on [[AWS EC2]] and on on-premises servers
	2. It is possible to enable real-time logs and store them for 1 day, 1 month or forever
