[Bash 8]
---
Question:
---
	ssh -p 3333 level7@157.230.73.80
	Use Bash 7 password
	This is almost the same thing as the last level, just gotta do one more step.

Answer
---
	1. We get a lot of text, that seems like base64
	2. Let's try to decode it in kali with base64 -d 
	3. Command: base64 -d encoded.txt > decoded
	4. Let's check what filetype it is: file decoded
	5. decoded: gzip compressed data, last modified: Fri Mar 30 07:04:41 2018, from Unix, original size 10240
	6. So the file is a gzip archive, lets 7z extract it:
	7. If we cat the file we get a manifesto from phrack
	8. At the bottom: level8:my-wit-ran-out-5-levels-ago


Flag:
---
	my-wit-ran-out-5-levels-ago