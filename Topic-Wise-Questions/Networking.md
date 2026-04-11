# Networking Interview Questions (Topic-wise Collection)

---

## VPC & Subnets

- As you are using multiple services like VPC, what is the best architecture in terms of security and networking point of view if we need to setup 3 tier architecture in AWS? *(AlignedAutomation)*
- How do you differentiate public and private subnet? *(AlignedAutomation)*
- What is difference between public and private subnet? *(PivotChain)*
- How do you setup custom VPC in terms of security? *(T-Systems)*
- I have created 2 subnets in a VPC and choose /28 as my CIDR range. I have created 14 servers in it and want to add more servers. Is it possible to add CIDR range? *(T-Systems)*
- What is a NAT Gateway? *(InfracloudTech)*

---

## Security Groups & NACLs

- What is basic difference between Security group and NACL? *(AlignedAutomation)*
- SG and NACL - which is stateful and which is stateless? *(AlignedAutomation)*
- Explain difference between SG and NACL *(Allvue)*
- What is the difference between SG and NACL? Which is stateful and which is stateless? *(GlobalPayments)*
- Where the application is hosted and how SGs are helping to restrict access on the app? *(Spryc)*

---

## VPC Peering & Transit Gateway

- Can you explain VPC peering? *(T-Systems)*
- Difference between VPC peering and transit gateway *(GlobalPayments)*
- Consider in one VPC you have EKS and in another VPC you have jump server. How the connectivity will occur? *(LTIMindtree)*

---

## Kubernetes Networking

- What is NATting in K8S? SNAT and DNAT *(MindBowser)*
- Where can we check if inter pod communication is allowed? *(AlignedAutomation)*
- Suppose you have deployed application on EKS cluster and for some reason your pods are not able to communicate with each other. What could be the reason? *(AlignedAutomation)*
- If nodes are scattered in 2 different namespaces, how the pods in the nodes connect with each other? *(RakutenSymphony)*
- Suppose our subnet is having IP exhaustion issue but new pods need to be launched, how to tackle this? *(Securonix)*
- DNS resolution is failing inside Kubernetes pods — how do you troubleshoot? *(SRE/Questions)*
- A network policy is blocking traffic between services in different namespaces. How would you design and debug the policy to allow only specific communication paths? *(K8S_SBQ)*

---

## TCP/IP & Connectivity

- How to check connectivity between 2 instances? *(Helpshift)*
- Can you explain some TCP connection states like what connection state you usually see when you see charts of TCP connections active? *(Helpshift)*
- Command to check what connections are active in your machine *(Helpshift)*
- How to check if port is open or not? *(PivotChain)*
- How to check IP address of machine? *(PivotChain)*
- I am not able to login remote machine using SSH. What can we do? *(PivotChain)*

---

## Load Balancing

- What is the difference between ALB and NLB? *(Apptware)*
- What kind of LBs do you work on? *(GlobalPayments)*
- Suppose your ALB has issue as 504 gateway issue, how will you troubleshoot? *(T-Systems)*
- What kind of security did you implement while configuring load balancers? *(T-Systems)*

---

## DNS

- How to manage K8S DNS? *(AlignedAutomation)*
- What is the Core DNS in K8S? *(MindBowser)*

---

## Cross-Account / Multi-Region

- Suppose one application is hosted in one AWS account and other application is in different account. User tells application is not accessible or they're unable to reach URL. But all configs are looking good. How to troubleshoot? *(Securonix)*
- What is DDOS attack? *(LTIMindtree)*

---

## Architecture

- What is 3 tier application? *(Spryc)*
- You have to deploy 2 apps on single EC2 instance in such a way that one is node js and second is java app. But these 2 apps need to be exposed on 2 different IP. How we can setup? *(MindBowser)*
- Can we attach 2 EC2 IPs to single EC2 instance? *(MindBowser)*
