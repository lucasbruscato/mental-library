Lambda is a [[serverless]] service with the following key elements:

- it's used for short executions (max 15 minutes of runtime)
- it's for only virtual functions
- it runs on-demand
- the scaling is automated

It's easy to monitor through [[AWS CloudWatch]] , supports several programming languages (Python, Node.js, Java, C#, Golang, Ruby, Rust, etc) and it also offers an easy pricing model.

It can be triggered by CloudWatch Events EventBridge, for example:

![[AWS Lambda triggering via CloudWatch.png]]