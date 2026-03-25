# AWS EC2 Linux Deployment Lab

## Overview

This project demonstrates provisioning and configuring a Linux-based virtual server using AWS EC2. It covers instance setup, security configuration, and remote access.

## Services Used

* AWS EC2
* Security Groups
* SSH

## Key Tasks Performed

* Launched EC2 instance
* Configured inbound rules (SSH, HTTP, HTTPS)
* Connected securely via SSH
* Performed basic system setup

## Deployment Steps

### Launch Instance

* Select Ubuntu AMI
* Configure instance type
* Attach security group

### Configure Security Group

* Allow SSH (port 22)
* Allow HTTP (port 80)
* Allow HTTPS (port 443)

### Connect via SSH

```
ssh -i key.pem ubuntu@<public-ip>
```

## Output

* Successful SSH connection
* Running Linux instance
* Add AWS console and terminal screenshots

## Learning Outcomes

* Cloud infrastructure provisioning
* Secure remote access using SSH
* Basic Linux server management

## Possible Enhancements

* Automate provisioning using Terraform
* Deploy web server (Nginx/Apache)
* Integrate monitoring tools
