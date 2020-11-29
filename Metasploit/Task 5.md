## Move that shell!

**Q1:** What service does nmap identify running on port 135? \
Answer: `msrpc`

![image](https://user-images.githubusercontent.com/33615252/100544944-3668b800-327f-11eb-86e9-4e10e7663953.png)

**Q2:** Now that we've scanned our victim system, let's try connecting to it with a Metasploit payload. First, we'll have to search for the target payload. In Metasploit 5 (the most recent version at the time of writing) you can simply type 'use' followed by a unique string found within only the target exploit. For example, try this out now with the following command 'use icecast'. What is the full path for our exploit that now appears on the msfconsole prompt? *This will include the exploit section at the start \
Answer: `exploit/windows/http/icecast_header`

![image](https://user-images.githubusercontent.com/33615252/100545011-9a8b7c00-327f-11eb-9501-fa9085550b7f.png)

**Q3:** What is the name of the column on the far left side of the console that shows up next to 'Name'? \
Answer: `#`

![image](https://user-images.githubusercontent.com/33615252/100545058-ee966080-327f-11eb-99ba-d88b3324795d.png)
