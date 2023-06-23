RDS stands for Relational Database Service, it's a managed database service using SQL as a query language.

It allows the creation of these database distributions:
1. Postgres
2. MySQL
3. MariaDB
4. Oracle
5. Microsoft SQL Server
6. [[AWS Aurora]]

The advantage of using RDS instead of deploying a DB on EC2 is that RDS is a managed service:
- Automated provisioning, OS patching
- Possibility to easily perform automatic backups
- Has monitoring dashboards
- Provides read replicas
- Multi [[AWS Availability Zones]] for disaster recovery
- Scaling capability (both vertically and horizontally)
- Storage backed by [[AWS EBS Volume]]

Can't perform an SSH into the instance tho.