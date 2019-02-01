[Z3r0 C00l Bruh!]
---
Question:
---
	Hackers keep secrets.

Answer
---
	1. We are presented a file with the name "hackers.jpeg"
	2. After running some diagnostic on it e.g strings, we can see that there is something off with the headers of the file

![alt text](https://i.imgur.com/95Ote39.png)

	4. As I've done a lot of stego my self, this is obviously used with steghide, as it presents these headers / hexinfo
	5. I unlocked the hints as my bruteforce didn't go as planned in terms of extracting the embedded file
	6. After i while, i thought why not try "neverlanctf" for the password of the picture
	7. steghide extract -sf hackers.jpeg --passphrase neverlanct

![alt text](https://i.imgur.com/9q4TPMl.png)

	8. Cat the output of the file "Ohno.txt" presents us with the following:

	I wonder what this is????
	Fowbjcsniuwcwscotsxvevvko

	9. Firstly i thought it was base64 (it was not)
	10. Secondly i thought it was a caesar cipher / rot 13 (it was not)
	11. Thidrdly i thought it was a Viginere cipher
	12. It was a Viginere with the password "hackers" (as the hint gave us "what are they")

![alt text](https://i.imgur.com/Ag2OGOh.png)

	The result of the decryptet message:
	Yourflagismyfavoritemovie

	13. Tried first "Yourflagismyfavoritemovie"
	14. Tried second "myfavoritemovie"
	15. Success!


Comment:
---
	hint1: Most CTF keys are the name of the CTF but not all.
	hint2: What Are they?

Flag:
---
	Yourflagismyfavoritemovie
	myfavoritemovie
