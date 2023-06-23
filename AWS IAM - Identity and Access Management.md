IAM stands for Identity and Access Management and is a Global service within AWS.

At the moment of the account creation in AWS, a root account is created by default, but that one shouldn't be used or shared, instead, you should create users and groups.

Users can belong to one or more groups, but not necessarily have to belong to a group.

IAM has the property to give permissions to users or groups using JSON documents called policies ([[AWS IAM Policies]]).

Being part of IAM is MFA ([[AWS IAM MFA]]), multi-factor authentication that can be use and added to each IAM user including root.

Apart from users and groups, there are also [[AWS IAM Roles]].

And finally, there are some IAM security tools, such as:
1. [[AWS IAM Credentials Report]]
2. [[AWS IAM Access Advisor]]

Some of the best practices when using AWS IAM:
1. Don't use root account except for AWS setup
2. Assign users to groups and assign permissions to groups
3. Create a strong password policy + enforce the use of [[AWS IAM MFA]]
4. Create and use [[AWS IAM Roles]] for giving permissions to AWS services
5. Audit permissions to your account using [[AWS IAM Credentials Report]] and [[AWS IAM Access Advisor]]

