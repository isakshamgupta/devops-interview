# Terraform Interview Questions (Topic-wise Collection)

---

## Basics & Workflow

- Explain terraform workflow *(Allvue)*
- What is Terragrunt, and what problems does it solve that Terraform alone does not address effectively? *(Custom)*
- Whats the difference between Terraform and Cloud formation? *(Allvue)*
- Explain flow of resource creation in terraform *(InfracloudTech)*
- What does terraform init do? *(HSBC)*
- I need to check what all resources are created on terraform, how to check? *(HSBC)*
- If I have to check what all modules, resources created in AWS without browsing through state file, how can we do it? *(HSBC)*

---

## State Management

- What is terraform state file? What is best practice to maintain terraform state file? *(Allvue)*
- How do you maintain terraform statefile? *(Allvue)*
- How are you managing state files in terraform? *(Fiserv)*
- How are you maintaining your terraform state file? *(LTIMindtree)*
- What is the purpose of remote statefile? *(InfracloudTech)*
- How do you design a good state management using S3 and dynamoDB? *(Helpshift)*
- Can you explain using terraform workspaces vs using separate state files? *(Securonix)*
- You did a terraform apply and state file is updated. Now if in AWS UI you delete a resource. Next time when we run terraform code, what will happen? *(Allvue)*
- If I have created resources on AWS using terraform and someone modified them manually in UI. How to tackle this? *(Securonix)*
- If the Terraform state file is accidentally deleted, how would you recover or rebuild the state? *(Custom)*
- How to handle drifts in terraform files? *(Apptware)*
- Your Terraform apply fails due to drift — how do you resolve it? *(SRE/Questions)*

---

## State Locking & Concurrency

- You are a team of 10 people and 2 people does terraform apply at same time. How to prevent this? *(Helpshift, InfracloudTech)*
- As you have automated creating configurations using terraform, how to manage state locking and prevent conflict when multiple people are working on same terraform project? *(Securonix)*
- If you run terraform script and someone is also running same script at same time with some changes, how will terraform behave? *(HSBC)*
- What are the steps to remove or disable lock? What set of commands does terraform have for the same? *(Helpshift)*
- What is state locking in Terraform? Why is it important, and how do you implement it? *(Custom)*
- We are working in a team and multiple members make some changes in same terraform scripts. How can we avoid overriding the backend files? *(Apptware)*
- When you are trying to spinup 10 EC2 machines using terraform, 5 gets created and at the time of creation of 6th the node goes down on EKS. State file is stored at S3. How would you recover from this error of stale state? *(Entain)*

---

## Variables & Configuration

- In which file do you mention values of variables in terraform? *(Helpshift, InfracloudTech)*
- If you want to submit something through your CI pipeline, then how to maintain TFVARS file as the values shouldnt be hardcoded each time? *(Helpshift, InfracloudTech)*
- Can you explain local blocks and data sources blocks in terraform? *(Helpshift)*
- Can you tell me basic difference between count and for_Each in terraform? *(Helpshift)*
- How are you handling sensitive data in terraform or AWS? *(Fiserv)*

---

## Modules & Structure

- What are modules in terraform? *(Helpshift, InfracloudTech)*
- How do you structure terraform for larger environment? How does your directory structure look like in a complex environment wrt modules, workspaces, statefiles? *(Helpshift)*
- If we define modules at root level and reference them, what do you think will be the problem? *(Helpshift)*
- If I have one project folder and I want to use that same codebase on multiple environments like dev, UAT, prod, how can we do that in terraform? *(Allvue)*
- How to setup a terraform project for multi environment setup like dev, staging, prod? *(Securonix)*
- How do you ensure your IaC templates (Terraform/CloudFormation) are secure and reusable? *(SRE/Questions)*

---

## Workspaces

- Command to create workspace *(Fiserv)*
- Can you explain using terraform workspaces vs using separate state files? *(Securonix)*

---

## Terraform with AWS

- Can you tell me a practical example of how to deploy a AWS VPC using terraform scripts? *(Helpshift)*
- We're using EKS cluster, how to use terraform to create resources? *(Helpshift)*
- We created an EC2 using terraform to deploy application. Here I need to change some attributes and now using plan its suggesting for replace. When we do replace our app goes down. How to avoid this? *(InfracloudTech)*
- Have you created infrastructure using terraform? How's your experience on creating backups as well using terraform scripts or modules? *(Persistent)*

---

## Taints & Advanced

- What are taints in terraform? *(Helpshift, InfracloudTech)*
