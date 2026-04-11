# CI/CD Pipeline Interview Questions (Topic-wise Collection)

---

## Jenkins Pipeline

- What are the types of pipelines in Jenkins? Write declarative syntax with common stages *(CCTech)*
- What is the difference between Scripted and declarative pipeline? *(HSBC)*
- Write jenkins pipeline stages *(Infospica)*
- What are stages in your Jenkins pipeline? *(LTIMindtree)*
- Write the base steps used in CICD pipeline and state plugins used *(RakutenSymphony)*
- In jenkins, what are different stages are you using inside pipeline? *(Fiserv)*
- How is structure of CICD pipelines at your organization? *(Spryc)*
- Can you explain any CICD process that you have implemented in your project? *(PivotChain)*
- Can you explain what is CICD and how do you setup in your project? *(Allvue)*

---

## Jenkins Architecture & Configuration

- What is jenkins architecture? *(InfracloudTech)*
- What are different types of jenkins jobs? *(InfracloudTech)*
- What is a multi-branch pipeline? *(InfracloudTech)*
- What is jenkins agent? *(RakutenSymphony)*
- If you have hundreds of worker nodes and want to run hundreds of jobs concurrently with almost no queuing, how to do that in jenkins? *(InfracloudTech)*
- There is a plugin called active choice active parameter in jenkins. Why it is used? *(RakutenSymphony)*

---

## Jenkins Security & Credentials

- How to pass credentials inside jenkins pipeline? *(CCTech)*
- How do you secure credentials in jenkins? *(CCTech)*
- In jenkins suppose there is an user who needs access to specific folder, how to achieve that? Which plugin is used? *(Helpshift)*
- How to authenticate to dockerhub from jenkins? *(Infospica)*

---

## Jenkins with Docker/K8S

- Write stage for building docker image and pushing it to ECR using jenkinsfile *(CCTech)*
- Suppose developer writes code in GitHub repo which we need to checkout and deploy on EKS cluster. What pipelines steps are required? *(HSBC)*
- How to setup CICD pipeline to deploy artifacts to EKS cluster? *(Equifax)*
- In your CICD pipeline, how will you ensure deployment file has the latest image we pushed to ECR? *(Equifax)*
- If we're deploying image on EKS cluster, I want to split that image name with colon with string variable in pipeline, how to do that? *(HSBC)*
- You might have integrated Jenkins with your EKS cluster. Where you will be adding cluster details like API server endpoints, secrets in Jenkins? *(LTIMindtree)*

---

## Jenkins Scripting

- How do you sandwich shell inside a pipeline? *(RakutenSymphony)*
- If you have to deploy application on linux environment, how will you connect linux from jenkins? *(CCTech)*

---

## Build Tools

- When you do maven clean install, does that require internet access over the servers? *(Apptware)*
- I have javascript backend app and react frontend app. I am building backend app from maven and doing npm install for frontend app. We're deploying the apps manually. We've to pitch implementation plan to build and deploy apps from scratch using CI/CD approach to client. *(CCTech)*

---

## Deployment Strategies

- What is blue green and canary deployments? Which has downtime? *(Allvue)*
- When to use blue green and when to use canary deployments? *(Entain)*
- How do you justify the cost of maintaining 2 environments in blue green deployments? What factors are considered while applying this strategy? *(Entain)*
- How to deploy app on production without downtime? *(Infospica)*
- How do you ensure there is zero downtime during app upgrade? *(Fortinet)*

---

## Branching Strategies

- What are standard branching strategies used for an application? *(AlignedAutomation, Entain)*
- What branching strategies do you use in your current project? *(InfracloudTech)*
- What is the branching strategy you use in project? *(LTIMindtree)*

---

## Code Quality & Security

- How have you integrated Security tool like sonarqube with application? *(CCTech)*
- If there is any vulnerability in code, what is the approach to resolve? *(CCTech)*
- We're running a Job in CI pipeline. One of the API call is getting timed out which DEV is also unable to figure out. How would you help them to figure this out? *(Entain)*

---

## CI/CD General

- What all things in CI/CD have you worked on? *(Apptware)*
- If you have deployed dev branch and deployed on dev env, if I want to move that code to staging env, how to do that? *(AlignedAutomation)*
- How to maintain branching standards once testing is done and we want to move code from dev to staging? *(AlignedAutomation)*
- A deployment just caused an outage — how do you roll back and prevent this in the future? *(SRE/Questions)*
