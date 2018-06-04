---
layout: page
permalink: /developer/development-environment/
title: The Build environment
author: Liviu Ionescu

date: 2015-09-10 18:32:00 +0300

---

## Liviu Ionescu's build environment

I'm currently using macOS 10.12.x running on a Mac Book Pro 2011, with 16 GB of RAM and 1 TB of SSD. The debugging sessions are started from within Eclipse on macOS. I currently have no debug capabilities on other platforms (sorry for this).

For testing the resulting plug-ins binaries on other platforms, I install them on Eclipses within several virtual machines running on Parallels Desktop 10:

-   Ubuntu 16.x, 64-bit
-   Ubuntu 14.x, 64-bit
-   Windows 8.1, 64-bit
-   Windows 7, 32-bit

For the multi-platform builds I use [Docker](https://www.docker.com), which on macOS runs under a Linux virtual machine. 
