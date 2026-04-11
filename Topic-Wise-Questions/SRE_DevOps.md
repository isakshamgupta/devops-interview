# SRE & DevOps Concepts Interview Questions (Topic-wise Collection)

---

## SRE Fundamentals

- How do you define Site Reliability Engineering (SRE) and how does it differ from traditional operations? *(SRE/Questions)*
- Can you explain what "toil" means in SRE and how you've reduced it in your projects? *(SRE/Questions)*
- Can you explain what is toil and how can we reduce it? *(Volkswagen)*
- What strategies do you use to balance feature delivery vs. system reliability? *(SRE/Questions)*
- How do you convince product managers to respect error budgets when they push for fast feature delivery? *(SRE/Questions)*
- Developers push new features frequently, and reliability is suffering. How do you handle the tradeoff? *(SRE/Questions)*
- Explain one best practice for SRE in your project *(Persistent)*

---

## SLOs, SLIs, SLAs

- What are SLOs, SLIs, and SLAs? Can you share an example of how you implemented or monitored them? *(SRE/Questions)*
- What do you mean by 99.9% availability in AWS? Have you encountered the situation of unavailability of any resources? *(HCL)*
- How do you approach SLA reporting and analysis to stakeholders? *(Volkswagen)*
- Can you explain scenario where your reports facilitated any strategic decision or process improvement when you reported SLA? *(Volkswagen)*

---

## Incident Management & Response

- Your production service is down. Walk me through your first 5 steps *(SRE/Questions)*
- How do you approach blameless postmortems? Can you walk through a real incident you handled? *(SRE/Questions)*
- What kind of incident management tools you have used and what activities done? *(Entain)*
- You receive multiple alerts at once from different services — how do you prioritize? *(SRE/Questions)*
- A deployment just caused an outage — how do you roll back and prevent this in the future? *(SRE/Questions)*

---

## MTTR & Auto-Remediation

- What metrics do you monitor to measure and reduce MTTR? *(SRE/Questions)*
- You're asked to reduce mean time to recovery (MTTR). What automations would you introduce? *(SRE/Questions)*
- What are some best practices for auto-remediation of incidents? *(SRE/Questions)*
- Explain how you'd design a system to self-heal after a failure *(SRE/Questions)*
- How do you integrate alerting and runbooks to improve incident response time? *(SRE/Questions)*

---

## Troubleshooting Production Issues

- Walk me through how you troubleshoot a production issue when latency suddenly spikes *(SRE/Questions)*
- Latency suddenly spikes in one of your critical APIs — how do you troubleshoot? *(SRE/Questions)*
- A dashboard shows CPU and memory usage are normal, but users still report slowness — what's your approach? *(SRE/Questions)*
- We're running a Job in CI pipeline. One of the API call is getting timed out which DEV is also unable to figure out. How would you help them to figure this out? *(Entain)*
- What you do usually when you want help from other teams and they're not responding? How leadership address these kind of things? *(Entain)*

---

## High Availability & Disaster Recovery

- Can you explain how you've set up highly available and fault-tolerant architectures in AWS? *(SRE/Questions)*
- A region in AWS goes down — how do you design your systems for high availability and fault tolerance? *(SRE/Questions)*
- What you are doing for DR strategy in your current project? *(LTIMindtree)*
- Before setting up infra for an application, what is the process of standardizing any DR? *(AlignedAutomation)*
- Please walk through the Disaster Recovery plans used in your application which circles around database *(Equifax)*

---

## Microservices Resilience

- What is a circuit breaker pattern, and how does it improve microservices reliability? *(SRE/Questions)*
- How do you implement retry logic without causing cascading failures? *(SRE/Questions)*
- Can you explain backoff strategies and when you'd use them? *(SRE/Questions)*
- Describe a scenario where a downstream dependency was failing — how did you keep your service resilient? *(SRE/Questions)*
- How would you design a dependency health check mechanism? *(SRE/Questions)*
- What are the trade-offs between retries and timeouts, and how do you balance them? *(SRE/Questions)*

---

## Performance & Latency

- What are P50, P90, P99 response times and why are they important? *(SRE/Questions)*
- How do you identify and resolve API latency bottlenecks in a distributed system? *(SRE/Questions)*
- Can you share an example where you significantly improved application performance? *(SRE/Questions)*
- How would you design a dashboard to monitor latency SLIs? *(SRE/Questions)*
- If you notice the P99 latency spiking suddenly, what's your troubleshooting approach? *(SRE/Questions)*

---

## Migration & Architecture Decisions

- Can you explain the journey of migrating from on-prem K8S cluster to EKS? What was the approach that was considered moving to EKS cluster? *(Entain)*
- Was the above migration done with downtime? *(Entain)*
- What is the problem you solved in your recent past? *(Entain)*
- In your career have you taken a decision related to application architecture? *(Apptware)*

---

## Deployment Strategies

- What is blue green and canary deployments? Which has downtime? *(Allvue)*
- When to use blue green and when to use canary deployments? *(Entain)*
- How do you justify the cost of maintaining 2 environments in blue green deployments? *(Entain)*

---

## Agile & ITIL

- How is your experience with agile and ITIL frameworks? Have you got a chance to work with priority incidents? *(Volkswagen)*
- Can you explain some agile metrics and why we need to focus on them? *(Volkswagen)*
- What is service lifecycle model in ITIL? *(Volkswagen)*
- In terms of team management, your team members are cherry picking tasks within team. How will you manage? *(Volkswagen)*

---

## Automation & Efficiency

- What is your experience in automating and optimizing deployments? *(HCL)*
- What is the recent automation you did in your current role? *(HCL)*
- Can you tell me any interesting work you did lately? What was the solution and your role involvement? *(Persistent)*
- Explain the challenges you faced when you had to recover situation in production systems *(Persistent)*
- You have mentioned you reduced deployment errors. How did you do that? *(Persistent)*
- What is your core skillset? *(Persistent)*

---

## Cost & Budget

- What do you mean by cost optimization in AWS? What techniques have you used to achieve the same? *(Apptware)*
- Have you got chance to work on budget policy? *(Volkswagen)*
