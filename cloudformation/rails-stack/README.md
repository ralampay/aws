# Cloudformation for a Rails Stack

## Infrastructure

* VPC
* 1 Public Subnet
* 1 Private Subnet
* EC2 deployed to public subnet
* RDS deployed to private subnet
* S3
* SecurityGroup (RSWebApp)
* SecurityGroup (RSDatabase)

## Software
* Ubuntu 20.04
* Ruby 2.7.1
* Nginx

## Steps in Creating the Template

1. Create an ec2 keypair for ssh-ing into ec2
2. Create IAM user
