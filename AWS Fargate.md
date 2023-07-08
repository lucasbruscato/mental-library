It's similar to [[AWS ECS]] , i.e., it also launches Docker containers on AWS, some of the key elements:

1. The user does not need to provision the infrastructure, simpler than [[AWS ECS]]
2. It can be [[serverless]]
3. AWS handles CPU / RAM on the containers depending on the need

The Docker images that can be used by this service are stored in [[AWS ECR]].