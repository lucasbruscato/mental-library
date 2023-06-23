For the replication to work one must first enable the versioning ([[AWS S3 Versioning]]) in source and destination buckets.

There are two forms of replication:
1. Cross-Region Replication (CRR) - use case: compliance, lower latency access, replication across accounts
2. Same-Region Replication (SRR) - use case: live replication

The buckets can be in different AWS account and also different region.