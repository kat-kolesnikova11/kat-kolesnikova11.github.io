---
layout: default
permalink: /csprojects/
title: Computer Science Projects
---

- Implementation of efficient oblivious IntArray and Stack data structures in EMP. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Implementing stack functionality in secure computation is nuanced. A
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;naive MPC implementation of stack requires access time linear in the
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;maximum size of the stack N (i.e. entire encrypted stack container must
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;be scanned). We implement a much better approach, with access cost O(log 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;N ). Read the write-up for more information.
    
Link to project in Github [here](https://github.com/katkolesnikova/EMP-projects)

Link to project writeup [here](https://katkolesnikova.github.io/obstackpaper)
    
- Web server implemented in assembly. This webserver can accept multiple connections at a time, as it has a forking process, and it supports both reading and writing to files. Code written in 2024.  Link to Github [here](https://github.com/katkolesnikova/Assembly-Web-Server)
