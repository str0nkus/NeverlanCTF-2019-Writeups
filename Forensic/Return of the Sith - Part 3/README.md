[Return of the Sith - Part 3]
---
Question:
---
	Ok, great. They had full root access, did they leave anything else behind? Any other backdoor?

Answer
---
	1. After some research in the bash_history, i was able to spot something weird.

![alt text](https://i.imgur.com/ILWmCs6.png)

	2. Looks like the user mysql has been turned to root
	3. SSH has been enabled, and mysql user is allowed with sh-shell.

Flag:
---
	mysql