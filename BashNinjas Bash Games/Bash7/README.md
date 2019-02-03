[Bash 7]
---
Question:
---
	ssh -p 3333 level6@157.230.73.80
	Use Bash 6 password
	Look in level7.txt. You'll have to figure out what to do with that on your own.

Answer
---
	1. cat level7.txt
	2. We are presented with some base64 text

	UlVMRVMKClRoZSBJbnRlcm5ldCBpcyBhIHNtYWxsIHBsYWNlLiBXb3JkIGdldHMgYXJvdW5kLCBmYXN0LgoKRm9sbG93IHRoZXNlIHJ1bGVzIGF0IGFsbCB0aW1lczoKCi0gT25seSBoYWNrIHRoaW5ncyB5b3Ugb3duCgotIERvIG5vdCBoYWNrIGFueXRoaW5nIHlvdSByZWx5IG9uCgotIFJlc3BlY3QgdGhlIHJpZ2h0cyBvZiBvdGhlcnMKCi0gS25vdyB0aGUgbGF3LCB0aGUgcG9zc2libGUgcmlzaywgYW5kIHRoZSBjb25zZXF1ZW5jZXMgZm9yIGJyZWFraW5nIGl0CgotIEZpbmQgYSBzYWZlIHBsYXlncm91bmQKCmxldmVsNzp3aGl0ZS1oYXRzLWhhdmUtdmFsdWVzLWFuZC1ydWxlcwo=

	Translates to:
	RULES
	The Internet is a small place. Word gets around, fast.
	Follow these rules at all times:
	- Only hack things you own
	- Do not hack anything you rely on
	- Respect the rights of others
	- Know the law, the possible risk, and the consequences for breaking it
	- Find a safe playground
	level7:white-hats-have-values-and-rules


Flag:
---
	white-hats-have-values-and-rules