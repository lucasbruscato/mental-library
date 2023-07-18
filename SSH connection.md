SSH is one of the most important functions to control a remote machine using command line.

It allows the user to access locally another machine (Linux, Windows, MacOS) using:

- the ip or dns name
- the port, the standard is 22 for SSH
- access key pair (pem file, for example)

A snippet of how to use it:

```
ssh -i access-key-basic-instance.pem ec2-user@18.208.164.1060
```

The elements of the snippet:

1. "-i" is the parameter representing that a access key will be used
2. "access-key-basic-instance.pem" is the file with the key
3. "ec2-user" is the standard user from [[AWS EC2]] servers
4. "@18.208.164.1060" is representing the public ipv4 address
