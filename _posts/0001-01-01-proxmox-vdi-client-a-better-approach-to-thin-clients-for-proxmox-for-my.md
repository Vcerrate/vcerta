---
title: "PROXMOX VDI Client - A Better Approach to Thin Clients for Proxmox"
image: "https:\/\/i.ytimg.com\/vi\/oLatrZBFQrw\/hqdefault.jpg"
vid_id: "oLatrZBFQrw"
categories: "Science-Technology"
tags: ["PROXMOX","Client","Better"]
date: "2022-04-09T12:17:52+03:00"
vid_date: "2022-04-07T15:15:02Z"
duration: "PT15M56S"
viewcount: "8369"
likeCount: "489"
dislikeCount: ""
channel: "apalrd's adventures"
---
{% raw %}For my new trick, I'm progressing the Raspberry Pi (or Debian) + Proxmox Thin Client forward using a new Python tool written by a viewer of mine. Called PVE-VDIClient, it looks like a login screen but it authenticates via the Proxmox API, queries a list of all VMs the user has access to, and lets you choose which to launch into. Now, you can provision VMs per user and let any user in the system login to any of their VMs from any thin client in your system, without having to individually hardcode VM IDs on the thin client.<br /><br />I know the Raspberry Pi and Debian are both split in popularity with thin clients (probably because Raspberry Pi's are basically impossible to buy right now), so for this video I again wrote instructions for both Pi OS and Debian in my blog post, but this time I chose to follow the Debian version on video. The result is the same for both OSes, a login screen which authenticates back to Proxmox, using the SPICE protocol for remote access, and SOUND WORKS!<br /><br />Link to my blog post with the commands to follow along:<br /><a rel="nofollow" target="blank" href="https://www.apalrd.net/posts/2022/raspi_spice_vdi/">https://www.apalrd.net/posts/2022/raspi_spice_vdi/</a><br /><br />Link to the PVE-VDIClient by Josh Patten on Github:<br /><a rel="nofollow" target="blank" href="https://github.com/joshpatten/PVE-VDIClient">https://github.com/joshpatten/PVE-VDIClient</a><br /><br />Timestamps:<br />00:00 - Introduction<br />01:07 - Proxmox Config Recap<br />04:15 - PVE VDI Client<br />05:36 - PVE VDI Client Installation<br />10:30 - Launch on Boot<br />13:58 - Testing<br /><br />Raspberry Pi is a trademark of Raspberry Pi Trading<br />Proxmox is a trademark of Proxmox Server Solutions GmbH{% endraw %}
