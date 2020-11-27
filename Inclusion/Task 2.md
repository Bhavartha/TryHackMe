## Root It

**user flag** \
Answer: `60989655118397345799`

![image](https://user-images.githubusercontent.com/33615252/100475591-858cdc80-3109-11eb-9083-c424197d7368.png)
![image](https://user-images.githubusercontent.com/33615252/100476420-84f54580-310b-11eb-92f2-f1c2277fd80b.png)

The server is vulnerable to Local File Inclusion attack. \
We can access the /etc/passwd file. In this file we can see ssh credentials of the user \ 
We can then login using the credential and view the contents of user.txt
