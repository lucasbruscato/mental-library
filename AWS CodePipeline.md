This service orchestrates the different steps to have the code automatically pushed to production, it's the basis for CICD ([[Continuous Integration & Continuous Delivery]]).

1. It retrieves the code from [[AWS CodeCommit]]
2. Sends to [[AWS CodeBuild]] and build it
3. Then deploy the ready-to-deploy artifact generated in step 2. using [[AWS CodeDeploy]]
4. And finally sends to [[AWS Elastic Beanstalk]]

![[AWS CodePipeline orchestration layer.png]]