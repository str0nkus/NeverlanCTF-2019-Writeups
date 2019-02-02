[Binary 2]
---
Question:
---
	Our lead Software Engineer recently left and deleted all the source code and changed the login information for our employee payroll application. Without the login information none of our employees will be paid. Can you help us by finding the login information?
	***Flag is all caps

Answer
---
	1. Tried opening the application in IDA (didn't work because of missing libs)
	2. Tried running the app, found nothing
	3. Exported the app via 7zip, found nothing
	4. Used a hex-editor on the application
	5. Found some weird text startig with {F},{L},{A},{G}

![alt text](https://i.imgur.com/vzZ6oiP.png)

Flag:
---
	flag{ST0RING_STAT1C_PA55WORDS_1N_FIL3S_1S_N0T_S3CUR3}
	ST0RING_STAT1C_PA55WORDS_1N_FIL3S_1S_N0T_S3CUR3