The Read Replica in AWS RDS enables to scale the read workload of your database in multiple objects, can create up to 15 read replicas and the data is only written to the main database.

![[AWS RDS Read Replicas scheme.png]]

The main difference between the Read Replicas and the deployment in Multi-AZ is that the replication in Multi-AZ occurs in another [[AWS Availability Zones]] and the replication database is considered a "Failover DB", i.e., in case of issues with the main database, it defaults to the failover (read/write).