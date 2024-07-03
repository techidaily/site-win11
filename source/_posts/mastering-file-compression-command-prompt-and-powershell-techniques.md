---
title: "Mastering File Compression: Command Prompt & PowerShell Techniques"
date: 2024-06-25T11:26:56.414Z
updated: 2024-06-26T11:26:56.414Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering File Compression: Command Prompt & PowerShell Techniques"
excerpt: "This Article Describes Mastering File Compression: Command Prompt & PowerShell Techniques"
keywords: File Compression Mastery,Command Prompt Tips,PowerShell Guide,Windows Compression,Efficient Storage,Data Size Reduction,Optimize Files Quickly
thumbnail: https://thmb.techidaily.com/6244e9865f3cd047c2f60d5d60d859b9d635a96ea7300f114708b93a9cc09aeb.JPG
---

## Mastering File Compression: Command Prompt & PowerShell Techniques

 Are you running out of space on your Windows PC? The best thing you can do to free up some space is to compress big files through zipping. There are plenty of third-party tools that can come in handy in this situation.

 However, if you prefer to use Command Prompt or Windows PowerShell over anything else, there are commands you can use in these utilities to zip or unzip files. So, let's check out how to zip or unzip files using Command Prompt and Windows PowerShell.

## How to Zip Files Using Command Prompt

 You can zip files through Command Prompt using the tar command. It's a command line tool that helps you to extract files and create archives. However, this command only works in Windows 10 or later.

Here's how to zip files using Command Prompt:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Command Prompt** and**Run as administrator** from the right pane.
3. In the console, type the following command and press**Enter** . Replace**'Place'** with the location of the file.  
`cd Place`  
![Place of the file](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/place.jpg)
4. Type**dir** and press**Enter** . It'll show the files inside the selected folder.  
![Dir command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dir.jpg)
5. To zip all the files inside the selected folder, type the following command and press**Enter** . Replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored. Also, replace '**FileExt** ' with the extension of the file you're zipping.  
`tar -a -c -f Compressed.zip *.FileExt`  
![Tar command in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tar.jpg)
6. To zip a single file, execute the following command. Again, replace '**Compressed** ' with the name you want to give your folder where the zip file will be stored, '**FileExt** ' with your file's extension, and '**FileName** ' with the name of the file you want to zip.  
`tar -a -c -f Compressed.zip FileName.FileExt`  
![Compressing one file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/compressing-one-file.jpg)

## How to Zip Files Using Windows PowerShell

 There are several viable ways to[create zip files on Windows](https://www.makeuseof.com/easy-ways-create-zip-file-windows-10/) . One of these is through Windows PowerShell. However, the**tar** command doesn't work in Windows PowerShell; we'll use another command to get the work done.

Here's how to zip files using Windows PowerShell:

1. Open the Start Menu, type**Windows PowerShell,** and choose Run as administrator from the right pane.
2. In the console, type the following command and press**Enter** . Ensure to replace**file destination** and**target location** with the location of the file and the place where you want the file to be zipped, respectively. Also, replace**file name** with the name of the file you want to zip and**destination name** with the destination folder name.  
`Compress-Archive -LiteralPath 'file destination\file name' -DestinationPath 'target location\destination name'`  
![Zipping command in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping.jpg)

 If you want to zip multiple files, execute the following command. Replace**file destination** and**file destination 1** with the location of the first and second files, respectively. And replace**file name** and**file name 2** with the first and second file names.

`Compress-Archive -LiteralPath 'file destination\file name', 'file destination 1\file name 2 -DestinationPath 'target location\destination name'  
`

![Zipping 2 files at once](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/zipping-2.jpg)

## How to Unzip Files Using Command Prompt

 There may be situations where you want to[unzip files on your Windows computer](https://www.makeuseof.com/unzip-files-windows-10/) . Fortunately, you can do that as well using Command Prompt. Here's how:

1. Launch Command Prompt with admin privileges.
2. Use the**cd** command to head toward the zip file's location.
3. Type the following command and press**Enter** . Replace '**Name** ' with the name of the zip file.  
`tar -xf Name.zip`  
![Unzipping file in CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping-file.jpg)

You've successfully unzipped the file.

## How to Unzip Files Using Windows PowerShell

 Windows PowerShell lets you quickly unzip files on your computer. Here's how to do that:

1. Open Windows PowerShell with admin rights.
2. Type the following command and press**Enter** . Make sure to replace <**file** **destination** \> and <**target** **location** \> with the location of the zip file and the place where you want the file to be unzipped, respectively.  
`Expand-Archive -LiteralPath <file destination> -DestinationPath <target location>`  
![Unzipping file in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/unzipping.jpg)

## Save Up Space on Windows 11 by Zipping Your Files

 As a Windows user, you will always come across situations where you want to zip or unzip files. However, if you don't want to use a third-party tool, you can use Command Prompt and Windows PowerShell to quickly zip and unzip files on Windows using the above methods.

 Meanwhile, you might be interested in learning a few important Command Prompt commands.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/elevate-typing-efficiency-with-w11-bespo-points/"><u>Elevate Typing Efficiency with W11, Bespo Points</u></a></li>
<li><a href="https://win11.techidaily.com/visual-virtuoso-top-tips-to-overcome-blurry-windows-11-displays/"><u>Visual Virtuoso: Top Tips to Overcome Blurry Windows 11 Displays</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-way-to-relaunch-printer-service/"><u>Efficient Way to Relaunch Printer Service</u></a></li>
<li><a href="https://win11.techidaily.com/esd-file-transformation-mastery-your-pathway-to-windows-iso-success/"><u>ESD File Transformation Mastery: Your Pathway to Windows ISO Success</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-removing-windows-defender-error-0x80004004/"><u>Understanding & Removing Windows Defender Error 0X80004004</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-pasting-snippets-via-crafted-keybinds-in-windows-11-and-11/"><u>Effortless Pasting Snippets via Crafted Keybinds in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-the-security-of-windows-11s-s-mode/"><u>Unpacking the Security of Windows 11'S 'S Mode'</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-function-key-modifications-in-windows-1011/"><u>Effortless Function Key Modifications in Windows 10/11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-ultimate-guide-to-choosing-a-screen-swivel-cam-for-your-needs-for-2024/"><u>The Ultimate Guide to Choosing a Screen Swivel Cam for Your Needs for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-unlocking-full-screen-recording-features-in-mi-11/"><u>[New] 2024 Approved  Unlocking Full-Screen Recording Features in Mi 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-realme-gt-5-240w-by-drfone-android/"><u>How to Bypass FRP on Realme GT 5 (240W)?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/hacking-back-photo-viewing-in-windows-11-easily-for-2024/"><u>Hacking Back Photo Viewing in Windows 11 Easily for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-xiaomi-14-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Xiaomi 14 Pro | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-iphone-6s-plus-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From iPhone 6s Plus? Heres the Best Fixes</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-how-to-use-autotune-in-audacity-with-plugins-for-free/"><u>New In 2024, How to Use Autotune in Audacity with Plugins for Free?</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-turning-beauty-blogging-into-cash/"><u>In 2024, Turning Beauty Blogging Into Cash</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-androidiphones-finest-top-10-cost-effective-image-enhancers-ranked/"><u>In 2024, Android/iPhone's Finest – Top 10 Cost-Effective Image Enhancers Ranked</u></a></li>
</ul></div>
