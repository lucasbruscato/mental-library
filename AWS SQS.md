SQS stands for Simple Queue Service, this service centralizes the calls forming the queue and orchestrate the requests to other services.

Some of it's properties:

1. It's a fully managed [[serverless]]
2. It's used to decouple applications
3. The default retention of messages is 4 days to the max of 14 days
4. There is no limit to how many messages can be in the queue
5. Messages are deleted once read by consumers (other services)
6. The messages are shared by consumers and it can be scaled horizontally

![[AWS SQS - process.png]]
