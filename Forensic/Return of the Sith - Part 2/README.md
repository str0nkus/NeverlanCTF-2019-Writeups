[Return of the Sith - Part 2]
---
Question:
---
	Since they got in with VNC, they were locked into his user account, without any root access.
	The user used SUDO for 'protection' so that means he’s safe from the attacker getting his password, right?
	The goal here is to figure out if the user was able to escalate to root without having the user's password.
	DO BE CAREFUL since messing with a VM has the ability to remove traces of what you’re looking for.
	This IS a forensics challenge.

Answer
---
	1. After traversing the logs for quite some time, i discovered the .xd folder
	2. In the .xd folder there was hiding a sudo-stealer:

![alt text](https://i.imgur.com/H3Wn9qj.png)

Flag:
---
	flag{CHECK-OUT-MY-SUDO-STEALER}
