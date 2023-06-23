The EBS snapshot is useful when one wants to move EBS to another [[AWS Availability Zones]], the process to perform that is illustrated below.

![[AWS EBS Snapshot.png]]

There are two important features:

1. **EBS Snapshot Archive:** one can move the snapshot to an "archive tier" that is 75% cheaper, but it takes 24 to 72 hours for restoring the archive.
2. **Recycle Bin:** one can establish rules to specify retention (from 1 day to 1 year) over deleted snapshots.