# Kubernetes Interview Questions (Topic-wise Collection)

---

## Architecture & Core Concepts

- Please explain the K8S Architecture *(InfracloudTech)*
- Explain the Kubernetes Architecture *(LTIMindtree)*
- What is CNI? *(HCL)*
- What are Kubernetes CNI (Container Network Interface) plugins? Can you explain their role and give some examples? *(Custom)*
- What are the different CNI plugins available in K8S? *(InfracloudTech)*
- What are different CRIs (Container Runtime Interfaces)? *(InfracloudTech)*
- What is the role of kubeproxy? *(InfracloudTech)*
- What is the Core DNS in K8S? *(MindBowser)*
- How to manage K8S DNS? *(AlignedAutomation)*
- DNS resolution is failing inside Kubernetes pods — how do you troubleshoot? *(SRE/Questions)*
- What is configMap? *(RakutenSymphony)*
- What is the purpose of a ServicePort in Kubernetes? *(Custom)*
- What is a Deployment in K8s, and how does it manage pods? *(Custom)*
- How do you separate environments (like Dev, Staging, Prod) within Kubernetes or across clusters? *(Custom)*
- What is init container? *(LTIMindtree)*
- What is daemon sets? *(LTIMindtree)*
- What is the key difference between deployments and stateful sets? *(LTIMindtree)*
- Explain the difference between deployment, stateful set and daemon set in K8S *(PivotChain)*
- How to pass env variables to deployment? *(LTIMindtree)*
- If we dont specify replicas in deployment manifest, what will happen? *(Equifax)*
- Write deployment manifest to deploy 2 instances of nginx and explain the same *(Infospica)*
- What is service account in K8S cluster? *(RakutenSymphony)*

---

## Services & Networking

- Difference between clusterIP, nodeport and LB services? *(AlignedAutomation)*
- Can you explain difference between services modes node port and cluster IP in K8S and tell use cases? *(Spryc)*
- Can you explain how does service maps incoming calls to particular pod or app? *(Equifax)*
- What will happen if labels and selectors dont match? *(Equifax)*
- Can you explain difference between external and internal service? *(Equifax)*
- Can a service of type ClusterIP access pod which is on different cluster? *(Equifax)*
- What is the difference between LB service type and ingress? Why ingress is used if we have LB service type? *(AlignedAutomation)*
- What is the difference between K8S ingress and LB service? *(PivotChain)*
- What is Ingress Controllers? *(HCL)*
- What are the different ingress resources you have used? SSL offloading is happening at SSL, I want it to happen at pod level. How to achieve this? *(InfracloudTech)*
- Explain strategy to setup ingress controller in EKS and doing SSL termination *(Securonix)*
- If we have 5 apps on K8S cluster and have 5 individual services for them all of which exposed by clusterIP and we want to expose app via ingress. How to manage LB in that case? *(MindBowser)*
- How will you manage LB in on-prem K8S? *(MindBowser)*
- How to expose our microservices to external world? *(LTIMindtree)*
- What is the difference between service and virtual service in K8S? *(PivotChain)*
- What is NATting in K8S? SNAT and DNAT *(MindBowser)*
- If nodes are scattered in 2 different namespaces, how the pods in the nodes connect with each other? *(RakutenSymphony)*
- Lets say your backend service is running in NS1 and DB running in NS2. Now NS1 service has to get connection of DB all the time. Now consider 2 scenarios where DB is using node port and then cluster IP, DB port gets down and gets up. What will be the impact in both cases? What is the preferred way to get seamless connection in case our pod goes down? *(RakutenSymphony)*
- A network policy is blocking traffic between services in different namespaces. How would you design and debug the policy to allow only specific communication paths? *(K8S_SBQ)*
- You have two applications running in separate pods and a shared database pod. Both applications should be able to communicate with the database, but must not communicate with each other. How would you design this using Kubernetes networking concepts? *(Custom)*
- An end user is trying to access an application deployed on Kubernetes via a LoadBalancer service, but receives a 503 error. Network policies are also configured. How would you troubleshoot this issue end-to-end? *(Custom)*
- How would you restrict access to your Kubernetes-hosted application based on geographic location (e.g., block specific countries)? *(Custom)*
- I have deployed microservice on K8S cluster and I dont want that cluster to be accessed outside environment. How to configure that? *(AlignedAutomation)*
- Where can we check if inter pod communication is allowed? *(AlignedAutomation)*
- Suppose you have deployed application on EKS cluster and for some reason your pods are not able to communicate with each other. What could be the reason? *(AlignedAutomation)*

---

## Pods, Scheduling & Scaling

