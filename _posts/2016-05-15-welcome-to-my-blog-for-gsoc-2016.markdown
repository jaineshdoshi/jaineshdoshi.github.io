---
layout: post
title:  "Welcome to my Blog for GSoC 2016!"
date:   2016-05-15 13:07:23
author: Jainesh Doshi
categories: GSoC 2016
tags:	GSoC ArchC
cover:  "/assets/archc.png"
---

## Overview

I am working with the organization [ArchC][archc], [Computer Systems laboratory][csl], [University of Campinas][unicamp], Brazil for Google Summer of Code 2016. My project is aimed at booting an operating system on the Functional Simulator ArchC developed by the group. I would be mentored by [Prof. Rodolfo][rodolfo] and his student Maxiwell from his research group. Upon further researching about the architecture and OS that should be used for this project I concluded that the open source [eCos][ecos] Operating system upon the MIPS architecture in the simulator would be an optimal choice.

### The Zeroth Checkpoint
	
The timeline and various checkpoints were predecided in the proposal itself. To be well prepared and start comfortably on ArchC, I had a Zeroth Checkpoint that included studying the already available implementation of the bootable [linux image][gem5-inux-image] for the full system mode of another simulator [gem5][gem5] and get a better picture of the essentials needed and modify the tasks writtne in my proposal as per needed. I will summarize and put up my findings from the above here soon!
Next up is the first checkpoint.

### The First Checkpoint

Since I am from IIT Bombay, my summer break starts earlier than other schools from around the world. Hence I decided to move my timeline for GSoC up as I could utilize my time more optimally. I also have started working on my Masters thesis in a similar area so I do occasionally jump from one project to another at times when I get saturated with the one that I am working on. I am interested in the field of High Preformane Computing and have also explored Neuromorphic Engineering to cater to my curiousity. To begin with I already had installed and fiddled around with the ArchC simulator and [MPSoC][mpsoc] on my laptop earlier though. 
I had divided the whole projet into subtasks inorder to be well organized and be more modular. 
The first checkpoint consisted of the following subtasks:
* Get acquainted on a higher level with the functioning of the simulator
* Identification of the virtual environment and its requirements
* Choose and configure HAL for the board, architecture that will support the OS on the simulator


[archc]:			http://www.archc.org/
[ecos]:				http://ecos.sourceware.org/
[gem5]:				www.gem5.org/
[gem5-linux-image]:	http://www.m5sim.org/Download
[mpsoc]:			http://www.archc.org/benchs/mpsocbench/index.html
[rodolfo]:			http://www.ic.unicamp.br/~rodolfo/
[csl]:				https://lsc.ic.unicamp.br/
[unicamp]:			www.unicamp.br/unicamp/en

