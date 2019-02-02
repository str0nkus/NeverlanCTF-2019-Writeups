[Return of the Sith - Part 1]
---
Question:
---
	After a quick gander, we realized the user installed VNC with a crappy password. Can you get the password he used so we can prove to him it was bad?
	Note: The password is the flag, it is not in the flag{} format.

Answer
---
	1. Booted up the VM
	2. We are after the password that VNC is using
	3. We are aware that the passwd file for vnc is stored in /home/KyloRen/.vnc/passwd
	4. Transferred the passwd file to my kali installation
	5. Downloaded the github repo for vncpwd (https://github.com/jeroennijhof/vncpwd)
	6. Used the vncpwd to get the pw
	7. Password = darthvad

![alt text](https://i.imgur.com/zkt9S08.png)

Flag:
---
	darthvad