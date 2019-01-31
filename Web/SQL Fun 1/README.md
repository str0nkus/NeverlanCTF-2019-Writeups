[SQL Fun 1]
---
Question:
---
	REPORT: 'My Customer forgot his Password. His Fname is Jimmy. Can you get his password for me? It should be in the users table'
	https://challenges.neverlanctf.com:1150

Answer
---
	SELECT * FROM users WHERE Fname="jimmy"

![alt text](https://i.imgur.com/bN01156.png)

Comment
---
	Flag was easy enough, need to construct a SQL-injection query to get info from the users table where firstname -match "jimmy"

Flag:
---
	flag{SQL_F0r_Th3_W1n}