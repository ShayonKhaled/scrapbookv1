---
title: "What did go wrong"
date: "2023-04-05"
categories: 
  - "scrapbook"
tags: 
  - "32-day"
coverImage: "April-5.jpg"
---
<!--more-->

The SSD arrived today. For the first half of the day I was away so my classmate kindly took it upon himself to install the SSD, remove the current Windows 11 OS and put Windows 10 on it. I wasn't sure which version of Ubuntu I needed for ROS so I asked him to not install Ubuntu before I came.

And then when we tried to install Ubuntu alongside the already installed Windows 10, everything started going wrong. First, only the Windows was booting and we didn't have the option to boot to Ubuntu. Then he brought GRUB back in but then we were no longer able to boot to Windows.

It was saying the signature was invalid, which meant we needed to turn Secure Boot from BIOS off. However, the Secure Boot was enabled and greyed out by default, and even after setting admin password on BIOS it wasn't working. After a few hours, we called it a day. Gonna take a look at it tomorrow with a fresh mind.

I do have to wonder, since when did dual booting get this complicated? While I'd never been much of a heavy Linux user, I did install Linux Mint and Ubuntu on two different occasions few years back and they worked just fine, I didn't even need to type any commands into the terminal.

On a brighter note, the SSD gave the computer a huge performance boost. Even though it's SATA (because the motherboard doesn't have a NVME port), the improvement is still very noticeable.
