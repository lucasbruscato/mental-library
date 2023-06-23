An ELB is a managed load balancer (which means that AWS will guarantee it's work, upgrades, maintenance and high availability).

The definition of load balancers:

![[AWS Elastic Load Balancer - simple load balancer.png]]

There are four types of load balancer (illustrated below):
1. **Application Load Balancer**: used for HTTP(s) / gRPC protocols (layer 7); HTTP routing features and static DNS (URL).
2. **Network Load Balancer**: used for TCP / UDP protocols (layer 4); high performance like MM of RPS; static IP through elastic IP.
3. **Gateway Load Balancer**: used for GENEVE protocol on IP packets (layer 3); route traffic to firewalls that you manage on EC2 instances; intrusion detection.
4. Classic Load Balancer but it's retired in 2023.

![[AWS Elastic Load Balancer - types of load balancer.png]]