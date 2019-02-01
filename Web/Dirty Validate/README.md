[Dirty Validate]
---
Question:
---
	To keep my server from doing a lot of work, I made javascript do the heavy lifting of checking a user's password
	https://challenges.neverlanctf.com:1135

Answer
---
	1. First i did some testing in regards of the username / password bit, and what it actually checks

![alt text](https://i.imgur.com/7BC61Hi.png)
	
	2. I looked through the source-code but didn't become any smarter, as I am a noob in JS.
	3. I started to look at what the browser did in the connection state to the .php scripts.
	4. It looks like this:

![alt text](https://i.imgur.com/lcndqdG.png)

	5. I followed the link, and got the information about the users:

![alt text](https://i.imgur.com/Ocf9APv.png)

	6. After inputing username and "test" as password i tried to follow the users, which in turn gave me the following:
	-
	JimmyOneShoe
	V3JvbmcgdXNlcg==
	Wrong user
	-
	Mr. Clean
	bm90IHRoaXMgb25lIGVpdGhlci4uLg0K
	not this one either...
	-
	Dr. Whom
	ZmxhZ3tEMG4ndF83cnVzN19KU30=
	flag{D0n't_7rus7_JS}

Flag:
---
	flag{D0n't_7rus7_JS}
