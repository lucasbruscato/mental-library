This section covers the tooling and methodologies to enable a better integration of multiple applications in AWS.

There are two types of communication:

1. Synchronous communication: application to application
2. Asynchronous communication (also known as event based): application to queue to application

In 1. there might be problems with sudden spikes of traffic in any given application, therefore a good practice is to decouple applications.

The tools covered in this section to enable this are:

1. [[AWS SQS]] - queue model
2. [[AWS SNS]] - pub/sub model
3. [[AWS Kinesis]] - big data streaming
4. [[Amazon MQ]] - hybrid alternative to SQS and SNS for on-prem servers
