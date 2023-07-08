It's an Amazon database with the following properties:

1. Highly available with replication across 3 [[AWS Availability Zones]]
2. It's a NoSQL database
3. Scales easily as it's a [[serverless]] database
4. Low latency for data retrieval
5. Low cost and auto scaling capabilities

There is an option to make it **fully managed in-memory cache**, it's called DynamoDB Accelerator (DAX). It presents around 10x the performance improvement when accessing your DynamoDB tables.