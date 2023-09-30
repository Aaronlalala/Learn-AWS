# EC2

EC2 stands for Elastic Compute Cloud

Usage:

1. Rent virtual machines
2. Storing data on virtual drives
3. Dsitributeing load across machines
4. Sclaing the services using an auto-scaling group



## EC2 sizing & configuration options

- OS: Linus, Windows, or Mac OS
- CPU
- RAM
- How much storage space:
  - Network-attached
  - hardware
- Network card: speed of the card, Public IP address
- Firewall rules
- Bootstrap script

Public ip will change after restart instances.

## EC2 Instance Types

m5.2xlarge

- m: instance class
- 5: generate
- 2xlarge: size of instances

## EC2 User Data

## Security Groups

Only contains allow rules. They are a firewall on EC2 instances. They regulate: 1. Access to Ports. 2. I.P. 3. Control of inbound (try to access instance) and outbound network (instance tries to access internet).

Referencign other security groups. Instances with referenced security group could access.

**What is ports?**

21, 21, 22, 80, 443, 3389.

## SSH

SSH allows you to control a remote machine, all using the command line.

1. Access to the directory that contains .pem file: cd /Users/aaronlalala/Documents/Codes/Learn-AWS
2. chmod 0400 EC2Tutorial.pem
3. Log in with ssh: ssh -i EC2Tutorial.pem ec2-user@13.59.195.43