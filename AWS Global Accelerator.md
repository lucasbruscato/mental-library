It's a service to **improve the availability and performance** in the information transfer for AWS applications.

It leverages the AWS internal network to optimize the route of the user's application basically sending the traffic through edge locations with private AWS networks.

![[AWS Global Accelerator - comparison without accelerator.png]]

The comparison with [[Amazon CloudFront]] is:

1. CloudFront improves the performance with **cacheable content** and the content is served at the edge
2. Global Accelerator has no caching and improves by **proxying packets** at the edge and improves the performance for a wide range of applications over TCP or UDP