[Bash 6]
---
Question:
---
	ssh -p 3333 level5@157.230.73.80
	Use Bash 5 password
	Look around for more guidance.


Answer
---
	1. There is located a picture in the homedirectory called "Syl.jpg"
	2. I'll pull that to my local machine to look at it
	3. scp -P 3333 level5@157.230.73.80:/home/level5/Syl.jpg /mnt/c/Users/[Redacted]/Desktop
	4. Picture contains flag: have-you-memorized-the-code-yet

Flag:
---
	have-you-memorized-the-code-yet