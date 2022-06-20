---
layout: default #commented in now, try switching
#layout: page # should include 'hero' stuff and comments?
title: Books title line #was ignored??
nav_order: 1
has_children: true
---

Link A [link text](linkpage1) #works once file saved into folder - but treats it as text not HTML, so downloads

Link B [link B text with folder](ozarubooks/linkpage2) #doesn't work, superfluous

Link C [link C text with md](linkpage1.md) #works OK, file also converted to HTML so displays, perfect

Link D [link D text with folder and md](ozarubooks/linkpage2.md) #HTML converted but folder is superfluous

Link C2 [link C text with html](ozarubooks/linkpage2.html) #?? should work?
