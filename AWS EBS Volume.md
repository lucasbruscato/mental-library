An EBS (Elastic Block Store) Volume is a network drive you can attach to your instances while they run, it allows your instances to persist data, even after their termination.

Some details of it are:

1. **It's a network drive:** it uses the network to communicate, which means there might be a bit of latency.
2. **It's locked to an [[AWS Availability Zones]] (AZ):** that means that to move across one needs to make a [[AWS EBS Snapshot]] it first.
3. **Have a provisioned capacity (size in GBs, and IOPS):** the size can be increase over time, but get billed for all the provisioned capacity.

One important note is that for the [[AWS Certified Cloud Practitioner by Stephane Maarek]] it is only considered that they can only be mounted one EC2 instance at a time.

A good analogy for the EBS Volume is to think of them as a "network USB stick".