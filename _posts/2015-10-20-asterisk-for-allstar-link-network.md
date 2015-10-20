---
layout: post
title: "Asterisk for AllStarLink Network"
description: "Informaton on an something I posted to QRZ/app_rpt a while ago"
category: asterisk
tags: []
---
{% include JB/setup %}

# AllStarLink/Asterisk

Main site:  [AllStarLink Network](https://allstarlink.org)

Note:  Both of these repositories were made a while ago as a place to put the code for others to use.  They currently are
not maintained in any way, so you are on your own if you use them.  The ideal way to use these repositories would be to
fork them, so if you make any changes or find bugs, you can make the changes and send me a pull request later.

**Repository:  [AllStarLink](https://github.com/KG7QIN/AllStarLink)**

This is my inital contribution to the AllStar Link Network/Asterisk.  There, you will find the files I pushed to the repo for getting the forked 
version of Asterisk to compile on a modern (3.x+) Linux Kernel.  It runs, and I've successfully run this one several of my 
machines for connecting to the AllStarLink Network.

This also contains the ports of the pathches needed for DAHDI to 2.10.2+2.10.2-complete.


**Repository:  [AllStarLink-FreeBSD](https://github.com/KG7QIN/AllStarLink-FreeBSD)**

Additionally, there exists an untested port of the patches to the DAHDI driver for FreeBSD.  This was modified from the 
FreeBSD ports tree.  It compiles, runs and loads into the FreeBSD Kernel without a panic (a good thing!)

