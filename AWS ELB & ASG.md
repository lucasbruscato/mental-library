In AWS, ELB stands for Elastic Load Balancing and ASG stands for Auto Scaling Groups.

The topics covered in this discussion were:

1. **Vertical scalability**: means increasing the size of an instance, for example, from instance t2.micro to t2.large. It's very common for non distributed systems like databases.
2. **Horizontal scalability**: means increasing the number of instances or systems for your application, very common for distributed systems like web applications.
3. **High availability**: it goes hand in hand with horizontal scaling and it's only considered if the application or system is running in at least 2 [[AWS Availability Zones]].
4. **Scalability vs Elasticity vs Agility**
	1. Scalability: ability to accommodate a larger load by scaling vertically or horizontally.
	2. Elasticity: once it's scalable, elasticity means that there is a possibility for "auto-scaling" so the system can adapt to the load.
	3. Agility: not related to scalability, it's about new IT resources that are a click away.
5. [[AWS Elastic Load Balancer]] - to manage and forward internet traffic to multiple servers (EC2 instances) downstream (spread load across multiple downstream instances, for example).
6. [[AWS Auto Scaling Group]] - to scale up or down the number of EC2 instances depending on the internet traffic.