---
title: Timeshift
draft: false
tags:
  - timeshift
  - snapshots
  - linux
---
[Timeshift](https://github.com/linuxmint/timeshift) for Linux is an application that provides functionality similar to the System Restore feature in Windows and the Time Machine tool in Mac OS. Timeshift protects your system by taking incremental snapshots of the file system at regular intervals. These snapshots can be restored at a later date to undo all changes to the system.

In RSYNC mode, snapshots are taken using rsync and hard-links. Common files are shared between snapshots which saves disk space. Each snapshot is a full system backup that can be browsed with a file manager.

In BTRFS mode, snapshots are taken using the in-built features of the BTRFS filesystem. BTRFS snapshots are supported only on BTRFS systems having an Ubuntu-type subvolume layout (with @ and @home subvolumes).

Timeshift is similar to applications like rsnapshot, BackInTime and TimeVault but with different goals. It is designed to protect only system files and settings. User files such as documents, pictures and music are excluded. This ensures that your files remain unchanged when you restore your system to an earlier date. If you need a tool to back up your documents and files please take a look at the excellent BackInTime application which is more configurable and provides options for saving user files.