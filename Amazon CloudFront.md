It's a Content Delivery Network (CDN), **it serves to improve the read performance by letting the content cached in edges spread around the world**.

It has DDoS protection, integration with Shield and AWS Web Application Firewall.

The differences between CloudFront and [[AWS S3]] Cross Region Replication are:

- **CloudFront** is great for static content that must be available everywhere
	- The files are cached for maybe a day
	- It uses the global edge network (~200 locations)
- **S3 Cross Region Replication** is great for dynamic content that needs to be available at low-latency in a few [[AWS Region]]s
	- The data is really replicated in each region the user sets
	- It's read only
	- Files are updated in near real-time
