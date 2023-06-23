It's a functionality for cost savings (i.e., only run at optimal capacity) to scale out (also know as scale up) by adding EC2 instances or scale in (also known as scale down) by removing EC2 instances to match the current load.

There are a few scaling strategies, they are:

1. Manual scaling: update the size of an ASG manually
2. Dynamic scaling: respond to a change in demand
	1. Simple / step scaling: based on a [[AWS CloudWatch]] alarm that is triggered (CPU > 70%, or CPU < 30%, for example)
	2. Target tracking scaling: the avg CPU of ASG instances to be around 40%, for example
	3. Schedule scaling: scale in for 2am until 8am, for example
3. Predictive scaling: uses ML to predict future traffic