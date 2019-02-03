[Bash 4]
---
Question:
---
	ssh -p 3333 level3@157.230.73.80
	Use Bash 3 password: child-of-honor
	So you know how to use grep or some other similar program. Good for you. Now can
	you do the same thing with a binary file?

Answer
---
	1. Downloaded the file "random" via scp
	2. scp -P 3333 level3@157.230.73.80:/home/level3/random /mnt/c/Users/[REDACTED]/Dekstop
	3. Opened the file in notepad++ as it's easy
	4. Ctrl + F searched for level4
	5. Found the following on line 376:

![alt text](https://i.imgur.com/af2MdX2.png)

Flag:
---
	only*hack^things%you$own