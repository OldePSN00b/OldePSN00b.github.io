---
layout: post
comments: true
title:  "ESXi is (wa$) sexy"
date:   2024-04-17 11:38:00 -0500
categories: jekyll update
---
  After we were well into imaging PCs and saving more time, my director at the time came to talk
to me one day about something called virtualization by a company called VMWare. Prior to this, we 
were running one OS per server and were backing things up using Symantec BackupExec. I googled and researched, read all about it and how it worked. I was pretty intrigued to say the least and we approached administration at the time and explained what we planned on doing. After we finally 
had them understand the bare minimum on what was being planned, we set out to virtualize all of
our physical servers which we eventually did. We phased out some pretty old hardware at the same 
time, because why not. If we were going to be down, might as well come back up on new, shiny 
hardware.

  We enhanced our networking around this time. We have multiple buildings which we manage and we had Cisco RVS4000 units set up to all VPN tunnel back to our main building via DSL (we hated this). My director at the time worked with other departments and administration to get fiber installed in town to all of our buildings, doing away with our RVS4000 units and VPN tunnels. During that transition, we moved from a 1.5mb T1 to a 300mb fiber internet connection (today I have us at 1gb connection to the internet). We implemented a second network for guest wireless and new hardware and centrally manage 

  Things moved a lot quicker after that as we felt BackupExec was getting a little long in the tooth
and a software called Veeam Backup piqued our interest. We bought NAS boxes from QNAP and started 
using that for backup storage. Things ramped up even after that, analog phones gone and VOIP became 
king. People started clamoring for wireless so we ended up deploying internal and guest wireless to 
all our buildings.

<script src="https://utteranc.es/client.js"
        repo="OldePSN00b/OldePSN00b.github.io" 
        issue-term="pathname"
        theme="github-light"
        label="comment"
        crossorigin="anonymous"
        async>
</script>