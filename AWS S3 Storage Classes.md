The current available storage classes are:

1. **S3 Standard - General Purpose:**
	1. used for frequently accessed data
	2. low latency and high throughput
2. **S3 Infrequent Access (IA):** less frequently accessed but requires rapid access when needed
	1. Standard - IA:
		1. used for less frequently accessed data
		2. lower cost than S3 standard
	1. One Zone - IA:
		1. data is lost when AZ is destroyed
		2. used for secondary backup copies or data you can recreate
4. **S3 Glacier:** low cost storage for archiving / backup; price for storage and object retrieval cost
	1. Instant Retrieval: 
		1. millisecond retrieval, great for data accessed once a quarter
		2. min storage duration of 90 days
	2. Flexible Retrieval:
		1. different retrieval programs
		2. min storage duration of 90 days
	3. Deep Archive: 
		1. for long term storage
		2. min storage duration of 180 days
5. **S3 Intelligent Tiering:**
	1. Small monthly monitoring and auto-tiering fee
	2. Moves objects automatically between Access Tiers based on usage
	3. There are no retrieval charges

![[AWS S3 Storage Classes - classes comparison.png]]

![[AWS S3 Storage Classes - price comparison.png]]