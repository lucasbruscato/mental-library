ECS stands for Elastic Container Service, it allows the user to launch Docker containers on AWS.

Key elements:
1. The user must provision and maintain the infrastructure (the [[AWS EC2 - Elastic Compute Cloud]], for example)
2. AWS handles the starting / stopping of the containers
3. It has integrations with [[AWS Elastic Load Balancer]]

The Docker images that can be used by this service are stored in [[AWS ECR]].