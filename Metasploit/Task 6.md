## We're in, now what? 

**Q1:** First things first, our initial shell/process typically isn't very stable. Let's go ahead and attempt to move to a different process. First, let's list the processes using the command 'ps'. What's the name of the spool service? \

Answer: `spoolsv.exe`

![image](https://user-images.githubusercontent.com/33615252/100545440-cad41a00-3281-11eb-9f83-0c0d246dba72.png)

**Q2:** Let's go ahead and move into the spool process or at least attempt to! What command do we use to transfer ourselves into the process? This won't work at the current time as we don't have sufficient privileges but we can still try \

Answer: `migrate`

![image](https://user-images.githubusercontent.com/33615252/100545663-e986e080-3282-11eb-8e3d-01e922dab598.png)

**Q3:** Well that migration didn't work, let's find out some more information about the system so we can try to elevate. What command can we run to find out more information regarding the current user running the process we are in? \

Answer: `getuid`

**Q4:** How about finding more information out about the system itself? \

Answer: `sysinfo`

![image](https://user-images.githubusercontent.com/33615252/100545716-3965a780-3283-11eb-852c-3e6a5e8a481d.png)

