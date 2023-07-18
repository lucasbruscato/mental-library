It's a fully managed broker service that provides similar functionalities as [[AWS SQS]] and [[AWS SNS]] but for on-premises applications that might be using open protocols (MQTT, AMQP, STOMP, Openwire, WSS).

It integrates with RabbitMQ and ActiveMQ, and Amazon MQ's properties are:

1. Doesn't scale as SQS / SNS
2. Runs on servers, can run with multiple [[AWS Availability Zones]] with failover
3. Has both queue feature (SQS) and topic features (SNS)