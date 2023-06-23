This property is enabled at the bucket level.

It's considered as a best practice to version your buckets, protect against unintended deletes and ease the roll back to previous versions.

The same key overwrite (i.e., total path) will change the "version", also if you just delete the file and so on.

![[AWS S3 Versioning - functionality.png]]