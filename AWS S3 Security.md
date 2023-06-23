The permissions and security properties are sparse:

1. User-based: IAM policies
2. Resource-based:
	1. Bucket policies - wide rules from the S3 console
	2. Object Access Control List (ACL) - finer grain
	3. Bucket Access Control List (ACL) - less common

Note: an IAM principal (account or user) can access an S3 object if:
- The user IAM permissions ALLOW it OR the resource policy ALLOWS it
- AND there is no explicit DENY

In order to have a static website hosting (example of how the URL would look like below), the S3 should have the policy for public access enabled.

http://{bucket-name}.s3-website-{aws-region}.amazonaws.com
