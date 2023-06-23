It's the main building block on AWS, it's known as "infinitely scaling" storage.

The objects (files) are stored in S3 buckets (directories), some details about the buckets are:
1. Buckets must have a globally unique name (across all regions and accounts)
2. Buckets are defined at the region level, although it seems to be a global service
3. Naming convention:
	1. no uppercase or underscore
	2. 3-63 characters long
	3. not an ip
	4. must start with lowercase or number
	5. cant have a prefix as "xn--"
	6. cant have a suffix as "-s3alias"

Each object in S3 has a key, the key is the full path, for example:

` s3://my-bucket/folder_x/my_file.txt

There is no concept of directories in s3 buckets, just keys with very long names that contains slashes.

Regarding the objects:
- Max object size is 5TB (if uploading more than 5TB, must use multi-part upload)
- Metadata is possible to be added
- Tags, useful for security / lifecycle
- Version ID, if versioning is enabled

Apart from it, there are some properties of s3 worth mentioning:

- The permissions are covered in [[AWS S3 Security]]
- The versioning is covered in [[AWS S3 Versioning]]
- The replication is covered in [[AWS S3 Replication]]
- The storage classes are covered in [[AWS S3 Storage Classes]]
- The encryption is covered in [[AWS S3 Encryption]]