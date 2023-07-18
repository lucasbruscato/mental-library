It was formerly known as [[AWS CloudWatch]] Events and it serves mainly two purposes:

1. Cron scheduler: Work to trigger events in several different services, such as:
	1. To run a [[AWS Lambda]] function every hour
	2. To reboot an [[AWS EC2]] machine every week
2. Event Pattern: Event rules to react to a service to do something, such as:
	1. Send messages in [[AWS SNS]] topics
	2. Trigger a process when an [[AWS S3]] document is uploaded

It's possible to archive events sent to an event bus and there is also the possibility to replay archived events.