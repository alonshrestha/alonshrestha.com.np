---
title: Backup and Restore your Linux System to the Previous State with "SystemBack"
layout: post
date: '2019-07-21'
tag:
- system back
- ubuntu
- linux
- backup
- restore
star: true
category: blog
author: alonshrestha
---

### What is SystemBack?

**SystemBack** is an open-source application for Linux which makes it easy to create live backup images of your system and user saved configurations. People who are new to Linux make mistakes with the configuration of system root files and as a result, crash the system. In this case, SystemBack is a helpful application for backing up and restoring your system in the previous state.

> **Table of Content**

* TOC
{:toc}

### Advantages

-  Live boot image.
-  Easy installation and fast recovery.

### Disadvantages

- If your .sblive file is more than 4 GB then, cannot be converted to ISO file.

### Install SystemBack in Ubuntu

 - <span class="evidence">sudo add-apt-repository ppa:nemh/systemback </span>
- <span class="evidence"> sudo apt-get update </span>
-  <span class="evidence"> sudo apt-get install systemback </span>

![](/assets/images/blog/2019-07-21/1.PNG)

###  How to use?

- After installation, search application by clicking on windows or simply typing SystemBack in the terminal.

![](/assets/images/blog/2019-07-21/2.PNG)

- Enter your password and press OK.

![](/assets/images/blog/2019-07-21/3.PNG)

- Now go to Live system create.

![](/assets/images/blog/2019-07-21/4.PNG)

- Click Create new for creating a system image.

![](/assets/images/blog/2019-07-21/5.PNG)

![](/assets/images/blog/2019-07-21/6.PNG)

- Your system gets back up with a live image. (Time depends on your system size)

![](/assets/images/blog/2019-07-21/7.PNG)

- After that, a .sblive file is being created i.e your system image.

![](/assets/images/blog/2019-07-21/8.PNG)

- Select the image file and click to convert to ISO.
- You can convert a .sblive file to ISO or can burn to CD/DVD or boot in Pendrive directly.

{% include note.html content= ".sblive cannot be converted to ISO if its size is more than 4GB." %}

- Now you can boot your system for installation and restore to the previous state.