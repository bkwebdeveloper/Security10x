---
title: "How Securely Delete Files in Windows"
date: 2019-08-07T12:32:36+05:30
draft: false
image: "uploads/how-to-securely-delete-files-in-windows-10_thumb800.jpg"
tags: ["Security10x News"]
---

When you delete a file, it isn't really gone. So if you want to make sure your private data gets deleted for good in Windows, here's how to erase it permanently.

Not many people know this, but Windows has its own built-in secure deletion tool called **Cipher** that's been present since Windows XP came out.

To run Cipher, launch PowerShell (which has replaced Command Prompt) by right-clicking on the Start menu and choosing Windows PowerShell from the menu.

Now type the following: `cipher /w:C:`
![how_to_securely_delete_files_in_windows_10-cipher](https://security10x.com/uploads/cipher.jpg)
This can take a very long time, so if you want to speed things up, you can specify the exact folder where you want ciper to operate by typing the full path.

For example, if you wanted to securely erase everything which has already been deleted in your Documents folder, you need type in its location as follows: `Cipher /w:C:\Users\Jim\Documents`

You can also use a free, open-source tool [Eraser](https://eraser.heidi.ie/download/).

Read the full story on **[TechAdvisor](https://www.techadvisor.co.uk/how-to/windows/how-securely-delete-files-in-windows-10-3675546/)**.