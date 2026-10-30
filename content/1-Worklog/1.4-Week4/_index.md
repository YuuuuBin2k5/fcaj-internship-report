---
title: "Week 4 Worklog"
weight: 4
chapter: false
pre: "<b>1.4. </b>"
---

### Week 4 Objectives:

* Review VPC networking and access control with Security Groups.
* Learn about EC2, Linux server access, and preparing a Node.js environment.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Review VPCs and CIDR and identify address ranges for the VPC and its subnets.<br>- Distinguish public and private subnets using their routing configuration.<br>- Study local routes, routes to an Internet Gateway, and subnet route table associations.<br>- Compare Security Groups and Network ACLs: scope, inbound/outbound rules, and stateful versus stateless filtering.<br>- Review the VPC lab network configuration before preparing EC2. | 26/10/2026 | 26/10/2026 | [Amazon VPC](https://000003.awsfcaj.com/) |
| 4 | - Check the VPC, public subnet, route table, and Internet Gateway for the office practice session.<br>- Learn the purposes of AMIs, instance types, EBS, and key pairs when launching EC2.<br>- Follow the guide to select Amazon Linux, configure storage, and name the instance.<br>- Select the subnet and configure a public IP and Security Group; study restricting SSH to the client IP.<br>- Try launching the instance, check its status, and record connection details. | 28/10/2026 | 28/10/2026 | [Amazon EC2](https://000004.awsfcaj.com/) |
| 5 | - Read the SSH instructions covering the server address, ec2-user login, and private key file.<br>- Learn to check the IP address, port 22, and Security Group rules when a connection fails.<br>- Learn pwd, ls, cd, mkdir, cat, and nano for working with Linux directories and files.<br>- Read about installing Node.js with nvm and checking versions with node -v and npm -v.<br>- Study Git and the steps for transferring application source code to the server. | 29/10/2026 | 29/10/2026 | [Connect to EC2 Linux](https://000004.awsfcaj.com/4-launchlinuxinstance/4.2-connectlinuxinstance/) |
| 6 | - At the office, continue checking EC2 connectivity and the Node.js, npm, and Git setup steps.<br>- Try creating a small Node.js application with an endpoint that returns a test response.<br>- Study the listening address, application port, and Security Group rules needed for client access.<br>- Try requests from the server and browser and compare responses with application logs.<br>- Record actual results and review lab instances, EBS storage, and network resources before cleanup. | 30/10/2026 | 30/10/2026 | [Node.js on EC2](https://000004.awsfcaj.com/6-awsfcjmanagement-linux/6.2-setupnodejsonec2linux/) |

### Week 4 Achievements:

* Expected to better understand connectivity from the internet to EC2 through subnets, route tables, and Security Groups.
* Expected to learn AMI selection, key pair creation, Linux instance launch, and SSH access.
* The practical goal is to run a simple Node.js application; deployment results will be updated based on actual practice.
