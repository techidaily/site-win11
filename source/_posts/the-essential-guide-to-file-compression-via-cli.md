---
title: The Essential Guide to File Compression via CLI
date: 2024-06-25T11:42:25.138Z
updated: 2024-06-26T11:42:25.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes The Essential Guide to File Compression via CLI
excerpt: This Article Describes The Essential Guide to File Compression via CLI
keywords: FileCompress CLI,DataPackCLI,ZipCLIGuide,ArchiveCmds,MinifyFilesCLI,CompressionTechniques,CommandLineArchiving
thumbnail: https://thmb.techidaily.com/770723973e178e7a8930f29e3f500f2a61aa4b3ccf5eb07317cde4aac3003016.jpg
---

## The Essential Guide to File Compression via CLI

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
<li><a href="https://win11.techidaily.com/uncomplicated-linux-use-without-wsl/"><u>Uncomplicated Linux Use Without WSL</u></a></li>
<li><a href="https://win11.techidaily.com/easy-paths-back-to-success-in-steam-gaming/"><u>Easy Paths Back to Success in Steam Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-shadows-tackling-wacatacbml-on-microsoft-windows/"><u>Unveiling the Shadows: Tackling Wacatac.B!ml on Microsoft Windows</u></a></li>
<li><a href="https://win11.techidaily.com/prioritizing-improvement-in-windows-11/"><u>Prioritizing Improvement in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-stop-hyber-v-with-ease-in-windows-11-pro/"><u>Guide: Stop Hyber-V with Ease in Windows 11 Pro</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-windows-parsing-hiccup-code-0xc00ce556/"><u>Correcting Windows Parsing Hiccup Code 0xC00CE556</u></a></li>
<li><a href="https://win11.techidaily.com/exclusive-key-collectors-deal-wintry-windows-11-priced-at-612-per-year/"><u>Exclusive Key Collector's Deal - Wintry Windows 11 Priced at $6.12 Per Year</u></a></li>
<li><a href="https://win11.techidaily.com/launching-quake-mode-using-windows-terminal/"><u>Launching Quake Mode: Using Windows Terminal</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-social-media-sweepstakes-twitters-favorite-videos-ranked/"><u>[Updated] Social Media Sweepstakes  Twitter's Favorite Videos Ranked</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/prevent-unwanted-recordings-quit-time-tricks-for-2024/"><u>Prevent Unwanted Recordings  Quit Time Tricks for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-wmm-tutorial-for-aspiring-animators/"><u>[New] The Ultimate WMM Tutorial for Aspiring Animators</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-directly-viewing-facebook-videos-on-your-apple-tv-setup/"><u>[New] In 2024, Directly Viewing Facebook Videos on Your Apple TV Setup</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/premier-solutions-for-virtual-team-interactions-for-2024/"><u>Premier Solutions For Virtual Team Interactions for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y100a-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y100A Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-masterclass-in-capturing-conversations-for-later-review/"><u>[New] Masterclass in Capturing Conversations for Later Review</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-decoding-disconitro-how-it-works-and-how-you-can-join-for-2024/"><u>[New] Decoding DiscoNitro  How It Works and How You Can Join for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
</ul></div>
