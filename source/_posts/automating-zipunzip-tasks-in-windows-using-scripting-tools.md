---
title: Automating Zip/Unzip Tasks in Windows Using Scripting Tools
date: 2024-06-25T09:55:33.817Z
updated: 2024-06-26T09:55:33.817Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Automating Zip/Unzip Tasks in Windows Using Scripting Tools
excerpt: This Article Describes Automating Zip/Unzip Tasks in Windows Using Scripting Tools
keywords: Automate Unzip Windows,Window Unzip Scripts,Zip Tool Windows Script,Windows File Automation,Script Zip Extract Windows,Easy Windows Unzip Script,Scripting Tools Unzip Task
thumbnail: https://thmb.techidaily.com/605743c45d46920946cf620896ea214cdef6126e457144d63179eeaf5994b016.jpg
---

## Automating Zip/Unzip Tasks in Windows Using Scripting Tools

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
<li><a href="https://win11.techidaily.com/methods-to-end-persistent-login-error-alerts-on-pc/"><u>Methods to End Persistent Login Error Alerts on PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-radeon-driver-updates-in-windows-11-step-by-step-guide/"><u>Mastering Radeon Driver Updates in Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/executing-chatgpt-on-windows-systems/"><u>Executing ChatGPT on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-functional-shortcuts-cure-errors-in-win-11/"><u>Rectify: Functional Shortcuts - Cure Errors in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-display-performance-with-high-ppi-settings/"><u>Maximizing Display Performance with High PPI Settings</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-and-powershell-a-comparative-analysis-on-their-uniqueness/"><u>Windows Terminal & PowerShell: A Comparative Analysis on Their Uniqueness</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-and-remedying-code-error-0x80072f8f/"><u>Preventing and Remedying Code Error 0X80072f8f</u></a></li>
<li><a href="https://android-location.techidaily.com/10-free-location-spoofers-to-fake-gps-location-on-your-honor-magic-5-lite-drfone-by-drfone-virtual/"><u>10 Free Location Spoofers to Fake GPS Location on your Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-exclusive-top-10-leading-fb-video-platforms/"><u>In 2024, Exclusive Top 10  Leading FB Video Platforms</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-exploring-the-leading-10-cost-effective-podcast-production-applications/"><u>2024 Approved Exploring the Leading 10 Cost-Effective Podcast Production Applications</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-streamlining-cd-manipulation-with-wmp/"><u>[New] Streamlining Cd Manipulation with WMP</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-earnings-potential-with-youtube-adsense-payments-per-1k-viewer/"><u>[Updated] Unlocking Earnings Potential with Youtube AdSense  Payments Per 1K Viewer</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-asus-rog-phone-7-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Asus ROG Phone 7 Location on Skout | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/unlock-your-dvds-a-beginners-guide-to-converting-to-digital-video-formats-for-2024/"><u>Unlock Your DVDs A Beginners Guide to Converting to Digital Video Formats for 2024</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-best-video-format-converter-for-pc-and-online/"><u>Updated In 2024, Best Video Format Converter for PC and Online</u></a></li>
</ul></div>
