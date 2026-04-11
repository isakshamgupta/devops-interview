# Monitoring & Observability Interview Questions (Topic-wise Collection)

---

## General Monitoring

- What kind of monitoring do you support and use? *(Allvue)*
- How is the monitoring done in your project using DataDog and Splunk? Is it using metrics or any other means? *(Persistent)*
- In past 6 months which tools have you used mostly? How are you deploying applications onto servers? *(Infospica)*
- What was your evaluation criteria to choose monitoring tool for your EKS cluster? *(Entain)*
- For a production application, what all metrics will you setup for that application? *(Equifax)*
- What kind of automations have you done in your projects? *(Equifax)*

---

## DataDog

- Datadog is agentless or agent based? *(AlignedAutomation)*
- How do you monitor your K8S cluster using datadog? *(AlignedAutomation)*
- What are the most important metrics you consider while monitoring EKS cluster using datadog? *(Entain)*

---

## Splunk

- How to setting up splunk for any application? *(AlignedAutomation)*
- If there is performance related issue showing in splunk logs, how to troubleshoot it? *(AlignedAutomation)*

---

## CloudWatch

- Is cloudwatch agent is mandatory to configure metrics/services monitoring? *(CCTech)*
- What all the services have you done on cloudwatch? *(HCL)*
- In cloudwatch, what all things have you worked upon? *(Apptware)*
- Have you worked on cloudwatch alerts? How did you configure them? *(Apptware)*
- Can you explain difference between cloudwatch logs and cloudwatch metrics? *(Volkswagen)*
- How cloudwatch detects things like node is down, crashLoopBackoff errors? *(Fortinet)*
- EC2 went down and I want alert triggered. How to configure in AWS? *(T-Systems)*

---

## Alerting & Notifications

- In SNS what all options do we have for alerts? *(Apptware)*
- Did you face any challenges in setting up SMS notifications delivery? *(Apptware)*
- How did you set up the subscribers list in SNS? *(Apptware)*
- You're getting too many false alerts from your monitoring system. What steps would you take to tune it? *(SRE/Questions)*
- How do you integrate alerting and runbooks to improve incident response time? *(SRE/Questions)*

---

## Logging

- Which tool do you use for logging? *(CCTech)*
- Can you explain monitoring and logging used for your deployment? *(Fortinet)*
- How do you use logs, metrics, and traces together for root cause analysis? *(SRE/Questions)*
- Logs are growing too fast and filling up disk space — how do you handle log rotation and retention? *(SRE/Questions)*

---

## Metrics & Performance

- What is the difference between average and percentile? *(Equifax)*
- Can you explain 400 and 500 HTTP codes? *(Equifax)*
- What are P50, P90, P99 response times and why are they important? *(SRE/Questions)*
- How would you design a dashboard to monitor latency SLIs? *(SRE/Questions)*
- If you notice the P99 latency spiking suddenly, what's your troubleshooting approach? *(SRE/Questions)*
- A dashboard shows CPU and memory usage are normal, but users still report slowness — what's your approach? *(SRE/Questions)*
- Difference between CPU utilization and load average in Linux *(Helpshift)*

---

## Kubernetes Monitoring

- Your monitoring system give alert of high CPU usage unexpectedly on K8S node. How would you troubleshoot to identify cause and mitigate it? *(Volkswagen)*
- If any node is down on prod how will you get to know that? What will be the troubleshooting steps? *(Fortinet)*
- If we're not using cloudwatch, what could be other way to check if node is down in automatic way? Where the cron job will run? *(Fortinet)*
- How to check resource utilization of nodes in K8S? *(PivotChain)*

---

## Troubleshooting with Monitoring

- Walk me through how you troubleshoot a production issue when latency suddenly spikes *(SRE/Questions)*
- Latency suddenly spikes in one of your critical APIs — how do you troubleshoot? *(SRE/Questions)*
- You receive multiple alerts at once from different services — how do you prioritize? *(SRE/Questions)*
- There is performance issue in business critical application which seems to be related to DB query from logs. How would you handle the situation minimizing impact and later resolve it? *(Volkswagen)*
- How do you identify and resolve API latency bottlenecks in a distributed system? *(SRE/Questions)*
