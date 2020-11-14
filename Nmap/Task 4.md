## Nmap Scanning

Perform some basic nmap scanning and learn to read through the results
<br/><br/>


**Let's go ahead and start with the basics and perform a syn scan on the box provided. What will this command be without the host IP address?**

Answer: `nmap -sS`

<br/>

**After scanning this, how many ports do we find open under 1000?**

Answer: `2`

![image](https://user-images.githubusercontent.com/33615252/99152435-c75c6280-26c7-11eb-953a-abd2255fc30b.png)

<br/>

**What communication protocol is given for these ports following the port number?**

Answer: `tcp`

<br/>

**Perform a service version detection scan, what is the version of the software running on port 22?**

Answer: `6.6.1p1`

![image](https://user-images.githubusercontent.com/33615252/99152506-51a4c680-26c8-11eb-8db2-b2efd89e823b.png)

<br/>

**Perform an aggressive scan, what flag isn't set under the results for port 80?**

Answer: `httponly`

![image](https://user-images.githubusercontent.com/33615252/99152599-bd872f00-26c8-11eb-920a-8fc9b7187872.png)

<br/>

**Perform a script scan of vulnerabilities associated with this box, what denial of service (DOS) attack is this box susceptible to? Answer with the name for the vulnerability that is given as the section title in the scan output. A vuln scan can take a while to complete. In case you get stuck, the answer for this question has been provided in the hint, however, it's good to still run this scan and get used to using it as it can be invaluable.**

Answer: `http-slowloris-check`

![image](https://user-images.githubusercontent.com/33615252/99152779-efe55c00-26c9-11eb-8b00-fd85747ad51c.png)
