[It's to KeyZ]
---
Question:
---
	It looks like N30 has been keeping passwords secret with some software he wrote,but he should know better than to rely on proprietary software for security.
	It looks like he left the repo public too!

Answer
---
	1. Who is N30? (https://neverlanctf.com/creators)
	
	2. N30 is (Zane Durkin, co-founder of neverlan - much props bro)
	
	3. After some poking around i found his github (https://github.com/durkinza)
	
	4. Which again led me to the repo "KeyZ" (https://github.com/durkinza/KeyZ)
	
	5. After trying to download the smaz-compression part, which led me into nothingness i tried to utalize the ./key function

	6. After several tries i read the man documentation which lead me to:
	" key -g poetry "Shakespeare's Tenth Sonnet "

	7. I tried the following:
	" root@cccp:~/_git/KeyZ# ./key -g /root/_ctf/neverlanctf/keyz/passwords.keyz "flag" "

![alt text](https://i.imgur.com/KmXNCDU.png)

Flag:
---
	flag{bu7_1ts_pr0pr1etary}