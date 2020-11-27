## Root It

**user flag** \
Answer: `60989655118397345799`

![image](https://user-images.githubusercontent.com/33615252/100475591-858cdc80-3109-11eb-9083-c424197d7368.png)
![image](https://user-images.githubusercontent.com/33615252/100476420-84f54580-310b-11eb-92f2-f1c2277fd80b.png)

The server is vulnerable to Local File Inclusion attack. \
We can access the /etc/passwd file. In this file we can see ssh credentials of the user \ 
We can then login using the credential and view the contents of user.txt


**root flag** \
Answer: `42964104845495153909`

![image](https://user-images.githubusercontent.com/33615252/100477457-63e22400-310e-11eb-828f-bd8b803e0b21.png)

We see that we can execute `socat` command using root privileges \
We can take advantage of this to spawn a shell \
On that shell we search all txt files on the system with **root** in name \
We find one file and we can view the contents of that file to get our solution