- Developer has developed a Java application. He has given all code to you and you've to put everything inside a container and create a pod out of it. You've to make sure that pod doesnt run without running the application and pod gets down as soon as app gets down. How we can achieve this? *(RakutenSymphony)*
- What is readiness and liveness probes in K8S? *(Equifax)*
- Suppose you have deployed an application and its failing with error in readiness probe of pod. How will you debug the issue? *(Equifax)*
- Are you handling graceful termination in K8S pods? *(Spryc)*
- How do you handle graceful termination of pods in Kubernetes? *(SRE/Questions)*
- Suppose you have a pod and you want to restrict it going into some of the worker nodes, what will you do? *(LTIMindtree)*
- I have an application to be deployed in which I have 3 replicas. All 3 should be deployed on different nodes. How we can achieve this? *(InfracloudTech)*
- If we need pods to run on multiple nodes, how to achieve that? *(Fortinet)*
- Using anti affinity, how to manage 10000 pods? *(Fortinet)*
- If there are multiple worker nodes and 100s of pods are running on them, one node goes down due to some reason, what will happen in that case? How they will be scheduled on other nodes? *(Fortinet)*
- If any scaling is required for the deployment you've created, how you can do it? *(Fortinet)*
- Have you used HPA in your current project? What kind of conditions you're setting in HPA manifest files? *(Fortinet)*
- How are you doing K8S auto scaling? Describe HPA, VPA, CA *(Fiserv)*
- Can you horizontally scale the pod based on CPU/Memory metrics? *(LTIMindtree)*
- Your cluster autoscaler is not scaling up even though pods are in Pending state. What would you investigate? *(K8S_SBQ)*

---

## Storage & Volumes

- What do you mean by PV and PVC? *(HCL)*
- What if I delete PVC for a pod by mistake? *(HCL)*
- What if we delete PV? *(HCL)*
- State different volume access modes in K8S *(InfracloudTech)*
- A stateful set in Kubernetes is losing data after pod restarts — what's your approach? *(SRE/Questions)*
- You have a StatefulSet deployed with persistent volumes, and one of the pods is not recreating properly after deletion. What could be the reasons, and how do you fix it without data loss? *(K8S_SBQ)*
- How are you taking backups of K8S PV? *(LTIMindtree)*
- What is emptyDir in Kubernetes? What are its uses? *(Custom)*
- If we delete the pod, the copied content bound to it will be deleted or not? *(LTIMindtree)*

---

## Cluster Management & Troubleshooting

- Your pod keeps getting stuck in CrashLoopBackOff, but logs show no errors. How would you approach debugging and resolution? *(K8S_SBQ)*
- A pod is in OOMKilled (Out of Memory) state. How would you troubleshoot and resolve this issue? *(Custom)*
- **Follow-up:** If there is no resource shortage at the node level, what additional checks would you perform to identify and fix the issue? *(Custom)*
- If pods are stuck in crashed loop backoff, how to troubleshoot? *(Securonix)*
- If you have deployed app on K8S and pod is not coming up, how will you debug the issue? *(HSBC)*
- How do you debug K8S pods with different commands? *(Fiserv)*
- If any node is down on prod how will you get to know that? What will be the troubleshooting steps? *(Fortinet)*
- If our worker node goes down in our K8S cluster, what steps would you take to troubleshoot the issue? *(PivotChain)*
- How cloudwatch detects things like node is down, crashLoopBackoff errors? *(Fortinet)*
- If we're not using cloudwatch, what could be other way to check if node is down in automatic way? Where the cron job will run? *(Fortinet)*
- How are you maintaining High Availability if you have 70 pods running on multiple nodes? *(Fortinet)*
- How do you define there will be 3 master nodes or multiple etcd instances for app? *(Fortinet)*
- Assume that you have a K8S cluster with single master node. But on single master I need 3 etcd instances. How to achieve this? *(InfracloudTech)*
- Have you ever backed up etcd data? *(InfracloudTech)*
- How much traffic is required to have 20 master nodes? *(Fortinet)*
- How big is your prod cluster? How many master and worker nodes are there? *(Fortinet)*
- How many users consume these services? *(Fortinet)*
- For each service how many replicas are there? *(Fortinet)*
- Assume we've K8S cluster with multiple master and 5 worker nodes and we've app deployed on worker nodes. Application has 2 replicas. Application is exposed using nodePort service on 30000 port. The user is hitting the request on 30000 port on worker node 5. Will he get the response? *(InfracloudTech)*
- Assume the master node went down and we're hitting it with DNS service. Will we get the response back from application? *(InfracloudTech)*
- In K8S master node is the brain of cluster. In public cloud master node should be managed by cloud provider. If in on-prem cluster our master node goes down and application is not running properly. As a devops engineer how to ensure master node should not be down and if it goes down how it should auto heal? *(MindBowser)*
- On public cloud EKS we have multiple node. So even if one node goes down we can have another node up and reattch to master node. But in on-prem we cannot do that. If on-prem node goes down, how to make that node up and reattch to master? *(MindBowser)*

---

## Deployment & Updates

