# Docker Interview Questions (Topic-wise Collection)

---

## Dockerfile Basics

- Write a simple docker file to containerize a nodejs app *(CCTech)*
- Write a simple docker file to containerize a java app *(CCTech)*
- Write simple python docker file *(Infospica)*
- If I give you codebase of java application, would you be able to write dockerfile for the same? *(Apptware)*
- Write basic steps involved in writing docker file to build an image *(PivotChain)*
- What is the difference between COPY and ADD in dockerfile? *(InfracloudTech, RakutenSymphony, PivotChain)*
- Can the ENTRYPOINT in dockerfile be overridden? *(InfracloudTech)*
- What is ENTRYPOINT in docker? *(PivotChain)*

---

## Multi-Stage Builds

- What is multi stage docker file? *(InfracloudTech)*
- How many stages we can pass in multi stage docker file at max? *(InfracloudTech)*
- What is multi stage build in docker? *(Infospica, Spryc)*
- Is multi stage build in docker? *(Spryc)*
- Scenario based on dockerfile provided — Python service to be dockerized needs to do a code review of dockerfile. The dockerfile size is very huge. So we can use multi stage builds *(Entain)*

---

## Docker Image Best Practices

- What are the best practices for reducing docker image size? *(LTIMindtree)*
- I dont want to recreate image after 2/3 months as it is having vulnerabilities. But I need to run one image which should have no vulnerabilities in future. Your cluster is having internet access. How can you achieve this when our image runs it has latest packages without vulnerabilities? *(PivotChain)*

---

## Docker Networking & Storage

- What are different types of networks in docker? *(InfracloudTech)*
- While using docker, container gets restarted and we need to have data within containers. How can we do that? *(Persistent)*
- While installing docker on local there are predefined storage area. If you want to alter it, can we alter? *(InfracloudTech)*

---

## Docker Commands & Operations

- Command to run docker container, go inside container *(CCTech)*
- How can we check if docker container is running or not? *(PivotChain)*
- Write stage for building docker image and pushing it to ECR using jenkinsfile *(CCTech)*
- How to authenticate to dockerhub from jenkins? *(Infospica)*

---

## Docker Compose

- Write a simple docker compose file for multiple services *(Infospica)*
- Why we use docker compose? *(Spryc)*

---

## Docker Security

- Assume that you have a dockerfile in which you pass username and password. When doing docker inspect, we can see credentials. So how we can avoid this? *(InfracloudTech)*
- Suppose we've pipeline using which we're building docker image and pushing it to ECR. Here we've to pass AWS credentials in form of access keys. But we dont want to pass credentials or store them on any provider/server. How we can achieve the successful pipeline without storing credentials anywhere? *(MindBowser)*

---

## Docker with Kubernetes

- Developer has developed a Java application. He has given all code to you and you've to put everything inside a container and create a pod out of it. You've to make sure that pod doesnt run without running the application and pod gets down as soon as app gets down. How we can achieve this? *(RakutenSymphony)*
- You have to deploy 2 apps on single EC2 instance in such a way that one is node js and second is java app. But these 2 apps need to be exposed on 2 different IP. How we can setup? *(MindBowser)*
