# aws-addrbook
Simple Address Book application on AWS EC2 instance

# What
This project launches an AWS EC2 instance (free-tier), and launches a simple address book SpringBoot application on it.


# Pre-requisites:
Install latest ansible on Linux local host


# How
This project consists of ansible playbooks to:
## Launch EC2 VM (free-tier)
Ansible Extra Arguments to be passed:
* aws_access_key
* aws_secret_key
* region

```
ansible-playbook -u ec2-user /root/aws_work/ansible-aws/ec2_app.yml -e ...
```
