## We're in, now what? 

**Q1:** First things first, our initial shell/process typically isn't very stable. Let's go ahead and attempt to move to a different process. First, let's list the processes using the command 'ps'. What's the name of the spool service?

Answer: `spoolsv.exe`

![image](https://user-images.githubusercontent.com/33615252/100545440-cad41a00-3281-11eb-9f83-0c0d246dba72.png)

**Q2:** Let's go ahead and move into the spool process or at least attempt to! What command do we use to transfer ourselves into the process? This won't work at the current time as we don't have sufficient privileges but we can still try

Answer: `migrate`

![image](https://user-images.githubusercontent.com/33615252/100545663-e986e080-3282-11eb-8e3d-01e922dab598.png)

**Q3:** Well that migration didn't work, let's find out some more information about the system so we can try to elevate. What command can we run to find out more information regarding the current user running the process we are in?

Answer: `getuid`

**Q4:** How about finding more information out about the system itself?

Answer: `sysinfo`

![image](https://user-images.githubusercontent.com/33615252/100545716-3965a780-3283-11eb-852c-3e6a5e8a481d.png)

**Q5:** This might take a little bit of googling, what do we run to load mimikatz (more specifically the new version of mimikatz) so we can use it? /

Answer: `load kiwi`

**Q6:** Let's go ahead and figure out the privileges of our current user, what command do we run?

Answer: `getprivs`

![image](https://user-images.githubusercontent.com/33615252/100546143-aa0dc380-3285-11eb-832f-c9a4f70f825e.png)

**Q7:** What command do we run to transfer files to our victim computer?

Answer: `upload`

![image](https://user-images.githubusercontent.com/33615252/100546215-15f02c00-3286-11eb-998f-6ef6437aca3d.png)

**Q8:** How about if we want to run a Metasploit module?

Answer: `run`

![image](https://user-images.githubusercontent.com/33615252/100546279-89923900-3286-11eb-86c4-e5d659c9cc22.png)

**Q9:**  A simple question but still quite necessary, what command do we run to figure out the networking information and interfaces on our victim? 

Answer: `ipconfig`

![image](https://user-images.githubusercontent.com/33615252/100546333-daa22d00-3286-11eb-809a-42a547b14f87.png)

**Q10:** One quick extra question, what command can we run in our meterpreter session to spawn a normal system shell? 

Answer: `shell`

![image](https://user-images.githubusercontent.com/33615252/100546569-12f63b00-3288-11eb-9738-0a37f2c0b97f.png)


**Other**

![image](https://user-images.githubusercontent.com/33615252/100546713-d70fa580-3288-11eb-982e-0e51f8574d50.png)
