---
title: "List Directories in a GUI, Part-2"
date: 2019-08-11T09:42:36+05:30
draft: true
image: "uploads/"
tags: ["Operating Systems", "Linux", "Windows"]
categories: ["Learn Hacking", "Operating Systems"]
---

In operating systems, files and folders or directories are organized in a hierarchical directory tree. 
![](https://security10x.com/uploads/list-directory.png)
You have a main directory that branches off and holds other directories and files. We call the location of these files and directories, paths. Most paths in Windows looks something like this `C:\Users\Cindy\Desktop`.

> In Windows, file systems are assigned to drive letters which look like `C:`, or `D:`, Or `X:`.

Remember that file systems are used to keep track of files on our computer. Each file system has a root directory which is the parent for all other directories in that file system. 

> The root directory of C: would be written C:\, and the root directory of X: would be written X:\. 

> Subdirectories are separated by backslashes, unlike Linux, which uses forward slashes. 

Let's open up this PC and navigate to our main directory. The main directory in a Windows system is the drive that the file system is stored on. 
![](https://security10x.com/uploads/windows-system.png)
In this case, our file system is stored on `Local Disk C`, `Local Disk E`, and `Local Disk F`.