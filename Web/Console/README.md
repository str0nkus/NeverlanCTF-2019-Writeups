[Console]
---
Question:
---
	You control the browser
	https://challenges.neverlanctf.com:1120

Answer
---
	1. I spent a long time trying to find the md5 hash "7b1ece53a46f4a5a2995b9cf901bf457" on several sites to see what it was, but no luck.
	2. The question text lead to "You are incontrol of the browser" so i tried to tweak some stuff in the source of the code.
	3. First i tried to change the MD5 hash to see if it had any effect, it did not.
	4. I ended up with changing the getThat to "Y":

![alt text](https://i.imgur.com/laXn5qs.png)

	5. This gave me the flag:

![alt text](https://i.imgur.com/SVU5YDw.png)

Flag:
---
	flag{console_controls_js}