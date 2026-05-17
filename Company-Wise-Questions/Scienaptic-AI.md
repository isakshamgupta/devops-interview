# ✅ L1 Scienaptic AI  Technical Assessment

## Kubernetes

1. Kubernetes OOM Issue
   - A pod is in **OOMKilled (Out of Memory)** state. How would you troubleshoot and resolve this issue?
   - **Follow-up:** If there is no resource shortage at the **node level**, what additional checks would you perform to identify and fix the issue?

2. Kubernetes Network Isolation Design
   - You have **two applications running in separate pods** and a **shared database pod**.
   - Both applications should be able to communicate with the database, but **must not communicate with each other**.
   - How would you design this using Kubernetes networking concepts?

3. 503 Error Troubleshooting in Kubernetes
   - An end user is trying to access an application deployed on Kubernetes via a **LoadBalancer service**, but receives a **503 error**.
   - Network policies are also configured.
   - How would you troubleshoot this issue end-to-end?

4. Geo-Blocking in Kubernetes
   - How would you **restrict access to your Kubernetes-hosted application based on geographic location (e.g., block specific countries)?**

5. Kubernetes CNI Plugins
   - What are **Kubernetes CNI (Container Network Interface) plugins**?
   - Can you explain their role and give some examples?

6. What is `emptyDir` in Kubernetes?
   - What is `emptyDir` in Kubernetes and how is it used?

## Terraform

7. Terragrunt vs Terraform
   - What is **Terragrunt**, and what problems does it solve that Terraform alone does not address effectively?

8. Terraform State Locking
   - What is **state locking in Terraform**?
   - Why is it important, and how do you implement it?

9. Terraform State File Recovery
   - If the **Terraform state file is accidentally deleted**, how would you recover or rebuild the state?
