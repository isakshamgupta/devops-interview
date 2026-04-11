# Security & DevSecOps Interview Questions (Topic-wise Collection)

---

## IAM & Access Control

- Difference between IAM role and IAM user. Can we attach IAM role to IAM user? *(GlobalPayments)*
- What is instance profile in AWS? *(GlobalPayments)*
- Can you explain Role based access control with respect to IAM? *(Spryc)*
- Difference between AWS managed and custom managed policies? *(T-Systems)*
- How many types of authentication does AWS have? *(MindBowser)*
- What is OIDC? *(MindBowser)*

---

## Kubernetes Security

- How to manage security in kubernetes? *(Infospica)*
- How do you maintain security of cluster to ensure its vulnerability free? *(Fortinet)*
- Are K8S secrets safe to use? *(InfracloudTech)*
- How do you handle secrets in K8S? *(PivotChain)*
- How are you managing secrets of applications? *(Fortinet)*
- How to manage secrets in EKS clusters securely? *(Securonix)*
- What is service account in K8S cluster? *(RakutenSymphony)*
- You have a pod for which you want to restrict access on other K8S objects, how to control that in K8S? *(LTIMindtree)*
- How do you secure communication between microservices in Kubernetes? *(SRE/Questions)*

---

## Docker Security

- Assume that you have a dockerfile in which you pass username and password. When doing docker inspect, we can see credentials. So how we can avoid this? *(InfracloudTech)*
- Suppose we've pipeline using which we're building docker image and pushing it to ECR. Here we've to pass AWS credentials in form of access keys. But we dont want to pass credentials or store them on any provider/server. How we can achieve the successful pipeline without storing credentials anywhere? *(MindBowser)*

---

## Pipeline Security

- How to use Hashicorp vault in CICD pipeline? *(AlignedAutomation)*
- How do you secure credentials in jenkins? *(CCTech)*
- How to pass credentials inside jenkins pipeline? *(CCTech)*
- How are you handling sensitive data in terraform or AWS? *(Fiserv)*

---

## Code Security

- How have you integrated Security tool like sonarqube with application? *(CCTech)*
- If there is any vulnerability in code, what is the approach to resolve? *(CCTech)*
- How do you take care of security at your organization? *(Spryc)*

---

## S3 & Data Security

- How will you secure S3 bucket? *(T-Systems)*
- One of your S3 buckets accidentally exposed data publicly — what immediate and long-term actions do you take? *(SRE/Questions)*

---

## SSL/TLS

- Have you ever implemented SSL and TLS certificates? *(T-Systems)*
- What kind of security did you implement while configuring load balancers? *(T-Systems)*
- Explain strategy to setup ingress controller in EKS and doing SSL termination *(Securonix)*

---

## Audit & Compliance

- Can you walk through how you'd audit user activity in a production environment? *(SRE/Questions)*
- Describe a time when you had to ensure a system was compliant with security standards (e.g., SOC 2, HIPAA, ISO 27001) *(SRE/Questions)*
- How would you implement audit logging in a Kubernetes cluster or API service? *(SRE/Questions)*
- How do you detect and respond to unauthorized privileged access in your environment? *(SRE/Questions)*

---

## Secrets Management & Rotation

- You notice engineers often forget to rotate secrets — how would you automate this? *(SRE/Questions)*
