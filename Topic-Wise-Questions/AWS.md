# AWS Interview Questions (Topic-wise Collection)

---

## VPC & Networking

- As you are using multiple services like VPC, what is the best architecture in terms of security and networking point of view if we need to setup 3 tier architecture in AWS? Where will you place EC2 in that 3 tier architecture? *(AlignedAutomation)*
- How do you differentiate public and private subnet? *(AlignedAutomation)*
- How will you define subnet whether its public or private? State difference *(LTIMindtree)*
- What is difference between public and private subnet? *(PivotChain)*
- What is basic difference between Security group and NACL? *(AlignedAutomation)*
- SG and NACL - which is stateful and which is stateless? *(AlignedAutomation)*
- Explain difference between SG and NACL *(Allvue)*
- What is the difference between SG and NACL? Which is stateful and which is stateless? *(GlobalPayments)*
- State difference between SG and NACL *(LTIMindtree)*
- What is AWS VPC architecture? *(Infospica)*
- What is the difference between stateful and stateless in VPC? *(Infospica)*
- How do you setup custom VPC in terms of security? *(T-Systems)*
- I have created 2 subnets in a VPC and choose /28 as my CIDR range. I have created 14 servers in it and want to add more servers. Is it possible to add CIDR range? *(T-Systems)*
- Can you explain VPC peering? *(T-Systems)*
- Difference between VPC peering and transit gateway *(GlobalPayments)*
- Consider in one VPC you have EKS and in another VPC you have jump server. How the connectivity will occur? *(LTIMindtree)*
- What is a NAT Gateway? *(InfracloudTech)*

---

## IAM & Security

- Difference between IAM role and IAM user. Can we attach IAM role to IAM user? *(GlobalPayments)*
- What is instance profile in AWS? *(GlobalPayments)*
- Can you explain Role based access control with respect to IAM? *(Spryc)*
- How many types of authentication does AWS have? *(MindBowser)*
- What is OIDC? *(MindBowser)*
- Difference between AWS managed and custom managed policies? *(T-Systems)*
- How will you secure S3 bucket? *(T-Systems)*

---

## EC2 & Compute

- How to launch EC2 instance from CLI? *(CCTech)*
- User has admin access to AWS but he cant access EC2. What could be the reason? *(CCTech)*
- How many ways we can access EC2 instance in AWS? *(GlobalPayments)*
- Suppose you have EC2 server having volume of around 500GB. The volume is getting full when we deploy the application onto it. We have to increase size of volume, will we require restart or not? *(InfracloudTech)*
- Can you explain different kind of EBS volumes in AWS? *(T-Systems)*
- Can I attach same disk on different servers when I want to mount share filesystem with AWS? *(T-Systems)*
- What is the difference between snapshot and AMI? *(T-Systems)*
- From snapshot or AMI can I recover whole VM? *(T-Systems)*
- If I want to deploy application on EC2 which required HA, what will be your approach? *(T-Systems)*
- An EC2 instance in production is unreachable — what checks do you perform? *(SRE/Questions)*
- EC2 went down and I want alert triggered. How to configure in AWS? *(T-Systems)*
- What are the different states of the VMs in AWS? *(Fiserv)*
- Suppose my VMs are standalone and I have trouble with VM start. What steps I will use to troubleshoot? Machine is in failed state *(Fiserv)*
- You notice some intermittent performance issues with DB hosted on EC2 and its using EBS storage. How will you investigate and troubleshoot these issues? *(Volkswagen)*
- Can we attach 2 EC2 IPs to single EC2 instance? *(MindBowser)*

---

## Auto Scaling & Load Balancing

- Can you explain autoscaling? What are the types? *(Allvue)*
- What is autoscaling? *(GlobalPayments)*
- What is use of health check in autoscaling? *(GlobalPayments)*
- How to auto scale app/EC2 in AWS? *(CCTech)*
- ASG is not launching instances. How to fix this issue? *(T-Systems)*
- What is load balancing? What are types of LB? *(Allvue)*
- Lets say you have many instances and there is ALB in place. How ALB knows the incoming request to be routed to specific EC2 or app? *(Allvue)*
- What kind of LBs do you work on? *(GlobalPayments)*
- What is the difference between ALB and NLB? *(Apptware)*
- Suppose your ALB has issue as 504 gateway issue, how will you troubleshoot? *(T-Systems)*
- What kind of security did you implement while configuring load balancers? *(T-Systems)*
- Have you ever implemented SSL and TLS certificates? *(T-Systems)*

