---
title: "Windows 11 | How to Enable Logon Sound in Windows 11"
image: "https:\/\/i.ytimg.com\/vi\/Z2HKUZTSZIU\/hqdefault.jpg"
vid_id: "Z2HKUZTSZIU"
categories: "Education"
tags: ["How to Enable Logon Sound in Windows 11","windows 11 logon sound not playing","windows 11 login sound"]
date: "2022-01-16T14:13:36+03:00"
vid_date: "2022-01-15T19:04:22Z"
duration: "PT10M32S"
viewcount: "13"
likeCount: "1"
dislikeCount: ""
channel: "CNATT"
---
{% raw %}#Howto #Windows11 #LogonSound #StartupSound<br /><br />How to Enable Logon Sound in Windows 11? [Tutorial]<br /><br /><br />⏰Timestamps⏰<br /><br />00:00 Introduction <br />01:51 Step 1: Create a VBScript File to play the sound<br />04:28 Step 2: Set the Logon sound in Windows 11 using the Task Scheduler<br />08:41 Change Logon Sound<br />09:30 Disable Logon Sound<br /><br />-----------------------------------------------------------------------------------------<br />-------------------------------VBScript Codes---------------------------------<br />-----------------------------------------------------------------------------------------<br />Set oVoice = CreateObject(&quot;SAPI.SpVoice&quot;)<br />set oSpFileStream = CreateObject(&quot;SAPI.SpFileStream&quot;)<br />oSpFileStream.Open &quot;C:\Windows\Media\LogonSound.wav&quot;<br />oVoice.SpeakStream oSpFileStream<br />oSpFileStream.Close<br />---------------------------------------------------------------------------------------------<br /><br /><br />In Windows 7 and earlier, Logon sound, Logoff sound, and Shutdown sound were available.<br /><br />Why Windows 11 doesn't play the Logon sound?<br />In newer versions of Windows, Microsoft focused on making Windows boot and Shut down faster and completely removed the sounds which play at Logon, Logoff and shutdown.<br /><br />If you try to restore these events using the Registry, they will not play. <br /><br />In another video, We showed you how you can change the Startup sound using a third-party software, but some users are reluctant to use third-party software. (<a rel="nofollow" target="blank" href="https://youtu.be/wAuhgjoVGlw)">https://youtu.be/wAuhgjoVGlw)</a><br /><br />There is only one solution left and that is to set the sound to logon without using third-party software.<br /><br />The  logon sound is a sound that Windows plays when you sign in to your user account. <br /><br />This is a separate sound from the startup sound, but can be a good alternative to the startup sound for those who do not use third-party software to change the Startup sound.{% endraw %}
