---
title: Timeshift saves the day!
draft: false
tags:
  - timeshift
  - snapshots
  - linux
---
I had a moment of frustration and panic when I turned on my workstation today and discovered the updates from last night had broken my Nvidia drivers and caused the system to boot into a broken state, I had to unplug all but one of my 4 displays to get a usable system.

After a few minutes of thought, I remembered that when I setup the system over a year ago I also setup [[Timeshift]] with daily automatic snapshots!  After opening [[Timeshift]] and selecting restore using the previous snapshot I rebooted the system and was presented with a fully functioning system with active Nvidia drivers.

I'm sure it saved hours of frustration trying to fix the broken Nvidia drivers!

Now that everything was working properly again, I made a fresh snapshot and then updated my system again, but this time everything worked properly after rebooting...