---

## S3

- To host static website using S3 bucket, what is the essential policy to attach for it? *(GlobalPayments)*
- How to enable/disable versioning in S3? *(InfracloudTech)*
- Is cross zone replication is possible in S3 bucket? *(T-Systems)*
- You need a compliance retention of 7 years in my S3 storage. How will you design your S3? *(T-Systems)*
- One of your S3 buckets accidentally exposed data publicly — what immediate and long-term actions do you take? *(SRE/Questions)*

---

## RDS & Database

- What is the difference between DB backup and RDS snapshot? *(InfracloudTech)*
- Please walk through the Disaster Recovery plans used in your application which circles around database *(Equifax)*
- Suppose one of the region fails which is used to store data in particular DB. Now DB was in same region and its also not accessible. What is the fallback plan here? *(Equifax)*
- What's your approach for handling database reliability and backups in an SRE role? *(SRE/Questions)*
- How you can take backup of instance or block volumes in AWS? *(LTIMindtree)*

---

## Lambda & Serverless

- Can you explain what kind of automations have you done using lambda or shell scripting? *(Allvue)*
- What language runtime are you using for lambda functions? *(Allvue)*
- What exactly is serverless in lambda? *(InfracloudTech)*

---

## CloudWatch & Monitoring

- Is cloudwatch agent is mandatory to configure metrics/services monitoring? *(CCTech)*
- What all the services have you done on cloudwatch? *(HCL)*
- In cloudwatch, what all things have you worked upon? *(Apptware)*
- Have you worked on cloudwatch alerts? How did you configure them? *(Apptware)*
- Can you explain difference between cloudwatch logs and cloudwatch metrics? *(Volkswagen)*
- How cloudwatch detects things like node is down, crashLoopBackoff errors? *(Fortinet)*

---

## SNS & Notifications

- In SNS what all options do we have for alerts? *(Apptware)*
- Did you face any challenges in setting up SMS notifications delivery? *(Apptware)*
- How did you set up the subscribers list in SNS? *(Apptware)*

---

## CloudFront & CDN

- What is AWS cloudfront? How frequently is it good to refresh cloudfront at edge locations? How will it affect the performance? *(InfracloudTech)*

---

## ECR

- If our application is using the ECR repository, but images of multiple apps are being pushed to same ECR repo. As ECR charges us on basis of the data stored, is there any way we can optimize the storage over there? *(Apptware)*

---

## EKS

- What are different cluster types in EKS? *(Apptware)*
- Why are you exposing applications on EC2 instead of fargate? *(Apptware)*

---

## DR & High Availability

- What you are doing for DR strategy in your current project? *(LTIMindtree)*
- Before setting up infra for an application, what is the process of standardizing any DR? *(AlignedAutomation)*
- A region in AWS goes down — how do you design your systems for high availability and fault tolerance? *(SRE/Questions)*
- Can you explain how you've set up highly available and fault-tolerant architectures in AWS? *(SRE/Questions)*

---

## Cost Optimization

- What do you mean by cost optimization in AWS? What techniques have you used to achieve the same? *(Apptware)*
- Have you got chance to work on budget policy? *(Volkswagen)*

---

## Cross-Account & Multi-Region

- Suppose one application is hosted in one AWS account and other application is in different account. User tells application is not accessible or they're unable to reach URL. But all configs are looking good. How to troubleshoot? *(Securonix)*
- What is DDOS attack? *(LTIMindtree)*
- How do you monitor cloud resources (EC2, S3, VPC, IAM, etc.) for reliability and compliance? *(SRE/Questions)*

---

## General

- What all AWS services have you used in your role? *(AlignedAutomation, Infospica)*
- How are you automating infrastructure provisioning? *(Allvue)*
- With your learnings in GCP and working experience in AWS, what differences did you realize? What advantages does AWS have over GCP? *(Apptware)*
- What all services have you worked on in AWS? *(Apptware)*
- What do you mean by 99.9% availability in AWS? Have you encountered the situation of unavailability of any resources? *(HCL)*
