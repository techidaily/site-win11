---
title: "Unzipping Complex Archives: A Windows CLI Expert's Manual"
date: 2024-06-25T11:44:11.953Z
updated: 2024-06-26T11:44:11.953Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unzipping Complex Archives: A Windows CLI Expert's Manual"
excerpt: "This Article Describes Unzipping Complex Archives: A Windows CLI Expert's Manual"
keywords: Unzip Windows Files,CLI Archive Handling,Zipping Windows Utilities,Command Line Data Extraction,Advanced File Compression,Windows CLI Archival Guide,Mastering Archive Management
thumbnail: https://thmb.techidaily.com/2041635073b88dca4044a894fcdb4e9d1f4358f133672dcfc64784a5955ccf2a.jpg
---

## Unzipping Complex Archives: A Windows CLI Expert's Manual

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
<li><a href="https://win11.techidaily.com/efficient-techniques-for-inspecting-and-cleansing-windows-trail/"><u>Efficient Techniques for Inspecting & Cleansing Windows Trail</u></a></li>
<li><a href="https://win11.techidaily.com/brightening-your-computerenas-dark-background-issue/"><u>Brightening Your Computer'enas Dark Background Issue</u></a></li>
<li><a href="https://win11.techidaily.com/making-windows-alt-codes-function-again-51-characters/"><u>Making Windows ALT Codes Function Again (51 Characters)</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-insight-discerning-storage-type-on-windows/"><u>Exclusive Insight: Discerning Storage Type on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-your-computer-writes-on-new-program-placement/"><u>Deciphering Your Computer' Writes on New Program Placement</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-modify-calculators-color-scheme-dark/"><u>How To Modify Calculator's Color Scheme (Dark)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-extend-a-volume-on-windows-without-erasing-personal-data/"><u>How to Extend a Volume on Windows Without Erasing Personal Data</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-the-ultimate-tutorial-on-how-to-openedit-srt-on-mac/"><u>[Updated] The Ultimate Tutorial on How to Open/Edit SRT on Mac</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-experts-take-on-using-luts-for-image-enhancement-in-pscc/"><u>2024 Approved  Expert's Take on Using LUTs for Image Enhancement in PSCC</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-bold-and-bright-the-best-tiktok-pfp-strategies-to-impress/"><u>2024 Approved  Bold and Bright  The Best TikTok PFP Strategies to Impress</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-edit-like-a-pro-the-5-best-iphone-video-editing-apps/"><u>New Edit Like a Pro The 5 Best iPhone Video Editing Apps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-from-zero-to-hero-top-10-intro-creator-websites-for-beginners/"><u>Updated From Zero to Hero Top 10 Intro Creator Websites for Beginners</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-innovative-advanced-gaming-monitoring-tools-for-a-better-experience/"><u>In 2024, Innovative, Advanced Gaming Monitoring Tools for a Better Experience</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/roblox-revealed-masterful-methods-for-closer-insight-for-2024/"><u>Roblox Revealed  Masterful Methods for Closer Insight for 2024</u></a></li>
</ul></div>
