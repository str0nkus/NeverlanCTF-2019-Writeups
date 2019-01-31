[SQL Fun 2]
---
Question:
---
	REPORT: A Client forgot his Password... again. Could you get it for me? He has a users account and his Lname is Miller if that helps at all. Oh! and Ken was saying something about a new table called passwd; said it was better to separate things
	
	https://challenges.neverlanctf.com:1155

Answer
---
	1. Construct SQLi string to get username and table: SELECT * FROM users WHERE Lname="Miller"

![alt text](https://i.imgur.com/hHdkfAt.png)

	2. Join this table with the passwd table: SELECT * FROM users JOIN passwd WHERE Lname="Miller"

![alt text](https://i.imgur.com/I9G9O1w.png)
	
	3. One of the tables gives us: ZmxhZ3tXMWxsX1kwdV9KMDFOX00zP30=
	4. Decode base64 value
	5. Flag: flag{W1ll_Y0u_J01N_M3?}

Flag:
---
	flag{W1ll_Y0u_J01N_M3?}