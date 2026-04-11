# Microservices & Architecture Interview Questions (Topic-wise Collection)

---

## Architecture Design

- What is 3 tier application? *(Spryc)*
- As you are using multiple services like VPC, what is the best architecture in terms of security and networking point of view if we need to setup 3 tier architecture in AWS? Where will you place EC2 in that 3 tier architecture? *(AlignedAutomation)*
- Explain the architecture of your project which is deployed on EKS/K8S cluster *(Fortinet)*
- Please explain the K8S Architecture *(InfracloudTech)*
- Explain the Kubernetes Architecture *(LTIMindtree)*
- In your career have you taken a decision related to application architecture? *(Apptware)*

---

## Microservices Communication

- How do you secure communication between microservices in Kubernetes? *(SRE/Questions)*
- If nodes are scattered in 2 different namespaces, how the pods in the nodes connect with each other? *(RakutenSymphony)*
- Lets say your backend service is running in NS1 and DB running in NS2. Now NS1 service has to get connection of DB all the time. What will be the impact? What is the preferred way to get seamless connection? *(RakutenSymphony)*
- I have deployed microservice on K8S cluster and I dont want that cluster to be accessed outside environment. How to configure that? *(AlignedAutomation)*
- How to expose our microservices to external world? *(LTIMindtree)*

---

## Resilience Patterns

- What is a circuit breaker pattern, and how does it improve microservices reliability? *(SRE/Questions)*
- How do you implement retry logic without causing cascading failures? *(SRE/Questions)*
- Can you explain backoff strategies and when you'd use them? *(SRE/Questions)*
- Describe a scenario where a downstream dependency was failing — how did you keep your service resilient? *(SRE/Questions)*
- How would you design a dependency health check mechanism? *(SRE/Questions)*
- What are the trade-offs between retries and timeouts, and how do you balance them? *(SRE/Questions)*

---

## Service Discovery & Load Balancing

- What is the Core DNS in K8S? *(MindBowser)*
- If we have 5 apps on K8S cluster and have 5 individual services for them all of which exposed by clusterIP and we want to expose app via ingress. How to manage LB in that case? *(MindBowser)*
- How will you manage LB in on-prem K8S? *(MindBowser)*
- What is the difference between service and virtual service in K8S? *(PivotChain)*

---

## Performance & Latency

- How do you identify and resolve API latency bottlenecks in a distributed system? *(SRE/Questions)*
- Can you share an example where you significantly improved application performance? *(SRE/Questions)*
- There is performance issue in business critical application which seems to be related to DB query from logs. How would you handle the situation minimizing impact and later resolve it? *(Volkswagen)*

---

## Message Queues & Dependencies

- When you deploy your app on worker nodes, does your replication use any external services like message queues and how do you manage them? *(Fortinet)*

---

## Hosting & Deployment

- Where the application is hosted and how SGs are helping to restrict access on the app? *(Spryc)*
- You have to deploy 2 apps on single EC2 instance in such a way that one is node js and second is java app. But these 2 apps need to be exposed on 2 different IP. How we can setup? *(MindBowser)*
- Can we attach 2 EC2 IPs to single EC2 instance? *(MindBowser)*
