# Linux & Shell Scripting Interview Questions (Topic-wise Collection)

---

## Linux Administration & Troubleshooting

- What kind of linux administration experience do you have? *(GlobalPayments)*
- Can you explain Linux file structure or directory structure? *(GlobalPayments)*
- One of the production Linux server doesnt boot properly and its stuck. What steps will you take to troubleshoot? *(T-Systems)*
- There is a critical linux server and disk usage is 100% and application is stopped. How to troubleshoot? *(T-Systems)*
- Your system is not able to login from customer side and issue is showing as permission denied. How will you troubleshoot? *(T-Systems)*
- Suppose any service fails to start in Linux system, what will you check and troubleshoot? *(T-Systems)*
- If any filesystem is corrupted, what things will you check? *(T-Systems)*
- I accidentally deleted /etc/passwd file. I want to recover the same. How will you do it? *(T-Systems)*
- My system suddenly gets rebooted, how to check what happened? *(T-Systems)*
- I updated my kernel and rebooted. Now system drops to kernel panic like unable to mount rootfs throwing unexpected error. In this case what can be done? *(T-Systems)*
- My server becomes unresponsive due to OOM exception. How will be your approach to troubleshoot? *(T-Systems)*
- I want to have certain entries without entering config file in Linux. How will I do that? *(T-Systems)*

---

## Disk & Storage

- Suppose your disk usage is very high and you want to see which directories or files are consuming more space. Which command will you use? *(Persistent)*
- What is difference between du and df? *(GlobalPayments)*
- What do you understand by mounting a disk persistently? *(T-Systems)*
- I want to resize partition in Linux machine. What is the command used? *(T-Systems)*
- What is swap memory? *(GlobalPayments)*

---

## Process & Performance Monitoring

- How to monitor linux server performance? *(GlobalPayments)*
- Can you tell me how to find load average of any system in linux? What are 3 main numbers in load average? *(Helpshift)*
- Difference between CPU utilization and load average in Linux *(Helpshift)*
- How do you find out most I/O consuming processes in linux? *(Helpshift)*
- How do you identify if your system is capable of handling memory related workloads? How to check if its choking on memory? *(Helpshift)*
- How do you kill process and what exact flags we can use for it? *(Helpshift)*
- How to check if process is running or not in Linux? *(PivotChain)*
- How to check CPU cores in linux? *(PivotChain)*
- How to check RAM on linux machine and also storage? *(PivotChain)*

---

## Networking Commands

- How to check connectivity between 2 instances? *(Helpshift)*
- Can you explain some TCP connection states like what connection state you usually see when you see charts of TCP connections active? *(Helpshift)*
- Command to check what connections are active in your machine *(Helpshift)*
- How to check if port is open or not? *(PivotChain)*
- How to check IP address of machine? *(PivotChain)*
- I am not able to login remote machine using SSH. What can we do? *(PivotChain)*

---

## Log Management

- In order to troubleshoot any issue, what types of var files do we monitor? If my server has booted, where the logs get recorded? *(GlobalPayments)*
- If user is unable to login to server, which log file should we check? *(GlobalPayments)*
- Any cronjob didnt work properly, how will you troubleshoot? Log path for cronjob *(T-Systems)*
- Logs are growing too fast and filling up disk space — how do you handle log rotation and retention? *(SRE/Questions)*

---

## Shell Scripting

- What kind of automation you did with shell scripting? *(Spryc)*
- Can you explain what kind of automations have you done using lambda or shell scripting? *(Allvue)*
- If you have written shell script to take backup and have scheduled shell script via cron job that runs at some time everyday, how can we ensure that script is running everyday? Also how we get to know that its running at the specified time? *(AlignedAutomation)*
- Without checking log file where logs getting appended, can we check if script is running? *(AlignedAutomation)*
- If you have to write shell script to monitor CPU usage which gives you alert when 80% is breached, how will you write that? *(Persistent)*
- You need to automate user creation in active directory in shell. How would you create it? *(Persistent)*
- Can you give an example of a bash script you wrote for automation or monitoring? *(SRE/Questions)*
- Explain a scenario where your scripting reduced manual effort significantly *(SRE/Questions)*
- How do you structure error handling and logging in your scripts? *(SRE/Questions)*

---

## Shell Commands & Utilities

- Can you give me command to find modified files in last 24 hrs and compress them into a single file? Give single command *(Fiserv)*
- If I want to replace a string in file with another string, which command to use? *(Fiserv)*
- Which command is used to substitute a string or pattern within a particular directory in Linux? *(Custom)*
- Using above command if I want alternate occurrences of string to be replaced in a file, how to do that? *(Fiserv)*
- How do you filter or search for a specific word/pattern in Linux using grep or sed? *(Custom)*
- What is the difference between $* and $@ in shell? *(Fiserv)*
- Write a Python script to search for a specific file within a folder or directory. *(Custom)*
