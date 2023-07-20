It's a firewall that controls traffic from and to a [[AWS VPC#Subnets|subnet]], with rules that only include IP addresses.

Some properties:
1. Can have both ALLOW and DENY rules
2. Return traffic must be explicitly allowed by rules
3. Are attached at the subnet level

Main difference to [[AWS Security Groups]] is that Security Groups:
1. Can only have ALLOW rules
2. Return traffic is automatically allowed
3. Are attached at the instance level
