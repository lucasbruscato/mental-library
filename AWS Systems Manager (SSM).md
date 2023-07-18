It supports the management of [[AWS EC2]] and on-premises systems at scale (therefore, it's a hybrid service).

The most important features are:
1. patching automation for enhanced compliance
2. run commands over all servers
3. store parameters with SSM parameter store

It works for Linux, Windows, MacOS and Raspberry Pi OS.

It's also enables the user to access the instances creating a **SSM Session Manager**:

1. No SSH access, bastion hosts, or SSH keys needed
2. No port 22 needed (thus better security)
3. Supports Linux, macOS and Windows
4. It sends session log data to S3 or [[AWS CloudWatch]]