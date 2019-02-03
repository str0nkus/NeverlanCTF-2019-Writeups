[Bash 3]
---
Question:
---
	ssh -p 3333 level2@157.230.73.80
	Use Bash 2 password
	Ok. So you found the hidden file. How about trying to find the password in plain
	sight? You'll have to figure out how to sift through the muck though...

Answer
---
	1. Found the file canyoufindme.txt
	2. We know that the password is in there somewhere
	3. All passwords had "-" (dashes) in them, so we're grepping for that
	4. ls -la | grep -
	5. Found: level3:child-of-honor

Flag:
---
	child-of-honor