---
title: "All About DLL Hijacking - My Favorite Persistence Method"
image: "https:\/\/i.ytimg.com\/vi\/3eROsG_WNpE\/hqdefault.jpg"
vid_id: "3eROsG_WNpE"
categories: "Education"
tags: ["About","Hijacking","Favorite"]
date: "2022-03-21T13:34:49+03:00"
vid_date: "2022-03-20T18:03:51Z"
duration: "PT20M23S"
viewcount: "6009"
likeCount: "517"
dislikeCount: ""
channel: "IppSec"
---
{% raw %}00:00 - Intro<br />00:25 - Why DLL Hijack is my favorite persistence, talk about a few others<br />02:03 - Going over the source code to our sample applications to talk about DLL Hijacking<br />03:20 - Compiling our executable and dll then transfering it to our windows box<br />04:50 - Using Process Monitor to show standard DLL Hijacking (when a DLL Does not exist)<br />06:10 - Showing the order windows tries to load the DLL (Directory of binary then PATH)<br />07:20 - Talking about a somewhat common mistake when people make edits to the PATH (ex: Java/Python/etc)<br />09:00 - Placing the DLL test.exe is looking for and achieving code execution<br />11:25 - Showing if we can write in c:\Windows, we can hijack most dll's explorer.exe loads from system32.<br />14:00 - Messing up using Process Monitor for a bit, sorry should have prepped a bit more<br />15:30 - Showing why explorer is unique, then putting CSCAPI.DLL into c:\Windows\... This would get ran anytime a user logs into the system<br />17:55 - DLL Hijacking OneDrive for user level persistence<br />19:30 - Wrapping up, talking about some videos where I talk more about creating DLL's which can help with this{% endraw %}
