# Elastic Block Store

It's a network drive and causes a bit of latency. It can be detached from one instand and attached to antoher one. One instance could have multiple attached.

It's bounded to AZ.



## EBS Snapshots

Make a backup.

EBS Snapshot Archive: is cheaper

Recycle Bin for EBS Snapshots. Have a time to recover.

Move volume across AZ.



## Amazon Machine Image

AMI is a customization of an EC2 instance.

You can launch EC2 instances from:

- A public AMI: AWS provided
- Your own AMI: you make and maintain them yourself
- An AWS MarketPlace AMI: an AMI someone self made (pand potentially sells.)



## AMI Process

So that we could save the state of our instances and reuse it in future.

- Start an EC2 instance and customize it
- Stop the instance (for data integrity)
- Build and AMI
- Launch instances from other AMIs.

## EC2 Image Builder

Used to automate the creation of Virtual Mahicnes or container images.

Automate the creation, maintenance, vlidation and testing of EC2 AMI.

## EC2 Instance Store

Hardware disk. But need to backup data by yourself because they will lost if the EC2 instance is terminated.

## Elastic File System

It can be mounted on multiple EC2 instances in multiple AZ.