- Can you tell me the process of deployment of app on K8S cluster? *(Fortinet)*
- Can you explain how to deploy Linux application in K8S? *(PivotChain)*
- How do you update the application or image, how to do that? *(Fortinet)*
- If there are 100s of microservices running, how can we change image of each? *(Fortinet)*
- How do you update the config map if the CM value is changed? *(Fortinet)*
- What is your update strategy for prod clusters like EKS? *(Fortinet)*
- How do you ensure there is zero downtime during app upgrade? *(Fortinet)*
- Its quite difficult to manage manifest files for different services. How are you managing them? Did you evaluate any other tools to manage manifest files? *(Entain)*

---

## Security in Kubernetes

- How to manage security in kubernetes? *(Infospica)*
- How do you maintain security of cluster to ensure its vulnerability free? *(Fortinet)*
- How are you managing secrets of applications? *(Fortinet)*
- How do you handle secrets in K8S? *(PivotChain)*
- How to manage secrets in EKS clusters securely? *(Securonix)*
- Are K8S secrets safe to use? *(InfracloudTech)*
- You have a pod for which you want to restrict access on other K8S objects, how to control that in K8S? *(LTIMindtree)*
- How do you secure communication between microservices in Kubernetes? *(SRE/Questions)*

---

## EKS Specific

- Explain the architecture of your project which is deployed on EKS/K8S cluster *(Fortinet)*
- What was your contribution in configuring EKS cluster? *(Spryc)*
- What different cluster types in EKS? *(Apptware)*
- We run into disaster and application goes down. You have access to EKS cluster. If I ask you to take etcd snapshot, will it be possible? *(Apptware)*
- On EKS we've deployed 2 services nginx and tomcat. Both having deployment and service components. How nginx deployment will know it should connect to respective nginx service and similarly for tomcat? *(LTIMindtree)*
- You might have integrated Jenkins with your EKS cluster. Where you will be adding cluster details like API server endpoints, secrets in Jenkins? *(LTIMindtree)*
- Consider in one VPC you have EKS and in another VPC you have jump server. How the connectivity will occur? *(LTIMindtree)*
- If you have some files into local or jump server and you've to connect to EKS cluster and copy files to PODS in EKS, how to copy those files? *(LTIMindtree)*
- If you want to copy a file inside a namespace, which command will you use? *(HCL)*
- If you have 2 namespaces, how to ensure particular app is deployed to specific namespace only? State command *(HSBC)*
- Under the prod namespace, I want to deploy one application? *(HCL)*
- Suppose our subnet is having IP exhaustion issue but new pods need to be launched, how to tackle this? *(Securonix)*
- Can you explain process to deploy K8S cluster in an offline environment without any internet access? *(PivotChain)*
- How will you manage image pull issue is there from online access in K8S cluster? *(PivotChain)*
- What challenges have you faced working with EKS/Kubernetes in production, and how did you resolve them? *(SRE/Questions)*
- Can you explain the journey of migrating from on-prem K8S cluster to EKS? What was the approach that was considered moving to EKS cluster? *(Entain)*
- From K8S perspective what standards do you follow for the on-premises deployments? *(AlignedAutomation)*

---

## Scenario-Based (K8S_SBQ)

- Your pod keeps getting stuck in CrashLoopBackOff, but logs show no errors. How would you approach debugging and resolution?
- You have a StatefulSet deployed with persistent volumes, and one of the pods is not recreating properly after deletion. What could be the reasons, and how do you fix it without data loss?
- Your cluster autoscaler is not scaling up even though pods are in Pending state. What would you investigate?
- A network policy is blocking traffic between services in different namespaces. How would you design and debug the policy to allow only specific communication paths?

---

## NLB / ALB in K8S

- What is the difference between ALB and NLB? *(Apptware)*
- If we have K8S cluster, can we use NLB over there? *(Apptware)*
- I have deployment that scales upto 10 replicas and NLB has specific/static IPs that exposes those pods. What about new pods that get generated during scaling or rollout? How NLB handle this if IPs are fixed? *(Apptware)*
- We have K8S cluster. We've to deploy database as K8S object. Which object type can we use? *(Apptware)*
- If you want to deploy same manifest yml file into AWS, is there anything we need to create for DB in AWS? Which one to use EBS or EFS? *(Apptware)*

---

## Monitoring K8S

- Can you explain monitoring and logging used for your deployment? *(Fortinet)*
- How do you monitor your K8S cluster using datadog? *(AlignedAutomation)*
- What are the most important metrics you consider while monitoring EKS cluster using datadog? *(Entain)*
- What was your evaluation criteria to choose monitoring tool for your EKS cluster? *(Entain)*
- How to check resource utilization of nodes in K8S? *(PivotChain)*
- Your monitoring system give alert of high CPU usage unexpectedly on K8S node. How would you troubleshoot to identify cause and mitigate it? *(Volkswagen)*
