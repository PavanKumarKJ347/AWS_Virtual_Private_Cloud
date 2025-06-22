## **Virtual Private Cloud**
**Virtual Private Cloud is a private network in which we can provision resources like servers, storages and load balancers etc.**<br>
**Virtual Private Cloud contains both public and private subnets which are created in Multiple Availability Zones.**

## **CIDR Block**
**Classes Inter Domain Routing is a method for allocating IP addresses and its routing to resources provisioned in private networks.**

## **Internet Gateway**
**Internet Gateway is a virtual router in AWS which will enable internet connectivity to VPC.**<br>
**Internet Gateway will be attached to VPC and provides internet access to public subnets.**<br>
**1 Internet Gateway can be attached to Only 1 VPC.**

## **Subnets**
**A subnet is a range of IP addresses within VPC.**<br>
**Subnet CIDR should be subset of VPC CIDR.**<br>
**We divide virtual private cloud into multiple sub networks and create resources like EC2 servers and load balancers etc.**

## **Public Subnet**
**Subnet which will have an access to internet called as public subnet.**<br>
**Servers in public subnet can access internet and we can also reach servers from internet.**<br>
**Public Subnets will have a route connection to internet gateway in route table.**

## **Private Subnet**
**Subnet which does not have an access to internet called as private subnet.**<br>
**Servers in private subnet cannot access internet and we cannot reach servers from internet.**<br>
**Private Subnets will not have a route connection to internet gateway in route table.**

**Note**
**Resources created in public subnet can be accessed from internet.**<br>
**Resources created in private subnet cannot be accessed from internet.**<br>
**Resources created in public and private subnet can be communicated with each other within same network.**

## **Route Tables**
**Route Tables routes network traffic to resources in VPC.**<br>
**Route Tables will be configured in such a way that public subnets will have routes to the internet gateway and private subnets will have routes to NAT Gateway.**

## **NAT Gateway**
**We can create NAT Gateway when servers created in private subnets needs an access to internet.**<br>
**We can define route from private subnet to NAT Gateway and servers created in private subnets will be able to access internet via NAT Gateway.**<br>
**NAT Gateway created in public subnet allows servers in the private subnet to access the internet.**

## **Network Access Control List**
**NACL is a firewall at subnet level.**<br>
**NACL will be created automatically when subnets are created.**

## **Security Group**
**Security Group is a firewall at server level.**

## **Public IPs**
**Public IP address is an IPv4 address that is reachable from the internet and Public IP addresses will be given by Internet Service Provider.**

## **Private IPs**
**Private IPs are assigned to resources in VPC by Network Router.**
